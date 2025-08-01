# ExtraNyaa Privacy Policy

**Effective Date**: August 1, 2025  
**Last Updated**: August 1, 2025

## Overview

ExtraNyaa is a Chrome extension that enhances your Nyaa.si browsing experience by displaying your MyAnimeList (MAL) anime status on torrent listings. This privacy policy explains how we collect, use, and protect your information.

## Information We Collect

### 1. MyAnimeList Account Data
- **What we collect**: Your anime list, watching status, episode progress, and anime ratings
- **How we collect it**: Through MyAnimeList's official API using OAuth2 authentication
- **Why we collect it**: To display your anime status on Nyaa.si torrent listings

### 2. Browsing Activity (Limited Scope)
- **What we collect**: Torrent titles and anime names from Nyaa.si pages you visit
- **How we collect it**: By reading page content when you browse Nyaa.si
- **Why we collect it**: To match torrents with anime in your MAL list and display status badges

### 3. Technical Data
- **What we collect**: Extension settings, debug logs (if enabled), and cached anime data
- **How we store it**: Locally in your browser using Chrome's storage API
- **Why we collect it**: To improve performance and provide offline functionality

## ⚠️ GOOGLE REVIEW CONSIDERATIONS

### High-Risk Areas for Chrome Web Store Review:

#### 1. **OAuth Token Storage** 🔴 **HIGH RISK**
- **Risk**: We store MyAnimeList OAuth access tokens locally
- **Mitigation**: Tokens are stored using Chrome's secure storage API, not transmitted to external servers
- **Google Concern**: Token storage could be flagged for security review

#### 2. **Cross-Site Data Access** 🔴 **HIGH RISK**
- **Risk**: Extension reads content from both Nyaa.si and MyAnimeList
- **Mitigation**: Access is limited to specific URLs and only reads public page content
- **Google Concern**: Cross-site data access may trigger additional scrutiny

#### 3. **API Data Collection** 🟡 **MEDIUM RISK**
- **Risk**: We fetch comprehensive anime lists from MyAnimeList API
- **Mitigation**: Data is used only for extension functionality, not shared with third parties
- **Google Concern**: Large-scale data collection may require additional justification

#### 4. **Real-Time Monitoring** 🟡 **MEDIUM RISK**
- **Risk**: Extension monitors page changes on MyAnimeList in real-time
- **Mitigation**: Monitoring is limited to anime status changes for badge updates
- **Google Concern**: Real-time monitoring could be seen as excessive data access

## How We Use Your Information

### Primary Uses
1. **Status Display**: Show your anime watching status on Nyaa.si torrent listings
2. **Performance**: Cache anime data locally for faster page loading
3. **User Experience**: Remember your preferences and settings

### We DO NOT:
- Sell your data to third parties
- Share your information with advertisers
- Track you across other websites
- Store data on external servers (everything is local)

## Data Storage and Security

### Local Storage Only
- **All data is stored locally** in your browser using Chrome's storage API
- **No external servers**: We don't operate any servers or databases
- **No cloud sync**: Data stays on your device only

### Security Measures
- OAuth2 secure authentication with MyAnimeList
- Encrypted local storage through Chrome's built-in security
- No password storage (OAuth tokens only)
- Regular cleanup of expired data

## Third-Party Services

### MyAnimeList Integration
- **Service**: MyAnimeList.net API
- **Purpose**: Authenticate user and fetch anime list data
- **Data Shared**: None (we only receive data from them)
- **Their Privacy Policy**: https://myanimelist.net/about/privacy_policy

### No Other Third Parties
- We do not integrate with any other external services
- No analytics, tracking, or advertising services
- No data sharing with other companies

## Your Rights and Controls

### Data Access
- View your stored data through the extension's debug panel
- Export your anime database as a JSON file
- Import previously exported data

### Data Deletion
- Uninstall the extension to remove all local data
- Clear browser data to remove cached information
- Revoke MAL authentication to invalidate stored tokens

### Settings Control
- Toggle features on/off through extension settings
- Control debug logging
- Manage episode count display preferences

## Data Retention

### Automatic Cleanup
- OAuth tokens expire according to MAL's policy

### Manual Cleanup
- Users can clear all data by uninstalling the extension
- Export/import functionality allows data portability
- Settings reset available through extension popup

## Changes to This Policy

We may update this privacy policy to reflect changes in our practices or for legal compliance. Users will be notified of significant changes through:
- Extension update notes
- GitHub repository announcements

## Contact Information

### Issues and Support
- **GitHub Issues**: https://github.com/Acen/ExtraNyaa/issues
- **Repository**: https://github.com/Acen/ExtraNyaa

### Privacy Concerns
For privacy-related questions or concerns, please open an issue on our GitHub repository with the "privacy" label.

## Compliance and Legal

### Chrome Web Store Policies
This extension complies with:
- Chrome Web Store Developer Program Policies
- Google's Privacy Policy Requirements
- Manifest V3 security standards

### Data Protection
- No GDPR concerns (no EU data processing/storage servers)
- No CCPA concerns (no personal data sale)
- Minimal data collection principles applied

## Technical Implementation Details

### For Transparency
- **Build Process**: Uses TypeScript and Bun for transpilation
- **No Obfuscation**: Code is minified, however not obfuscated and auditable
- **Minimal Permissions**: Only requests necessary Chrome permissions

---

## Summary for Users

**What ExtraNyaa does with your data:**
✅ Reads your MyAnimeList anime list to show status on Nyaa.si  
✅ Stores everything locally on your device for privacy  
✅ Uses secure OAuth2 authentication (no password storage)  
✅ Operates entirely offline after initial sync  

**What ExtraNyaa does NOT do:**
❌ Send your data to external servers  
❌ Track you across other websites  
❌ Sell or share your information  
❌ Collect unnecessary personal information  

---

*This privacy policy is designed to be transparent about our data practices and highlight areas that may require additional review by Chrome Web Store policies.*
