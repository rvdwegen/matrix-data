# DNS Product Features

This file contains features specific to DNS Filtering and Management products.

## Company

| ID | Name | Description |
|----|------|-------------|
| parent | Parent | Parent Company |
| emp_size | Employee Size | Size of the company or division |
| founded | Founded | Year the company was founded |
| headquarters | Headquarters | Location of company headquarters |
| public_private | Public/Private | Whether the company is publicly traded or privately held |
| acquisition | Acquisition | Details about any acquisitions |

## Architecture & Infrastructure

| ID | Name | Description |
|----|------|-------------|
| anycast_dns | Anycast DNS | DNS servers distributed globally using anycast technology for improved performance and reliability |
| cloud_based | Cloud Based | Service delivered from the cloud without local hardware requirements |
| on_premises | On-Premises Option | Ability to deploy the solution on-premises |
| hybrid | Hybrid Deployment | Support for both cloud and on-premises deployment |
| local_proxy | Local Proxy/Appliance/VM | Support for local proxy servers, appliances, or virtual machines |
| multi_tenant | Multi-Tenant | Support for multiple tenants in a single instance |
| ipv6 | IPv6 Support | Support for IPv6 DNS resolution and filtering |
| dnssec | DNSSEC Support | Support for DNS Security Extensions |
| dns_over_https | DNS over HTTPS (DoH) | Support for DNS over HTTPS protocol |
| dns_over_tls | DNS over TLS (DoT) | Support for DNS over TLS protocol |
| private_dns | Private DNS | Support for private DNS zones and custom DNS records |
| recursive_dns | Recursive DNS | Provides recursive DNS resolution services |
| authoritative_dns | Authoritative DNS | Provides authoritative DNS hosting services |
| global_server_network | Global Server Network | Number and distribution of DNS servers globally |
| api_access | API Access | Programmatic access to the platform via API |
| high_availability | High Availability | Redundancy and failover capabilities |
| scalability | Scalability | Ability to scale with increasing demand |

## Web Filtering & Security

| ID | Name | Description |
|----|------|-------------|
| category_filtering | Category-Based Filtering | Ability to filter content based on predefined or custom categories |
| content_filtering | Content Filtering | Filtering of web content based on policies and rules |
| custom_lists | Custom Allow/Deny Lists | Support for custom whitelists and blacklists |
| time_filtering | Time-Based Filtering | Filtering based on time of day or day of week |
| safe_search | Safe Search Enforcement | Enforcement of safe search in search engines and YouTube |
| malware_phishing | Malware & Phishing | Protection against malware and phishing attempts |
| botnet | Botnet Protection | Protection against botnet communication and control |
| ransomware | Ransomware Protection | Protection against ransomware attacks |
| cryptomining | Cryptomining Protection | Protection against cryptomining scripts |
| zero_day | Zero-Day Protection | Protection against zero-day threats |
| typosquatting | Typosquatting Protection | Protection against typosquatting domains |
| domain_generation | Domain Generation Algorithm Protection | Protection against DGA-based malware |
| ai_threat | AI/ML Threat Analytics | Use of artificial intelligence and machine learning for threat detection |
| threat_intelligence | Threat Intelligence | Integration with threat intelligence feeds |
| custom_block_pages | Customized Block Pages | Ability to customize the pages shown when content is blocked |
| ssl_inspection | SSL Inspection | Ability to inspect encrypted SSL/TLS traffic |
| bypass_options | Bypass Options | Ability to temporarily bypass filtering |
| geoip_blocking | GeoIP Blocking | Blocking access based on geographic location |
| app_blocking | Application Blocking | Ability to block specific applications |
| file_type_filtering | File Type Filtering | Filtering based on file types |
| keyword_filtering | Keyword Filtering | Filtering based on keywords in URLs or content |
| regex_filtering | Regex Filtering | Filtering using regular expressions |

## Client & Endpoint Management

