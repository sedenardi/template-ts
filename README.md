# template-js
Template for javascript projects.

### Usage

    newProj=<your project folder>
    git clone --depth=1 --branch=master https://github.com/sedenardi/template-ts.git $newProj
    cd $newProj
    rm -rf .git
    NODE_ENV=development npm install

### Contains

- .gitignore for node_modules, .DS_Store, and package-lock
- eslint & babel-eslint
- .eslintrc rules
