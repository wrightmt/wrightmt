# FakeOMattic Privacy Policy

**Last Updated**: November 4, 2024

## Overview

FakeOMattic is committed to protecting your privacy. This extension does not collect, store, transmit, or share any personal information.

## Data Collection

**FakeOMattic collects ZERO data.**

We do not:
- Collect personal information
- Track your browsing activity
- Monitor which websites you visit
- Store form data you fill
- Transmit any data to external servers
- Use analytics or tracking tools
- Share information with third parties

## Data Generation

All test data is generated **locally in your browser** using JavaScript. The fake names, emails, phone numbers, and other data are created on-demand and are never saved or transmitted anywhere.

## Data Storage

The only information stored by FakeOMattic is your **settings preferences** (such as custom phone number format), which is stored locally using Chrome's `chrome.storage.sync` API. This data:
- Stays on your device (and syncs across your Chrome browsers if you're signed in)
- Is never sent to our servers (we don't have any servers!)
- Can be cleared by removing the extension

## Permissions Explained

FakeOMattic requests the following permissions for legitimate functionality:

### activeTab
**Purpose**: Access the current tab to fill form fields when you click "Fill All Inputs"
**Usage**: Only accesses pages when you explicitly trigger the extension
**Data Access**: Reads and writes to form fields only (does not access page content, cookies, or sensitive data)

### storage
**Purpose**: Save your custom settings (like phone number format preferences)
**Usage**: Stores settings locally in your browser
**Data Stored**: Only your configuration preferences

### contextMenus
**Purpose**: Add a "Fill All Inputs with Test Data" option to the right-click menu
**Usage**: Provides convenient access to filling functionality
**Data Access**: None - just adds a menu item

### scripting
**Purpose**: Inject content scripts into web pages to populate form fields
**Usage**: Dynamically loads scripts when you trigger the fill action
**Data Access**: Only interacts with form input elements

## Third-Party Services

FakeOMattic does **not** use any third-party services, including:
- Analytics (Google Analytics, etc.)
- Error tracking
- Advertising networks
- External APIs
- Remote servers

## Works Completely Offline

FakeOMattic functions entirely offline. After installation, you can disconnect from the internet and it will work exactly the same.

## Children's Privacy

FakeOMattic does not knowingly collect information from anyone, including children under 13. The extension is designed for web developers, QA testers, and anyone who needs to test forms.

## Changes to This Policy

If we update this privacy policy, we will:
- Update the "Last Updated" date above
- Post the new policy at the same location
- Notify users through extension updates if changes are significant

## Your Rights

Since we don't collect any data, there's nothing for us to:
- Access
- Modify
- Delete
- Export

However, you can always:
- Remove the extension to delete all stored settings
- Modify settings in the extension's Options page
- View the source code (it's open for inspection)

## Open Source

FakeOMattic's code is available for inspection. You can verify that we don't collect data by reviewing the source code.

## Contact

If you have questions or concerns about privacy:
- **Creator**: Matt Wright
- **Extension Page**: [Chrome Web Store link will go here after publishing]
- **Issues**: Check browser console for technical issues

## Compliance

This extension complies with:
- Chrome Web Store Developer Program Policies
- General Data Protection Regulation (GDPR) - by collecting no data
- California Consumer Privacy Act (CCPA) - by collecting no data

## Summary

**In plain English**: FakeOMattic doesn't spy on you, doesn't collect your data, doesn't send anything anywhere, and works completely offline. It just fills forms with fake data when you ask it to. That's it!

---

**Version**: 1.0.0
**Author**: Matt Wright
**Built with**: Claude AI
