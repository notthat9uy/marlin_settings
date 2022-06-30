# Have to download the latest
https://github.com/MarlinFirmware/Configurations/archive/release-2.0.9.3.zip

Marlin-2.0.x\config\examples\Creality\Ender-3\CrealityV422


# Build Cheatsheet
## platformio.ini 
Ender-3 (Before 2.1)
````
default_envs = STM32F103RET6_creality
````
Ender-3 (After 2.1)
````
default_envs = STM32F103RE_creality
````

CR-10S
````
default_envs = mega2560
````

## Header config files
Replace files in Marlin folder