# Report

The **Reports** module provides administrators with a centralized interface for accessing and reviewing financial reports and ledger information across wallets and transactions. The module is designed to provide visibility into financial movements, wallet balances, employee-related wallet activity, transaction records, and vendor-related information.

The Reports page displays multiple report categories through dedicated tabs, allowing administrators to select the appropriate report based on the information they need to review.

<figure><img src="../../../.gitbook/assets/image (62).png" alt=""><figcaption></figcaption></figure>

#### Reports Dashboard

The Reports page contains the following report tabs:

* **Treasury Ledger**
* **Service Wallet Ledger**
* **Admin Wallet**
* **Employee Wallet Summary**
* **Transaction Report**
* **Vendor Report**

Each report provides information for a specific financial or operational area within the CorpCash platform.

### Treasury Ledger

<figure><img src="../../../.gitbook/assets/image (63).png" alt=""><figcaption></figcaption></figure>

The **Treasury Ledger** is the default selected report in the displayed interface. It provides a detailed record of financial transactions associated with the Treasury Wallet.

The ledger enables administrators to review individual financial movements and understand how each transaction affects the available wallet balance.

It displays the following information:

<table><thead><tr><th width="191">Field</th><th>Description</th></tr></thead><tbody><tr><td><strong>Transaction ID</strong></td><td>Unique identifier assigned to the transaction.</td></tr><tr><td><strong>Type</strong></td><td>Indicates whether the transaction is a <strong>Credit</strong> or <strong>Debit</strong>.</td></tr><tr><td><strong>Amount</strong></td><td>Amount associated with the transaction.</td></tr><tr><td><strong>Balance After</strong></td><td>Wallet balance available after the transaction has been processed.</td></tr><tr><td><strong>Created By</strong></td><td>Email address or user identifier of the administrator/user who initiated the transaction.</td></tr><tr><td><strong>Created At</strong></td><td>Date and time when the transaction record was created.</td></tr></tbody></table>

#### Transaction Type

The **Type** field identifies the nature of the financial movement.

**Credit** indicates that an amount has been added to the applicable wallet, resulting in an increase in the wallet balance.

**Debit** indicates that an amount has been deducted from the applicable wallet, resulting in a decrease in the wallet balance.

The **Balance After** field provides the resulting wallet balance following the transaction and can be used to track the financial position of the wallet over time.

### Search and Filtering

The Reports module provides search and filtering controls that allow administrators to narrow the displayed records and locate specific financial transactions.

The Treasury Ledger includes a search field with the placeholder **“Search by ID or remarks...”**. Administrators can use this field to search for relevant records using the supported transaction identifier or remarks.

The **All Types** dropdown allows administrators to filter transactions according to their transaction type. This can be used to distinguish between credit and debit transactions.

The **Select date range** field allows administrators to restrict the displayed records to a specific period. This is useful when reviewing transactions for a particular reporting period, reconciliation cycle, or audit requirement.

An additional **Filter** icon is available next to the date range control for applying further supported filtering criteria.

Administrators can combine the available search and filtering options to narrow the dataset and efficiently locate the required records.

### Export&#x20;

<figure><img src="../../../.gitbook/assets/image (65).png" alt=""><figcaption></figcaption></figure>

The **Export** option is available on the Reports page and allows administrators to extract the displayed report data for further analysis, reconciliation, reporting, or record-keeping purposes.

Before exporting information, administrators should apply the required search criteria, transaction type, date range, and other available filters to ensure that the required dataset is displayed.

Exported reports should be handled securely because they may contain financial and transaction-related information.

### Report Navigation

Administrators can switch between the available report types by selecting the corresponding tab at the top of the Reports page.

<figure><img src="../../../.gitbook/assets/image (66).png" alt=""><figcaption></figcaption></figure>

#### Service Wallet Ledger

The **Service Wallet Ledger** provides ledger information associated with service wallets. It can be used to review financial movements and transaction activity related to service-level wallet operations.

<figure><img src="../../../.gitbook/assets/image (71).png" alt=""><figcaption></figcaption></figure>

When the **Service Wallet Ledger** tab is selected, it is highlighted to indicate that the corresponding report is active.

### Service Wallet Ledger Table

The Service Wallet Ledger displays transaction records in a structured tabular format. Each record provides information required to identify the transaction, understand the financial movement, determine the payment method, and verify its processing status.

