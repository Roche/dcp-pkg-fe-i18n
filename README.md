<a href="https://open-dcp.ai" target="_blank"><img src="https://docs.open-dcp.ai/assets/img/logo.png" width="400" alt="Laravel Logo"></a>

##### Pioneering open-source GMP analytics for a more accessible, enjoyable, and productive data-driven future.

<a href="https://open-dcp.ai"><img src="https://img.shields.io/badge/license-Apache--2.0-blue.svg" alt="License Apache-2.0"></a> <a href="https://www.repostatus.org/#wip"><img src="https://www.repostatus.org/badges/latest/wip.svg" alt="Project Status: WIP – Initial development is in progress, but there has not yet been a stable, usable release suitable for the public."></a>

## About Data Computation Platform (DCP)

The [Data Computation Platform (DCP)](https://open-dcp.ai) is a browser-based application enabling various data analytics and visualization concepts for (real-time) process monitoring and reporting. It serves as the nexus between innovation and compliance in pharmaceuticals, enabling seamless integration of tools for GxP-compliant advancements. Validated for GxP compliance, DCP facilitates both the parallel usage of apps in a regulated context and as engineering or information-only tools. Evolving from a closed system to an open, collaborative platform, DCP embodies resilience, overcoming challenges to drive collective progress. Ultimately, DCP signifies the union of innovation and compliance in Pharma 4.0, propelling unified advancements while steadfastly meeting regulatory standards.

### Repository Structure

DCP delivers its dedicated data analytics and visualization concepts as modules extending the DCP Framework. These modules seamlessly integrate with the framework and foster synergies to reduce development and maintenance costs while increasing delivery speed.

#### DCP Modules

The following list summarizes the framework components and modules of DCP:

- [**Core**](https://open-dcp.ai/architecture)
    - Backend: [Core](hhttps://gitlab.com/roche/dcp/platform/backend/core/core) | [Framework](https://gitlab.com/roche/dcp/platform/backend/core/framework) | [Mock Data Sources](https://gitlab.com/roche/dcp/platform/backend/core/mock-data-sources)
    - Frondend: [Base](https://gitlab.com/roche/dcp/platform/frontend/apps/core/base) | [Administration](https://gitlab.com/roche/dcp/platform/frontend/apps/core/administration) | [Login](https://gitlab.com/roche/dcp/platform/frontend/apps/core/login) | [Side Menu](https://gitlab.com/roche/dcp/platform/frontend/apps/core/side-menu) | [Top Navigation](https://gitlab.com/roche/dcp/platform/frontend/apps/core/top-navigation)
    - Calculation: [acdcClient](https://gitlab.com/roche/dcp/analytical-core/r-language/core/acdcclient) | [acdcDataFactory](https://gitlab.com/roche/dcp/analytical-core/r-language/core/acdcdatafactory) | [acdcReport](https://gitlab.com/roche/dcp/analytical-core/r-language/core/acdcreport)
- [**API Service**](https://open-dcp.ai/get-started#api)
    - Backend: [Gateway](https://gitlab.com/roche/dcp/platform/backend/api-service/gateway) | [Filebuilder](https://gitlab.com/roche/dcp/platform/backend/api-service/filebuilder)
    - Frondend: [API Service](https://gitlab.com/roche/dcp/platform/frontend/apps/api-service)
- [**Basic**](https://open-dcp.ai/module/basic)
    - Backend: [Basic](https://gitlab.com/roche/dcp/platform/backend/basic)
    - Frondend: [Basic](https://gitlab.com/roche/dcp/platform/frontend/apps/basic)
    - Calculation: [Basic](https://gitlab.com/roche/dcp/analytical-core/r-language/modules/basic)
- [**ChromTA**](https://open-dcp.ai/module/chromta)
    - Backend: [ChromTA](https://gitlab.com/roche/dcp/platform/backend/chromta)
    - Frondend: [ChromTA](https://gitlab.com/roche/dcp/platform/frontend/apps/chromta)
    - Calculation: [ChromTA](https://gitlab.com/roche/dcp/analytical-core/r-language/modules/chromta)
- [**DReAM**](https://open-dcp.ai/module/dream)
    - Backend: [DReAM](https://gitlab.com/roche/dcp/platform/backend/dream)
    - Frondend: [DReAM](https://gitlab.com/roche/dcp/platform/frontend/apps/dream)
    - Calculation: [DReAM](https://gitlab.com/roche/dcp/analytical-core/r-language/modules/dream)
- [**MVDA**](https://open-dcp.ai/module/mvda)
    - Backend: [MVDA](https://gitlab.com/roche/dcp/platform/backend/mvda)
    - Frondend: [MVDA](https://gitlab.com/roche/dcp/platform/frontend/apps/mvda)
    - Calculation: [MVDA](https://gitlab.com/roche/dcp/analytical-core/r-language/modules/mvda)
- [**SAW**](https://open-dcp.ai/module/saw)
    - Backend: [SAW](https://gitlab.com/roche/dcp/platform/backend/saw)
    - Frondend: [SAW](https://gitlab.com/roche/dcp/platform/frontend/apps/saw)
    - Calculation: [SAW](https://gitlab.com/roche/dcp/analytical-core/r-language/modules/saw)

#### Git Submodules

Web components and several other frontend related components are implemented as Git submodules to enhance reusability.

- [App](https://gitlab.com/roche/dcp/platform/frontend/submodules/dc-app)
- [Assets](https://gitlab.com/roche/dcp/platform/frontend/submodules/dc-assets)
- [Batch](https://gitlab.com/roche/dcp/platform/frontend/submodules/dc-batch)
- [Core](https://gitlab.com/roche/dcp/platform/frontend/submodules/dc-core)
- [Filter](https://gitlab.com/roche/dcp/platform/frontend/submodules/dc-filter)
- [GxP Status](https://gitlab.com/roche/dcp/platform/frontend/submodules/dc-gxp-info)
- [GxP Web Components](https://gitlab.com/roche/dcp/platform/frontend/submodules/dc-gxp-web-components)
- [Layout](https://gitlab.com/roche/dcp/platform/frontend/submodules/dc-layout)
- [Pages](https://gitlab.com/roche/dcp/platform/frontend/submodules/dc-pages)
- [Sensor](https://gitlab.com/roche/dcp/platform/frontend/submodules/dc-sensor)
- [Shared](https://gitlab.com/roche/dcp/platform/frontend/submodules/dc-shared)
- [Site Store](https://gitlab.com/roche/dcp/platform/frontend/submodules/dc-site-store)
- [Store](https://gitlab.com/roche/dcp/platform/frontend/submodules/dc-store)
- [User](https://gitlab.com/roche/dcp/platform/frontend/submodules/dc-user)

#### Customizer Tool

To comply with Roche's branding policies, you must use the customizer tool to remove Roche-specific branding elements before distribution or use in a production environment. The customizer tool modifies only the visual elements such as logos, colors, and fonts, without altering any functional aspects of the project.

We encourage all users and organizations to use this customizer tool to adjust the visual branding to fit their own company's branding guidelines. This ensures that the appearance of the frontend user interface aligns with your company's identity while maintaining the functional integrity of the project.

You can find the customizer tool and instructions for its use at the following link: [Customizer](https://gitlab.com/roche/dcp/platform/frontend/customizer)

## Learning DCP

A very simple [Get Started](https://open-dcp.ai/get-started) guide is available on our website. To delve deeper into the application, please refer to the documentation provided on [docs.open-dcp.ai](https://docs.open-dcp.ai).

## Security

If you think you have found a security vulnerability in DCP or one of its modules, you can report it using our [Contact Form](https://open-dcp.ai/contact) or by emailing us at [info@open-dcp.ai](mailto:info@open-dcp.ai). All security vulnerabilities will be promptly addressed.

## Contributing

The contribution guide can be found in the [DCP documentation](https://docs.open-dcp.ai/contribution_guide/1.0/code_of_conduct).

## License

DCP and its modules are open-source and licensed under the [Apache License Version 2.0](https://www.apache.org/licenses/LICENSE-2.0.txt).

### Notice
This project includes branding specific to Roche. When redistributing or using this project, you must use the provided customizer tool to remove Roche-specific branding elements that pertain solely to the appearance of the frontend user interface.
