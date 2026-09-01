# Awesome-Cloud-Asset-Inventory

Top Cloud Asset Inventory Ecosystem

Curated List of SaaS Products & Open-Source GitHub Projects
Focused on Cloud Asset Discovery, Multi-Cloud Inventory, Cloud Resource Visibility, Configuration Intelligence, CSPM, CAASM & Infrastructure Graphs
Last updated: September 2026

This repository tracks notable SaaS/hosted platforms and open-source projects for Cloud Asset Inventory. These tools discover, collect, normalize, query, visualize, and continuously monitor cloud infrastructure assets across AWS, Microsoft Azure, Google Cloud, Kubernetes, SaaS platforms, and other environments.

Typical capabilities include cloud resource discovery, configuration inventory, account and subscription mapping, IAM visibility, asset relationships, infrastructure graphs, security posture monitoring, attack-surface discovery, vulnerability context, compliance reporting, and historical cloud configuration analysis.

Examples include Lacework, Wiz, Orca Security, Tenable Cloud Security, Palo Alto Prisma Cloud, Microsoft Defender CSPM, Google Cloud Asset Inventory, CloudQuery, Steampipe, and Axonius (the category leaders).

Open-source emphasis: This section is heavily expanded with open-source cloud inventory platforms, infrastructure graph engines, CSPM tools, cloud configuration collectors, SQL-over-cloud APIs, security auditing tools, asset databases, Kubernetes inventory systems, and automation frameworks. The open-source ecosystem is particularly strong for building custom self-hosted cloud asset inventory platforms by combining data collectors, graph databases, SQL engines, security scanners, and visualization tools.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

Table of Contents

SaaS/Hosted Platforms

Open-Source GitHub Projects

Additional Strong Open-Source Options

How to Contribute

Disclaimer

## SaaS/Hosted Platforms

