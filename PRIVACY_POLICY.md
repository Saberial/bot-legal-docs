# Privacy Policy

**Effective Date:** July 23, 2025  
**Last Updated:** July 23, 2025

## 1. Introduction

This Privacy Policy describes how the Warhammer Monitor software ("the Software," "we," "us," or "our") handles information when you use our open-source monitoring application.

**Important:** This Software runs entirely on your own systems. We do not operate any central servers or collect data from your installation.

## 2. Information We Do NOT Collect

As an open-source application that runs locally on your device, we do **NOT** collect, store, or transmit:

- Personal identification information
- Discord bot tokens or credentials
- Discord channel IDs or server information
- Monitoring data or history
- Usage statistics or analytics
- Error reports or crash data
- IP addresses or device information

## 3. Data Stored Locally on Your Device

The Software stores the following data locally on your device:

### 3.1 Configuration Data
- **File:** `config.json`
- **Contains:** Discord bot token, channel IDs, monitoring settings
- **Purpose:** Configure the Software's operation
- **Retention:** Until you delete or modify the file

### 3.2 Monitoring History
- **Files:** `data/app-history.json`, `data/news-history.json`, `data/downloads-history.json`
- **Contains:** Historical data about monitored content to prevent duplicate notifications
- **Purpose:** Track what content has already been reported
- **Retention:** Configurable, automatically managed by the Software

### 3.3 Log Files
- **Files:** `logs/*.log`
- **Contains:** Application activity logs, error messages, operational status
- **Purpose:** Debugging and monitoring Software performance
- **Retention:** Automatically rotated when they exceed size limits

### 3.4 Backup Data
- **Files:** `data-backup/*`
- **Contains:** Backup copies of monitoring history
- **Purpose:** Data recovery and migration
- **Retention:** Manual management by user

## 4. Third-Party Services

The Software interacts with third-party services to function:

### 4.1 Discord API
- **Data Sent:** Messages and embeds to your configured Discord channels
- **Purpose:** Send notifications about detected content
- **Discord's Privacy Policy:** https://discord.com/privacy
- **Your Responsibility:** Configure Discord bot permissions appropriately

### 4.2 Apple App Store API
- **Data Accessed:** Public app information (version, description, ratings)
- **Purpose:** Monitor for app updates
- **Apple's Privacy Policy:** https://www.apple.com/privacy/
- **Data Flow:** Public API data → Local storage → Discord notifications

### 4.3 Warhammer Community Website
- **Data Accessed:** Public articles and download listings
- **Purpose:** Monitor for new community content
- **Games Workshop Privacy Policy:** https://www.games-workshop.com/en-GB/Privacy-Policy
- **Data Flow:** Public website data → Local storage → Discord notifications

## 5. Data Security

### 5.1 Your Responsibilities
- **Secure Configuration:** Protect your `config.json` file containing Discord tokens
- **File Permissions:** Ensure appropriate file permissions on your system
- **Access Control:** Limit who can access your installation directory
- **Backup Security:** Secure any backups you create

### 5.2 Software Design
- **Local Operation:** All processing occurs on your local system
- **No Central Database:** No data is sent to external databases
- **Open Source:** Code is publicly auditable for security review

## 6. Data Sharing

We do **NOT** share any data because:
- We do not have access to your data
- All data remains on your local system
- The Software operates independently

However, **you** control what data is shared when:
- Posting Discord notifications (content summaries are sent to your Discord channels)
- Sharing log files for support (review logs before sharing)
- Contributing to the project (ensure no sensitive data in submissions)

## 7. Data Retention and Deletion

### 7.1 Automated Retention
- **Log Files:** Automatically rotated when exceeding configured size limits
- **History Files:** Limited to prevent excessive growth (configurable)

### 7.2 Manual Deletion
You can delete data at any time by:
- Removing configuration files
- Deleting the entire installation directory
- Using provided cleanup scripts
- Configuring shorter retention periods

## 8. Children's Privacy

This Software is not directed to children under 13. If you are under 13, do not use this Software. If you are between 13 and 18, ensure you have parental permission before using Discord or configuring bots.

## 9. International Data Transfers

Since all data remains on your local system, there are no international data transfers by the Software itself. However:
- Discord may process your bot's messages according to their privacy policy
- Third-party APIs may be accessed from your location

## 10. Changes to Privacy Policy

We may update this Privacy Policy by:
- Posting changes to the GitHub repository
- Updating the "Last Updated" date
- Providing notice in release notes for significant changes

Your continued use after changes indicates acceptance of the updated policy.

## 11. Your Rights

Since we don't collect your data, traditional data protection rights don't apply to us. However, you have complete control over:
- **Access:** You can view all data stored locally
- **Portability:** Copy your data files to other systems
- **Deletion:** Remove any or all data at any time
- **Modification:** Edit configuration and data files directly

## 12. Compliance with Laws

### 12.1 GDPR (European Users)
- **Data Controller:** You are the data controller for your installation
- **Data Processor:** The Software processes data on your behalf
- **Legal Basis:** Legitimate interest in monitoring content

### 12.2 CCPA (California Users)
- **Personal Information:** We do not collect personal information as defined by CCPA
- **Data Sales:** We do not sell personal information

## 13. Security Incidents

If you discover a security vulnerability:
1. **DO NOT** post it publicly in GitHub Issues
2. Contact the maintainers privately
3. Allow reasonable time for fixes before disclosure
4. Follow responsible disclosure practices

## 14. Contact Information

For privacy-related questions:
- **GitHub Issues:** For general questions (review for sensitive information first)
- **Project Repository:** [Repository URL]
- **Security Issues:** [Maintainer contact information]

## 15. Third-Party Links

This Privacy Policy only applies to the Software itself. When using Discord, Apple services, or Warhammer Community websites, their respective privacy policies apply.

## 16. Open Source Nature

This is an open-source project. You can:
- **Audit the Code:** Review how data is handled
- **Propose Changes:** Suggest privacy improvements
- **Fork the Project:** Create your own version with different privacy practices

---

**Summary:** We don't collect your data because we can't - everything runs on your system. You have complete control over your data and privacy. 