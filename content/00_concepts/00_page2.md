+++
title = "Config hierarchy"
chapter = false
weight = 3
+++


Taskcat uses two config files: _**Global config**_  and _**Project config**_

### Project Config
This config file provides project-specific configurations.

The project config file is located in the root of your project folder _`<PROJECT_ROOT>/.taskcat.yml`_

Since each lab uses the `cfn-project` directory as the _project root_, this is where our project-specific taskcat config file will reside.

### Global config
This config file provides global settings that become defaults for **all projects**.

The global config file is located in user's home-directory.  _`~/.taskcat.yml`_

_***Note: The project-level configuration takes precedence over any items in the global config.***_
__***However, Global parameters take precedence over project-level parameters. See below for more details.***__

