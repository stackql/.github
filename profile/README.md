<!-- web assets -->
[logo]: https://stackql.io/img/stackql-logo-bold.png "stackql logo"
[homepage]: https://stackql.io/
[docs]: https://stackql.io/docs
[blog]: https://stackql.io/blog

<!-- repos and links -->
[core]: https://github.com/stackql/stackql
[deploy]: https://github.com/stackql/stackql-deploy
[deployaction]: https://github.com/stackql/stackql-deploy-action
[license]: https://github.com/stackql/stackql/blob/main/LICENSE
[registry]: https://github.com/stackql/stackql-provider-registry
[contributing]: https://github.com/stackql/stackql/blob/main/CONTRIBUTING.md
[discussions]: https://github.com/orgs/stackql/discussions
[jupyterdemo]: https://github.com/stackql/stackql-jupyter-demo
[pystackql]: https://github.com/stackql/pystackql
[stackqljs]: https://github.com/stackql/stackqljs
[google2openapi]: https://github.com/stackql/google-discovery-to-openapi
[openapisaurus]: https://github.com/stackql/openapisaurus
[aws2openapi]: https://github.com/stackql/aws-cfn-schema-to-openapi
[azure2openapi]: https://github.com/stackql/stackql-azure-openapi
[codespaces]: https://github.com/stackql/stackql-codespaces-notebook
[actionsdemo]: https://github.com/stackql/stackql-actions-demo
[setupstackql]: https://github.com/stackql/setup-stackql
[stackqlassert]: https://github.com/stackql/stackql-assert
[stackqlexec]: https://github.com/stackql/stackql-exec
[middleware]: https://github.com/stackql/stackql-middleware
[playground]: https://github.com/stackql/stackql-playground
[server]: https://github.com/stackql/stackql-server
[anysdk]: https://github.com/stackql/any-sdk

<!-- badges -->
[latestreleasebadge]: https://img.shields.io/github/v/release/stackql/stackql?sort=semver "Latest Release"
[downloadsbadge]: https://img.shields.io/github/downloads/stackql/stackql/total "Downloads"
[licensebadge]: https://img.shields.io/github/license/stackql/stackql "License"

<!-- social -->
[twitter]: https://twitter.com/stackql
[discord]: https://discord.com/invite/xVXZ9d5NxN

[golang]: https://img.shields.io/badge/golang-%2300ADD8.svg?plastic&logo=go&logoColor=white
[typescript]: https://img.shields.io/badge/typescript-%23007ACC.svg?plastic&logo=typescript&logoColor=white
[javascript]: https://img.shields.io/badge/javascript-%23323330.svg?plastic&logo=javascript&logoColor=%23F7DF1E
[denodeploy]: https://img.shields.io/badge/deno%20deploy-000000?v&logo=deno&logoColor=white
[deno]: https://img.shields.io/badge/deno-000000?v&logo=deno&logoColor=white
[docker]: https://img.shields.io/badge/docker-%230db7ed.svg?plastic&logo=docker&logoColor=white
[react]: https://img.shields.io/badge/react-%2320232a.svg?plastic&logo=react&logoColor=%2361DAFB
[githubactions]: https://img.shields.io/badge/github%20actions-%232671E5.svg?plastic&logo=githubactions&logoColor=white
[openapi]: https://img.shields.io/badge/openapi-%236C757D.svg?plastic&logo=openapiinitiative&logoColor=white
[jupyter]: https://img.shields.io/badge/jupyter-F37626.svg?&plastic&logo=Jupyter&logoColor=white
[python]: https://img.shields.io/badge/python-3776AB.svg?plastic&logo=Python&logoColor=white
[npmjs]: https://img.shields.io/badge/npm-CB3837.svg?plastic&logo=nodedotjs&logoColor=white
[postgresql]: https://img.shields.io/badge/postgresql-4169E1.svg?plastic&logo=postgresql&logoColor=white

