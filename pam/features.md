# PAM Product Features

This file contains features specific to Privileged Access Management (PAM), Endpoint Privilege Management, and Identity Access Management (IAM) products.

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
| disaster_recovery | Disaster Recovery | Built-in disaster recovery capabilities |
| scalability | Scalability | Ability to scale with increasing demand |
| containerized | Containerized Deployment | Support for containerized deployment (Docker, Kubernetes) |
| api_access | API Access | Provides API for custom integrations |
| microservices | Microservices Architecture | Built on a microservices architecture |

## Privileged Account Management

| ID | Name | Description |
|----|------|-------------|
| password_vault | Password Vault | Secure storage for privileged credentials |
| password_rotation | Automatic Password Rotation | Automatically rotate passwords on a schedule |
| password_complexity | Password Complexity Rules | Enforce password complexity requirements |
| shared_account_mgmt | Shared Account Management | Management of shared privileged accounts |
| service_account_mgmt | Service Account Management | Management of service accounts |
| admin_account_mgmt | Administrative Account Management | Management of administrative accounts |
| emergency_access | Emergency/Break-Glass Access | Emergency access to privileged accounts |
| checkout_workflow | Credential Checkout Workflow | Process for checking out privileged credentials |
| checkout_approval | Checkout Approval | Approval workflow for credential checkout |
| checkout_time_limit | Checkout Time Limits | Time limits for credential checkout |
| checkout_reason | Checkout Reason | Require reason for credential checkout |
| credential_discovery | Credential Discovery | Automatically discover privileged accounts |
| credential_onboarding | Credential Onboarding | Process for onboarding new privileged accounts |
| password_reconciliation | Password Reconciliation | Verify and reconcile password changes |
| password_verification | Password Verification | Verify password validity |
| account_dependencies | Account Dependencies | Track dependencies between accounts |
| account_grouping | Account Grouping | Group accounts by function or system |
| ssh_key_mgmt | SSH Key Management | Management of SSH keys |
| api_key_mgmt | API Key Management | Management of API keys |
| cloud_key_mgmt | Cloud Key Management | Management of cloud service keys |
| certificate_mgmt | Certificate Management | Management of digital certificates |

## Privileged Session Management

| ID | Name | Description |
|----|------|-------------|
| session_monitoring | Session Monitoring | Real-time monitoring of privileged sessions |
| session_recording | Session Recording | Record privileged sessions for audit |
| session_isolation | Session Isolation | Isolate privileged sessions from user endpoints |
| session_termination | Session Termination | Ability to terminate suspicious sessions |
| session_shadowing | Session Shadowing | Allow administrators to view active sessions |
| command_filtering | Command Filtering | Filter commands during privileged sessions |
| keystroke_logging | Keystroke Logging | Log keystrokes during privileged sessions |
| file_transfer_control | File Transfer Control | Control file transfers during privileged sessions |
| clipboard_control | Clipboard Control | Control clipboard usage during privileged sessions |
| jump_box | Jump Box Functionality | Provide secure jump box for privileged access |
| web_session_mgmt | Web Session Management | Management of privileged web sessions |
| rdp_session_mgmt | RDP Session Management | Management of RDP sessions |
| ssh_session_mgmt | SSH Session Management | Management of SSH sessions |
| db_session_mgmt | Database Session Management | Management of database sessions |
| app_session_mgmt | Application Session Management | Management of application sessions |
| protocol_handlers | Protocol Handlers | Support for various protocols (RDP, SSH, VNC, etc.) |
| session_proxy | Session Proxy | Proxy for privileged sessions |
| session_audit | Session Audit | Audit of privileged sessions |
| session_analytics | Session Analytics | Analytics of privileged session activity |

## Endpoint Privilege Management

