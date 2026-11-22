<!-- web assets -->
[logo]: https://stackql.io/img/stackql-logo-bold.png "stackql logo"
[homepage]: https://stackql.io/
[docs]: https://stackql.io/docs
[blog]: https://stackql.io/blog

<!-- repos and links -->
[core]: https://github.com/stackql/stackql
[registry]: https://github.com/stackql/stackql-provider-registry
[registry-org]: https://github.com/stackql-registry
[deploy]: https://github.com/stackql/stackql-deploy-rs
[setupstackql]: https://github.com/stackql/setup-stackql
[stackqlassert]: https://github.com/stackql/stackql-assert
[stackqlexec]: https://github.com/stackql/stackql-exec
[deployaction]: https://github.com/stackql/stackql-deploy-action
[pystackql]: https://github.com/stackql/pystackql
[omnisdk]: https://github.com/stackql-labs/omnisdk
[workbench]: https://github.com/stackql/stackql-workbench
[psql-wire]: https://github.com/stackql/psql-wire
[deploy-crates]: https://crates.io/crates/stackql-deploy
[crates-mcp]: https://crates.io/crates/stackql-mcp
[npmjs-mcp]: https://www.npmjs.com/package/@stackql/mcp-server
[nuget-mcp]: https://www.nuget.org/packages/StackQL.Mcp
[nuget-mcp-agent-fwk]: https://www.nuget.org/packages/StackQL.Mcp.AgentFramework
[pypi-mcp]: https://pypi.org/project/stackql-mcp-server/
[oci-mcp]: https://hub.docker.com/r/stackql/stackql-mcp

[license]: https://github.com/stackql/stackql/blob/main/LICENSE
[contributing]: https://github.com/stackql/stackql/blob/main/CONTRIBUTING.md
[discussions]: https://github.com/orgs/stackql/discussions

<!-- badges -->
[latestreleasebadge]: https://img.shields.io/github/v/release/stackql/stackql?sort=semver "Latest Release"
[downloadsbadge]: https://img.shields.io/github/downloads/stackql/stackql/total "Downloads"
[dockerpullsbadge]: https://img.shields.io/docker/pulls/stackql/stackql "Docker Pulls"
[licensebadge]: https://img.shields.io/github/license/stackql/stackql "License"
[orgstars]: https://img.shields.io/github/stars/stackql?style=flat&label=org%20stars "GitHub Org Stars"

<!-- social -->
[x]: https://x.com/stackql
[discord]: https://discord.com/invite/xVXZ9d5NxN

<!-- languages -->
[golang]: https://img.shields.io/badge/golang-%2300ADD8.svg?plastic&logo=go&logoColor=white
[rust]: https://shields.io/badge/-Rust-3776AB?style=flat&logo=rust
[typescript]: https://img.shields.io/badge/typescript-%23007ACC.svg?plastic&logo=typescript&logoColor=white
[javascript]: https://img.shields.io/badge/javascript-%23323330.svg?plastic&logo=javascript&logoColor=%23F7DF1E
[githubactions]: https://img.shields.io/badge/github%20actions-%232671E5.svg?plastic&logo=githubactions&logoColor=white
[openapi]: https://img.shields.io/badge/openapi-%236C757D.svg?plastic&logo=openapiinitiative&logoColor=white
[python]: https://img.shields.io/badge/python-3776AB.svg?plastic&logo=Python&logoColor=white
[npmjs]: https://img.shields.io/badge/npm-CB3837.svg?plastic&logo=nodedotjs&logoColor=white
[postgresql]: https://img.shields.io/badge/postgresql-4169E1.svg?plastic&logo=postgresql&logoColor=white
[sqlbadge]: https://img.shields.io/badge/sql-0F4C81.svg?plastic&logo=sqlite&logoColor=white
[dotnet]: https://img.shields.io/badge/.NET-5C2D91?style=badge&logo=.net&logoColor=white
[docker]: https://img.shields.io/badge/docker-%230db7ed.svg?plastic&logo=docker&logoColor=white

<!-- language: lang-none -->
<div align="center">

[![logo]][homepage]  
![latestreleasebadge]
![orgstars]
![downloadsbadge]
![dockerpullsbadge]
![licensebadge]

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

> 🔍 **Looking for StackQL Provider Dev Projects** Head to the [__`stackql-registry`__][registry-org] GitHub org.

## Pillars of StackQL

The three pillars of StackQL Studios are:

- **Relevance**.  Make users more productive and empowered.
- **Reliability**.  Do what it says on the outside of the box.
- **Elegance**.  As simple as possible, but no simpler.  Ease of uptake and use.

### Development Streams

These are the key streams in ongoing development:

1. RDBMS functionality, centred on [the `stackql` core][core]. SQL logic and ACID semantics atop TCP/IP, local process calls.
2. Generic wire-protocol agnostic foreign system interfaces via [__`omnisdk`__][omnisdk].
3. Declarative IaC support through [`stackql-deploy`][deploy] and [__`omnisdk`__][omnisdk].
4. The coverage and testing of [provider interface definition documents][registry] leveraging [`omnisdk`][omnisdk].  
5. Full support for the [`postgres` wire protocol][psql-wire].  
6. Analytics. Including CSPM, audit, entitlements/UAM, inventory, finops and more.

