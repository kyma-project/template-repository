# Docs

## Overview

The docs folder contains two subfolders - `user` and `contributor`. 
The `user` subfolder contains the end-user documentation, including any overview, usage or troubleshooting documents. The content of this folder is displayed on the [Kyma website](https://kyma-project.io/#/). To have the content properly displayed on the website, you must add your documentation to the `_sidebar.md` file that must be created in the `user` folder. For more information on how to use `_sidebar.md`, follow [this guide](https://github.com/kyma-project/community/blob/main/docs/guidelines/content-guidelines/01-user-docs.md#publish-a-document-from-a-new-module-repostory).

The `contributor` subfolder includes any developer-related documentation to help you manually install, develop, and operate a module.

All documents must be properly numbered according to the structure proposed in [this decision record](https://github.tools.sap/kyma/community/issues/180) to have a common structure across all modules.

You can divide your documentation into relevant folders to avoid many documents in one `docs/user` or `docs/contributor` folder. For example, if you have many technical reference documents, you can create a `technical reference` folder in `docs/user`. Each folder must have its own `_sidebar.md` file with the links to the main module page and to the docs located in the folder.