# Activities

<figure><img src="../../.gitbook/assets/image (158).png" alt=""><figcaption></figcaption></figure>

This module in CorpCash provides an audit trail of administrative activities performed within the platform. It enables administrators to review and track actions performed by users, including report downloads, wallet configuration updates, wallet transfers, wallet point revocations, and vendor cash-out approvals by recording the user, role, action, resource type, description, status, and timestamp. The module provides visibility into **who performed an action, the user's role, the action performed, the affected resource, a description of the activity, the execution status, and the date and time of the activity**.

For example, if an administrator needs to investigate a wallet transfer, they can review the activity log to identify **which user performed the transfer, the operation that was executed, the affected resource, the amount or recipient involved, and when the action occurred**.

#### Accessing the Activities Module

{% stepper %}
{% step %}
### Log in to CorpCash

Log in to the CorpCash platform using valid administrator credentials.

<figure><img src="../../.gitbook/assets/image (159).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
### Open the Activities module

From the left navigation panel, locate **Activities**.

<figure><img src="../../.gitbook/assets/image (160).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
### Click Activities

Click **Activities**.

The system displays the Activities dashboard.

<figure><img src="../../.gitbook/assets/image (161).png" alt=""><figcaption></figcaption></figure>
{% endstep %}
{% endstepper %}

## Summary Cards

The top section of the Activities page contains four summary cards.

These cards provide a quick overview of the activity status without requiring the administrator to inspect individual records.

<figure><img src="../../.gitbook/assets/image (164).png" alt=""><figcaption></figcaption></figure>

<table><thead><tr><th width="64" align="right">S. No.</th><th width="137">Summary Card</th><th>Description</th></tr></thead><tbody><tr><td align="right">1</td><td><strong>Total Activities</strong></td><td>Displays the total number of activities recorded across the platform for the available activity history.</td></tr><tr><td align="right">2</td><td><strong>Today's Activities</strong></td><td>Displays the number of activities recorded during the current day, calculated from midnight onward.</td></tr><tr><td align="right">3</td><td><strong>Critical Actions</strong></td><td>Displays the number of activities classified as critical or sensitive administrative actions. The interface specifically references revocations and configuration changes.</td></tr><tr><td align="right">4</td><td><strong>Failed Actions</strong></td><td>Displays the number of activities that were unsuccessful, including operations associated with errors or rejections.</td></tr></tbody></table>

### Activity Category Filters

The **Activities** module provides category-based filters that allow administrators to view audit records according to the functional area in which the activity was performed.

<figure><img src="../../.gitbook/assets/image (165).png" alt=""><figcaption></figcaption></figure>

<table><thead><tr><th width="64" align="right">S. No.</th><th width="119">Category</th><th>Description</th></tr></thead><tbody><tr><td align="right">1</td><td><strong>All</strong></td><td>The system displays activity records from all available categories. The <strong>All</strong> filter remains highlighted to indicate the active selection.</td></tr><tr><td align="right">2</td><td><strong>Wallet</strong></td><td>The system filters the activity table and displays wallet-related records.</td></tr><tr><td align="right">3</td><td><strong>Employee</strong></td><td>The system displays only employee-related activity records.</td></tr><tr><td align="right">4</td><td><strong>Vendor</strong></td><td>The system filters the activity records and displays vendor-related activities.</td></tr><tr><td align="right">5</td><td><strong>Settlement</strong></td><td>The system displays settlement-related activity records.</td></tr><tr><td align="right">6</td><td><strong>Configuration</strong></td><td>The system displays configuration-related activity records.</td></tr><tr><td align="right">7</td><td><strong>Rewards</strong></td><td>The system displays reward-related activity records.</td></tr><tr><td align="right">8</td><td><strong>Authentication</strong></td><td>The system displays authentication-related activity records.</td></tr><tr><td align="right">9</td><td><strong>Reporting</strong></td><td>The system displays reporting-related activity records.</td></tr></tbody></table>

## Export Activities

The **Export** functionality enables administrators to extract activity records from the **Activities** module for audit, compliance, reporting, investigation, and offline analysis purposes.

The Export control provides three export&#x20;

The Activities page provides an **Export** button that includes a dropdown indicator, suggesting three export scopes and three supported output formats, allowing administrators to determine **which records to export** and **in which format** the activity data should be generated.

<figure><img src="../../.gitbook/assets/image (166).png" alt=""><figcaption></figcaption></figure>

When the administrator clicks **Export**, an export configuration menu is displayed.

The menu is divided into two primary sections:

1. **Scope**
2. **Format**

The administrator must select the required scope and format before initiating the export.

<table><thead><tr><th width="107">Section</th><th width="146">Option</th><th>Purpose</th></tr></thead><tbody><tr><td><strong>Scope</strong></td><td>Export Current View</td><td>Exports the records currently visible in the activity table.</td></tr><tr><td><strong>Scope</strong></td><td>Export Filtered Records</td><td>Exports all records matching the currently applied filters.</td></tr><tr><td><strong>Scope</strong></td><td>Export Full Audit Log</td><td>Exports the complete audit dataset.</td></tr><tr><td><strong>Format</strong></td><td>CSV</td><td>Generates the activity data in CSV format.</td></tr><tr><td><strong>Format</strong></td><td>Excel</td><td>Generates the activity data in Excel format.</td></tr><tr><td><strong>Format</strong></td><td>PDF</td><td>Generates the activity data in PDF format.</td></tr></tbody></table>

### Activities Page