<table><thead><tr><th width="149.15380859375">Field</th><th>Description</th></tr></thead><tbody><tr><td><strong>ET ID</strong></td><td>Employee Transaction ID associated with the transaction. Where the transaction is not directly associated with an employee transaction, the field may display <strong>“-”</strong>.</td></tr><tr><td><strong>ST ID</strong></td><td>Service Transaction ID assigned to the service-level transaction.</td></tr><tr><td><strong>Type</strong></td><td>Indicates the financial movement associated with the transaction, such as <strong>Credit</strong> or <strong>Debit</strong>.</td></tr><tr><td><strong>Amount</strong></td><td>Specifies the monetary value associated with the transaction.</td></tr><tr><td><strong>Payment Mode</strong></td><td>Indicates the payment method or service through which the transaction was processed, such as <strong>Gift Card</strong>.</td></tr><tr><td><strong>Created At</strong></td><td>Specifies the date and time when the service transaction was created.</td></tr><tr><td><strong>Status</strong></td><td>Indicates the current processing state of the transaction, such as <strong>Pending</strong>, <strong>Success</strong>, or <strong>Rejected</strong>.</td></tr></tbody></table>

**Transaction Type**

<figure><img src="../../../.gitbook/assets/image (72).png" alt=""><figcaption></figcaption></figure>

<table><thead><tr><th width="120.26922607421875">Transaction Type</th><th width="392.03851318359375">Description</th><th>Example</th></tr></thead><tbody><tr><td><strong>Credit</strong></td><td>Indicates that funds have been added to the applicable service wallet or represent an incoming financial movement.</td><td>A credit transaction of <strong>1,000</strong> or <strong>100</strong> added to the service wallet.</td></tr><tr><td><strong>Debit</strong></td><td>Indicates that funds have been deducted from the applicable service wallet as part of a service transaction.</td><td>A debit transaction associated with a <strong>Gift Card</strong> purchase or service payment.</td></tr></tbody></table>

### Transaction Status

<figure><img src="../../../.gitbook/assets/image (73).png" alt=""><figcaption></figcaption></figure>

The **Status** field provides the current processing state of the service wallet transaction.

It displays the following statuses:

| Status       | Description                                                                                         |
| ------------ | --------------------------------------------------------------------------------------------------- |
| **Pending**  | Indicates that the transaction has been initiated but has not yet reached a final processing state. |
| **Success**  | Indicates that the transaction has been successfully processed.                                     |
| **Rejected** | Indicates that the transaction was not accepted or completed successfully.                          |

The status information is particularly useful for identifying transactions that require further investigation or reconciliation.

### Transaction Type Filter

The **All Types** dropdown allows administrators to filter the Service Wallet Ledger according to the transaction type.

<figure><img src="../../../.gitbook/assets/image (74).png" alt=""><figcaption></figcaption></figure>

Administrators can use this filter to distinguish between different financial movements, such as:

* Credit
* Debit

Selecting a specific transaction type allows administrators to focus on only the relevant financial activity.

### Status Filter

The **All Statuses** dropdown allows administrators to filter transactions based on their processing status.

<figure><img src="../../../.gitbook/assets/image (75).png" alt=""><figcaption></figcaption></figure>

This enables administrators to isolate transactions such as:

* Pending
* Success
* Rejected

For example, administrators can select **Pending** to review transactions that have not yet reached a final status.

### Date Range Filter

The **Select date range** field allows administrators to restrict the displayed transactions to a specified period.

<figure><img src="../../../.gitbook/assets/image (76).png" alt=""><figcaption></figcaption></figure>

This functionality can be used for:

* Daily transaction review
* Monthly reconciliation
* Periodic financial reporting
* Audit investigations
* Historical transaction analysis

Administrators can combine the date range with other filters to obtain a more targeted dataset.

### Export Functionality

<figure><img src="../../../.gitbook/assets/image (77).png" alt=""><figcaption></figcaption></figure>

The **Export** button allows administrators to export the report data for external analysis, reconciliation, reporting, or record-keeping purposes.

Administrators should apply the required search criteria and filters before exporting when only a specific subset of transactions is required.

For example, an administrator may filter the report by:

