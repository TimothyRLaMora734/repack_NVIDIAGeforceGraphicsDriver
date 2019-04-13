## NVIDIA Geforce Graphics Driver Repack

Blog: http://puresoftapps.blogspot.com/2019/01/nvidia-graphics-driver-mod-2019-10-01.html

Download: https://github.com/alanfox2000/repack_dotNetAppx/releases


#### Windows 10 Standard Driver

Components:

- Graphics Driver

- HD Audio Driver

- PhysX System Software

- Update Core

- PPC

Modified:

- Update Core (for game profile update) can be selected during installation

- Remove "NIVIDIA telemetry monitor" and "NIVIDIA crash and telemetry reporter" which included in Update Core Component

- Remove Display Driver NvTelemetry Plugin for NVIDIA Container

- Remove all NVIDIA Help HTML files (NvCplSetupInt.exe file size reduce ~72 MB (~74%))

- Remove NvInstallerUtil.dll (Telemetry), NVNetworkService.exe and NVNetworkServiceAPI.dll in NVI2 folder

- Modify DisplayDriver.nvi and UpdateCore.nvi file UsesNvTelemetry value to false (Default: True)

- Include a Utility (AutoHotkey Script) which allow selecting installation switches and support automatic installing unsigned driver

- Add Dolby Digital Format on HDMI output ("NVIDIA Output" Sound Property -> Advanced Tab -> Default Format: Dolby Digital)

- Add Dolby Home Theater v4 and Dolby Advanced Audio v2 support 

- Apply TweakForce Xtreme-G Registry Modification on INF:

Paletted Textures In Video Memory 
Render Quality Flags 
Target Flush Count 
Texture Clamp Behavior 
Texture LOD Bias 
Use Cached PCI Mappings 
Texture Memory Space 
Downloaded Memory Space 
Texture Precache 
UMA Fast Frame Buffering 
Main 3D rendering 
Triple Buffering


---------------------------------------------------------

#### Windows 10 DCH Driver

Components:

- Same as Windows 10 Standard Driver

Modified:

- Same as Windows 10 Standard Driver

- Automatically offline install NVIDIA Control Panel UWP app

- Remove invalid NVIDIA Control Panel shortcut on Windows Control Panel



---------------------------------------------------------

#### Windows 7/8.1 Standard Driver

Components:

- Graphics Driver

- HD Audio Driver

- PhysX System Software

- Update Core

Modified:

- Same as Windows 10 Standard Driver



#### Support:

To keep this driver maintenance, click the below donate button (PayPal)

