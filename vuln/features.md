# Vuln Product Features

This file contains features specific to Vulnerability Management products.

## Company

| ID | Name | Description |
|----|------|-------------|
| parent | Parent | Parent Company |
| emp_size | Employee Size | Size of the company or division |
| founded | Founded | Year the company was founded |
| headquarters | Headquarters | Location of company headquarters |
| public_private | Public/Private | Whether the company is publicly traded or privately held |
| acquisition | Acquisition | Details about any acquisitions |

## Architecture & Deployment

| ID | Name | Description |
|----|------|-------------|
| cloud | Cloud | Cloud-based deployment option |
> Cloud-based deployments are hosted by the vendor and typically require no infrastructure management.
| on_premises | On Premises | On-premises deployment option |
> On-premises deployments are installed on your own infrastructure and may require more maintenance.
| hybrid | Hybrid | Supports both cloud and on-premises deployment options |
| saas | SaaS | Software as a Service delivery model |
| private_cloud | Private Cloud | Ability to deploy in a private cloud environment |
| multi_tenant | Multi-Tenant | Multi-tenant architecture for MSPs |
| high_availability | High Availability | Redundancy and failover capabilities |
| scalability | Scalability | Ability to scale with increasing demand |
| containerized | Containerized Deployment | Support for containerized deployment (Docker, Kubernetes) |
| api_access | API Access | Provides API for custom integrations |
| distributed_scanning | Distributed Scanning | Support for distributed scanning architecture |
| agent_based | Agent-Based | Uses agents installed on endpoints for scanning |
| agentless | Agentless | Performs scanning without requiring agents |
| offline_scanning | Offline Scanning | Ability to scan systems that are not connected to the internet |

## Discovery & Asset Management

| ID | Name | Description |
|----|------|-------------|
| network_discovery | Network Discovery | Automatically discover assets on the network |
| asset_inventory | Asset Inventory | Maintain an inventory of all assets |
| asset_classification | Asset Classification | Classify assets based on criticality or other factors |
| asset_tagging | Asset Tagging | Tag assets for organization and filtering |
| asset_grouping | Asset Grouping | Group assets by function, location, or other criteria |
| cmdb_integration | CMDB Integration | Integration with Configuration Management Database |
| cloud_asset_discovery | Cloud Asset Discovery | Discover assets in cloud environments |
| container_discovery | Container Discovery | Discover containers and container images |
| iot_discovery | IoT Discovery | Discover Internet of Things devices |
| ot_discovery | OT Discovery | Discover Operational Technology devices |
| mobile_discovery | Mobile Device Discovery | Discover mobile devices |
| dynamic_asset_tracking | Dynamic Asset Tracking | Track assets as they move or change |
| asset_baselining | Asset Baselining | Establish baselines for assets |
| asset_lifecycle | Asset Lifecycle Management | Track assets through their lifecycle |
| asset_relationships | Asset Relationship Mapping | Map relationships between assets |

## Scanning & Assessment

| ID | Name | Description |
|----|------|-------------|
| vulnerability_scanning | Vulnerability Scanning | Scan for known vulnerabilities |
| network_scanning | Network Scanning | Scan network devices for vulnerabilities |
| web_app_scanning | Web Application Scanning | Scan web applications for vulnerabilities |
| database_scanning | Database Scanning | Scan databases for vulnerabilities |
| cloud_scanning | Cloud Infrastructure Scanning | Scan cloud infrastructure for vulnerabilities |
| container_scanning | Container Scanning | Scan containers and container images for vulnerabilities |
| code_scanning | Code Scanning | Scan source code for vulnerabilities |
| mobile_app_scanning | Mobile App Scanning | Scan mobile applications for vulnerabilities |
| iot_scanning | IoT Scanning | Scan IoT devices for vulnerabilities |
| ot_scanning | OT Scanning | Scan operational technology for vulnerabilities |
| configuration_scanning | Configuration Scanning | Scan for misconfigurations |
| compliance_scanning | Compliance Scanning | Scan for compliance violations |
| authenticated_scanning | Authenticated Scanning | Perform scans with authentication credentials |
| unauthenticated_scanning | Unauthenticated Scanning | Perform scans without authentication credentials |
| scheduled_scanning | Scheduled Scanning | Schedule scans to run automatically |
| continuous_scanning | Continuous Scanning | Perform continuous, ongoing scanning |
| on_demand_scanning | On-Demand Scanning | Perform scans on demand |
| deep_scanning | Deep Scanning | Perform thorough, in-depth scans |
| fast_scanning | Fast Scanning | Perform quick scans for rapid assessment |
| scan_templates | Scan Templates | Pre-defined templates for common scan types |
| custom_scanning | Custom Scanning | Create custom scan profiles |
| scan_throttling | Scan Throttling | Control scan performance impact |
| scan_windows | Scan Windows | Define time windows for scanning |
| scan_blackout_periods | Scan Blackout Periods | Define periods when scanning is not allowed |