**Transaction Type → Debit**\
**Status → Success**\
**Date Range → Required reporting period**

The resulting records can then be exported for further processing.

{% hint style="info" %}
Exported financial and transaction information should be handled securely and shared only with authorized personnel.
{% endhint %}

#### Admin Wallet

The **Admin Wallet** report provides information related to transactions and financial activity performed through the Admin Wallet. Administrators can use this report to review wallet movements and associated transaction details.

<figure><img src="../../../.gitbook/assets/image (78).png" alt=""><figcaption></figcaption></figure>

**Admin Wallet Report Fields**

<table><thead><tr><th width="154.923095703125">Field</th><th>Description</th></tr></thead><tbody><tr><td><strong>Transaction ID</strong></td><td>Unique identifier assigned to each Admin Wallet transaction. It can be used to track and reference a specific transaction.</td></tr><tr><td><strong>Employee Name</strong></td><td>Name of the employee associated with the transaction. If the transaction is not associated with a specific employee, the field may display <strong>“—”</strong>.</td></tr><tr><td><strong>Employee Email</strong></td><td>Registered email address of the employee associated with the transaction. If no employee is associated, the field may display <strong>“—”</strong>.</td></tr><tr><td><strong>Wallet Type</strong></td><td>Identifies the employee wallet affected by the transaction, such as <strong>Reward</strong> or <strong>Meal</strong>.</td></tr><tr><td><strong>Amount</strong></td><td>Specifies the monetary amount involved in the transaction.</td></tr><tr><td><strong>Mode</strong></td><td>Indicates the mode through which the transaction was initiated or processed. In the displayed records, the mode is <strong>Individual</strong>.</td></tr><tr><td><strong>Created At</strong></td><td>Specifies the date and time at which the transaction record was created.</td></tr><tr><td><strong>Status</strong></td><td>Indicates the processing status of the transaction. The displayed records show <strong>Success</strong>.</td></tr></tbody></table>

#### Transaction Type Filter

The **All Types** filter is available in the **Admin Wallet** report within the **Reports** module. It allows administrators to filter Admin Wallet transaction records based on the type of employee wallet associated with the transaction.

When the filter is set to **All Types**, the system displays transactions across all available wallet types. Administrators can select a specific wallet type from the dropdown to narrow the report results.

#### Available Filter Options

The **All Types** dropdown provides the following options:

<table><thead><tr><th width="133.76922607421875">Filter Option</th><th>Description</th></tr></thead><tbody><tr><td><strong>All Types</strong></td><td>Displays Admin Wallet transactions across all available wallet types. This is the default selection.</td></tr><tr><td><strong>Meal</strong></td><td>Filters the report to display transactions associated with the <strong>Meal</strong> wallet.</td></tr><tr><td><strong>Fuel</strong></td><td>Filters the report to display transactions associated with the <strong>Fuel</strong> wallet.</td></tr><tr><td><strong>Travel</strong></td><td>Filters the report to display transactions associated with the <strong>Travel</strong> wallet.</td></tr><tr><td><strong>Reward</strong></td><td>Filters the report to display transactions associated with the <strong>Reward</strong> wallet.</td></tr></tbody></table>

#### All Types

The **All Types** option is selected by default. When this option is applied, the report displays transactions associated with all wallet types available in the Admin Wallet report.

This option is useful when administrators need to review the complete Admin Wallet transaction history without restricting the results to a particular wallet category.

#### Meal

Selecting **Meal** filters the Admin Wallet report to display only transactions associated with the **Meal Wallet**.

This filter can be used when administrators need to review transactions related specifically to meal benefits or meal-wallet allocations.

#### Fuel

Selecting **Fuel** filters the report to display only transactions associated with the **Fuel Wallet**.

Administrators can use this option to isolate fuel-related employee wallet transactions for monitoring, reconciliation, or reporting.

#### Travel

Selecting **Travel** filters the report to display only transactions associated with the **Travel Wallet**.

This allows administrators to review transactions specifically related to travel benefits or travel-wallet allocations.

#### Reward

Selecting **Reward** filters the report to display only transactions associated with the **Reward Wallet**.

This option can be used to review reward-related wallet transactions and analyze employee reward allocations or transfers.

#### Using the All Types Filter

