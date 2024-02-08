---
title: Addresses and Accounts
description: Learn about addresses and accounts in PohjoisMail to efficiently manage your organization's email communication.
---

## What is an Address?
In PohjoisMail, an address serves as a gateway to direct emails to their intended destinations. While resembling email addresses, they are distinct objects within the PohjoisMail structure. Addresses do not function independently but play a vital role in email forwarding and routing. For more details on addresses and other components of PohjoisMail's structure, refer to the [structure guide](/guides/structure).

## What is an Account?
An account represents individual users within your organization. Each account is linked to a single address and operates similarly to a standard email account, complete with folders for organizing emails. Users can access their accounts via the PohjoisMail webmail interface or through email clients using IMAP, SMTP, and/or POP3 protocols.

## How do Addresses and Accounts Work Together?
When an email is sent to an address, it is received by the address and forwarded to the service using that address. Email accounts are just another PohjoisMail service, so the email is then forwarded to the account. The account then processes everything further using industry-standard email server protocols. Therefore, everything you already know about email accounts applies here.

## Do I Need to Create an Address for Every Account?
No, you don't. Creating an address can be done simultaneously with creating an account and does not require a separate process. When creating an account, you will be prompted to create an address for it if one does not already exist.

## How do I Create an Account?
Creating an account is straightforward. Navigate to the Addresses section of your organization and click the "New Address" button. You will then be prompted to name your account. An account name should ideally be the name of the person who will be using it.

Next, you will be prompted to create an address for the account. If you already have an existing address, you can select "Use an already existing address" and choose the desired address.

If you do not have an address, you can select "Create a new address" and name the address accordingly. It's recommended to standardize address names within your organization, such as "firstname.lastname@yourorg.com" or "firstname@yourorg.com", to avoid confusion and facilitate efficient email management.

## Conclusion
Congratulations! You now understand how to create an account and an address for that account within PohjoisMail. You also grasp how addresses and accounts collaborate and how to manage them effectively. Should you have any questions, feel free to reach out to us via chat. We're here to assist you. In the next guide, we'll delve into groups and how they can enhance your organization's email management.
