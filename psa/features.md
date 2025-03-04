# PSA Product Features

This file contains features specific to Professional Services Automation (PSA) products.

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
| db_access | On Premises Database Access | Direct access to the database in on-premises deployments |
> Database access can be important for custom reporting and integration with other systems.
| cloud_db | Cloud DB Access | Direct Access to the database in a cloud-deployment |
| hybrid | Hybrid | Supports both cloud and on-premises deployment options |
| white_label | White Label | Ability to rebrand the solution with your own branding |


## Core Functionality

| ID | Name | Description |
|----|------|-------------|
| multi_tenant | Multi-Tenant Support | Ability to manage multiple clients/organizations within a single instance |
| mobile_app | Mobile App | Dedicated mobile application for on-the-go access |
| api | API Access | Provides API for custom integrations |
| multi_timezone | Multi-Timezone Support | The ability to support multiple (global) timezones all at once from the end-user to the technician. |
| multi_language_support | Multi-Language Support | Supports multiple languages or the ability to create your own language pack. |
| global_search | Global Search | Search globally from any area of the application, with options to filter down specifics. |


## Ticketing

| ID | Name | Description |
|----|------|-------------|
| ticketing | Ticketing | Core ticketing functionality |
| ticket_status_custom | Ticket Status Customization | Ability to customize ticket statuses |
| scheduled_tickets | Scheduled / Recurring Ticket Creation | Create tickets on a schedule or recurring basis |
| threaded_conversations | Threaded Conversations | Threaded conversation support in tickets |
| email_to_ticket | Email to Ticket creation | Create tickets from incoming emails |
| automatic_replies | Automatic Replies | Automated responses to tickets |
| agent_calendar | Agent Calendar Integrations | Calendar integration for technicians |
| dispatch | Dispatch / Ticket Assigning | Assign and dispatch tickets to technicians |
| auto_dispatch | Automated Dispatch / Assigning | Assign and dispatch tickets automatically based on different types (Round Robin/Capacity) |
| ticket_areas | Ticket Area Type (Boards, Teams) | Organize tickets by boards or teams |
| time_tracking | Time Tracking | Track time spent on tickets |
| action_work_types | Action Based Work Types / Automatic Adjustments | Action-based billing or automatic adjustments of time entries to properly match to the business.  (After-Hours Calcs, Proper workrole billing) |
| sla | Service Level Agreements | Support for service level agreements |
| custom_sla | Custom SLA's (Per client, per contact) | Client or contact-specific SLAs |
| sla_options | SLA Options (Impact / Urgency) | Configure SLAs based on impact and urgency |
| ola | Operational Level Agreements | Support for operational level agreements |
| change_control | Change Control System | System for managing changes |
| knowledge_base | Knowledge Base / Internal Documentation | Knowledge base for internal documentation |
| services_catalog | Services Catalog | Catalog of available services |
| opportunity_ticketing | Opportunity Ticketing / Sales Ticketing | Ticketing for sales opportunities |
| attachments | Attachments | Support for file attachments in tickets |
| ticket_relationships | Ticket Merging/Childing/Linking/Splitting | Ability to relate tickets to each other |
| task_lists | Task Lists / Check List | Task lists or checklists within tickets |
| canned_responses | Canned Response Templates | Pre-defined response templates |
| work_roles | Work Role / Work Type | Define different work roles or types |
| ticket_types | Ticket Type / SubType | Categorize tickets by type and subtype |
| follow_tickets | Follow Ticket(s) | Ability to follow or watch tickets |
| ticket_priorities | Ticket Priorities | Define and set ticket priorities |
| custom_fields | Custom Fields | Add custom fields to tickets |
| add_products | Add Products to Ticket | Associate products with tickets |
| custom_ticket_info | Custom Ticket Information | Customize new ticket forms |
| rmm_integration | Deep RMM Integration | Perform RMM actions from tickets |
| ai_ticketing | AI In Ticketing | AI assistance in ticketing in general |
| ticket_notes | Public Notes / Private Notes | Support for public and private notes |

## Company/Contacts/Assets

| ID | Name | Description |
|----|------|-------------|
| company_management | Company Management | Manage client companies |
| child_companies | Child Companies | Support for parent-child company relationships |
| site_management | Site Management | Manage multiple client sites |
| company_grouping | Grouping of Companies | Group companies by vertical or team |
| contact_management | Contact Management | Manage client contacts |
| duplication_handling | Duplication issues | Handle duplicate contacts or companies |
| company_imports | Automated Company Imports | Import companies automatically |
| contact_imports | Automated Contact Imports | Import contacts automatically |
| crm | CRM | Customer relationship management features |
| asset_management | Asset Management | Track and manage client assets |
| asset_assigning | Asset Assigning | Assign assets to clients or users |
| automated_asset | Automated Asset Intake/Retire | Automate asset lifecycle management |
| client_portal | Client Portal | Portal for client access |
| portal_customization | Client Portal Customization | Customize the client portal |
| portal_forms | Custom Client Portal Forms | Create custom forms for the client portal |
| inventory_management | Inventory Management | Track and manage inventory |
| proration_billing | Proration Billing | Support for prorated billing |

