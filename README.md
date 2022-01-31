## Jetstream Labs Project Scaffold

This package is a simple project scaffold that keeps you from having to constantly install best practice tools for commits, releases and code formatting.

This package installs the following tools:

1. **Semantic Release**
2. **Husky**
3. **Prettier**
4. **Commitlint**
5. **StyleCI Cli** *(requires subscription)*

Of course it also includes sensible config files for all the given packages.

### Intended Audience

This package was designed with PHP developers in mind, but feel free to download it and modify it to your needs.

### Installation

It can be installed via git clone or via composer.

```sh
% git clone https://github.com/jetstreamlabs/scaffold <your-project-dir>
```

or 

```sh
% composer create-project jetstreamlabs/scaffold <your-project-dir>
```

then 

```sh
% cd <your-project-dir>

% rm -rf .git // if still present

% composer install 
% npm install
```

### Additional Setup

Open `release.config.js` and go to line **80** and change the repository url to the one you'll be using to store your project.

Go to line **92** and edit the name of your Changelog file heading.

If you have a **StyleCI** subscription you can use the `husky` pre-commit hook that's set up in the `.husky` directory.

That's it, build something cool

 