| Product | Description | Starting Tier / Pricing | Free Tier Limit / Free Trial Details |
| :--- | :--- | :--- | :--- |
| **Lacework (FortiCNAPP)** | Cloud security and CNAPP platform providing cloud asset visibility, configuration intelligence, workload security, threat detection, and security posture management across cloud environments. | Custom enterprise contracts starting at ~$36,000/year (or ~$360/workload/year for legacy starter tiers). | 14-day guided Cloud Security Assessment (CSA) / PoC evaluation (no perpetual free tier). |
| **Wiz** | Agentless cloud security platform that discovers cloud resources and relationships across multi-cloud environments while connecting asset inventory with vulnerabilities, identities, exposures, and attack paths. | Custom enterprise subscription starting at ~$30,000–$50,000/year (licensed in blocks of 100 workloads across Cloud, Code, and Sensor modules). | 14-day guided Proof of Concept (PoC) / cloud risk assessment trial (no perpetual free tier). |
| **Orca Security** | Agentless cloud security platform providing automated cloud asset discovery and contextual risk analysis across cloud infrastructure, workloads, identities, and data assets. | Annual contracts typically starting at ~$15,000/year (~$39–$45/workload/year for core CSPM/CWPP modules). | 30-day full-featured free trial available on AWS Marketplace and official portal (no perpetual free tier). |
| **Tenable Cloud Security** | Cloud-native security platform providing visibility into cloud resources, configurations, identities, vulnerabilities, and security posture across public-cloud environments. | Enterprise contracts starting at ~$150–$350/resource/year (or via Tenable One asset licensing starting at ~$2,275/year base packs). | 30-day free trial available via AWS Marketplace / web portal request (full CNAPP & CIEM evaluation; no perpetual free tier). |
| **Palo Alto Networks Prisma Cloud** | Cloud-native application protection platform combining cloud asset visibility with CSPM, CIEM, workload security, vulnerability management, compliance, and infrastructure security. | Credit-based model starting at ~$300–$640 per Prisma Cloud Credit/year (starter deployment bundles typically start at ~$10,800/year). | 30-day free trial on Prisma Cloud portal (15-day free trial with initial test credits on AWS Marketplace; no perpetual free tier). |
| **Microsoft Defender for Cloud** | Cloud security platform providing security posture management, cloud asset visibility, recommendations, compliance monitoring, workload protection, and multi-cloud security capabilities. | Foundational CSPM is $0.00 (Free); Defender for Servers starts at $5.00–$15.00/server/month; Defender CSPM at $5.11/billable resource/month. | Foundational CSPM is Free forever (continuous asset discovery, Secure Score, MCSB benchmarks across Azure/AWS/GCP); 30-day free trial for all paid Defender plans. |
| **Microsoft Defender CSPM** | Cloud security posture management capabilities within Microsoft Defender for Cloud, providing inventory and contextual security analysis for cloud resources and cloud-native workloads. | $5.11 per billable resource/month (metered hourly across compute, database, storage, and serverless assets). | 30-day free trial per subscription/environment (baseline asset posture and recommendations covered by Foundational CSPM free forever). |
| **Google Cloud Asset Inventory** | Native Google Cloud service for searching, exporting, analyzing, and monitoring metadata and configuration information about Google Cloud resources and IAM policies. | $0.00 (Core Asset Inventory API search, export, and IAM policy analysis calls are free; standard GCP storage/BigQuery rates apply only for exported data sinks). | Free forever with unlimited API search and export calls across organization assets (subject to standard GCP per-project API rate quotas). |
| **CloudQuery** | Cloud infrastructure data platform that synchronizes configuration and asset data from cloud providers, SaaS services, and APIs into SQL-queryable destinations. It supports cloud asset inventory, CSPM, FinOps, and vulnerability-management use cases. | AWS Marketplace Starter package starts at $44,516/year (1.2 billion synced rows + Silver support); self-hosted open-source CLI is free. | 14-day free trial for CloudQuery Cloud; monthly free sync quota for official cloud source plugins without credit card; open-source core SDK is free forever. |
| **Steampipe (Turbot Pipes)** | SQL-based cloud intelligence platform that enables users to query cloud APIs and infrastructure using SQL, supporting inventory, compliance, governance, and security analysis. | Developer plan is $0.00 (Free); Team plan starts at $49.00/month (includes 3 users, 2,000 compute minutes, 20 GB storage; $19/additional user/month); Enterprise starts at $249.00/month. | Developer plan is Free forever (1 user, 400 compute minutes/month, 3 GB storage, 5 workspaces); Steampipe open-source CLI and plugins are free forever. |
| **Axonius** | Cybersecurity asset management platform that aggregates asset information from many security and IT systems to create a unified inventory across devices, identities, cloud assets, SaaS, and other technology environments. | Annual enterprise subscription starting at ~$25,000–$35,000/year (~$3.00–$5.00/asset/month scaled by total unified assets). | 14-day guided proof-of-concept / interactive sandbox demo (no perpetual free tier). |
| **JupiterOne** | Cyber asset intelligence platform focused on collecting and analyzing cyber assets and their relationships through graph-based asset visibility and security context. | Starter/Mid-Market plans start at ~$500.00/month (~$6,000/year for up to 200,000 data points); custom quotes for enterprise tiers. | Free Community tier forever (basic asset inventory and compliance tracking for startups, limited to 10 API requests/minute); 14-day free trial for paid tiers. |
| **Censys** | Internet and attack-surface intelligence platform that can help organizations discover externally exposed cloud infrastructure, services, certificates, and assets. | Censys Search Community is $0.00; Search Starter begins at $100.00 (prepaid search credits); Censys ASM enterprise starts at ~$60,000/year. | Free Community tier forever (100 search credits / up to 250 queries/month for basic host and certificate lookups); 30-day free trial for Search Pro / 14-day trial for ASM. |
| **CyCognito** | External attack-surface management platform that discovers and analyzes externally exposed organizational and cloud-connected assets. | Annual enterprise contracts typically start at ~$20,000–$30,000/year (scaled by external asset scope and scanning frequency). | Free Attack Surface Risk Assessment (scoped single scan/evaluation for a specific subsidiary or asset group; no perpetual free tier). |
| **Randori (Palo Alto Networks)** | Attack-surface and exposure-management technology within Microsoft's / Palo Alto Networks security ecosystem, focused on discovering and analyzing organizational attack surfaces. | Enterprise contracts historically start at ~$15,000/year (now integrated into Palo Alto Networks Cortex XPANSE / ASM portfolio). | 7-day to 14-day scoped attack surface review / Proof-of-Concept assessment (no perpetual free tier). |
| **Rapid7 InsightCloudSec** | Cloud security and compliance platform providing cloud infrastructure visibility, resource inventory, policy monitoring, risk analysis, and automated remediation. | Asset-based pricing starting at ~$5,000–$6,000/month (~$60,000–$66,000/year billed annually) for up to 500 billable cloud instances. | 30-day proof-of-concept / guided evaluation environment (no perpetual free tier). |
| **Check Point CloudGuard** | Cloud-native security platform providing cloud posture management, workload protection, application security, and infrastructure visibility. | Starts at ~$36.00–$50.00/asset/year (~$3.00–$4.17/asset/month) on annual contracts, or pay-as-you-go per VM instance hour on AWS/Azure. | 30-day free trial on AWS Marketplace and direct portal (full security feature evaluation up to trial limits; no perpetual free tier). |
| **Aqua Security** | Cloud-native security platform providing visibility and protection for cloud workloads, containers, Kubernetes, and cloud infrastructure. | Enterprise subscriptions start at ~$3,500–$10,000/year (based on workload units and code repositories; open-source Trivy/Tracee tools are free). | 14-day free trial for Aqua CSPM Advanced on AWS Marketplace; perpetually free Developer tier for basic container image scanning. |
| **Sysdig** | Cloud-native security platform supporting Kubernetes and cloud asset visibility, workload analysis, posture management, vulnerability detection, and runtime security. | Starts at $15.00–$40.00/host/month (billed annually, or $0.007/compute hour); enterprise deployments average $40.00–$120.00/host/month. | 30-day free trial with full CNAPP and Kubernetes security features across connected hosts and clusters (no perpetual free tier). |
| **Datadog Cloud Security Management** | Cloud security and observability platform combining cloud infrastructure visibility with security posture monitoring, misconfiguration detection, and threat analysis. | CSM Pro starts at $10.00/host/month (billed annually, or $12.00 on-demand); CSM Enterprise starts at $25.00/host/month ($30.00 on-demand). | 14-day free trial with full platform access (CSM, CSPM, and threat detection across connected infrastructure; no perpetual free tier). |
| **ServiceNow CMDB** | Enterprise configuration-management platform that can integrate discovery and cloud inventory information into a centralized CMDB and service-management ecosystem. | ITOM Discovery packages start at ~$90.00–$200.00/user/month or ~$30.00–$45.00/managed node/year on enterprise contracts (typically starting ~$10,000–$40,000+/year). | Personal Developer Instance (PDI) Free forever on the ServiceNow Developer Portal (full CMDB schema and discovery workflows for learning/testing; must stay active). |
| **Device42** | IT asset discovery and infrastructure inventory platform supporting hybrid infrastructure, cloud resources, dependencies, and configuration-management use cases. | Starts at ~$1,449.00/year (~$2.50–$4.50/device/month) for core discovery and inventory, scaling with monitored device tiers. | 14-day free trial limited to 100 devices (no credit card required; no perpetual free tier). |

