# Nuxeo Case Management Workflow Dashboards Parent Project

This repository is for building the Plugin and Marketplace package for the Case Management Workflow Dashboards.

This sample uses [Nuxeo Data Visualzation](https://doc.nuxeo.com/x/WZCRAQ) to present a dashboard for each Case Management Workflow.

# Building

[![Build Status](https://qa.nuxeo.org/jenkins/buildStatus/icon?job=Sandbox/sandbox_cm-workflow-dashboards-parent-master)](https://qa.nuxeo.org/jenkins/view/sandbox/job/Sandbox/job/sandbox_cm-workflow-dashboards-parent-master/)

Then navigate into the root folder for this project and run:

    mvn clean install

The Marketplace package will be placed in the `cm-workflow-dashboards-mp/target` folder.

# Deploying

You may deploy the zip using `nuxeoctl` or the Nuxeo Admin Center.

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