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
2. Go into doubleflints `extension` directory and point to `ln -s ../../babak.pgsql-0.0.1/syntaxes/pgsql.tmLanguage`
3. Refresh vscode

a copy of the babak.pgsql-0.0.1 should be under `~/work/2018/feb/` as well