Open-Source GitHub Projects

CloudQuery

Open-source cloud infrastructure data platform for synchronizing cloud configuration and security data into databases and data warehouses. It is specifically designed for cloud asset inventory, CSPM, FinOps, and vulnerability-management use cases across AWS, Azure, GCP, Kubernetes, SaaS, and many other sources.

Steampipe

Open-source SQL engine for querying cloud APIs, SaaS platforms, and infrastructure services as relational tables. Particularly useful for ad hoc cloud asset inventory, compliance analysis, configuration auditing, and infrastructure reporting.

Cartography

Open-source infrastructure asset mapping and graph platform that collects cloud assets and relationships into a graph database. Useful for understanding multi-cloud environments, identities, permissions, dependencies, and attack paths.

Prowler

Major open-source cloud security platform supporting AWS, Azure, GCP, Kubernetes, Microsoft 365, and other environments. It combines asset discovery with security assessments, compliance checks, continuous monitoring, and remediation guidance. 
GitHub
+1

ScoutSuite

Open-source multi-cloud security auditing tool that gathers cloud configuration data and generates detailed reports for AWS, Azure, GCP, Oracle Cloud, and other supported environments.

Cloud Custodian

Open-source rules engine for cloud governance, security, and cost management. It can discover, filter, inventory, report on, and automatically act on cloud resources across multiple providers.

CloudMapper

Open-source AWS visualization and auditing platform that collects AWS configuration data and creates diagrams and reports for cloud infrastructure inventory and security analysis.

CloudSploit

Open-source cloud security and configuration auditing project supporting multiple cloud providers. Useful for discovering infrastructure configuration risks and building inventory-driven security workflows.

CloudGraph

Open-source graph-based cloud infrastructure tool designed to collect and query cloud assets and their relationships for security and visibility use cases.

Fix Inventory

Open-source cloud inventory and infrastructure management project focused on collecting cloud resources and representing infrastructure data for automation and analysis.

Komiser

Open-source cloud environment inspector and resource discovery tool that inventories cloud infrastructure and provides visibility into resources across supported cloud providers.

CloudFox

Open-source cloud reconnaissance and enumeration tool designed to collect attacker-relevant cloud information from AWS, Azure, and other supported environments.

ElectricEye

