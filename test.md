<p align="center">
    <img width="300" src="https://s2.loli.net/2024/04/30/NJrstR1QzpoLyIT.png" alt="title">
</p>
<hr>
<p align="center">Timeless and Classics Guns Zero for Fabric</p>
<p align="center">Ported Timeless and Classics Zero Forge 1.20.1 to Fabric 1.20.1.</p>
<p align="center">
    <a href="https://www.curseforge.com/minecraft/mc-mods/timeless-and-classics-zero">
        <img src="http://cf.way2muchnoise.eu/full_timeless-and-classics-zero.svg" alt="CurseForge Download">
    </a>
    <img src="https://img.shields.io/badge/license-GNU GPL 3.0 | CC%20BY--NC--ND%204.0-green" alt="License">
    <br>
    <a href="https://jitpack.io/#MCModderAnchor/TACZ">
        <img src="https://jitpack.io/v/MCModderAnchor/TACZ.svg" alt="jitpack build">
    </a>
    <a href="https://crowdin.com/project/tacz">
        <img src="https://badges.crowdin.net/tacz/localized.svg" alt="crowdin">
    </a>
</p>
<p align="center">
    <a href="https://github.com/We-Cant-Coding/TACZ-Fabric/issues">Report Bug</a>    ·
    <a href="https://github.com/We-Cant-Coding/TACZ-Fabric/releases">View Release</a>    ·
    <a href="https://tacwiki.mcma.club/zh/">Wiki</a>
</p>

Timeless and Classics Guns Zero is a gun mod for Minecraft Fabric 1.20.1.

## Notice

- If you have any bugs, you can visit [Issues](https://github.com/We-Cant-Coding/TACZ-Fabric) to
  submit issues.

## Authors

- Programmer: `286799714`, `TartaricAcid`, `F1zeiL`, `xjqsh`, `ClumsyAlien`
- Artist: `NekoCrane`, `Receke`, `Pos_2333`
- Porting: `MaGyul`, `LaeDev`

## Credits

- Other players who have helped me in any ways, and you

## License

- Code: [GNU GPL 3.0](https://www.gnu.org/licenses/gpl-3.0.txt)
- Assets: [CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/)

## Maven

```groovy
repositories {
    // Choose one of the following two methods

    // CurseForge
    maven {
        // Add curse maven to repositories
        name = "Curse Maven"
        url = "https://www.cursemaven.com"
        content {
            includeGroup "curse.maven"
        }
    }

    // Modrinth
    maven {
        // Add modrinth maven to repositories
        name = "Modrinth Maven"
        url = "https://api.modrinth.com/maven"
        content {
            includeGroup "maven.modrinth"
        }
    }
}

dependencies {
    // Choose one of the following two methods

    // CurseForge
    // You can see the https://www.cursemaven.com/

    // If you want to use version tacz-fabric-1.20.1-1.0.2-hotfix2-release
    modImplementation "curse.maven:timeless-and-classics-zero-1028108:5621380"

    // Modrinth
    // You can see the https://modrinth.com/

    // If you want to use version tacz-fabric-1.20.1-1.0.2-hotfix2-release
    modImplementation "maven.modrinth:timeless-and-classics-zero:1.0.2-hotfix2"
}
```
