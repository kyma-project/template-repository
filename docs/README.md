# Docs

## Overview

The `docs` folder contains three subfolders - `user`, `contributor`, and, optionally, `operator`.

The `user` subfolder contains the end-user documentation, which is displayed on the [Kyma website](https://kyma-project.io/#/) and in the SAP Help Portal. Depending on your module needs, the subfolder must include overview, usage, or technical reference documents. To display the content on the website properly, create a `_sidebar.ts` file in the `user` subfolder and list the documents it contains there. For more information on how to publish user documentation, follow [this guide](https://github.com/kyma-project/community/blob/main/docs/guidelines/content-guidelines/01-user-docs.md).

The `contributor` subfolder includes any developer-related documentation to help them manually install, develop, and operate a module.

The `operator` subfolder is optional. Create it only if your module/component is delivered to restricted markets. The subfolder includes documentation relevant to operators. However, do not duplicate any existing documentation from the `user` or `contributor` folders into the `operator` folder.

To have a common structure across all modules, all documents must be properly numbered according to the following structure.

It is suggested to use the following titles if you have the content that matches them; otherwise use your own, more suitable titles, or simply skip the ones you find irrelevant.

   - 00-xx-overview
   - 01-xx-tutorial/configuration  
   - 02-xx-usage  
   - 03-xx-troubleshooting

where `xx` is the number of the given document. For example:

   ```bash
   00-00-overview-telemetry-manager
   00-10-overview-logs
   00-20-overview-traces
   00-30-overview-metrics
   01-10-configure-logs 
   01-20-configure-traces 
   01-30-configure-metrics
   02-10-use-logs
   02-20-use-traces
   02-30-use-metrics
   (...)
   ```

If you have other content that does not fit into the above topics, create your own 04-10-module-specific document(s).

You can divide your documentation into subfolders to avoid having too many documents in one `docs/user` or `docs/contributor` folder. For example, if you have many technical reference documents, you can create a `technical reference` subfolder in `docs/user` and keep relevant documentation there.
