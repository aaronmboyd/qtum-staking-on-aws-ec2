# Staking QTUM with Amazon EC2

### Prerequisites
* An AWS account. If you aren't already a customer, every new account (with a valid credit card that hasn't been used for a previous account) is valid for 12 months of the [AWS Free Tier](https://aws.amazon.com/free/), which includes 750 hours a month of EC2 resources, which can keep your node staking 24/7.

* Familiarity with Linux and terminal usage. This guide will be using an Ubuntu instance as the remote EC2 instance, and any Debian-based Linux operating system as a host to connect to the EC2 server.

* Understand how the `root` and `ubuntu` users [are managed in Ubuntu EC2 instances](https://alestic.com/2009/04/ubuntu-ec2-sudo-ssh-rsync/)

#### A brief note on security

This guide isn't to discuss the relative benefits of any security software, password store, or patterns. The weakest link is always us. Do some reading and evaluate the tools that work for you. The best security pattern is one you understand and actually use, consistently.

Cloud password managers like [LastPass](https://www.lastpass.com/) are not perfect, but provide a good balance of usability and security. Client-side decryption, browser plug-in, and bundled 2FA private key storage works well.

From here on I'll assume you know how to secure passwords. This means [not storing private keys in plain text in Evernote](https://ethereumworldnews.com/notable-cryptocurrency-influencer-looses-over-1-million-to-hacker/).

### Instructions

1. Create an AWS Free Tier account.
2. Recommended - add a multi-factor authentication method to login to AWS. Find the _My Security Credentials_ section in your account:

![My Security Credentials](images/aws-my-security-essentials.png)

* Add the MFA of your choice:

![Add MFA](images/add-virtual-mfa-to-aws-account.png)

3.




### Other reference links

* Sign up for free encrypted email at [ProtonMail](https://protonmail.com/) if you need a new identity for your AWS Free Tier.
