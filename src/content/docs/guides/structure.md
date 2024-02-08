---
title: Structure of PohjoisMail
description: Explore the unique structure of PohjoisMail for efficient email management.
---

PohjoisMail is meticulously structured to offer a seamless email experience, providing intuitive management of addresses, accounts, and domains. Below, we outline the key components of PohjoisMail's structure to help you navigate the platform effectively.

## Organizations

At the foundation of PohjoisMail's structure lies the organization. Serving as the central repository for all PohjoisMail services, each company or group of individuals should have its own organization. When creating an organization, choose a descriptive name and estimate the required number of accounts based on your entity's size. An organization is associated with a unique domain, which forms the basis of your email addresses.

## Addresses

Addresses in PohjoisMail act as gateways to direct emails to their intended destinations. While resembling email addresses, they are distinct objects within the PohjoisMail structure. An address doesn't function independently but plays a vital role in email forwarding and routing.

## Accounts

Accounts represent individual users within your organization. Each account is linked to a single address and operates similarly to a standard email account, complete with folders for organizing emails. Users can access their accounts via the PohjoisMail webmail interface or through email clients using IMAP, SMTP, and/or POP3 protocols.

| Event          | Action                                                |
| -------------- | ----------------------------------------------------- |
| Incoming Email | Received by the address and forwarded to the account. |
| Outgoing Email | Sent from the account using the associated address.   |

## Groups

Groups, traditionally known as mailing lists, are collections of email addresses bound to a specific address. Incoming emails to this address are automatically forwarded to all members of the group, which can include both internal and external email addresses.

| Event          | Action                                 |
| -------------- | -------------------------------------- |
| Incoming Email | Forwarded to all members of the group. |
| Outgoing Email | ❌                                     |

## Mailing Lists

Mailing lists facilitate bulk email communication with customers or subscribers. Bound to a designated address, mailing lists enable you to disseminate newsletters, updates, or other announcements to a large audience. Refer to the [mailing list guide](/docs/guides/mailing-lists) for comprehensive instructions on utilizing this feature effectively.

| Event          | Action                    |
| -------------- | ------------------------- |
| Incoming Email | ❌                        |
| Outgoing Email | Sent to every subscriber. |

## Senders

Senders offer a programmable means of dispatching emails via the PohjoisMail API. Bound to a specific address, senders empower developers to automate email transmission to any recipient. Proficiency in programming is necessary to leverage senders effectively.

| Event          | Action                           |
| -------------- | -------------------------------- |
| Incoming Email | ❌                               |
| Outgoing Email | Sent to the specified recipient. |

Explore the structured components of PohjoisMail to streamline your email management and communication processes.