Open-source multi-cloud and multi-SaaS security tool for asset management, security posture management, monitoring, and infrastructure security analysis.

Magpie

Cloud security posture-management approaches and graph-based inventory tooling can be built around Cartography-style asset relationship models and open-source CSPM components.

Cloud Custodian c7n

Policy-as-code platform that can maintain continuously updated views of cloud resources while enforcing governance and lifecycle policies.

AWS Config Resource Inventory Tools

Community projects and utilities for collecting, analyzing, exporting, and visualizing AWS resource configuration and inventory data.

Azure Resource Graph Samples

Open-source query examples and tooling for Azure Resource Graph, enabling large-scale discovery and analysis of Azure subscriptions and cloud resources.

GCP Asset Inventory Samples

Open-source examples and tooling from the Google Cloud ecosystem that can be adapted for querying and processing Google Cloud asset inventory information.

Cloud Security Alliance Cloud Controls Tools

Open-source resources, mappings, controls, and security projects that can support cloud asset governance and posture-management implementations.

Open Policy Agent

Open-source policy engine useful for evaluating cloud inventory and configuration data against organizational security and governance policies.

Kyverno

Open-source Kubernetes policy engine that can support Kubernetes asset governance, configuration validation, compliance, and inventory-related controls.

Kubescape

Open-source Kubernetes security platform that inventories Kubernetes configuration and evaluates clusters against security and compliance frameworks.

kube-state-metrics

Open-source Kubernetes component that exposes detailed cluster object state as metrics, providing a useful foundation for Kubernetes asset inventory and monitoring.

Kubecost Open Source

Open-source Kubernetes infrastructure analysis tooling that can provide visibility into workloads, namespaces, clusters, and resource utilization.

Backstage

Open-source developer portal platform that can act as a software and infrastructure catalog when integrated with cloud APIs, Kubernetes, Terraform, and internal systems.

Port Open Source Integrations

Open-source developer portal and service-catalog projects that can be adapted to build internal cloud asset catalogs and infrastructure inventories.

NetBox

Open-source infrastructure resource modeling and source-of-truth platform. While traditionally focused on networks and infrastructure, it can be extended and integrated with cloud environments for hybrid asset inventory.

Snipe-IT

Open-source IT asset management platform suitable for managing hardware and organizational assets and integrating cloud inventory data into broader IT asset-management workflows.

Ralph

Open-source asset-management and data-center inventory platform that can serve as part of a hybrid infrastructure inventory architecture.

i-doit Open

Open-source IT documentation and configuration-management database platform suitable for documenting infrastructure assets and relationships.

GLPI

Open-source IT asset and service-management platform that can be integrated with discovery and inventory systems for hybrid infrastructure management.

CMDBuild

Open-source configuration-management database framework for modelling assets, relationships, services, and infrastructure dependencies.

Neo4j Community

Open-source graph database technology suitable for building cloud asset graphs representing relationships between accounts, identities, resources, networks, applications, and security findings.

Apache AGE

Open-source graph extension for PostgreSQL that can be used to model cloud infrastructure relationships while retaining PostgreSQL for relational inventory data.

OpenSearch

Open-source search and analytics engine suitable for indexing and searching large cloud asset inventories, configurations, events, tags, and metadata.

PostgreSQL

Open-source relational database commonly used as a destination for normalized cloud inventory data and custom cloud asset-management platforms.

Apache Superset

Open-source business-intelligence platform suitable for visualizing multi-cloud asset inventories, ownership, resource distribution, security posture, and governance metrics.

Metabase

Open-source analytics platform that can provide self-hosted dashboards and reports for cloud resource inventory and configuration data.

Grafana

Open-source observability and visualization platform useful for cloud inventory dashboards, infrastructure metrics, compliance trends, and security posture reporting.

Apache Airflow

Open-source workflow orchestration platform for scheduling cloud inventory collection, API synchronization, data normalization, security scans, and reporting.

Prefect

Open-source workflow orchestration framework suitable for automating cloud discovery, inventory synchronization, enrichment, and analytics pipelines.

Node-RED

Open-source flow-based automation platform that can connect cloud APIs, inventory databases, alerts, dashboards, and IT operations workflows.

OpenTelemetry

Open-source observability framework that can complement asset inventory platforms by collecting infrastructure metadata, telemetry, and service relationships.

Additional Strong Open-Source Options

Cloud inventory engines: CloudQuery and Steampipe are among the strongest open-source foundations for building multi-cloud asset inventories. CloudQuery can synchronize normalized cloud configuration data into databases, while Steampipe enables SQL-based querying directly against cloud APIs. 
GitHub
+1

