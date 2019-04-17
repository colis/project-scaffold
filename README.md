# Pragmatic Project Scaffold

The Pragmatic Project Scaffold is a command line tool to quickly initialise a starter theme or plugin for your new project. It adheres to all Pragmatic's best practice coding standards and has been reviewed for security, performance, and scalability. This project is aimed specifically at the work that Pragmatic does, but we welcome all community contributions.

If you have an update for the theme or plugin that is generated, please submit those issues or pull requests with the associated repository:

[View the plugin repository](https://github.com/colis/plugin-scaffold)

## Set Up from Github

1.  Clone the [repository](https://github.com/colis/project-scaffold) locally
2.  Run `cd project-scaffold`
3.  Run `npm install`
4.  Run `npm link` to make the `create-pragmatic` command global

## Project Types

*   plugin

## Example Usage

`cd <your-project-directory>`

`create-pragmatic plugin human-plugin-name`

`npm install`

## Updating this tool

`create-pragmatic` is in active development. To get the latest, navigate to this folder in your home directory (or wherever else you have it installed) and `git pull`.

## Learn more about the packages used with this project

*   [Chalk](https://www.npmjs.com/package/chalk)
*   [Commander](https://www.npmjs.com/package/commander)
*   [FS extra](https://www.npmjs.com/package/fs-extra)
*   [Git clone](https://www.npmjs.com/package/git-clone)
*   [Path](https://www.npmjs.com/package/path)
*   [Replace in file](https://www.npmjs.com/package/replace-in-file)
