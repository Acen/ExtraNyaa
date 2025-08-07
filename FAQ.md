# Frequently Asked Questions (FAQ)

## Installation & Setup

### Q: How do I install ExtraNyaa?
**A:** The easiest way is through the Chrome Web Store:
1. Visit the [ExtraNyaa Chrome Web Store page](https://chrome.google.com/webstore/detail/extranyaa/cflojlcgllgkoeeffneclgkngejleoba)
2. Click "Add to Chrome"
3. Follow the setup prompts to connect to MyAnimeList

See our [Installation Guide](INSTALLATION.md) for detailed instructions.

### Q: Which browsers are supported?
**A:** ExtraNyaa works on:
- ✅ **Google Chrome** (Recommended)
- ✅ **Microsoft Edge** (Chromium-based)
- ✅ **Brave Browser**
- ✅ **Other Chromium browsers**
- ❌ **Firefox** (Not currently supported)
- ❌ **Safari** (Not supported)

### Q: Do I need a MyAnimeList account?
**A:** Yes, you need a free MyAnimeList account to use ExtraNyaa. The extension shows your personal anime tracking status, so it requires access to your MAL list.

## MyAnimeList Connection

### Q: Why can't I connect to MyAnimeList?
**A:** Try these solutions:
1. **Clear browser cookies** for MyAnimeList
2. **Restart Chrome** and try again

### Q: Is my MyAnimeList data safe?
**A:** Yes! ExtraNyaa:
- Uses **OAuth authentication** (secure login through MAL)
- Stores data **locally on your device**
- **Never shares** your data with third parties
- Makes **direct connections** between you and MyAnimeList

### Q: How often does my anime list sync?
**A:** Your list syncs:
- **Automatically** when you first connect
- **On demand** when you click "Refresh List" in the popup
- **Periodically** in the background (every few hours)
- **When you browse** new anime on MyAnimeList

## Status Icons & Features

### Q: Why don't I see status icons on Nyaa.si?
**A:** Check these common issues:
1. **Verify connection** - Click the ExtraNyaa icon to ensure you're connected to MAL
2. **Refresh the page** - Sometimes a page refresh is needed
3. **Check your list** - The anime should be in your MAL list to show icons

### Q: What do the different status icons mean?
**A:** Here's what each icon represents:
- ▶️ **Currently Watching** - Anime you're actively watching
- ⬜ **Plan to Watch** - Anime in your "Plan to Watch" list
- ✅ **Completed** - Anime you've finished watching
- ⏸️ **On Hold** - Anime you've paused/put on hold
- ❌ **Dropped** - Anime you've dropped
- ➕ **Add to List** - Anime not in your list (click to add)
- ❔ **Search** - Unknown anime (click to search MAL)

### Q: Why is the wrong anime being matched?
**A:** Sometimes complex or alternative titles can cause mismatches:
- **Click the icon** to verify it opens the correct MAL page
- **Check alternative titles** on the MAL page - they might match
- **Report persistent issues** as bugs in our [Issues](../../issues) section
- This is more common with sequels, OVAs, or titles with multiple seasons

### Q: Can I add anime to my list directly from Nyaa?
**A:** Currently, ExtraNyaa is read-only and shows your existing MAL status. To add anime:
1. **Click the ➕ icon** to go to the anime's MAL page
2. **Add it to your list** on MyAnimeList
3. **Refresh** the Nyaa page - it should have updated it's status as you added it to your list.

## Troubleshooting

### Q: The extension isn't working after an update
**A:** Try these steps:
1. **Restart Chrome** completely
2. **Check extension status** in `chrome://extensions/`
3. **Re-connect to MAL** through the extension popup
4. **Clear browser cache** if issues persist

### Q: I'm getting "Authorization failed" errors
**A:** This usually indicates a login issue:
1. **Clear MyAnimeList cookies** in your browser
2. **Log out** of MyAnimeList completely, then try again
3. **Check MAL status** - ensure MyAnimeList isn't down

### Q: Status icons appear but links don't work
**A:** This suggests a data sync issue:
1. **Click "Refresh List"** in the extension popup
2. **Wait a few minutes** for the refresh to complete
3. **Reload Nyaa.si** after the refresh
4. **Check MAL connection** status in the popup

### Q: The extension is slowing down my browser
**A:** ExtraNyaa is designed to be lightweight, but if you experience slowdowns:
1. **Update Chrome** to the latest version
2. **Restart the browser** to clear memory
3. **Check other extensions** - disable them temporarily to isolate the issue
4. **Report performance issues** with your browser version and system specs

## Features & Usage

### Q: Does ExtraNyaa work on mobile?
**A:** ExtraNyaa is designed for desktop Chrome browsers. Mobile Chrome doesn't support extensions, so it won't work on phones or tablets.

### Q: Can I use ExtraNyaa with other anime tracking sites?
**A:** Currently, ExtraNyaa only integrates with MyAnimeList. Support for other platforms (AniList, Kitsu, etc.) is not available but could be considered for future versions.

### Q: Does ExtraNyaa track manga or light novels?
**A:** No, ExtraNyaa focuses specifically on anime tracking. It only shows status for anime entries in your MyAnimeList.

### Q: Can I customize which status icons are shown?
**A:** Currently, all status types are shown by default. Customization options may be added in future updates based on user feedback.

## Updates & Support

### Q: How do I update ExtraNyaa?
**A:** Extensions from the Chrome Web Store update automatically:
- **Automatic updates** happen in the background
- **No action required** from you
- **Connection persists** through updates
- **Check [releases](../../releases)** for update notes

### Q: How do I report bugs or request features?
**A:** We welcome feedback! Please:
1. **Search existing [issues](../../issues)** first
2. **Create a new issue** with details:
   - Browser version
   - Extension version
   - Steps to reproduce
   - Screenshots if applicable
3. **Be specific** about the problem or feature request

### Q: Will ExtraNyaa always be free?
**A:** The core functionality of ExtraNyaa will always be free. Any potential future features that have operational costs to run may have a cost associated, but the basic anime tracking and status display will remain free forever.

## Still Need Help?

If your question isn't answered here:

1. **Check the [Installation Guide](INSTALLATION.md)** for setup help
2. **Search [Issues](../../issues)** for similar problems
3. **Create a new issue** with detailed information about your problem
4. **Include your browser version, extension version, and steps to reproduce**

---

*Can't find what you're looking for? [Create an issue](../../issues) and we'll help you out!*
