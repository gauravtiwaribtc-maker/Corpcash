---
hidden: true
---

# Settlement

### Settlement Module

The **Settlement** module provides administrators with a centralized interface to manage **vendor cash-out requests and settlement activities**. The module enables administrators to review pending cash-out requests, approve or reject requests, monitor processed settlements, and export processed settlement records for reconciliation and reporting purposes.

<figure><img src="../../.gitbook/assets/image (51).png" alt=""><figcaption></figcaption></figure>

The Settlement page is divided into two primary sections:&#x20;

1. **Pending Requests** and&#x20;
2. **Processed Requests**.&#x20;

It also provides summary information through the **Approved Amount** and **Pending Amount** indicators.

<figure><img src="../../.gitbook/assets/image (53).png" alt=""><figcaption></figcaption></figure>

#### Settlement Summary

At the top of the Settlement page, the system displays two summary cards that provide an overview of the current settlement position.

| Summary             | Description                                                                                              |   Value |
| ------------------- | -------------------------------------------------------------------------------------------------------- | ------: |
| **Approved Amount** | Represents the total amount associated with approved vendor cash-out requests.                           | **260** |
| **Pending Amount**  | Represents the amount currently associated with pending cash-out requests awaiting administrator action. |   **0** |

These summary values provide administrators with a quick overview of approved and outstanding settlement amounts without requiring them to review individual records.

### Pending Requests

The **Pending Requests** section displays vendor cash-out requests that are awaiting administrator review and action.

<figure><img src="../../.gitbook/assets/image (55).png" alt=""><figcaption></figcaption></figure>

The section is described as:

> **“Pending cashout requests only. Search by vendor and approve or reject.”**

This section is used as the primary workspace for processing outstanding vendor cash-out requests.

#### Pending Request Table

The pending request records are presented in a structured table with the following columns:

<table><thead><tr><th width="151">Field</th><th>Description</th></tr></thead><tbody><tr><td><strong>Vendor</strong></td><td>Identifies the vendor that submitted the cash-out request.</td></tr><tr><td><strong>Amount</strong></td><td>Specifies the amount requested by the vendor for cash-out.</td></tr><tr><td><strong>Created At</strong></td><td>Indicates the date and time when the cash-out request was created.</td></tr><tr><td><strong>Action</strong></td><td>Provides the available administrative actions for processing the request, such as approval or rejection.</td></tr></tbody></table>

#### Search Pending Requests

The Pending Requests section provides a **Search vendor** field that allows administrators to locate cash-out requests associated with a specific vendor.

<figure><img src="../../.gitbook/assets/image (56).png" alt=""><figcaption></figcaption></figure>

This functionality is particularly useful when multiple vendors have outstanding requests and the administrator needs to locate a specific vendor's request without manually reviewing the entire list.

An additional filter control is also available to apply supported filtering criteria to the pending requests.

#### Approving or Rejecting a Request

Administrators can review a pending cash-out request and use the available action controls to either **approve** or **reject** the request.

When a request is approved, the request moves from the Pending Requests section to the Processed Requests section and is recorded with an **Approved** status.

When a request is rejected, it is similarly moved to the Processed Requests section with a **Rejected** status.

The exact downstream financial processing associated with approval or rejection depends on the settlement rules and business configuration implemented in CorpCash.

## Processed Requests

The **Processed Requests** section provides a historical view of vendor cash-out requests that have already been processed.

<figure><img src="../../.gitbook/assets/image (57).png" alt=""><figcaption></figcaption></figure>

The section is described as:

**“Approved and rejected cashouts. Filter or search the list, then export to CSV when you need a file.”**

This section allows administrators to review previously processed settlement requests and use the information for reconciliation, reporting, auditing, and record keeping.

#### Processed Request Table

The Processed Requests table contains the following fields:

<table><thead><tr><th width="145">Field</th><th>Description</th></tr></thead><tbody><tr><td><strong>Request ID</strong></td><td>Unique identifier assigned to the vendor cash-out request. It can be used for tracking and reconciliation.</td></tr><tr><td><strong>Vendor</strong></td><td>Identifies the vendor associated with the cash-out request.</td></tr><tr><td><strong>Amount</strong></td><td>Specifies the amount requested for cash-out.</td></tr><tr><td><strong>Created At</strong></td><td>Indicates the date and time when the cash-out request was created.</td></tr><tr><td><strong>Status</strong></td><td>Indicates the outcome of the cash-out request, such as Approved or Rejected.</td></tr></tbody></table>

#### Example Records

| Request ID           | Vendor | Amount | Created At               | Status   |
| -------------------- | ------ | -----: | ------------------------ | -------- |
| COR17818453309955376 | Vendor |     25 | 19 Jun 2026, 10:32:10 am | Approved |
| COR17794425234697249 | Vendor |    125 | 22 May 2026, 03:05:23 pm | Approved |
| COR17788513578747529 | Vendor |     55 | 15 May 2026, 06:52:37 pm | Approved |

> The **Request ID** serves as an important reference for identifying an individual cash-out request and can be used when investigating or reconciling settlement records.

### Search and Filter Processed Requests

Administrators can use the **Search vendor** field in the Processed Requests section to locate settlement records associated with a particular vendor.

<figure><img src="../../.gitbook/assets/image (58).png" alt=""><figcaption></figcaption></figure>

The **Status** dropdown is available with **All** selected by default. Administrators can use this control to filter processed requests according to their settlement status.

The search and status filtering capabilities allow administrators to narrow the displayed records and focus on the required settlement data.

For example, an administrator can search for a specific vendor and then apply a status filter to review only the relevant processed requests.

### Export CSV

The **Export CSV** option is available in the Processed Requests section.

<figure><img src="../../.gitbook/assets/image (60).png" alt=""><figcaption></figcaption></figure>

Administrators can use this functionality to export processed settlement records into a CSV file for external use. Exported data can support:

* Financial reconciliation
* Vendor settlement verification
* Management reporting
* Audit activities
* Historical record keeping
* Offline data analysis

Administrators should apply the required search and status filters before exporting if only a specific subset of settlement records is required.

Because settlement information may contain financial and vendor-related data, exported files should be stored and shared securely.

### Settlement Workflow

The Settlement module supports the following general workflow:

**Vendor Cash-Out Request → Pending Request → Administrator Review → Approve/Reject → Processed Request → Reconciliation/Reporting**

A vendor initiates a cash-out request, after which the request becomes available under **Pending Requests**. An authorized administrator reviews the request and either approves or rejects it. Once processed, the request is recorded under **Processed Requests** with its corresponding status.

### Settlement Status

The Settlement module distinguishes between requests that require action and requests that have already been processed.

<figure><img src="../../.gitbook/assets/image (61).png" alt=""><figcaption></figcaption></figure>

**Pending:**\
The cash-out request is awaiting administrator review and approval or rejection.

**Approved:**\
The administrator has approved the cash-out request. The request is recorded as a processed settlement.

**Rejected:**\
The administrator has rejected the cash-out request. The request is retained in the processed history with its rejection status.
