# Settings

### Wallet Configuration

<figure><img src="../../.gitbook/assets/image (103).png" alt=""><figcaption></figcaption></figure>

The **Wallet Config** page in CorpCash enables authorized administrators to manage the availability of employee wallet types for the organization. Administrators can enable or disable individual wallet types based on organizational requirements.

The page is accessible through **Settings → Wallet Config**. When the Wallet Config page is selected, the system displays the available employee wallet types along with their current status, last update timestamp, and the action available for changing the wallet status.

#### Wallet Configuration Interface

The Wallet Config page displays the heading **“Wallet Config”** and the description **“Enable or disable employee wallet types for your organisation.”**

Each wallet type is represented as an individual configuration card. The card provides the wallet name, current status, last updated date and time, and an action button to change its availability.

The following wallet types are displayed in the provided interface:

| Wallet Type     | Current Status | Last Updated              | Available Action |
| --------------- | -------------- | ------------------------- | ---------------- |
| **Fuel**        | Inactive       | 02 Sept 2026, 12:58:08 pm | Enable Wallet    |
| **Meal Wallet** | Active         | 16 Jul 2026, 01:38:21 pm  | Disable Wallet   |
| **Reward**      | Active         | 19 Jun 2026, 10:24:58 am  | Disable Wallet   |
| **Travel**      | Active         | 16 Jul 2026, 01:38:20 pm  | Disable Wallet   |

#### Wallet Status

The **Status** indicator shows whether a particular employee wallet type is currently available within the organization.

**Active:**\
An Active status indicates that the wallet type is currently enabled. The interface provides a **Disable Wallet** option for an active wallet.

**Inactive:**\
An Inactive status indicates that the wallet type is currently disabled. The interface provides an **Enable Wallet** option, allowing the administrator to activate the wallet.

#### Enable Wallet

When a wallet is currently **Inactive**, the administrator can select **Enable Wallet** to activate the corresponding wallet type.

<figure><img src="../../.gitbook/assets/image (104).png" alt=""><figcaption></figcaption></figure>

For example, the **Fuel** wallet is shown as **Inactive** in the provided interface. The **Enable Wallet** button is therefore displayed for this wallet.

After the administrator enables the wallet, the system updates its status to **Active** and records the corresponding update timestamp.

#### Disable Wallet

When a wallet is currently **Active**, the administrator can select **Disable Wallet** to deactivate the corresponding wallet type.

<figure><img src="../../.gitbook/assets/image (105).png" alt=""><figcaption></figcaption></figure>

For example, the **Meal Wallet**, **Reward**, and **Travel** wallets are currently Active and therefore display the **Disable Wallet** action.

Once disabled, the wallet status is expected to change to **Inactive**, and the system updates the corresponding configuration timestamp.

#### Last Updated Information

Each wallet configuration card displays an **Updated** timestamp. This timestamp indicates when the wallet configuration was most recently modified.

<figure><img src="../../.gitbook/assets/image (106).png" alt=""><figcaption></figcaption></figure>

For example:

* Fuel — Updated **02 Sept 2026, 12:58:08 pm**
* Meal Wallet — Updated **16 Jul 2026, 01:38:21 pm**
* Reward — Updated **19 Jun 2026, 10:24:58 am**
* Travel — Updated **16 Jul 2026, 01:38:20 pm**

This information provides administrators with visibility into when the wallet configuration was last changed and can assist with configuration tracking and operational auditing.

