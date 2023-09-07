# Docs

## Overview

The `docs` folder contains two subfolders - `user` and `contributor`. 
The `user` subfolder contains the end-user documentation, which is displayed on the [Kyma website](https://kyma-project.io/#/). Depending on your module needs, the subfolder must include overview, usage, or technical reference documents. To display the content on the website properly, create a `_sidebar.md` file in the `user` and list the documents it contains there. For more information on how to publish user documentation, follow [this guide](https://github.com/kyma-project/community/blob/main/docs/guidelines/content-guidelines/01-user-docs.md).

The `contributor` subfolder includes any developer-related documentation to help them manually install, develop, and operate a module.

All documents must be properly numbered according to the structure proposed in [this decision record](https://github.tools.sap/kyma/community/issues/180) to have a common structure across all modules.

You can divide your documentation into more subfolders to avoid having too many documents in one `docs/user` or `docs/contributor` folder. For example, if you have many technical reference documents, you can create a `technical reference` subfolder in `docs/user` and keep relevant documentation there. Each subfolder in the `user` folder must have its own `_sidebar.md` file with the links to the main module page and the list of docs it contains.