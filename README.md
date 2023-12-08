## sp-fx-manifest-file-wp-demo

Refer file src/webparts/spFxManifestFileWpDemo/SpFxManifestFileWpDemoWebPart.manifest.json

Manifest File Demo WP - Here we have done below

Changed WP Group from Default to Text Media Content

Refer - 
developer.microsoft.com/json-schemas/spfx/client-side-web-part-manifest.schema.json

Added a new Icon from Fluent UI ICONN 

Refer - https://developer.microsoft.com/en-us/fluentui#/styles/web/icons

Enable Full Column Width Section Layout

Disable on Classic SharePoint Site

Hide WP from Toolbox

Inherit theme properties

# Screenshot of the Webpart 

src/WPOutput

# Environment Setup

npm install -g @microsoft/generator-sharepoint@1.9.1

npm install -g gulp@3.9.1

npm install -g yo@3.1.0

# Building the code
## Clone this repository
## Ensure that you are at the solution folder 
## in the command-line run:

npm install

gulp build

gulp serve

# Applies to

* [SharePoint Framework](https://learn.microsoft.com/sharepoint/dev/spfx/sharepoint-framework-overview)
* [Microsoft 365 tenant](https://learn.microsoft.com/sharepoint/dev/spfx/set-up-your-development-environment)

> Get your own free development tenant by subscribing to [Microsoft 365 developer program](http://aka.ms/m365devprogram)

# Contributor

* [Rakesh Kamble](https://github.com/RackeshKamble)

# Disclaimer

**THIS CODE IS PROVIDED *AS IS* WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING ANY IMPLIED WARRANTIES OF FITNESS FOR A PARTICULAR PURPOSE, MERCHANTABILITY, OR NON-INFRINGEMENT.**