## 🎯 Use Cases
- **Simplified Cloud Auditing and Compliance**: Audit resource deployments and configurations across multiple cloud and SaaS providers using a simple SQL-based framework
- **Federated Entitlements and Identity Management**: Generate reports joining data from an IdP with entitlements in a SaaS, PaaS, or IaaS resource provider
- **FinOps and Cost Optimization**: Analyze global resource deployment across multiple providers to identify opportunities for cost recovery or savings
- **Custom Reporting and Dashboarding**: Create custom multi-cloud inventory reports
- **Multi-cloud Resource Management**: One consistent SQL-based framework for XOps across all cloud, IdP and SaaS providers
- **Automated Infrastructure as Code (IaC)**: Transactional multi-cloud infrastructure-as-code framework using a SQL ETL approach
- **CI/CD Integration for Deployment Validation**: Integrate StackQL in your CI/CD workflows to validate resource state or enforce compliance
- **✨ AI Control Plane Automation** - Use StackQL as an MCP server to give AI agents and LLMs direct, SQL-based access to cloud and SaaS APIs for querying, provisioning, and managing resources
- **✨ Self-Describing Observability for AI Agents** - StackQL's provider registry and SQL interface are inherently discoverable, enabling AI agents to introspect available resources, operations, and schemas without external documentation
- **✨ AI-Native Infrastructure Tooling** - Integrate StackQL into agentic workflows, copilots, and chat-driven operations as a unified tool for multi-cloud infrastructure reasoning and action

## 🗄️ Key Repositories
| Repository | Languages | Description |
|------------|-----------|-------------|
| [__`stackql`__][core] | ![Go][golang] | StackQL core project that enables users to interact with cloud resources using SQL. |
| [__`stackql-provider-registry`__][registry] | ![OpenAPI][openapi] | A registry for cloud and SaaS providers for StackQL, generated from extensions to the providers' OpenAPI3 specifications. |
| [__`@stackql/mcp-server (npmjs)`__][npmjs-mcp] | ![npmjs][npmjs] ![TypeScript][typescript] ![JavaScript][javascript] | StackQL MCP Server distributed via NPM for JavaScript and TypeScript agent applications. |
| [__`stackql-mcp (crates.io)`__][crates-mcp] | ![Rust][rust] | StackQL MCP Server distributed via crates.io for Rust agent applications. |
| [__`stackql-mcp-server (pypi)`__][pypi-mcp] | ![Python][python] | StackQL MCP Server distributed via PyPi for Python agent applications. |
| [__`stackql/stackql-mcp (oci/dockerhub)`__][oci-mcp] | ![Dockerhub][docker] | StackQL MCP Server distributed via OCI for containerized agent applications. |
| [__`StackQL.Mcp (NuGet)`__][nuget-mcp]<br/>[__`StackQL.Mcp.AgentFramework (NuGet)`__][nuget-mcp-agent-fwk] | ![.NET][dotnet] | StackQL MCP Server distributed via NuGet for .NET agent applications. |
| [__`stackql-workbench`__][workbench] | ![Rust][rust] ![SQL][sqlbadge] | Native Windows and MacOS user interface for running StackQL queries with an AI chat interface. |
| [__`stackql-deploy`__][deploy] | ![Rust][rust] ![SQL][sqlbadge] | Declarative, state-file-less, infrastructure-as-code using StackQL, see it on [crates.io][deploy-crates]. |
| [__`setup-stackql`__][setupstackql] | ![GitHub Actions][githubactions] ![JavaScript][javascript] | GitHub Action to setup StackQL in an Actions workflow; see overview in the GitHub Actions [marketplace](https://github.com/marketplace/actions/setup-stackql) |
| [__`stackql-assert`__][stackqlassert] | ![GitHub Actions][githubactions] ![JavaScript][javascript] | GitHub Action to run compliance or validation checks using StackQL in an Actions workflow; see overview in the GitHub Actions [marketplace](https://github.com/marketplace/actions/stackql-assert) |
| [__`stackql-exec`__][stackqlexec] | ![GitHub Actions][githubactions] ![JavaScript][javascript] | GitHub Action to execute StackQL queries in an Actions workflow; see overview in the GitHub Actions [marketplace](https://github.com/marketplace/actions/stackql-exec) |
| [__`stackql-deploy-action`__][deployaction] | ![GitHub Actions][githubactions] ![SQL][sqlbadge] | GitHub Action to deploy or test stacks using `stackql-deploy`. |
| [__`pystackql`__][pystackql] | ![Python][python] | PyPi package to use StackQL within Python or IPython applications, see [readthedocs](https://pystackql.readthedocs.io/en/latest/) |
| [__`omnisdk`__][omnisdk] | ![Go][golang] ![OpenAPI][openapi] | Golang library to support traversal algorithms on StackQL augmented openapi doc structure and SQL semantics. |


## 👐 Getting Involved
We welcome contributions and community involvement in StackQL. Whether you're interested in contributing code (including SQL queries or new providers), reporting bugs, or requesting features, your input is valuable to us.

- [**Contributing Guidelines**][contributing]
- [**Discussions & Support**][discussions]

📜 StackQL is released under the [MIT License][license].


## 🛠️ Services We Provide
StackQL Studios provides custom audit services to create and automate client reports for Cloud Security Posture Management, Entitlements or User Access Management, FinOps/Cost Optimization, Network Analysis, Multi-Cloud Inventory Analysis, and more.  Contact us at [info@stackql.io](mailto:info@stackql.io)

---

🌍 For more information, visit our [website][homepage], follow us on [X][x], or join our [Discord Server][discord].