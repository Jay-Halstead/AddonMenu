# AddonMenu
VehicleSpawner is a FiveM resource coded in C# allowing you to create a custom vehicle spawner menu with categories and the ability to mark a vehicle "out of service", locking it from being spawned.
Installation
Create a new resource folder on your server.
Add the contents of "resource" inside it. This includes: "Client.net.dll", "fxmanifest.lua", "config.ini", "SharpConfig.dll", "NativeUI.dll"
In server.cfg, "ensure" VehicleSpawner, to make it load with your server startup.
Configuration
The "config.ini" file allows you to add categories and vehicles to the menu, you are also able to change the comamnd used to open/close it.
