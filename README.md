## SimpleGunKit
By Mishaho

Features
- gun drops
- gun pickups
- complete customization

Todo
- secure the remotes

Preview
![image](https://user-images.githubusercontent.com/59292383/167273536-ffb1968a-f287-4c5d-9761-11e97e08dbaf.png)

#### Instalation
Just put the folder in the workspace, it will then install itself at runtime.
This kit will use serverstorage to store guns, replicatedstorage to store remotes and the gunstats-module.
The folder in the workspace remains for gun drops and pickups.

#### Adding a gun
A gun requires a tool and a model. The tool is what the player will be using. The model is for pickup.
The tool needs to be unanchored and all parts must be welded together.
The tool requires a "Handle" with a "muzzle" and a "tracer".
The muzzle is where the bullet begins. The tracer is.. the tracer.
Inside the muzzle is also a PointLight, you can change the properties.

The model is more simple, all it needs it a primarypart and a name. The name **must** match the tool name.
The primarypart is used for the proximityprompts "pickup gun" and some minor other things.

Lastly, add configs for the gun in GunStats.lua.