Administrators can apply the filter by opening the **All Types** dropdown and selecting the required wallet type. Once a specific option is selected, the report updates the displayed transaction records based on the selected wallet type.

The filter can also be used in combination with other available report controls, including:

* **Search** — Search by employee name, employee email, or transaction ID.
* **All Status** — Filter transactions according to their processing status.
* **Select date range** — Restrict transactions to a specific period.
* **Additional Filter** — Apply other supported filtering criteria.
* **Export** — Export the filtered report data for further analysis or record keeping.

#### Example

If an administrator selects **Reward** from the **All Types** dropdown, the Admin Wallet report will be narrowed to transactions where the **Wallet Type** is **Reward**. Transactions associated with Meal, Fuel, or Travel wallets will not be included in the filtered results.

Similarly, selecting **Meal** will display only transactions associated with the Meal Wallet.

> **Note:** The available wallet types shown in the filter are based on the wallet types configured for the organization. The screenshot confirms **Meal, Fuel, Travel, and Reward** as the available options in the Admin Wallet report.

#### Employee Wallet Summary

The **Employee Wallet Summary** provides a consolidated view of employee wallet information. It can be used to review employee-level wallet balances and related financial information.

The report enables administrators to review the amount available in each employee wallet, compare balances across wallet types, and view the **total wallet balance** associated with each employee. It is particularly useful for employee-level financial monitoring, balance verification, reconciliation, and reporting.

#### Accessing Employee Wallet Summary

Administrators can access the report through:

**Reports → Employee Wallet Summary**

<figure><img src="../../../.gitbook/assets/image (79).png" alt=""><figcaption></figcaption></figure>

When the **Employee Wallet Summary** tab is selected, it is highlighted to indicate that the report is currently active.

The report provides a consolidated view of employee wallet balances across the following wallet categories:

* **Meal**
* **Fuel**
* **Travel**
* **Reward**
* **Total**

<figure><img src="../../../.gitbook/assets/image (80).png" alt=""><figcaption></figcaption></figure>

### Employee Wallet Summary Fields

<table><thead><tr><th width="183.76922607421875">Field</th><th>Description</th></tr></thead><tbody><tr><td><strong>Employee Email</strong></td><td>Displays the registered email address associated with the employee. This provides a unique contact reference for identifying the employee.</td></tr><tr><td><strong>Employee ID</strong></td><td>Displays the unique identifier assigned to the employee within CorpCash.</td></tr><tr><td><strong>Meal</strong></td><td>Displays the balance available in the employee's Meal Wallet.</td></tr><tr><td><strong>Fuel</strong></td><td>Displays the balance available in the employee's Fuel Wallet.</td></tr><tr><td><strong>Travel</strong></td><td>Displays the balance available in the employee's Travel Wallet.</td></tr><tr><td><strong>Reward</strong></td><td>Displays the balance available in the employee's Reward Wallet.</td></tr><tr><td><strong>Total</strong></td><td>Displays the consolidated balance across all wallet types associated with the employee.</td></tr></tbody></table>

#### Wallet-wise Balance

The report separates employee balances according to individual wallet categories. This allows administrators to identify how an employee's overall balance is distributed across different benefit wallets.

<figure><img src="../../../.gitbook/assets/image (81).png" alt=""><figcaption></figcaption></figure>

For example, an employee may have balances distributed between the **Meal**, **Travel**, and **Reward** wallets while having no balance in the **Fuel** wallet.

The **Total** column provides the consolidated value across the displayed wallet categories.

### Search Functionality

<figure><img src="../../../.gitbook/assets/image (82).png" alt=""><figcaption></figcaption></figure>

The Employee Wallet Summary provides a search field with the placeholder **“Search by email...”**.

Administrators can enter an employee's registered email address to locate the corresponding employee wallet summary.

This functionality is useful when administrators need to review the wallet balances of a specific employee without manually searching through the complete employee list.

For example, searching for an email such as [**kumar@yopmail.com**](mailto:kumar@yopmail.com) can be used to locate the corresponding employee's wallet summary.

### Export Functionality

<figure><img src="../../../.gitbook/assets/image (83).png" alt=""><figcaption></figcaption></figure>

The **Export** option is available on the Employee Wallet Summary page. Administrators can use this functionality to extract the employee wallet summary data for external analysis, reconciliation, reporting, or record keeping.