## Contracts/Billing/Invoicing

| ID | Name | Description |
|----|------|-------------|
| contract_support | Contract / Agreement Support | Support for client contracts and agreements |
| charge_codes | Charge Codes / Billing Types | Define different billing rates for work types |
| contract_dates | Contract Dates (Start / End) | Set contract start and end dates |
| product_contracts | Product / Addition to Contracts | Add products to contracts |
| product_billing_dates | Product Billing Start/End Dates | Set billing dates for products |
| auto_product_updates | Automatic Updates to Product/additions | Automatically update product information |
| general_ledger | General Ledger Configuration | Configure general ledger settings |
| accounting_integration | Account Package Integrations | Integration with accounting software |
| custom_contract_types | Custom Contract / Agreement Types | Define custom contract types |
| break_fix | Break-Fix (T&M) | Time and materials billing |
| ayce | AYCE W/Additions | All-you-can-eat contracts with additions |
| block_hours | Block Hours | Pre-purchased block hour contracts |
| flat_fee | Flat Fee / Single Price | Flat fee billing |
| bill_to_company | Bill To Company | Bill to the client company |
| bill_to_different | Bill To Different People | Bill to different contacts or sites |
| billing_periods | Billing Periods | Support for different billing periods |
| custom_taxing | Custom Taxing | Configure taxes by location |
| custom_bill_date | Custom Bill To Date | Set custom billing dates |
| bill_types | Bill Types | Support for different billing types |
| proration_options | Proration Options | Options for prorated billing |
| payment_collection | Payment Collection | Collect payments from clients |
| multiple_billing_hours | Multiple "Billing Hours" / Work Hours | Define different billing hours |
| invoice_templates | Custom Templates for Invoices | Customize invoice templates |
| invoicing_review | Invoicing Review | Review invoices before sending |

## Dashboards/Reports/KPIs

| ID | Name | Description |
|----|------|-------------|
| executive_reports | Executive Reports | Reports for executives |
| invoicing_reports | Invoicing Reports | Reports on invoicing |
| sla_reports | SLA Reports | Reports on SLA performance |
| dashboards | Dashboards | Dashboards for key metrics |
| custom_reporting | Custom Reporting | Create custom reports |
| custom_dashboarding | Custom Dashboarding | Create custom dashboards |

## Automations

| ID | Name | Description |
|----|------|-------------|
| new_ticket_notifications | New Ticket Notifications | Notifications for new tickets |
| ticket_updated_notifications | Ticket Updated Notifications | Notifications for ticket updates |
| ticket_closed_notifications | Ticket Closed Notifications | Notifications for closed tickets |
| sla_notification | SLA Notification | Notifications for SLA breaches |
| ticket_moving | Ticket Moving/Reassigning | Automatically move or reassign tickets |
| email_parsing | Email Parsing/Automation | Parse and automate based on emails |
| add_update_ticket | Add Update to Ticket | Automatically add updates to tickets |
| assign_to_ticket | Assign To Ticket | Automatically assign tickets |
| email_end_user | Email End User | Automatically email end users |
| email_company_contact | Email Company Contact | Automatically email company contacts |
| email_custom | Email Custom | Custom email automations |
| update_sla | Update SLA | Automatically update SLAs |
| change_status | Change Status | Automatically change ticket status |

## Project Management

| ID | Name | Description |
|----|------|-------------|
| project_management | Overall Project Management Module | Comprehensive project management functionality |
| project_types | Project Types | Define different project types |
| kanban_views | KanBan Views | Kanban board views for projects |
| phases_milestones | Phases/Milestones | Define project phases and milestones |
| project_templates | Project Templates | Templates for common project types |
| phase_templates | Phases Templates / Append Project Templates | Templates for project phases |
| project_management_features | Project Management | Core project management features |
| project_communication | Project Communication Tracking | Track project communications |
| project_products | Project Product Additions | Add products to projects |
| project_time_tracking | Task-Based/Ticket-Based Time Tracking | Track time on project tasks or tickets |

## Other

| ID | Name | Description |
|----|------|-------------|
| mobile_app | Mobile App | Mobile application for on-the-go access | 