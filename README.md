# test-library

This is a npm library for private.

## Modules

* a
* bb

## Usage of private library.

* Generate Personal Access Token**

  * Transit to Developer settings > Personal access tokens

  * Generate private key as "forReadPackages"

* Write `.npmrc` file

  * Write following statement to `.npmrc` file.

```shell:.npmrc
@Landmaster135:registry="https://npm.pkg.github.com"
//npm.pkg.github.com/:_authToken={generated Personal Access Token}
```

* Install package

  * Install package to project in command line

```shell
npm i @Landmaster135/{packaged library}
```

* If more detail is needed, Refer here.

  -> [GitHub Packagesを使って自作ライブラリを管理しよう](https://engineer-first.net/create-github-packages)
