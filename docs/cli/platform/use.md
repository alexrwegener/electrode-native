## `ern platform use`

#### Description

* Switch to (or activate) a specified platform version  
* Run the the `ern platform install` command beforehand if the version is not already installed

#### Syntax

`ern platform use <version>`

**Arguments**

`<version>`

* The Electrode Native version to activate.

#### Remarks

* If the target platform version is not installed locally, the `ern platform use <version>` command runs the [ern platform install] command which installs the version—before switching to the specified version.

[ern platform install]: ./install.md