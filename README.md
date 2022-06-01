# Reader Marketplace

An official store of Reader plugins.

## Installation

To enable a plugin in your reader app just click on the *Marketplace* button in the bottom right menu or head straight over to https://read.readwise.io/marketplace. There you can browse and manage all available plugins.

## Creating a Plugin

To create a Reader plugin you need to first create a plugin repository and then make a pull request to this repository with your plugin metadata added in `plugins.json` file. Each entry in the array should specify the following:

```json
{
    "name": "Name of your plugin",
    "description": "Long description of what your plugin does.",
    "packageName": "reader-example-plugin",
    "url": "URL to the plugin's github repository",
    "version": "1.0.0",
    "author": "Plugin's author"
  }
```



