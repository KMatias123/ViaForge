# ViaForge

**Client-side ViaVersion implementation for Forge**

Forked from ViaVersion/ViaFabric

Using CCBlueX/LiquidBase for Injection

#### Setup ViaForge
* **Eclipse** => `gradlew --debug setupDevWorkspace eclipse build`
* **IntelliJ** => `gradlew --debug setupDevWorkspace idea genIntellijRuns build`

#### Open project with your IDE
* **Eclipse** => `Right click => New => Java Project => Browse location => Select ViaForge folder => Finish`
* **IntellIJ** => `Open => Select ViaForge folder => Import gradle project`

## How to run workspace
* Add `-Dfml.coreMods.load=com.github.creeper123123321.injection.MixinLoader` to your run configuration

## Libraries
### Mixin
Mixin is a library to inject source into Minecraft

[Documentation](https://docs.spongepowered.org/5.1.0/en/plugin/internals/mixins.html)