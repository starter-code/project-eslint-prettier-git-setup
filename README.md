### Project Repo Setup

Good things to have:

- NPM +. NVM
- ESlint
- Prettier
- VSCode Workspace Settings
- Git + GitIgnore

#### NPM Setup

NPM
```
npm init --yes
```

NVM
```
touch .nvmrc
```

example file contents:
```
8.9.0
```

use NVM
```
nvm install
nvm use
```

#### ESlint Setup

```
npm i eslint
eslint --init
```

#### Prettier Setup

```
touch .pretterrc
```

settings:

```
{
"trailingComma": "es5",
"tabWidth": 2,
"semi": true,
"singleQuote": true
}
```

#### VSCode Workspace Settings

```
mkdir .vscode
cd .vscode
touch settings.json
```

settings:

```
{
"editor.formatOnSave": true
}
```

#### Git + GitIgnore

```
git init
```

```
touch .gitignore
```