| ID | Name | Description |
|----|------|-------------|
| least_privilege | Least Privilege Enforcement | Enforce principle of least privilege |
| app_control | Application Control | Control which applications can run |
| app_whitelisting | Application Whitelisting | Allow only approved applications to run |
| app_blacklisting | Application Blacklisting | Block specific applications from running |
| elevation_on_demand | Elevation on Demand | Elevate privileges on demand for specific tasks |
| just_in_time_admin | Just-in-Time Administration | Grant administrative privileges only when needed |
| admin_rights_removal | Admin Rights Removal | Remove standing administrative rights |
| privilege_discovery | Privilege Discovery | Discover privileges across endpoints |
| privilege_analytics | Privilege Analytics | Analytics of privilege usage |
| privilege_recommendations | Privilege Recommendations | Recommendations for privilege reduction |
| policy_based_controls | Policy-Based Controls | Controls based on defined policies |
| context_aware_controls | Context-Aware Controls | Controls based on context (time, location, etc.) |
| windows_support | Windows Support | Support for Windows operating systems |
| macos_support | macOS Support | Support for macOS operating systems |
| linux_support | Linux Support | Support for Linux operating systems |
| unix_support | Unix Support | Support for Unix operating systems |
| sudo_management | Sudo Management | Management of sudo privileges |
| uac_management | UAC Management | Management of User Account Control |
| driver_management | Driver Management | Control over driver installation |
| script_control | Script Control | Control over script execution |
| child_process_control | Child Process Control | Control over child processes |
| file_integrity_monitoring | File Integrity Monitoring | Monitor changes to critical files |
| registry_control | Registry Control | Control over registry changes |
| local_account_mgmt | Local Account Management | Management of local accounts |

## Identity and Access Management

| ID | Name | Description |
|----|------|-------------|
| sso | Single Sign-On | Single sign-on capabilities |
| mfa | Multi-Factor Authentication | Support for multi-factor authentication |
| adaptive_mfa | Adaptive MFA | Context-based multi-factor authentication |
| passwordless | Passwordless Authentication | Support for passwordless authentication |
| biometric_auth | Biometric Authentication | Support for biometric authentication |
| mobile_auth | Mobile Authentication | Support for mobile-based authentication |
| social_login | Social Login | Support for social login providers |
| federation | Federation | Identity federation capabilities |
| directory_integration | Directory Integration | Integration with directory services |
| active_directory | Active Directory Integration | Integration with Microsoft Active Directory |
| azure_ad | Azure AD Integration | Integration with Microsoft Azure Active Directory |
| ldap | LDAP Integration | Integration with LDAP directories |
| saml | SAML Support | Support for SAML authentication |
| oauth | OAuth Support | Support for OAuth authentication |
| openid_connect | OpenID Connect Support | Support for OpenID Connect |
| user_provisioning | User Provisioning | Automated user provisioning |
| user_deprovisioning | User Deprovisioning | Automated user deprovisioning |
| lifecycle_management | User Lifecycle Management | Management of user lifecycle |
| role_based_access | Role-Based Access Control | Access control based on roles |
| attribute_based_access | Attribute-Based Access Control | Access control based on attributes |
| policy_based_access | Policy-Based Access Control | Access control based on policies |
| dynamic_access_policies | Dynamic Access Policies | Access policies that adapt to context |
| access_certification | Access Certification | Periodic certification of access rights |
| access_request_workflow | Access Request Workflow | Workflow for requesting access |
| access_approval_workflow | Access Approval Workflow | Workflow for approving access requests |
| segregation_of_duties | Segregation of Duties | Enforce separation of responsibilities |
| identity_governance | Identity Governance | Governance of identity and access |
| identity_analytics | Identity Analytics | Analytics of identity and access patterns |

## Cloud Privilege Management

| ID | Name | Description |
|----|------|-------------|
| cloud_iam_integration | Cloud IAM Integration | Integration with cloud IAM services |
| aws_iam | AWS IAM Integration | Integration with AWS Identity and Access Management |
| azure_iam | Azure IAM Integration | Integration with Azure Identity and Access Management |
| gcp_iam | GCP IAM Integration | Integration with Google Cloud IAM |
| cloud_entitlement_mgmt | Cloud Entitlement Management | Management of cloud entitlements |
| cloud_access_broker | Cloud Access Security Broker | Control access to cloud services |
| cloud_privilege_analytics | Cloud Privilege Analytics | Analytics of cloud privilege usage |
| cloud_security_posture | Cloud Security Posture Management | Management of cloud security posture |
| multi_cloud_support | Multi-Cloud Support | Support for multiple cloud providers |
| cloud_account_protection | Cloud Account Protection | Protection of cloud service accounts |
| infrastructure_as_code | Infrastructure as Code Support | Support for infrastructure as code |
| devops_integration | DevOps Integration | Integration with DevOps tools and processes |
| container_security | Container Security | Security for containerized environments |
| kubernetes_integration | Kubernetes Integration | Integration with Kubernetes |

## Security & Compliance