| ID | Name | Description |
|----|------|-------------|
| roaming_client | Roaming Client Support | Support for clients that move between networks while maintaining protection |
| device_filtering | Device-Based Filtering | Filtering at the device level without requiring local DNS alterations |
| roaming_os_support | Roaming OS Support | Support for various operating systems when roaming |
| windows_client | Windows Client | Client software for Windows operating systems |
| macos_client | macOS Client | Client software for macOS operating systems |
| linux_client | Linux Client | Client software for Linux operating systems |
| ios_client | iOS Client | Client software for iOS devices |
| android_client | Android Client | Client software for Android devices |
| chromebook_client | Chromebook Client | Client software for Chromebook devices |
| client_auto_update | Client Auto-Update | Automatic updates for client software |
| client_deployment | Client Deployment Tools | Tools for deploying client software at scale |
| device_isolation | Device Isolation | Ability to isolate compromised devices from the network |
| network_segmentation | Network Segmentation Support | Support for VLANs, SSIDs, and other network segmentation technologies |
| mdm_integration | MDM Integration | Integration with Mobile Device Management solutions |

## Policy Management

| ID | Name | Description |
|----|------|-------------|
| role_policies | Role-Based Policies | Ability to assign different filtering policies based on user roles |
| group_policies | Group-Based Policies | Ability to assign policies based on user groups |
| location_policies | Location-Based Policies | Different policies based on location |
| device_policies | Device-Based Policies | Different policies based on device type |
| policy_inheritance | Policy Inheritance | Hierarchical policy inheritance |
| policy_scheduling | Policy Scheduling | Schedule when policies are active |
| policy_exceptions | Policy Exceptions | Create exceptions to policies for specific users or devices |
| policy_templates | Policy Templates | Pre-defined policy templates |
| policy_import_export | Policy Import/Export | Ability to import and export policies |
| end_user_access | End-User Access / Downstream IT | Ability for end-users or downstream IT to access and manage settings |
| delegated_admin | Delegated Administration | Ability to delegate administration to different levels |

## Reporting & Analytics

| ID | Name | Description |
|----|------|-------------|
| timeline_logs | Timeline Activity Logs | Chronological logs of activity for analysis |
| traffic_logs | Traffic Logs | Detailed logs of network traffic |
| export_options | Exporting Options | Ability to export logs and reports in various formats |
| real_time_monitoring | Real-Time Monitoring | Ability to monitor activity in real-time |
| behavior_analytics | User / Entity Behavior Analytics | Analysis of user and entity behavior to detect anomalies |
| custom_reports | Custom Reports | Ability to create custom reports |
| scheduled_reports | Scheduled Reports | Ability to schedule report generation and delivery |
| dashboard | Dashboard | Visual dashboard for monitoring and analytics |
| log_retention | Log Retention | Duration of log retention |
| siem_integration | SIEM Integration | Integration with Security Information and Event Management systems |
| alert_notifications | Alert Notifications | Configurable alerts and notifications |
| email_reports | Email Reports | Ability to send reports via email |

## DNS Management

| ID | Name | Description |
|----|------|-------------|
| dns_hosting | DNS Hosting | Hosting of DNS zones |
| domain_registration | Domain Registration | Domain registration services |
| dns_record_management | DNS Record Management | Management of DNS records |
| bulk_record_management | Bulk Record Management | Tools for managing multiple DNS records at once |
| dns_templates | DNS Templates | Templates for common DNS configurations |
| dns_propagation | DNS Propagation Monitoring | Tools for monitoring DNS propagation |
| dns_health_checks | DNS Health Checks | Monitoring of DNS health and performance |
| dns_failover | DNS Failover | Automatic failover for DNS services |
| geo_routing | Geographic Routing | Route DNS queries based on geographic location |
| load_balancing | Load Balancing | DNS-based load balancing |
| traffic_steering | Traffic Steering | Advanced traffic routing capabilities |
| dns_analytics | DNS Analytics | Analytics for DNS traffic and performance |
| dns_caching | DNS Caching | Control over DNS caching behavior |
| ttl_management | TTL Management | Management of Time-To-Live values |
| secondary_dns | Secondary DNS | Secondary DNS services for redundancy |
| zone_transfer | Zone Transfer | Support for zone transfers (AXFR/IXFR) |
| dynamic_dns | Dynamic DNS | Support for dynamic DNS updates |

