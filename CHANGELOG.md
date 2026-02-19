# Changelog

All notable changes to ExtraNyaa will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [v1.5.1] - 2026-02-19

### Bug Fixes
Episode Count Tracking: Fixed an issue where updating your watched episode count on MyAnimeList would not be detected by the extension
Improved Change Detection: Episode increment buttons on MAL pages are now reliably detected regardless of which section of the page they appear in

---


## [v1.4.0] - 2025-12-01

### What's New
Nyaa Listing Filters: Filter torrent listings on Nyaa.si by your MAL anime status (Watching, Completed, Plan to Watch, On Hold, Dropped, Not in List)
Community Score Badges: Scoring badges now appear on torrent pages showing the community score, your personal score, or both

### Improvements
Better Title Matching: Improved handling of Unicode symbols in anime titles (e.g. SPY×FAMILY), trailing numbers (e.g. "Tondemo Skill 2"), and ordinal season formats (e.g. "2nd Season" vs "Season 2")
Smarter Season Detection: More accurate distinction between season and part indicators when matching torrents to MAL entries

---


## [1.3.0] - 2025-08-07

### What's New
- **Automatic Sync**: Sync happens automatically when user is logged in, rather than needing to browse to either MAL or Nyaa.si
- **Intelligent Sync**: Sync completion notifications intelligently hide after being viewed in the popup
- **Real-Time Database Timestamps**: Anime records accurately track when they were last updated via MAL page viewing

### Improvements
- **Smarter Database Updates**: The extension now only updates database timestamps when actual changes are made to anime records

### User Interface
- **Cleaner Popup Experience**: Sync completion status automatically hides after being acknowledged by opening the popup
- **Reduced Notification Noise**: Toast messages for sync completion follow the same intelligent display logic

---

## [1.2.0] - 2025-08-05

### What's New
- **On-Page Status Indicators**: Replaced extension badge with clean status indicators directly on MyAnimeList anime pages
- **Chrome Web Store Compliance**: Reduced permissions to minimal set required for core functionality
- **Enhanced Privacy**: Removed unnecessary permissions (`tabs`, `activeTab`, `scripting`) for better user privacy

### Improvements
- **Cleaner Interface**: Status information now appears as a subtle indicator in the anime information block on MAL pages
- **Better User Experience**: Shows checkmark (✓) and last updated date directly within anime listing.
- **Improved Performance**: Streamlined architecture without badge management overhead
- **Minimal Permissions**: Extension now only requests `storage` and `identity` permissions plus host permissions for specific domains

### Technical Changes
- **Removed Badge System**: Eliminated extension badge functionality in favor of direct page integration
- **Simplified Architecture**: Removed tab event listeners and badge update messaging
- **Host Permission Optimization**: Leverages existing host permissions instead of requiring broader tab access
- **Real-Time Updates**: Maintains real-time status updates through custom events and DOM manipulation

---

## [1.1.0] - 2025-08-04

### What's New
- **Enhanced Anime Database**: ExtraNyaa now includes a comprehensive community-sourced anime database for better torrent matching
- **Automatic Database Updates**: Extension automatically checks for and applies database updates to improve anime recognition
- **Improved Coverage**: Better anime matching through expanded title variants and comprehensive anime data

### Improvements
- **Better Anime Recognition**: Enhanced database provides more accurate matching for obscure or newly released anime
- **Expanded Title Support**: Improved recognition of anime with multiple title variants and alternative names
- **Enhanced Reliability**: More consistent anime detection and matching across different torrent formats

### Notes
- **No User Action Required**: All existing data and functionality preserved
- **Automatic Updates**: Database improvements will be delivered automatically when community database is enabled
- **Optional Enhancement**: Users can enable community database for improved anime recognition on Nyaa.si

---

## [1.0.0] - 2025-08-01

### What's New
- **MyAnimeList Integration**: Seamlessly connects with your MAL account to show anime status on Nyaa.si torrents
- **Real-Time Status Updates**: Changes to your anime status on MAL instantly reflect in the extension
- **Smart Anime Matching**: Intelligently matches torrents using multiple title variants (main, synonyms, English, Japanese, alternative titles)
- **Visual Status Indicators**: Badges show your anime status (Watching, Completed, Plan to Watch, etc.) directly on torrent listings
- **Comprehensive Season Support**: Automatically detects and matches different seasons and episode ranges
- **One-Click MAL Search**: Quickly search MyAnimeList for unknown anime directly from Nyaa.si

### Improvements
- **Lightning-Fast Performance**: Status badges appear instantly on torrent listings - no waiting or loading delays
- **Enhanced Popup Interface**: Modern, intuitive design with status overview and debug tools
- **Robust Error Handling**: Clear error messages and automatic retry mechanisms for better reliability
- **Multi-Language Support**: Works with anime titles in Japanese, English, and romanized formats
- **Smart Episode Detection**: Accurately identifies episode numbers, seasons, and special episodes from torrent titles

### Technical Features
- **Real-Time Monitoring**: Status updates appear instantly when you change your anime list on MAL
- **OAuth2 Authentication**: Secure, standard authentication flow with MyAnimeList
- **Rock-Solid Reliability**: Built with modern development practices for consistent performance
- **Manifest V3**: Built with the latest Chrome extension standards for security and performance

### Key Capabilities
- **Automatic Status Sync**: Your anime status changes on MAL are immediately reflected on Nyaa.si
- **Intelligent Title Normalization**: Handles variations in anime titles, romanization, and formatting
- **Season-Aware Matching**: Correctly identifies which season of an anime a torrent belongs to
- **Debug Tools**: Built-in debugging features for troubleshooting and data management
- **Cross-Platform Data**: Your anime data syncs wherever you use the extension

### User Benefits
- **Save Time**: No more manually checking if you've already watched an anime
- **Stay Organized**: Keep track of your anime progress while browsing torrents
- **Discover Content**: Easily find new anime to add to your Plan to Watch list
- **Seamless Experience**: Natural integration that doesn't disrupt your browsing flow

### Privacy & Security
- **Secure Authentication**: Uses MAL's official OAuth2 system - no password storage
- **Local Data Storage**: Your anime data is stored locally on your device
- **Minimal Permissions**: Only requests necessary permissions for core functionality
- **No Data Collection**: Extension doesn't collect or transmit personal data

---

*Releases will be added here as they are promoted from development.*
```
