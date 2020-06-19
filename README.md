# ConfigAPI
[![](https://jitpack.io/v/Filocava99/ConfigAPI.svg)](https://jitpack.io/#Filocava99/ConfigAPI) <br><br>
With ConfigAPI you can easily create and manage your configuration files.  
Simply add ConfigAPI to your dependencies and create an instance of the class Config for each configuration file you need to manage.

## USAGE
```
Code (Java):
//Creating a config from a template
//If a file called myConfig.yml is found inside your plugin jar it will be used as a template during the config initialization,
//otherwise will be created an empty config
Config myConfig = new Config("myConfig.yml", myPluginInstance);
//Retrieving the FileConfiguration instance
FileConfiguration fc = config.getConfig();
fc.get("myValue");
fc.set("myValue", anything);
//Saving the config
myConfig.save();
```
 
--------------------------------------------------------------------
[MAVEN/GRADLE SUPPORT](https://jitpack.io/#Filocava99/ConfigAPI/Tag)
--------------------------------------------------------------------
