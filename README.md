# TypeScript Setup

## 1. You need to have node installed in your pc
## 2. Open the project folder in vs code
## 3. Initialize the node project with `npm init -y`
## 4. Make sure you have TypeScript compiler installed `tsc --version`
## 5. Initialize the TypeScript project `tsc --init --rootDir src --outDir dist`
## 6. Now you have `tsconfig.json` file and you never need to touch this file again
## 7. Install TypeScript devDependency for watching changes in your TypeScript files and transpile them for you
## 8. Run this command `npm install --save-dev typescript`
## 9. In your vscode click `F1` and search for `Tasks: Configure Default Build Task`
## 10. From the dropdown that appears choose `tsc: watch - tsconfig.json`
## 11. Press `F1` again and search for `Tasks: Run Build Tasks` and by now it should be watching your changes!
