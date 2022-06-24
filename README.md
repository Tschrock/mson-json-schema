MSON Schema
===========
A [JSON schema](https://json-schema.org/) for [MSON](https://github.com/MineLittlePony/Mson) models

## Usage

### VS Code
Copy the settings from `./.vscode/settings.json` to your project (you might need to modify the `fileMatch` option if you store your models in a different directory).

### Other IDEs
Google how to configure JSON Schemas in your IDE.

### Generic
Add the schema as a property at the top of your JSON file:

```json
{
    "$schema": "https://json.cp3.es/com.minelittlepony.mson/model.json"
}
```
