### Project Repo Setup

Good things to have:

- NPM
- ESlint
- Prettier
- VSCode Workspace Settings
- Git + GitIgnore

#### NPM Setup

```
npm init --yes
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
