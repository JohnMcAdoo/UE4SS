# This repo has been archived. The new repo can be found here: https://github.com/UE4SS-RE/RE-UE4SS

# Unreal Engine 4/5 Scripting System
### This tool has entered "Maintenance" mode. No more features will be added for the foreseeable future, but it will hopefully still be updated whenever new UE versions are released.

## Targeting UE Versions: From 4.12 To 5.0

The goal of UE4SS is not to be a plug-n-play solution that always works with every game.  
The goal is to have an underlying system that works for most games.  
You may need to update AOBs on your own, and there's a guide for that below.  

## Links

[Full installation guide](https://github.com/UE4SS/UE4SS/blob/master/Guides/FullInstallationGuide.md)  
[Updating AOBs](https://github.com/UE4SS/UE4SS/blob/master/Guides/FixingBrokenAOBs.md)  
[Generating UHT compatible headers](https://github.com/UE4SS/UE4SS/wiki/Generating-UHT-compatible-headers)

## Credits

- **CheatingMuppet** `Creator`
- **Archengius**
  - UHT compatible header generator
- **Narknon**
- **CasualGamer**
  - Injector code & aob scanner is heavily based on his work, 90% of that code is his.
- **SunBeam**
  - Extra signature for function 'GetFullName' for UE4.25.
  - Regex to check for proper signature format when loaded from ini.
  - Lots and lots of work on signatures
- **tomsa**
  - const char* to vector\<int> converter
    - tomsa: Idea & most of the code
    - CheatingMuppet: Nibblet support
- **boop** / **usize**
  - New UFunction hook method

## Thanks to everyone who helped with testing

- GreenHouse
- Otis_Inf
- SunBeam
- Motoson
- hooter
- Synopis