Before exporting, administrators should review the displayed records and apply the required search criteria when a specific employee or subset of data is required.

The exported information should be handled securely because it may contain employee identifiers, email addresses, and financial balance information.

### Pagination

The Employee Wallet Summary supports pagination to manage and navigate through employee records.

The screenshot indicates:

<figure><img src="../../../.gitbook/assets/image (84).png" alt=""><figcaption></figcaption></figure>

This means that **17 employee wallet summary records** are available, with **10 records displayed on the current page**.

The interface provides pagination controls to navigate between available pages. Administrators can also use the **Go to** option to navigate directly to a specific page.

<figure><img src="../../../.gitbook/assets/image (85).png" alt=""><figcaption></figcaption></figure>

















#### Transaction Report

<figure><img src="../../../.gitbook/assets/image (86).png" alt=""><figcaption></figcaption></figure>

The **Transaction Report** provides transaction-oriented information across the CorpCash platform. It can be used to review and analyze transaction activity based on the available reporting criteria.

It enables administrators to monitor transaction activity, review the associated employee and service, identify the wallet affected, verify transaction amounts and dates, and track the processing status of each transaction.

The **Transaction Report** can be accessed by navigating to **Reports → Transaction Report**. When selected, the Transaction Report tab is highlighted to indicate that the report is active.

<figure><img src="../../../.gitbook/assets/image (87).png" alt=""><figcaption></figcaption></figure>

#### Transaction Report Details

<table><thead><tr><th width="139.5384521484375">Field</th><th>Description</th></tr></thead><tbody><tr><td><strong>Transaction ID</strong></td><td>Unique identifier assigned to the transaction. It can be used to track and reference an individual transaction.</td></tr><tr><td><strong>Employee</strong></td><td>Identifies the employee associated with the transaction.</td></tr><tr><td><strong>Service</strong></td><td>Specifies the service or business operation through which the transaction was initiated, such as Rewards Bridge, Admin Transfer, Revoke, Vendor Payment, or Gift Card.</td></tr><tr><td><strong>Wallet Type</strong></td><td>Identifies the employee wallet associated with the transaction, such as Reward or Meal Wallet.</td></tr><tr><td><strong>Amount</strong></td><td>Specifies the amount involved in the transaction.</td></tr><tr><td><strong>Date</strong></td><td>Indicates the date and time when the transaction was created or recorded.</td></tr><tr><td><strong>Status</strong></td><td>Indicates the current processing state of the transaction, such as Success, Pending, or Failed.</td></tr></tbody></table>

#### Search Functionality

The Transaction Report provides a search functionality using this, administrators can locate transactions using either the **Transaction ID** or the associated **employee information**.

This functionality allows administrators to quickly locate a specific transaction or review all relevant transactions associated with an employee without manually searching through the complete report.

<figure><img src="../../../.gitbook/assets/image (88).png" alt=""><figcaption></figcaption></figure>

#### Wallet Type Filter

The **All Wallet Types** dropdown allows administrators to filter transaction records according to the wallet associated with the transaction.

<figure><img src="../../../.gitbook/assets/image (89).png" alt=""><figcaption></figcaption></figure>

The filter can be used to isolate transactions for a specific wallet type, such as:

* **Meal Wallet**
* **Fuel**
* **Travel**
* **Reward**

When **All Wallet Types** is selected, the report displays transactions across all available wallet types.

#### Status Filter

The **All Status** dropdown enables administrators to filter transactions according to their processing status.

<figure><img src="../../../.gitbook/assets/image (90).png" alt=""><figcaption></figcaption></figure>

The screenshot shows transaction statuses including:

<table><thead><tr><th width="113.576904296875">Status</th><th>Description</th></tr></thead><tbody><tr><td><strong>Success</strong></td><td>Indicates that the transaction was successfully processed.</td></tr><tr><td><strong>Pending</strong></td><td>Indicates that the transaction is still awaiting completion or has not reached a final processing state.</td></tr><tr><td><strong>Failed</strong></td><td>Indicates that the transaction could not be successfully processed.</td></tr></tbody></table>

This filter is particularly useful for identifying pending or failed transactions that may require further investigation.

#### Service Filter

The **All Services** dropdown allows administrators to filter transactions according to the service through which the transaction was initiated.