## Vulnerability Management

| ID | Name | Description |
|----|------|-------------|
| vulnerability_database | Vulnerability Database | Comprehensive database of known vulnerabilities |
| custom_vulnerabilities | Custom Vulnerabilities | Support for defining custom vulnerabilities |
| vulnerability_scoring | Vulnerability Scoring | Score vulnerabilities based on severity |
| cvss_support | CVSS Support | Support for Common Vulnerability Scoring System |
| vulnerability_trending | Vulnerability Trending | Track vulnerability trends over time |
| vulnerability_aging | Vulnerability Aging | Track how long vulnerabilities have been open |
| vulnerability_correlation | Vulnerability Correlation | Correlate vulnerabilities across assets |
| false_positive_management | False Positive Management | Identify and manage false positives |
| exception_management | Exception Management | Manage exceptions to vulnerability findings |
| vulnerability_verification | Vulnerability Verification | Verify the existence of vulnerabilities |
| exploit_availability | Exploit Availability | Track availability of exploits for vulnerabilities |
| threat_intelligence | Threat Intelligence | Integration with threat intelligence feeds |
| zero_day_detection | Zero-Day Detection | Detect zero-day vulnerabilities |
| vulnerability_prediction | Vulnerability Prediction | Predict potential vulnerabilities |
| attack_path_analysis | Attack Path Analysis | Analyze potential attack paths |
| attack_surface_analysis | Attack Surface Analysis | Analyze the attack surface |
| risk_scoring | Risk Scoring | Score risk based on vulnerabilities and other factors |
| risk_trending | Risk Trending | Track risk trends over time |
| risk_heatmaps | Risk Heatmaps | Visual representation of risk across the environment |
| risk_acceptance | Risk Acceptance | Process for accepting certain risks |
| risk_transfer | Risk Transfer | Process for transferring risks |

## Remediation Management

| ID | Name | Description |
|----|------|-------------|
| remediation_guidance | Remediation Guidance | Guidance on how to remediate vulnerabilities |
| remediation_workflows | Remediation Workflows | Workflows for managing remediation |
| remediation_prioritization | Remediation Prioritization | Prioritize vulnerabilities for remediation |
| remediation_automation | Remediation Automation | Automate remediation of vulnerabilities |
| patch_management | Patch Management | Manage and deploy patches |
| patch_verification | Patch Verification | Verify that patches have been applied correctly |
| configuration_remediation | Configuration Remediation | Remediate misconfigurations |
| remediation_slas | Remediation SLAs | Service level agreements for remediation |
| remediation_tracking | Remediation Tracking | Track remediation progress |
| remediation_validation | Remediation Validation | Validate that remediation was successful |
| remediation_rollback | Remediation Rollback | Roll back remediation if necessary |
| remediation_delegation | Remediation Delegation | Delegate remediation tasks to appropriate teams |
| remediation_approval | Remediation Approval | Approval workflow for remediation actions |
| remediation_scheduling | Remediation Scheduling | Schedule remediation activities |
| remediation_testing | Remediation Testing | Test remediation in non-production environments |

## Reporting & Analytics

| ID | Name | Description |
|----|------|-------------|
| executive_reporting | Executive Reporting | Reports designed for executive stakeholders |
| technical_reporting | Technical Reporting | Detailed technical reports |
| compliance_reporting | Compliance Reporting | Reports for compliance purposes |
| custom_reporting | Custom Reporting | Ability to create custom reports |
| scheduled_reports | Scheduled Reports | Automatically generate and send reports |
| report_templates | Report Templates | Pre-defined report templates |
| dashboards | Dashboards | Visual dashboards for key metrics |
| custom_dashboards | Custom Dashboards | Create custom dashboards |
| trend_analysis | Trend Analysis | Analyze trends over time |
| comparative_analysis | Comparative Analysis | Compare different time periods or environments |
| benchmarking | Benchmarking | Compare against industry benchmarks |
| metrics_kpis | Metrics and KPIs | Track key performance indicators |
| data_visualization | Data Visualization | Visual representation of data |
| data_export | Data Export | Export data for external analysis |
| bi_integration | BI Integration | Integration with business intelligence tools |

## Compliance & Frameworks

