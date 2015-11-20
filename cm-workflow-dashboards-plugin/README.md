# About Nuxeo Case Management Workflow Dashboards Plugin

This Nuxeo plugin uses [Nuxeo Data Visualzation](https://doc.nuxeo.com/x/WZCRAQ) to create dashboards for the Nuxeo Case Management Showcase.

It depends on the [cm-workflow-dashboards-elements](https://github.com/nuxeo-sandbox/cm-workflow-dashboards-elements) Polymer component.

# Requirements

See [CORG/Compiling Nuxeo from sources](http://doc.nuxeo.com/x/xION)

Building this sample requires the following software:

- [Node.js] (http://nodejs.org)
- [Bower] (http://bower.io)

# Building

Navigate into the folder that contains `pom.xml`.

    mvn clean install

The plugin will be placed in the `target` folder.

# Deploying

It is recommended to deploy the marketplace package. But the plug-in may be installed directly as well. 

Copy JAR file into `$NUXEO_HOME/nxserver/plugins/`.

# Usage

Once installed in the Case Manangement Showcase, these dashboards are available under ADMIN | Workflow.

There is also a bundled Web application for testing at `http://yourserver/nuxeo/cm-workflow-dashboards`.

# Resources

## Reporting issues

Contact [jfletcher@nuxeo.com](mailto:jfletcher@nuxeo.com)

# Licensing

[GNU Lesser General Public License (LGPL) v2.1](http://www.gnu.org/licenses/lgpl-2.1.html)

# About Nuxeo

Nuxeo dramatically improves how content-based applications are built, managed and deployed, making customers more agile, innovative and successful. Nuxeo provides a next generation, enterprise ready platform for building traditional and cutting-edge content oriented applications. Combining a powerful application development environment with SaaS-based tools and a modular architecture, the Nuxeo Platform and Products provide clear business value to some of the most recognizable brands including Verizon, Electronic Arts, Netflix, Sharp, FICO, the U.S. Navy, and Boeing. Nuxeo is headquartered in New York and Paris. More information is available at [www.nuxeo.com](http://www.nuxeo.com).