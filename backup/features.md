# Backup Product Features

This file contains features specific to Backup and Disaster Recovery products.

## Company

| ID | Name | Description |
|----|------|-------------|
| parent | Parent | Parent Company |
| emp_size | Employee Size | Size of the company or division |
| founded | Founded | Year the company was founded |
| headquarters | Headquarters | Location of company headquarters |
| public_private | Public/Private | Whether the company is publicly traded or privately held |
| acquisition | Acquisition | Details about any acquisitions |

## Architecture

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
| white_label | White Label | Ability to rebrand the solution with your own branding |
| api | API Access | Provides API for custom integrations |

## Backup Sources

| ID | Name | Description |
|----|------|-------------|
| windows_server | Windows Server | Support for Windows Server operating systems |
| windows_desktop | Windows Desktop | Support for Windows desktop operating systems |
| macos | macOS | Support for macOS operating systems |
| linux | Linux | Support for Linux operating systems |
| unix | Unix | Support for Unix operating systems |
| vmware | VMware | Support for VMware virtual environments |
| hyper_v | Hyper-V | Support for Microsoft Hyper-V virtual environments |
| azure_vm | Azure VMs | Support for Microsoft Azure virtual machines |
| aws_ec2 | AWS EC2 | Support for Amazon EC2 instances |
| google_compute | Google Compute | Support for Google Compute Engine instances |
| physical_servers | Physical Servers | Support for physical server backups |
| nas_devices | NAS Devices | Support for Network Attached Storage devices |
| san_devices | SAN Devices | Support for Storage Area Network devices |
| office365 | Microsoft 365 | Support for Microsoft 365 data (Exchange, SharePoint, OneDrive) |
| exchange | Exchange Server | Support for on-premises Exchange Server |
| sharepoint | SharePoint | Support for on-premises SharePoint |
| google_workspace | Google Workspace | Support for Google Workspace (Gmail, Drive, etc.) |
| mysql | MySQL | Support for MySQL databases |
| mssql | MS SQL | Support for Microsoft SQL Server databases |
| oracle | Oracle | Support for Oracle databases |
| postgresql | PostgreSQL | Support for PostgreSQL databases |
| mongodb | MongoDB | Support for MongoDB databases |
| containers | Containers | Support for container environments (Docker, Kubernetes) |
| mobile_devices | Mobile Devices | Support for mobile device backups |

## Backup Features

| ID | Name | Description |
|----|------|-------------|
| file_folder | File & Folder | File and folder level backups |
| image_based | Image-Based | Full system image backups |
| incremental | Incremental | Incremental backup capability |
| differential | Differential | Differential backup capability |
| continuous | Continuous | Continuous data protection (CDP) |
| synthetic_full | Synthetic Full | Ability to create synthetic full backups |
| deduplication | Deduplication | Data deduplication to reduce storage requirements |
| compression | Compression | Data compression to reduce storage requirements |
| encryption | Encryption | Data encryption for security |
| client_encryption | Client-Side Encryption | Encryption performed on the client before transmission |
| in_transit_encryption | In-Transit Encryption | Encryption of data during transmission |
| at_rest_encryption | At-Rest Encryption | Encryption of stored backup data |
| encryption_key_mgmt | Encryption Key Management | Options for managing encryption keys |
| versioning | Versioning | Ability to maintain multiple versions of backups |
| retention_policies | Retention Policies | Configurable retention policies |
| scheduling | Scheduling | Flexible backup scheduling options |
| bandwidth_throttling | Bandwidth Throttling | Control bandwidth usage during backups |
| block_level | Block-Level | Block-level backup capability |
| app_aware | Application-Aware | Application-aware backup processing |
| vss | VSS Integration | Volume Shadow Copy Service integration |
| open_file_backup | Open File Backup | Ability to back up files that are in use |
| bare_metal_recovery | Bare Metal Recovery | Restore to dissimilar hardware |
| granular_recovery | Granular Recovery | Recover individual files or objects without full restore |
| instant_recovery | Instant Recovery | Ability to instantly mount and use backups |
| self_service_portal | Self-Service Portal | Portal for end-users to perform their own restores |

## Disaster Recovery

| ID | Name | Description |
|----|------|-------------|
| local_virtualization | Local Virtualization | Ability to virtualize backups locally |
| cloud_virtualization | Cloud Virtualization | Ability to virtualize backups in the cloud |
| automated_dr_testing | Automated DR Testing | Automated disaster recovery testing |
| dr_orchestration | DR Orchestration | Orchestration of disaster recovery processes |
| failover | Failover | Automated failover capability |
| failback | Failback | Automated failback capability |
| rpo_customization | RPO Customization | Customizable Recovery Point Objectives |
| rto_customization | RTO Customization | Customizable Recovery Time Objectives |
| site_to_site_replication | Site-to-Site Replication | Replication between different sites |
| cross_hypervisor_recovery | Cross-Hypervisor Recovery | Recover across different hypervisor platforms |
| dr_runbooks | DR Runbooks | Support for disaster recovery runbooks |
| dr_documentation | DR Documentation | Tools for disaster recovery documentation |

