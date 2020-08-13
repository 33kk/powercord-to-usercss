# Powercord to UserCSS

## Usage

- copy files to theme folder
- npm i
- node powercord-to-usercss.js

## powercord-to-usercss.json

```json
{
	"manifestPath": "path to powercord_manifest.json, default: ./powercord_manifest.json",
	"outPath":      "output path, default: ./{theme name}.user.css"
	"name":         "override name in usercss metadata",
	"description":  "override description in usercss metadata",
	"namespace":    "override namespace in usercss metadata",
	"author":       "override author in usercss metadata",
	"license":      "override license in usercss metadata",
	"version":      "override version in usercss metadata",
}
```
