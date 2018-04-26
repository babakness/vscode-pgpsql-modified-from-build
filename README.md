To hack doubleflint's language file,

1. Open that extensions package.json and edit
```javascript
		"grammars": [
			{
				"language": "pgsql",
				"scopeName": "source.plpgsql.postgres",
				"path": "./extension/babak.tmLanguage"
			}
		],
```
2. **Get color coding to work**. Go into doubleflints `extension` directory and point to `ln -s ~/work/vscode-extensions/vscode-pgpsql-modified-from-build/syntaxes/pgsql.tmLanguage babak.tmLanguage`
3. Refresh vscode

a copy of this repo is under `~/work/vscode-extensions/`

PS - Regarding python showing this

local source @ ~/work/2018/mar/vscode-pgpsql-modified-from-build/
