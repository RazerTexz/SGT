# Simple Godot Template

## Configuring The Workflow
The workflow variables are defined in [godot-export.yml](https://github.com/RazerTexz/SGT/blob/main/.github/workflows/godot-export.yml)

### Workflow Variables
| Variable Name | Description |
| --- | --- |
| `GODOT_VERSION` | The Godot version for exporting the project |
| `DEBUG_KEYSTORE_ALIAS` | The alias name for the debug keystore |
| `DEBUG_KEYSTORE_PASSWORD` | The password for the debug keystore |
| `RELEASE_KEYSTORE_ALIAS` | The alias name for the release keystore |
| `RELEASE_KEYSTORE_PASSWORD` | The password for the release keystore |

## Mono Setup
Read [this](https://github.com/firebelley/godot-export?tab=readme-ov-file#mono-builds)

## Android Setup
Make sure to enable the `import_etc2_astc` option in project settings!

## Credits
- [Godot Engine](https://godotengine.org)
- [FireBelley](https://github.com/firebelley) for the [workflow action](https://github.com/firebelley/godot-export)