## Compliance & Privacy

| ID | Name | Description |
|----|------|-------------|
| compliance | GDPR/CCPA Compliance | Compliance with privacy regulations like GDPR and CCPA |
| hipaa | HIPAA Compliance | Compliance with healthcare privacy regulations |
| cipa | CIPA Compliance | Compliance with Children's Internet Protection Act |
| data_sovereignty | Data Sovereignty | Controls for data sovereignty requirements |
| audit_logging | Audit Logging | Comprehensive audit logging for compliance |
| compliance_reporting | Compliance Reporting | Reports for compliance purposes |
| data_retention | Data Retention Controls | Controls for data retention periods |
| privacy_controls | Privacy Controls | Features to enhance user privacy |
| consent_management | Consent Management | Tools for managing user consent |

## Integration

| ID | Name | Description |
|----|------|-------------|
| active_directory | Active Directory Integration | Integration with Microsoft Active Directory |
| azure_ad | Azure AD Integration | Integration with Microsoft Azure Active Directory |
| ldap | LDAP Integration | Integration with LDAP directories |
| saml | SAML Integration | Support for SAML authentication |
| oauth | OAuth Support | Support for OAuth authentication |
| rmm_integration | RMM Integration | Integration with Remote Monitoring and Management tools |
| psa_integration | PSA Integration | Integration with Professional Services Automation tools |
| connectwise_manage | ConnectWise Manage | Integration with ConnectWise Manage |
| autotask | Autotask | Integration with Autotask PSA |
| syncro | Syncro | Integration with Syncro |
| datto_rmm | Datto RMM | Integration with Datto RMM |
| ncentral | N-central | Integration with N-able N-central |
| connectwise_automate | ConnectWise Automate | Integration with ConnectWise Automate |
| ninja_rmm | NinjaRMM | Integration with NinjaRMM |
| webhook_support | Webhook Support | Support for webhooks for custom integrations |

## MSP Features

| ID | Name | Description |
|----|------|-------------|
| whitelabeling | Whitelabeling | Ability to customize branding for resellers or MSPs |
| multi_tenant_management | Multi-Tenant Management | Tools for managing multiple client tenants |
| client_reporting | Client Reporting | Client-specific reporting capabilities |
| client_onboarding | Client Onboarding | Tools for onboarding new clients |
| msp_dashboard | MSP Dashboard | Centralized dashboard for MSP management |
| msp_billing | MSP Billing Integration | Integration with MSP billing systems |
| service_tiers | Service Tiers | Support for different service tiers |
| msp_pricing | MSP Pricing | Special pricing for Managed Service Providers |
| msp_support | MSP-Specific Support | Dedicated support for MSPs |
| msp_training | MSP Training | Training resources for MSPs |

## Pricing & Licensing

| ID | Name | Description |
|----|------|-------------|
| per_user | Per User | Pricing based on number of users |
| per_device | Per Device | Pricing based on number of devices |
| per_location | Per Location | Pricing based on number of locations |
| per_query | Per Query | Pricing based on number of DNS queries |
| unlimited_queries | Unlimited Queries | Unlimited DNS queries included |
| free_tier | Free Tier | Availability of a free tier or version |
| trial_available | Trial Available | Availability of a free trial |
| monthly_billing | Monthly Billing | Option for monthly billing |
| annual_billing | Annual Billing | Option for annual billing |
| volume_discounts | Volume Discounts | Discounts for volume purchases |