| ID | Name | Description |
|----|------|-------------|
| compliance_frameworks | Compliance Frameworks | Support for compliance frameworks |
| pci_dss | PCI DSS | Payment Card Industry Data Security Standard |
| hipaa | HIPAA | Health Insurance Portability and Accountability Act |
| gdpr | GDPR | General Data Protection Regulation |
| nist_csf | NIST CSF | NIST Cybersecurity Framework |
| nist_800_53 | NIST 800-53 | NIST Special Publication 800-53 |
| nist_800_171 | NIST 800-171 | NIST Special Publication 800-171 |
| iso_27001 | ISO 27001 | ISO/IEC 27001 |
| soc2 | SOC 2 | Service Organization Control 2 |
| cis_benchmarks | CIS Benchmarks | Center for Internet Security Benchmarks |
| fedramp | FedRAMP | Federal Risk and Authorization Management Program |
| cmmc | CMMC | Cybersecurity Maturity Model Certification |
| custom_frameworks | Custom Frameworks | Support for custom compliance frameworks |
| compliance_mapping | Compliance Mapping | Map vulnerabilities to compliance requirements |
| compliance_scoring | Compliance Scoring | Score compliance posture |
| compliance_trending | Compliance Trending | Track compliance trends over time |
| evidence_collection | Evidence Collection | Collect evidence for compliance audits |
| audit_support | Audit Support | Support for compliance audits |

## Integration

| ID | Name | Description |
|----|------|-------------|
| siem_integration | SIEM Integration | Integration with Security Information and Event Management systems |
| soar_integration | SOAR Integration | Integration with Security Orchestration, Automation and Response platforms |
| ticketing_integration | Ticketing System Integration | Integration with ticketing systems |
| itsm_integration | ITSM Integration | Integration with IT Service Management tools |
| rmm_integration | RMM Integration | Integration with Remote Monitoring and Management tools |
| psa_integration | PSA Integration | Integration with Professional Services Automation tools |
| connectwise_manage | ConnectWise Manage | Integration with ConnectWise Manage |
| autotask | Autotask | Integration with Autotask PSA |
| servicenow | ServiceNow | Integration with ServiceNow |
| jira | Jira | Integration with Jira |
| devops_integration | DevOps Integration | Integration with DevOps tools and processes |
| ci_cd_integration | CI/CD Integration | Integration with Continuous Integration/Continuous Deployment pipelines |
| webhook_support | Webhook Support | Support for webhooks for custom integrations |
| api_integration | API Integration | Integration via API |
| data_import_export | Data Import/Export | Import and export data |
| email_integration | Email Integration | Integration with email systems |
| slack_integration | Slack Integration | Integration with Slack |
| teams_integration | Microsoft Teams Integration | Integration with Microsoft Teams |

## Security & Access Control

| ID | Name | Description |
|----|------|-------------|
| role_based_access | Role-Based Access Control | Access control based on roles |
| multi_factor_auth | Multi-Factor Authentication | Support for multi-factor authentication |
| sso_integration | Single Sign-On | Integration with single sign-on solutions |
| audit_logging | Audit Logging | Comprehensive audit logging |
| data_encryption | Data Encryption | Encryption of stored data |
| secure_communications | Secure Communications | Secure communication channels |
| api_security | API Security | Security controls for API access |
| user_activity_monitoring | User Activity Monitoring | Monitor user activity within the platform |
| session_management | Session Management | Manage user sessions |
| ip_restrictions | IP Restrictions | Restrict access by IP address |
| data_masking | Data Masking | Mask sensitive data |
| data_retention | Data Retention | Controls for data retention periods |
| data_purging | Data Purging | Securely purge data when no longer needed |

## MSP Features

| ID | Name | Description |
|----|------|-------------|
| white_label | White Label | Ability to rebrand the solution with your own branding |
| multi_tenant_management | Multi-Tenant Management | Tools for managing multiple client tenants |
| client_reporting | Client Reporting | Client-specific reporting capabilities |
| client_onboarding | Client Onboarding | Tools for onboarding new clients |
| msp_dashboard | MSP Dashboard | Centralized dashboard for MSP management |
| msp_billing | MSP Billing Integration | Integration with MSP billing systems |
| service_tiers | Service Tiers | Support for different service tiers |
| msp_pricing | MSP Pricing | Special pricing for Managed Service Providers |
| msp_support | MSP-Specific Support | Dedicated support for MSPs |
| msp_training | MSP Training | Training resources for MSPs |
| client_isolation | Client Isolation | Isolation between client environments |
| delegation | Delegation | Ability to delegate administration to clients |
| client_portal | Client Portal | Portal for client access |

## Pricing & Licensing

| ID | Name | Description |
|----|------|-------------|
| per_asset | Per Asset | Pricing based on number of assets |
| per_ip | Per IP | Pricing based on number of IP addresses |
| per_scan | Per Scan | Pricing based on number of scans |
| unlimited_scanning | Unlimited Scanning | Unlimited scanning included |
| tiered_pricing | Tiered Pricing | Pricing based on tiers of functionality |
| free_tier | Free Tier | Availability of a free tier or version |
| trial_available | Trial Available | Availability of a free trial |
| monthly_billing | Monthly Billing | Option for monthly billing |
| annual_billing | Annual Billing | Option for annual billing |
| volume_discounts | Volume Discounts | Discounts for volume purchases |
| perpetual_license | Perpetual License | One-time purchase option |
| subscription_license | Subscription License | Recurring subscription model |