<!-- language: lang-none -->
<div align="center">

[![logo]][homepage]  
<!-- ![latestreleasebadge]
![downloadsbadge]
![licensebadge] -->

</div>

<div align="center">

[__🌟 Visit our main GitHub Repository »__][core]

</div>

<div align="center">
<p align="center">

[__📖 Read the docs »__][docs]  [__📝 Visit our blog »__][blog]  
[👥 About Us](#about-stackql-studios) ·
[🚀 Use Cases](#use-cases) ·
[🗂️ Key Repositories](#key-repositories) ·
[👐 Getting Involved](#getting-involved) ·
[🛠️ Services We Provide](#services-we-provide)

</p>
</div>

## 🏢 About StackQL Studios
StackQL Studios maintains [__`stackql`__][core] and related projects. We are software and data engineers who consider cloud and SaaS services, resources, and assets data sources.  The best way to interact with data is through *SQL*.  

We are building a unified analytics and IaC framework using SQL for interacting with cloud and SaaS resources and APIs.  Our provider registry is based OpenAPI and GraphQL definitions for cloud and SaaS providers; see [__`stackql-provider-registry`__][registry].   

Our config file-based provider plugin approach lowers the entry barrier for contributions compared to traditional code-intensive plugin frameworks.  Our SQL-based framework enables a broader audience of users without requiring them to learn yet another DSL.  

> 🌐 Simplifying multi-cloud cloud resource management, XOps, and observability using familiarity and power of SQL.

## 🎯 Use Cases
- **Simplified Cloud Auditing and Compliance**: Audit resource deployments and configurations across multiple cloud and SaaS providers using a simple SQL-based framework
- **Federated Entitlements and Identity Management**: Generate reports joining data from an IdP with entitlements in a SaaS, PaaS, or IaaS resource provider
- **FinOps and Cost Optimization**: Analyze global resource deployment across multiple providers to identify opportunities for cost recovery or savings
- **Custom Reporting and Dashboarding**: Create custom multi-cloud inventory reports
- **Multi-cloud Resource Management**: One consistent SQL-based framework for XOps across all cloud, IdP and SaaS providers
- **Automated Infrastructure as Code (IaC)**: Transactional multi-cloud infrastructure-as-code framework using a SQL ETL approach
- **CI/CD Integration for Deployment Validation**: Integrate StackQL in your CI/CD workflows to validate resource state or enforce compliance

## 🗄️ Key Repositories
| Repository | Languages | Description |
|------------|-----------|-------------|
| [__`stackql`__][core] | ![Go][golang] | StackQL core project that enables users to interact with cloud resources using SQL. |
| [__`stackql-provider-registry`__][registry] | ![OpenAPI][openapi] ![Deno Deploy][denodeploy] | A registry for cloud and SaaS providers for StackQL, generated from extensions to the providers' OpenAPI3 specifications. |
| [__`stackql-deploy`__][deploy] | ![Python][python] | Declarative, state-file-less, infrastructure-as-code using StackQL, see it on [pypi](https://pypi.org/project/stackql-deploy/). |
| [__`stackql-deploy-action`__][deployaction] | ![GitHub Actions][githubactions] ![Python][python] | GitHub Action to deploy or test stacks using `stackql-deploy`. |
| [__`stackql-jupyter-demo`__][jupyterdemo] | ![Python][python] ![Jupyter][jupyter] ![Docker][docker] | Jupyter hub image with StackQL, including `%stackql` magic commands along with some sample notebooks to get started |
| [__`stackql-codespaces-notebook`__][codespaces] | ![Python][python] ![Jupyter][jupyter] | Template repository to use StackQL in GitHub Codespaces, along with sample notebooks to get started  |
| [__`stackql-server`__][server] | ![PostgreSQL][postgresql] | Self contained StackQL server with a Postgres backend for relational algebra and temporary storage, see [stackql/stackql-server](https://hub.docker.com/r/stackql/stackql-server) |
| [__`stackqljs`__][stackqljs] | ![NPMJS][npmjs] ![JavaScript][javascript] ![TypeScript][typescript] ![Deno][deno] | StackQL client library for Deno and Node.js, see [npmjs](https://www.npmjs.com/package/@stackql/stackqljs) |
| [__`pystackql`__][pystackql] | ![Python][python] | PyPi package to use StackQL within Python or IPython applications, see [readthedocs](https://pystackql.readthedocs.io/en/latest/) |
| [__`stackql-actions-demo`__][actionsdemo] | ![GitHub Actions][githubactions] ![JavaScript][javascript] | Demonstration of the StackQL GitHub Marketplace Actions to use StackQL in GitHub Actions workflows |
| [__`setup-stackql`__][setupstackql] | ![GitHub Actions][githubactions] ![JavaScript][javascript] | GitHub Action to setup StackQL in an Actions workflow; see overview in the GitHub Actions [marketplace](https://github.com/marketplace/actions/stackql-studios-setup-stackql) |
| [__`stackql-assert`__][stackqlassert] | ![GitHub Actions][githubactions] ![JavaScript][javascript] | GitHub Action to run compliance or validation checks using StackQL in an Actions workflow; see overview in the GitHub Actions [marketplace](https://github.com/marketplace/actions/stackql-studios-stackql-assert) |
| [__`stackql-exec`__][stackqlexec] | ![GitHub Actions][githubactions] ![JavaScript][javascript] | GitHub Action to execute StackQL queries in an Actions workflow; see overview in the GitHub Actions [marketplace](https://github.com/marketplace/actions/stackql-studios-stackql-exec) |
| [__`google-discovery-to-openapi`__][google2openapi] | ![JavaScript][javascript] ![OpenAPI][openapi] | Extracts compliant OpenAPI3 specification from Google discovery docs |
| [__`aws-cfn-schema-to-openapi`__][aws2openapi] | ![JavaScript][javascript] ![OpenAPI][openapi] | Creates compliant OpenAPI3 specifications with StackQL extensions from AWS CloudFormation schema documents |
| [__`stackql-azure-openapi`__][azure2openapi] | ![JavaScript][javascript] ![OpenAPI][openapi] | Creates compliant OpenAPI3 specifications from Microsoft AutoRest |
| [__`openapisaurus`__][openapisaurus] | ![TypeScript][typescript] ![Deno][deno] ![OpenAPI][openapi] | StackQL provider development studio using Deno/TypeScript |
| [__`stackql-middleware`__][middleware] | ![TypeScript][typescript] ![Deno][deno] | Use StackQL with a public or private registry to submit SQL queries in API `POST` bodies to extract, project or mutate data (similar to GraphQL, but using SQL)  |
| [__`stackql-playground`__][playground] | ![TypeScript][typescript] ![React][react] | Front end application connecting to a [__`stackql-middleware`__][middleware] server |
| [__`any-sdk`__][anysdk] | ![Go][golang] ![OpenAPI][openapi] | Golang library to support traversal algorithms on StackQL augmented openapi doc structure and SQL semantics. |

## 👐 Getting Involved
We welcome contributions and community involvement in StackQL. Whether you're interested in contributing code (including SQL queries or new providers), reporting bugs, or requesting features, your input is valuable to us.

- [**Contributing Guidelines**][contributing]
- [**Discussions & Support**][discussions]

📜 StackQL is released under the [MIT License][license].

## 🛠️ Services We Provide
StackQL Studios provides custom audit services to create and automate client reports for Cloud Security Posture Management, Entitlements or User Access Management, FinOps/Cost Optimization, Network Analysis, Multi-Cloud Inventory Analysis, and more.  Contact us at [info@stackql.io](mailto:info@stackql.io)

---

🌍 For more information, visit our [website][homepage], follow us on [X][twitter], or join our [Discord Server][discord].