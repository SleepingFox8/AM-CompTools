# AM-CompTools

This library contains functions for computing things that may be useful when writing "Advanced Macros" bots. This library is currently optimized for [advanced macros mod](https://www.curseforge.com/minecraft/mc-mods/advanced-macros) v9.2.0 or Minecraft v1.14.4. 

## How to use

You can add this library to your repository as a git submodule by using the command ``git submodule add https://github.com/SleepingFox8/AM-CompTools``. This will import the latest version of this repository into your github rebository as a subdirectory. 

From there you can import these libraries to your own ``.lua`` scripts by importing them via:

```lua
compTools = require ("AM-CompTools/compTools")
```

Library functrions can be called like so:

```lua
compTools.sortTableByKeys(yourTableHere)
```

If this repo updates, your repo's submodule will not update automatically. To update your repository's submodule, ``cd`` into your submodule's directory and run ``git pull origin master``.