When **All Services** is selected, the report displays transactions across all services available in the organization. Administrators can select an individual service from the dropdown to restrict the report to transactions associated with that specific service.

<figure><img src="../../../.gitbook/assets/image (91).png" alt=""><figcaption></figcaption></figure>

**The services including:**

<table><thead><tr><th width="133.76922607421875">Service</th><th>Description</th></tr></thead><tbody><tr><td><strong>All Services</strong></td><td>Displays transaction records associated with all available services. This is the default selection.</td></tr><tr><td><strong>Gift Card</strong></td><td>Filters the report to display transactions generated through the <strong>Gift Card</strong> service, such as transactions related to purchasing or issuing gift cards.</td></tr><tr><td><strong>Vendor Payment</strong></td><td>Filters the report to display transactions associated with <strong>payments made to vendors</strong>.</td></tr><tr><td><strong>Wallet Transfer</strong></td><td>Filters the report to display transactions involving the <strong>transfer of funds between wallets</strong> or supported wallet accounts.</td></tr><tr><td><strong>Fuel</strong></td><td>Filters the report to display transactions associated with the <strong>Fuel</strong> service.</td></tr><tr><td><strong>Travel</strong></td><td>Filters the report to display transactions associated with the <strong>Travel</strong> service.</td></tr><tr><td><strong>Meal</strong></td><td>Filters the report to display transactions associated with the <strong>Meal</strong> service.</td></tr></tbody></table>

The available service options may vary depending on the services enabled and configured within CorpCash.

#### Date Range Filter

The **Select date range** control enables administrators to restrict the report results to a specific date or reporting period.

<figure><img src="../../../.gitbook/assets/image (92).png" alt=""><figcaption></figcaption></figure>

This can be used for:

* Daily transaction monitoring
* Weekly or monthly reconciliation
* Financial reporting
* Historical transaction analysis
* Audit and compliance activities
* Investigation of specific transaction periods

Administrators can combine the date range with the wallet, status, and service filters to obtain a more targeted set of transaction records.

#### Export Functionality

The **Export** option enables administrators to extract Transaction Report data for external analysis, reconciliation, reporting, or record keeping.

<figure><img src="../../../.gitbook/assets/image (93).png" alt=""><figcaption></figcaption></figure>

Administrators can first apply the required search and filtering criteria and then select **Export** to generate the required dataset.

For example, an administrator can filter the report to display:

**Wallet Type → Reward**\
**Status → Failed**\
**Service → Gift Card**\
**Date Range → Required reporting period**

The resulting records can then be exported for further investigation or reconciliation.

#### Example Transaction Records

The screenshot displays **100 transaction records**, with **10 records displayed per page**.

#### Transaction Status Monitoring

The **Status** field allows administrators to distinguish between successfully completed transactions and transactions that may require attention.

A **Success** status indicates that the transaction has completed successfully. A **Pending** status indicates that processing is still in progress or has not reached a final state. A **Failed** status indicates that the transaction was unsuccessful and may require investigation or corrective action.

For example, the screenshot shows a **Gift Card** transaction for **50** with a **Pending** status and another Gift Card transaction for **400** with a **Failed** status.

#### Pagination

The Transaction Report supports pagination to facilitate navigation through large volumes of transaction records.

The screenshot indicates:

<figure><img src="../../../.gitbook/assets/image (94).png" alt=""><figcaption></figcaption></figure>

**Showing 1–10 of 100**

This means that **100 transaction records** are available, with **10 records displayed on the current page**.

The interface provides page navigation controls, including previous and next navigation and direct page selection. The **Go to** option allows administrators to navigate directly to a specific page.

<figure><img src="../../../.gitbook/assets/image (95).png" alt=""><figcaption></figcaption></figure>

#### Vendor Report

The **Vendor Report** is available within the **Reports** module of CorpCash and provides administrators with a consolidated view of transactions associated with vendors. The report enables administrators to monitor vendor-related financial activity, review cash-out requests and wallet credits, identify associated employees, verify transaction amounts, and track transaction dates and processing status.

The **Vendor Report** can be accessed by navigating to **Reports → Vendor Report**. When selected, the Vendor Report tab is highlighted to indicate that the report is currently active.

<figure><img src="../../../.gitbook/assets/image (96).png" alt=""><figcaption></figcaption></figure>

