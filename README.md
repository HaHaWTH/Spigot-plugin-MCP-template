## Spigot plugin MCP template (1.12.2)

Use MCP mappings to develop spigot plugins with ease.

## Components included

- SpecialSource remapper
- CraftBukkit to Searge mappings
- Searge to MCP mappings
- Spigot API 1.12.2
- Spigot NMS (MCP 9.42 remapped)

## How to use

- Clone this repo
- Run `mvn install -P setup-deobf-jar` in the project directory
- Import the project into your IDE
- Then you are all set!

## Note

Currently this template cannot remap reflective operations on NMS classes, you may need to manually locate them via mappings in `tools`.