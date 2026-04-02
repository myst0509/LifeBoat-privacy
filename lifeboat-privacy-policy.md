# LifeBoat Privacy Policy

**Last Updated:** March 31, 2026

## Overview

LifeBoat ("we", "our", or "us") is a Chrome extension for digital estate planning and account management. We are committed to protecting your privacy and being transparent about how we handle your data.

## Data We Collect

### Data Stored Locally (On Your Device)
- **Account information**: Websites you've logged into, usernames, and account categories
- **Vault data**: Passwords, 2FA codes, and notes stored in your encrypted vault
- **Trusted contacts**: Names and email addresses of people you designate as heirs
- **Preferences**: Your settings and customization choices

This data is stored locally in your browser using Chrome's storage API and is protected by your master password using AES-256-GCM encryption.

### Data Synced to Our Servers (Pro Users Only)
- **Encrypted vault backups**: Your vault data, encrypted with your master password before leaving your device
- **Account email**: For authentication purposes
- **Subscription status**: To manage your Pro subscription

**Important**: We use zero-knowledge encryption. Your master password never leaves your device, and we cannot decrypt your vault data.

### Data We Do NOT Collect
- Browsing history
- Cookies or tracking data
- Actual passwords (we only store encrypted blobs)
- Financial information (Stripe handles payments directly)
- Personal identification documents

## How We Use Your Data

- **Authentication**: To verify your identity when you log in
- **Cloud sync**: To backup and restore your encrypted vault across devices (Pro only)
- **Notifications**: To send check-in reminders and emergency alerts to your trusted contacts
- **Product improvement**: Anonymized, aggregated usage statistics

## Data Security

- **Encryption**: All sensitive data is encrypted using AES-256-GCM with PBKDF2 key derivation (310,000 iterations)
- **Zero-knowledge architecture**: Your master password never leaves your device
- **HTTPS**: All server communications use TLS encryption
- **No plain-text storage**: We never store unencrypted sensitive data

## Third-Party Services

We use the following third-party services:
- **Stripe**: For payment processing (Pro subscriptions)
- **SendGrid**: For sending email notifications
- **Plaid** (optional): For bank account linking to detect subscriptions

These services have their own privacy policies and handle data according to their terms.

## Data Retention

- **Local data**: Stored until you delete it or uninstall the extension
- **Server data**: Retained while your account is active; deleted within 30 days of account deletion
- **Backups**: Encrypted backups are retained for 90 days after deletion for recovery purposes

## Your Rights

You have the right to:
- **Access**: View all data we store about you
- **Export**: Download your data at any time
- **Delete**: Remove your account and all associated data
- **Opt-out**: Use LifeBoat without creating an account (local-only mode)

## Children's Privacy

LifeBoat is not intended for use by children under 13. We do not knowingly collect data from children.

## Changes to This Policy

We may update this privacy policy from time to time. We will notify you of significant changes via email or in-app notification.

## Contact Us

If you have questions about this privacy policy or your data, contact us at:

**Email**: privacy@lifeboat.app

---

## Summary

| What | Stored Where | Encrypted | We Can Read It? |
|------|--------------|-----------|-----------------|
| Your accounts | Your device | ✅ Yes | ❌ No |
| Your vault | Your device + our servers (Pro) | ✅ Yes | ❌ No |
| Your email | Our servers | ❌ No | ✅ Yes |
| Your password | Nowhere | N/A | ❌ Never stored |
| Payment info | Stripe (not us) | ✅ Yes | ❌ No |

**Bottom line**: Your sensitive data is encrypted before it ever leaves your device. We literally cannot read your passwords or vault contents.
