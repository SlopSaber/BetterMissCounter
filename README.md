# BetterMissCounter

- Displays your personal best miss count (misses + badcuts taken from ScoreSaber and BeatLeader)
- Customizable text and colors

![image](https://user-images.githubusercontent.com/45233053/153546888-6f96efc3-c32b-48f7-ac36-ffc8991ab48d.png)

## Installation

- Download the DLL from [Releases](https://github.com/catsethecat/BetterMissCounter/releases) and place it in your Plugins folder
- Requires BSIPA, BSML, BS_Utils, Counters+
- Go to the Counters+ menu in game, disable the default miss counter and enable this one

## Building

The project uses `BeatSaberDir` for Beat Saber references. If `..\Refs` exists, it is used as the local reference directory:

```powershell
dotnet build -c Release
```

For a game install, pass the game directory or set it in `BetterMissCounter.csproj.user`:

```powershell
dotnet build -c Release /p:BeatSaberDir="D:\BSManager\BSInstances\1.44.0"
```
