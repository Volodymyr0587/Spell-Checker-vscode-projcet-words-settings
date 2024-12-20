# Spell-Checker-vscode-projcet-words-settings

- Add this to `settings.json` file:

```
"cSpell.customDictionaries": {
    "project-words": {
      "name": "project-words",
      "path": "${workspaceRoot}/project-words",
      "description": "Words used in this project",
      "addWords": true
    },
    "custom": true, // Enable the `custom` dictionary
    "internal-terms": false // Disable the `internal-terms` dictionary
  },
```

- Create `project-words` file in root of your project (add words if needed):

```
autoprefix
dbclient
Devdb
DEVSENSE
embeddedhtml
esbenp
lockb
onecentlin
Palenight
phpserver
phpstorm
phptools
phpunit
```
