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

a copy of the babak.pgsql-0.0.1 should be under `~/work/vscode-extensions` as well
