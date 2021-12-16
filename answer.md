# Answers to technical test from WFT to Karim Guennoun

## Why use LTS versions rather than latest Unity3D?
Because this is a Long Time Support that guarantee the projects built in this version to last a long time without beeing deprecated.
The latest Unity3D version could have the latests features, but may be less stable or may change some of the api that could impact the project built on this non LTS version.

## What are magic folders in Unity3D?
+ **StreamingAssets** folder: this folder allow build unity project to access dynamically files in normal filesystem
+ **Editor**: Editor scripts add functionality to Unity during development, but aren’t available in builds at runtime. Scripts in a Editor folder run as Editor scripts, not runtime scripts.
+ **Gizmos**
+ **Resources**

## How do you structure the root of your `Assets` folder?
+ Materials
+ GUI
+ Effects
+ Meshes
+ Plugins
+ Prefabs
+ Resources
+ Scenes
+ Scripts
+ Textures


## Bonus: What plugins do you recommend to get started on a large Unity3D project and why?
+ Odin: to allow a strong and efficienty editor customization that will benefit to developers, game designer and graphic designers.
+ I don't have the name, but a plugin that gives a lot of utils and overrides to Unity standard classes