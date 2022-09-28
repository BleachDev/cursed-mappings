# Cursed Mappings

The mapping repo hosting all the mappings you definetely shouldn't use.

## Usage

To use any of these mappings you must add this to the repositories block in your build.gradle file:
```gradle
maven {
    name = "cursed-mappings"
    url = "https://raw.githubusercontent.com/BleachDev/cursed-mappings/main/"
}
```


### MCP Mappings on Legacy Fabric (1.3.2 - 1.12.2)
To use MCP on Legacy Fabric, change the yarn_mappings property in gradle.properties to this:
```gradle
yarn_mappings = <version>+build.mcp
```

### Yarn Mappings on Forge
`Coming Soon?`
