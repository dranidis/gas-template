# Google app script template

Node and npm

clasp

```
npm install -g @google/clasp
```

Type definitions for Apps Script

```
npm i -S @types/google-apps-script
```

## Edit the .clasp.json file

Paster the id of the google doc

## Login

```
clasp login
```

## upload the local files to Google Drive using the following clasp command:

```
clasp push --watch
```

This command watches for TypeScript file changes and uses typescript to compile the code and clasp to upload the project to Google Drive.