| ID | Name | Description |
|----|------|-------------|
| audit_logging | Audit Logging | Comprehensive audit logging |
| siem_integration | SIEM Integration | Integration with Security Information and Event Management systems |
| soc_integration | SOC Integration | Integration with Security Operations Center |
| threat_analytics | Threat Analytics | Analytics to detect threats |
| behavior_analytics | User Behavior Analytics | Analytics of user behavior to detect anomalies |
| risk_scoring | Risk Scoring | Score risk of users and activities |
| compliance_reporting | Compliance Reporting | Reports for compliance purposes |
| compliance_frameworks | Compliance Frameworks | Support for compliance frameworks |
| soc2 | SOC 2 Compliance | Service Organization Control 2 compliance |
| hipaa | HIPAA Compliance | Health Insurance Portability and Accountability Act compliance |
| gdpr | GDPR Compliance | General Data Protection Regulation compliance |
| pci_dss | PCI DSS Compliance | Payment Card Industry Data Security Standard compliance |
| nist | NIST Framework Support | National Institute of Standards and Technology framework support |
| iso27001 | ISO 27001 Compliance | ISO 27001 compliance |
| custom_compliance | Custom Compliance | Support for custom compliance requirements |
| data_sovereignty | Data Sovereignty | Controls for data sovereignty requirements |
| encryption | Encryption | Data encryption capabilities |
| key_management | Key Management | Management of encryption keys |
| secrets_management | Secrets Management | Management of application secrets |
| vulnerability_management | Vulnerability Management | Management of vulnerabilities |
| patch_management | Patch Management | Management of security patches |

## Management & Monitoring

| ID | Name | Description |
|----|------|-------------|
| centralized_management | Centralized Management | Single console for management |
| dashboard | Dashboard | Visual dashboard for status and analytics |
| reporting | Reporting | Comprehensive reporting capabilities |
| custom_reporting | Custom Reporting | Ability to create custom reports |
| scheduled_reports | Scheduled Reports | Automatically generate and send reports |
| alerting | Alerting | Configurable alerts for security events |
| notification_options | Notification Options | Options for receiving notifications |
| health_monitoring | Health Monitoring | Monitoring of system health |
| performance_monitoring | Performance Monitoring | Monitoring of system performance |
| capacity_planning | Capacity Planning | Tools for capacity planning |
| log_management | Log Management | Management of system logs |
| event_correlation | Event Correlation | Correlation of security events |
| mobile_app | Mobile App | Mobile application for management and monitoring |

## Integration

| ID | Name | Description |
|----|------|-------------|
| ticketing_integration | Ticketing System Integration | Integration with ticketing systems |
| itsm_integration | ITSM Integration | Integration with IT Service Management tools |
| rmm_integration | RMM Integration | Integration with Remote Monitoring and Management tools |
| psa_integration | PSA Integration | Integration with Professional Services Automation tools |
| connectwise_manage | ConnectWise Manage | Integration with ConnectWise Manage |
| autotask | Autotask | Integration with Autotask PSA |
| servicenow | ServiceNow | Integration with ServiceNow |
| jira | Jira | Integration with Jira |
| webhook_support | Webhook Support | Support for webhooks for custom integrations |
| chatops_integration | ChatOps Integration | Integration with chat platforms for operations |
| slack_integration | Slack Integration | Integration with Slack |
| teams_integration | Microsoft Teams Integration | Integration with Microsoft Teams |
| email_integration | Email Integration | Integration with email systems |
| custom_integrations | Custom Integrations | Support for custom integrations |

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

## Pricing & Licensing

| ID | Name | Description |
|----|------|-------------|
| per_user | Per User | Pricing based on number of users |
| per_admin | Per Administrator | Pricing based on number of administrators |
| per_endpoint | Per Endpoint | Pricing based on number of endpoints |
| per_account | Per Account | Pricing based on number of managed accounts |
| per_server | Per Server | Pricing based on number of servers |
| tiered_pricing | Tiered Pricing | Pricing based on tiers of functionality |
| free_tier | Free Tier | Availability of a free tier or version |
| trial_available | Trial Available | Availability of a free trial |
| monthly_billing | Monthly Billing | Option for monthly billing |
| annual_billing | Annual Billing | Option for annual billing |
| volume_discounts | Volume Discounts | Discounts for volume purchases |
| perpetual_license | Perpetual License | One-time purchase option |
| subscription_license | Subscription License | Recurring subscription model |
