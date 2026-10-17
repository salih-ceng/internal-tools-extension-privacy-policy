Privacy Policy

Last updated: October 17, 2026

Internal Tools Extension is designed for internal or enterprise browser-policy deployments. This Privacy Policy explains how the extension handles information.

Information We Do Not Collect

The extension does not collect, store, or transmit:

Website content, uploaded files, form entries, messages, or page text

Browsing history or browsing activity

Precise location information, such as GPS coordinates

Financial or payment information

Health information

Analytics, advertising, or profiling data

The extension may locally inspect the presence of upload-related browser controls and the current website host only as needed to apply its policy controls. This information is not retained or transmitted to the developer.

License Validation Information

To enable licensed functionality, the extension may handle the following information:

A license key entered by the user

A randomly generated installation identifier

License status and expiration information

License policy and allowlist configuration returned by the validation service

The license key and installation identifier are transmitted securely over HTTPS to https://license-server-mziq.onrender.com solely to validate the license, retrieve authorized configuration, and enforce device-assignment rules where applicable.

This information is not used for advertising, analytics, cross-site tracking, profiling, or any purpose unrelated to license validation and the extension's internal policy controls.

Technical Connection Information

When a license-validation request reaches the service, the service and its hosting provider receive the connection IP address and request timing as technical network metadata. This information is used only as needed for request delivery, security, rate limiting and troubleshooting. The extension does not request GPS coordinates or use this information for location profiling.

License-validation records may include successful validation times and device-assignment information to support internal license administration. These records do not include the websites visited or actions taken within those websites.

Local Storage

The extension stores license-related information locally in Chrome using Chrome's storage API. This may include the license key, installation identifier, license status, expiry information, and policy configuration.

Local license-related information remains in the browser until it is changed, removed, or the extension is uninstalled.

License Timing and Connection Interruptions

License validity is determined by the validation service using its own time. Changing the PC's clock does not independently invalidate a verified license. During a connection interruption, the extension continues using its most recently verified license and configuration, even if the saved expiry date has passed. Expiry or revocation takes effect following the next successful validation. A new license key requires service approval.

Clock changes are checked locally only to request fresh validation. The PC's clock readings and detailed clock-change samples are not included in license-validation requests.

Data Sharing

License-validation information is transmitted only to the developer's license-validation service, hosted through Render, for the limited purpose of providing license validation and related configuration.

We do not sell user data. We do not share user data for advertising, marketing, analytics, profiling, credit assessment, or any unrelated purpose.

Data Retention

The license-validation service retains license-validation records only for as long as reasonably necessary to validate licenses, maintain license status, and enforce device-assignment rules.

Website content, uploaded files, browsing history, and browsing activity are not retained by the extension or transmitted to the developer.

Security

License-validation information is transmitted using HTTPS. The extension does not intentionally expose license-related information to other websites or users.

Single Purpose

The extension has a single purpose: helping organizations enforce internal browser usage and security policies in controlled environments.

Changes to This Policy

This Privacy Policy may be updated when the extension's data practices change. Any updated version will be published at this page.

Contact

For questions about this Privacy Policy, contact the developer through the associated GitHub repository.
