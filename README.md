# Architect plugin for Craft CMS 3.x

A plugin for importing and exporting content models from [Craft CMS](http://craftcms.com/) using JSON.

![Screenshot](resources/img/the-architect.png)

Related: [Architect for Craft 2.x](https://github.com/Pennebaker/craftcms-thearchitect)

## Requirements

This plugin requires Craft CMS 3.0.0-RC1 or later.

## Installation

To install the plugin, follow these instructions.

1. Open your terminal and go to your Craft project:

        cd /path/to/project

2. Then tell Composer to load the plugin:

        composer require pennebaker/craft-architect

3.
    a. In the terminal run
       
               ./craft install/plugin architect

    ***or***
    
    b. In the Control Panel, go to Settings → Plugins and click the “Install” button for Architect.

## Architect Overview

The architect can import and export just about anything in craft that needs to be configured.
*ex. It can help with migrations by adding new fields needed by a structuring update and export existing fields for use on another website.*

## Configuring Architect

There isn't much to configure in Architect right now.

## JSON Schema
The example / syntax schemas are located on the [Repo's Wiki](https://github.com/Pennebaker/craft-architect/wiki)

If you're using the [Atom text editor](https://atom.io/), you can download a [snippet library](https://github.com/Emkaytoo/craft-json-snippets) to help speed up your writing custom models for the plugin. *(Might not be updated for the Craft 3 version of architect yet)*

## Using Architect

Visit architect in the admin CP for importing / exporting just about anything using JSON.

Current Working Imports:
- Site Groups
- Sites
- Sections
- Entry Types
- Asset Volumes
- Asset Transforms
- Tag Groups
- Category Groups
- Field Groups
- Fields
- Global Sets

Current Working Exports:
- Site Groups
- Sites
- Sections
- Entry Types
- Asset Volumes
- Asset Transforms
- Tag Groups
- Category Groups
- Field Groups
- Fields
- Global Sets

## Architect Roadmap

Some things to do, and ideas for potential features:

* Convert plugin for use with Craft 3

[2.0.0] ***complete***
- Importing

[2.1.0] ***complete***
- Exporting

[2.2.0] ***complete***
- Importing Users
- Exporting Users

[2.3.0] ***in-progress***
- Command Line
- Import and Update

[2.4.0] ***brainstorming***
- Migrations

Brought to you by [Pennebaker](https://pennebaker.com)
