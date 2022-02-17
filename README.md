# Nextjs Template

A minimal Nextjs template based on create-next-app with typescript, prettier, and pre-commit hooks configured.

### Code Style Changes (compared to default create-next-app)

-   Tab size: 4 spaces
-   Always add semicolons
-   Always use double quotes

### Use This Template

```shell
git clone https://github.com/DanielHeEGG/nextjs-template.git
cd nextjs-template

# if using different node version
nodeenv env --node=16.14.0
source ./env/bin/activate

# rename project in package.json before running
npm install

# if changed prettier settings
npx prettier --write .

npm run dev
```
