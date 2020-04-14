# Aporeto Cook Book

This repository contains recipes for Aporeto.

You can import them in your namespace to enhance your life.
If you believe you have a nice recipe and you feel like sharing it,
please open a pull request.

To import a recipe:

```shell
apoctl api import -n /yournamespace --file ./recipe.yaml
```

Or directly from Github:

```shell
apoctl api import -n /yournamespace --url https://raw.githubusercontent.com/aporeto-inc/cookbook/master/recipe-name.yaml
```

## Contribution

You already understand the power of recipes or want to understsand how it works?

Check out these two links:

* [Blog article about Recipes](https://devblog.aporeto.us/post/recipes/)
* [Example of a simple recipe](https://github.com/aporeto-inc/cookbook/blob/master/TEMPLATE.yaml)