The Activities page displays **“Audit log of all admin actions.”** This indicates that the module is primarily intended to maintain an auditable record of administrative operations performed within CorpCash.

The activity records are presented in a structured table, allowing administrators to review historical actions and trace specific administrative operations.

#### Activity Log Fields

<figure><img src="../../.gitbook/assets/image (162).png" alt=""><figcaption></figcaption></figure>

<table><thead><tr><th width="149">Field</th><th>Description</th></tr></thead><tbody><tr><td>Activity ID</td><td>Unique identifier assigned to the activity</td></tr><tr><td><strong>Performed By</strong></td><td>Identifies the user who performed the administrative action. The value may be an email address or another user identifier.</td></tr><tr><td><strong>Role</strong></td><td>Specifies the role of the user who performed the action, such as <strong>Admin</strong>.</td></tr><tr><td><strong>Action</strong></td><td>Identifies the system-defined action or operation performed by the user.</td></tr><tr><td><strong>Resource</strong></td><td>Identifies the type of resource affected by the action, such as <strong>Report</strong>, <strong>Cashout</strong>, <strong>Employee Wallet Config</strong>, or <strong>Admin Wallet Transaction</strong>.</td></tr><tr><td><strong>Description</strong></td><td>Provides a human-readable explanation of the activity, including relevant transaction or resource information.</td></tr><tr><td><strong>Status</strong></td><td>Indicates whether the recorded action was successfully completed. In the displayed records, the status is <strong>Success</strong>.</td></tr><tr><td><strong>Date &#x26; Time</strong></td><td>Specifies the date and time at which the activity occurred.</td></tr></tbody></table>

#### Pagination

<figure><img src="../../.gitbook/assets/image (163).png" alt=""><figcaption></figcaption></figure>

The Activities page supports pagination for navigating through historical activity records. The displayed page shows **10 records per page** and indicates the total number of available records.

Administrators can use the page navigation controls to move between available pages. The **Go to** option can also be used to navigate directly to a specific page.

## Search Activity Records

<figure><img src="../../.gitbook/assets/image (167).png" alt=""><figcaption></figcaption></figure>

The Activities page provides a search field for locating specific records.

The search field supports searches based on information such as:

* User
* Email
* Action
* Resource
* Transaction ID

## Date-Range Filter

The **Date Range** filter in the **Activities** module enables administrators to restrict activity records to a specific predefined time period. It is used to narrow the audit trail and review activities that occurred within the selected period.

The date-range filter is available in the Activities toolbar, alongside the **Status**, **Reset**, and **Export** controls.

#### Default Date Range

When the Activities page is opened, the Date Range filter shown in the provided interface is:

> **Last 30 days**

<figure><img src="../../.gitbook/assets/image (168).png" alt=""><figcaption></figcaption></figure>

#### Date Range Options

It shows four predefined date-range options.

<table><thead><tr><th width="65" align="right">S. No.</th><th width="153">Date Range Option</th><th>Description</th></tr></thead><tbody><tr><td align="right">1</td><td><strong>Today</strong></td><td>Displays activities recorded for the current day.</td></tr><tr><td align="right">2</td><td><strong>Last 7 days</strong></td><td>Displays activities recorded within the previous seven-day period according to the application's date-range calculation.</td></tr><tr><td align="right">3</td><td><strong>Last 30 days</strong></td><td>Displays activities recorded within the previous 30-day period.</td></tr><tr><td align="right">4</td><td><strong>Last 90 days</strong></td><td>Displays activities recorded within the previous 90-day period.</td></tr></tbody></table>

#### Example

Selecting **Last 30 days** displays activities recorded during the configured last-30-day period.

## 18. Status Filter

The **Status Filter** in the **Activities** module enables administrators to filter activity records according to the current outcome or processing status of an activity.

<figure><img src="../../.gitbook/assets/image (169).png" alt=""><figcaption></figcaption></figure>

The filter is available in the Activities toolbar and can be used independently or together with **Activity Category, Search, and Date Range** filters. The screenshot shows five available status options:

* **All Statuses**
* **Success**
* **Failed**
* **Pending**
* **Cancelled**
* **Rejected**

<table><thead><tr><th width="70" align="right">S. No.</th><th width="130">Status</th><th>Description</th></tr></thead><tbody><tr><td align="right">1</td><td><strong>All Statuses</strong></td><td>Displays activities regardless of their status.</td></tr><tr><td align="right">2</td><td><strong>Success</strong></td><td>Displays activities that were successfully completed.</td></tr><tr><td align="right">3</td><td><strong>Failed</strong></td><td>Displays activities that failed during processing or execution.</td></tr><tr><td align="right">4</td><td><strong>Pending</strong></td><td>Displays activities that are currently pending or have not yet reached a final processing state.</td></tr><tr><td align="right">5</td><td><strong>Cancelled</strong></td><td>Displays activities that were cancelled before completion.</td></tr><tr><td align="right">6</td><td><strong>Rejected</strong></td><td>Displays activities that were rejected and therefore did not complete successfully.</td></tr></tbody></table>

## Reset Functionality

The **Reset** functionality in the **Activities** module enables administrators to clear the filters and search criteria currently applied to the activity audit table. It provides a quick way to return the Activities view to its default filtering state before starting a new search or investigation.

The **Reset** button is located in the Activities filter toolbar, next to the **Status** and **Export** controls.

<figure><img src="../../.gitbook/assets/image (170).png" alt=""><figcaption></figcaption></figure>