Infrastructure graphs: Cartography, CloudGraph, Neo4j Community, Apache AGE, and PostgreSQL can be combined to build graph-based cloud inventories showing relationships between cloud accounts, identities, workloads, networks, storage, and services.

Open-source CSPM: Prowler, ScoutSuite, CloudSploit, Cloud Custodian, Kubescape, and related tools can enrich cloud inventory data with security posture, compliance, configuration risk, and remediation information. 
GitHub
+2
GitHub
+2

Cloud visualization: CloudMapper, Cartography, Neo4j visualization tools, Grafana, Apache Superset, and custom graph applications can provide infrastructure maps and asset relationship visualization.

SQL-driven cloud intelligence: Steampipe, CloudQuery, PostgreSQL, DuckDB, and Apache Arrow-based pipelines provide a strong architecture for storing and querying cloud inventory data at scale.

Kubernetes inventory: kube-state-metrics, Kubescape, Backstage integrations, Kubernetes APIs, OpenTelemetry, and Kubernetes dashboards can provide detailed inventory of clusters, workloads, namespaces, services, ingress resources, and policies.

Policy and governance: Open Policy Agent, Cloud Custodian, Kyverno, Checkov, and infrastructure-as-code scanners can evaluate discovered cloud assets against governance and security policies.

Hybrid asset management: NetBox, Snipe-IT, GLPI, CMDBuild, i-doit, and Ralph can complement cloud-native inventory tools by creating broader hybrid infrastructure and IT asset inventories.

Cloud data pipelines: Apache Airflow, Prefect, Dagster, Node-RED, Apache Kafka, and custom Python collectors can automate continuous cloud inventory collection and enrichment.

Security enrichment: Prowler, Trivy, Checkov, OpenVAS-compatible tooling, vulnerability databases, IAM analyzers, and cloud configuration scanners can add risk context to discovered cloud assets.

Asset search and analytics: OpenSearch, Elasticsearch-compatible tools, PostgreSQL, DuckDB, Apache Superset, Metabase, and Grafana can provide searchable and visual cloud asset intelligence.

Infrastructure-as-code correlation: Terraform state, OpenTofu, Crossplane, Backstage, Checkov, and cloud APIs can be combined to correlate deployed cloud assets with their infrastructure definitions and ownership.

Many community AWS inventory, Azure inventory, Google Cloud inventory, Kubernetes discovery, Terraform inventory, cloud graph, CMDB synchronization, and cloud asset tagging projects are available across GitHub.

Frameworks for building custom systems: Combine CloudQuery as the primary multi-cloud data collector with PostgreSQL or DuckDB for normalized asset storage. Add Cartography + Neo4j or Apache AGE for cloud relationship graphs, use Prowler and ScoutSuite for security posture enrichment, and use Cloud Custodian + Open Policy Agent for governance policies.

For visualization, add Apache Superset, Metabase, or Grafana. Use Apache Airflow or Prefect to schedule continuous inventory synchronization and enrichment. Integrate Backstage, NetBox, GLPI, or CMDBuild when a broader organizational asset catalog or hybrid CMDB is required.

This architecture can provide a powerful self-hosted alternative to commercial cloud asset inventory and CNAPP platforms, although enterprise platforms may provide more turnkey integrations, proprietary risk correlation, attack-path analysis, and managed operational workflows.

How to Contribute

Fork the repo.

Add/edit entries in README.md (follow existing format).

Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

Submit PR with a short explanation.

Star the repo if you find it useful!

Disclaimer

This is a community-curated list — not exhaustive and not an endorsement.

Cloud asset inventories can become incomplete if cloud accounts, subscriptions, regions, identities, APIs, or Kubernetes environments are not properly connected.

Security and CSPM findings require appropriate human review; automated discovery and configuration analysis can produce incomplete or context-dependent results.

Cloud environments change continuously, so inventory systems should be configured for regular or event-driven synchronization.

Cloud inventory data can contain sensitive infrastructure, identity, network, and configuration information and should be protected with appropriate access controls and encryption.

Self-hosted open-source solutions require ongoing maintenance, API credential management, data retention policies, backups, monitoring, and security hardening.

Open-source projects in this ecosystem often provide specialized components rather than complete turnkey replacements for enterprise CNAPP, CAASM, or cloud asset-management platforms.

Made for cloud engineers, platform teams, DevOps engineers, security architects, cloud security teams, IT asset managers, and organizations building transparent multi-cloud infrastructure intelligence.

Let's make cloud asset discovery more open, queryable, interoperable, and under your control.
