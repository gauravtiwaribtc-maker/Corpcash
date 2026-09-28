# Admin Wallet Dashboard

The **Admin Wallet** is a centralized fund-management module within the CorpCash platform. It enables authorized organization administrators to manage the organization's available funds and distribute those funds to employee wallets according to the organization's configured benefit, reward, reimbursement, or allocation programs.

The Admin Wallet acts as the **central administrative balance** from which funds can be managed before they are allocated to individual employee wallets. In addition to fund management, the module provides a transaction history that allows administrators to monitor, search, filter, review, and export wallet-related transactions.

The module is designed to provide administrators with a clear view of the organization's wallet position and the transactions performed against it.

## Role of the Admin Wallet in the Overall Wallet Structure

The Admin Wallet can be understood as the organization's central funding point.

A simplified fund flow is:

**Organization Funds → Admin Wallet → Employee Wallet → Employee Usage/Transaction**

The Admin Wallet is positioned between the organization's available funds and employee-level wallet allocations.

#### Example

Suppose an organization has an available Admin Wallet balance of:

**₹4,82,500**

The administrator can use this balance to allocate funds to employees.

For example:

| Employee    | Employee ID | Wallet | Allocation |
| ----------- | ----------- | ------ | ---------- |
| Sarah Chen  | EMP-001     | Meal   | ₹2,500     |
| Arjun Mehta | EMP-002     | Travel | ₹5,000     |
| Priya Nair  | EMP-003     | Fuel   | ₹3,100     |

After successful transfers, the corresponding amount is allocated to the selected employee wallets according to the system's transaction rules.

This provides administrators with a centralized mechanism for managing employee-level allocations rather than managing every employee wallet independently.

## Accessing the Admin Wallet

The Admin Wallet is accessible from the **Wallets** section of the application's left navigation menu.

#### Navigation Path

**Login → Select Organization → Wallets → Admin Wallet**

{% stepper %}
{% step %}
### Navigation Path

Log in to the **CorpCash Admin Portal** using your authorized administrator credentials.

Ensure that you are using an account with the required permissions to access wallet-management functionality.
{% endstep %}

{% step %}
###
{% endstep %}

{% step %}
### Open Wallets

From the left-hand navigation panel, locate **Wallets**.

Click **Wallets** to expand the wallet-management menu if it is collapsed.

<figure><img src="../../../.gitbook/assets/image (185).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
### Select Admin Wallet

Under the expanded **Wallets** menu, select **Admin Wallet**.

The Admin Wallet option provides access to the organization's centralized wallet-management interface.

<figure><img src="../../../.gitbook/assets/image (186).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
### Access the Admin Wallet Dashboard

The **Admin Wallet** page opens.

From this page, you can review the available balance and perform administrative wallet operations such as:

* **Add Funds**
* **Transfer Funds**
* **Revoke Points**
* Review **Transaction History**
* Search transactions
* Apply wallet and period filters
* View transaction details
* Export transaction records

<figure><img src="../../../.gitbook/assets/image (188).png" alt=""><figcaption></figcaption></figure>
{% endstep %}
{% endstepper %}

## Available Balance

The **Available Balance** section provides administrators with a real-time view of the funds currently available in the **Admin Wallet** for distribution to employee wallets.

This section is one of the primary reference points on the Admin Wallet page because it allows the administrator to determine the amount of funds that can currently be used for employee wallet operations.

As shown in the displayed image balance is:

> **₹4,82,500**











<figure><img src="../../../.gitbook/assets/image (190).png" alt=""><figcaption></figcaption></figure>



<figure><img src="../../../.gitbook/assets/image (191).png" alt=""><figcaption></figcaption></figure>













































































The Admin Wallet page provides a consolidated view of the organization's available digital token balance and real-time transaction activity.

#### Admin Wallet Balance <a href="#nuk8dk54w98" id="nuk8dk54w98"></a>

The balance card displays the current available balance in the Admin Wallet. This represents the available digital token balance that can be used for applicable wallet operations.

Example shown in the screen:

Admin Wallet: 9,75,412

**Wallet Actions**

Three primary actions are available in the upper-right section of the Admin Wallet page:

**Add Funds**

The Add Funds button allows the administrator to add funds to the Admin Wallet.

To add funds:

1. Click Add Funds.
2. Enter the required transaction information.
3. Provide the amount to be added.
4. Review the entered information.
5. Confirm the transaction.

The exact fields and confirmation steps may vary based on the configured CorpCash workflow.

&#x20;

&#x20;



**Transfer Funds**

The Transfer Funds button allows an administrator to distribute digital tokens from the Admin Wallet to an applicable employee wallet.

To transfer funds:

1. Click Transfer Funds.
2. Select or specify the recipient employee/wallet.
3. Select the applicable Wallet Type, if required.
4. Enter the amount to be transferred.
5. Review the transaction details.
6. Confirm the transfer.

After a successful transfer, the transaction is recorded in the transaction table

**Revoke Points**

The Revoke Points button is used to revoke previously allocated points, subject to the organization's configured rules and permissions.

To revoke points:

1. Click Revoke Points.
2. Select the applicable employee or transaction.
3. Enter/select the points to be revoked.
4. Review the details.
5. Confirm the revocation.

The resulting transaction is recorded in the transaction history.

Important: Administrators should verify the employee, wallet type, amount, and transaction details before confirming a revocation.