#### Vendor Report Fields

<table><thead><tr><th width="135.47857666015625">Field</th><th>Description</th></tr></thead><tbody><tr><td><strong>Transaction ID</strong></td><td>Unique identifier assigned to the vendor-related transaction. It can be used to track and reference a specific transaction.</td></tr><tr><td><strong>Vendor</strong></td><td>Identifies the vendor associated with the transaction.</td></tr><tr><td><strong>Type</strong></td><td>Specifies the type of vendor transaction, such as <strong>Cashout Request</strong> or <strong>Wallet Credit</strong>.</td></tr><tr><td><strong>Amount</strong></td><td>Specifies the monetary amount associated with the transaction.</td></tr><tr><td><strong>Employee</strong></td><td>Identifies the employee associated with the transaction, where applicable. If the transaction is not directly associated with an employee, the system displays <strong>“—”</strong>.</td></tr><tr><td><strong>Created At</strong></td><td>Indicates the date and time when the transaction record was created.</td></tr><tr><td><strong>Status</strong></td><td>Indicates the processing status of the transaction, such as <strong>Success</strong>.</td></tr></tbody></table>

### Transaction Types

The **Type** column identifies the nature of the vendor transaction.

<table><thead><tr><th width="163.25640869140625">Transaction Type</th><th>Description</th></tr></thead><tbody><tr><td><strong>Cashout Request</strong></td><td>Represents a request initiated for a vendor to cash out an available amount. These transactions may be associated with the vendor settlement process.</td></tr><tr><td><strong>Wallet Credit</strong></td><td>Represents an amount credited to the vendor wallet, generally associated with an employee-related vendor payment.</td></tr></tbody></table>

### Search Functionality

The Vendor Report provides a search functionality field with the placeholder **“Search by transaction ID or vendor...”**.

<figure><img src="../../../.gitbook/assets/image (97).png" alt=""><figcaption></figcaption></figure>

Administrators can use this field to locate vendor transactions by entering a supported **Transaction ID** or **Vendor** name.

This functionality allows administrators to quickly locate specific vendor activity without manually reviewing the complete report.

For example, an administrator can search using a transaction identifier such as:

**VWL-1787820238310-7045** or search for a specific vendor name.

### Vendor Filter

The **All Vendors** dropdown allows administrators to filter the report according to the vendor associated with the transaction.

<figure><img src="../../../.gitbook/assets/image (98).png" alt=""><figcaption></figcaption></figure>

When **All Vendors** is selected, transactions associated with all available vendors are displayed.

Administrators can select a specific vendor when they need to review only that vendor's transaction activity. This functionality is particularly useful for **vendor-level reconciliation, payment verification, and settlement monitoring**.

### Date Range Filter

The **Select date range** control enables administrators to restrict the displayed vendor transactions to a specific period.

<figure><img src="../../../.gitbook/assets/image (99).png" alt=""><figcaption></figcaption></figure>

The date-range filter can be used for:

* Daily transaction monitoring
* Periodic vendor reconciliation
* Settlement verification
* Historical transaction analysis
* Financial reporting
* Audit activities

The date range can be combined with the vendor filter and search functionality to narrow the report results.

### Export Functionality

The **Export** option allows administrators to extract Vendor Report data for external analysis, reconciliation, reporting, and record keeping.

<figure><img src="../../../.gitbook/assets/image (100).png" alt=""><figcaption></figcaption></figure>

Administrators can apply the required vendor, search, and date-range criteria before selecting **Export** when only a specific dataset is required.

Exported vendor and transaction information should be handled securely because it may contain financial and employee-related information.

### Pagination

The selected report displays records in a structured tabular format. In the displayed Treasury Ledger, the system shows **10 records per page**, with an indication of the total number of records available.

<figure><img src="../../../.gitbook/assets/image (67).png" alt=""><figcaption></figcaption></figure>

The interface provides pagination controls that allow administrators to navigate between available pages. Administrators can also use the **Go to** page control to navigate directly to a specific page.

<figure><img src="../../../.gitbook/assets/image (68).png" alt=""><figcaption></figcaption></figure>

The page-size control allows administrators to select the number of records displayed per page, where supported.

<figure><img src="../../../.gitbook/assets/image (69).png" alt=""><figcaption></figcaption></figure>
