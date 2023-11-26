# Zygisk-Il2CppDumper
Il2CppDumper with Zygisk, dump il2cpp data at runtime, can bypass protection, encryption and obfuscation.

This fork doesn't require you to specify a game package name but will dump any unity game it encounters.

## How to use
1. Install [Magisk](https://github.com/topjohnwu/Magisk) v24 or later and enable Zygisk
2. Download module from the Release page
3. Install module in Magisk
4. Start the game, `dump.cs` will be generated in the `/data/data/GamePackageName/files/` directory