## Storage & Archiving

| ID | Name | Description |
|----|------|-------------|
| local_storage | Local Storage | Support for local storage targets |
| cloud_storage | Cloud Storage | Support for cloud storage targets |
| tape_support | Tape Support | Support for tape backup devices |
| immutable_storage | Immutable Storage | Support for immutable storage to prevent tampering |
| worm_storage | WORM Storage | Write Once Read Many storage support |
| tiered_storage | Tiered Storage | Support for storage tiering |
| archive_support | Archiving | Long-term archiving capabilities |
| storage_seeding | Storage Seeding | Physical seeding of initial backups |
| bring_own_storage | Bring Your Own Storage | Ability to use your own storage infrastructure |
| multi_cloud_support | Multi-Cloud Support | Support for multiple cloud storage providers |
| azure_storage | Azure Storage | Support for Microsoft Azure storage |
| aws_storage | AWS Storage | Support for Amazon S3 and Glacier storage |
| google_storage | Google Storage | Support for Google Cloud Storage |
| wasabi | Wasabi | Support for Wasabi cloud storage |
| backblaze | Backblaze | Support for Backblaze B2 cloud storage |

## Security & Compliance

| ID | Name | Description |
|----|------|-------------|
| mfa | Multi-Factor Authentication | Support for multi-factor authentication |
| rbac | Role-Based Access Control | Granular role-based access controls |
| audit_logging | Audit Logging | Comprehensive audit logging |
| compliance_reporting | Compliance Reporting | Reports for compliance purposes |
| hipaa | HIPAA Compliance | Health Insurance Portability and Accountability Act compliance |
| gdpr | GDPR Compliance | General Data Protection Regulation compliance |
| soc2 | SOC 2 Compliance | Service Organization Control 2 compliance |
| ransomware_detection | Ransomware Detection | Ability to detect potential ransomware activity |
| ransomware_protection | Ransomware Protection | Features to protect against ransomware |
| air_gap | Air Gap | Air-gapped backup capabilities |
| data_isolation | Data Isolation | Isolation of backup data for security |
| data_sovereignty | Data Sovereignty | Controls for data sovereignty requirements |

## Management & Monitoring

| ID | Name | Description |
|----|------|-------------|
| centralized_management | Centralized Management | Single console for managing all backups |
| multi_site_management | Multi-Site Management | Manage backups across multiple sites |
| monitoring | Monitoring | Real-time monitoring of backup operations |
| alerting | Alerting | Configurable alerts for backup issues |
| reporting | Reporting | Comprehensive reporting capabilities |
| custom_reporting | Custom Reporting | Ability to create custom reports |
| scheduled_reports | Scheduled Reports | Automatically generate and send reports |
| dashboard | Dashboard | Visual dashboard for backup status |
| health_checks | Health Checks | Automated backup health checks |
| backup_verification | Backup Verification | Verification that backups are valid and restorable |
| capacity_planning | Capacity Planning | Tools for storage capacity planning |
| mobile_app | Mobile App | Mobile application for management and monitoring |

## Integration

| ID | Name | Description |
|----|------|-------------|
| psa_integration | PSA Integration | Integration with Professional Services Automation tools |
| rmm_integration | RMM Integration | Integration with Remote Monitoring and Management tools |
| connectwise_manage | ConnectWise Manage | Integration with ConnectWise Manage |
| autotask | Autotask | Integration with Autotask PSA |
| syncro | Syncro | Integration with Syncro |
| datto_rmm | Datto RMM | Integration with Datto RMM |
| ncentral | N-central | Integration with N-able N-central |
| connectwise_automate | ConnectWise Automate | Integration with ConnectWise Automate |
| ninja_rmm | NinjaRMM | Integration with NinjaRMM |
| email_notifications | Email Notifications | Email notification capabilities |
| sms_notifications | SMS Notifications | SMS notification capabilities |
| webhook_support | Webhook Support | Support for webhooks for custom integrations |
| snmp | SNMP Support | Support for Simple Network Management Protocol |

## Pricing & Licensing

| ID | Name | Description |
|----|------|-------------|
| per_device | Per Device | Pricing based on number of devices |
| per_user | Per User | Pricing based on number of users |
| per_gb | Per GB | Pricing based on storage used |
| capacity_based | Capacity-Based | Pricing based on total capacity |
| unlimited_storage | Unlimited Storage | Unlimited storage options |
| free_tier | Free Tier | Availability of a free tier or version |
| trial_available | Trial Available | Availability of a free trial |
| monthly_billing | Monthly Billing | Option for monthly billing |
| annual_billing | Annual Billing | Option for annual billing |
| usage_based | Usage-Based | Pay-as-you-go pricing model |
| msp_pricing | MSP Pricing | Special pricing for Managed Service Providers |

