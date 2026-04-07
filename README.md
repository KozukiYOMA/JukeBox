# JukeBox
JukeBox is a plugin that allows you to listen to music on your Minecraft server.

## How does this differ from the original?
This fork is a customized version I modified for use on my server.
This fork is fixes for some issues and a few customizations.
If you wish to use it, please download the source code and build it yourself.
As a rule, i don't submit pull requests to the original version for changes made to this fork, except for bug fixes.

## Documentation
You can find various tutorials in the [documentation page on SpigotMC](https://www.spigotmc.org/resources/jukebox-music-plugin.40580/field?field=documentation).

## Maven repository
Add this to your `repositories` section:
```xml
<repository>
	<id>codemc-repo</id>
	<url>https://repo.codemc.org/repository/maven-public/</url>
</repository>
```
And this to your `dependencies` section:
```xml
<dependency>
  <groupId>fr.skytasul</groupId>
  <artifactId>jukebox</artifactId>
  <version>VERSION</version>
  <scope>provided</scope>
</dependency>
```