## Google Chrome Custom Search Engines
#### By Greg Sadetsky ([original list by Dan Turkel](https://github.com/daturkel/custom-search-engines))

Google Chrome's Custom Search Engine feature allows you to add search shortcuts that can be used directly from the search bar (the "Omnibox") for sites other than your main search engine. These shortcuts work on (almost) any site that offers a search functionality -- be it Wikipedia, Amazon, Google Images, etc.

Example: you can set up a new search engine for Wikipedia that's mapped to the shortcut "w". To search Wikipedia from the Omnibox, you would then only need to type:

- <kbd>⌘</kbd> <kbd>L</kbd> to focus on the Omnibox (or <kbd>ctrl</kbd> <kbd>L</kbd> if you're on Windows)
- `w Pokemon` (shortcut + space + search term)
- <kbd>Enter</kbd>

##### Direct access

You can also map shortcuts to access frequently visited sites, such as Google Calendar ("c") or Gmail ("m"). There is no "search" involved in these shortcuts, but they work nevertheless!

##### Stopping sites from adding their own custom search engines

There is no way (as of now) to configure Google Chrome to stop sites from adding their own search engines (Chrome actually adds some sites on their behalf, without the site "asking" to be added).

If you prefer to maintain a clean list of custom search engines, you can use a Chrome extension to which I've contributed for that!

- ["Don't add custom search engines" in the Chrome Web Store](https://chrome.google.com/webstore/detail/dont-add-custom-search-en/dnodlcololidkjgbpeoleabmkocdhacc?hl=en)
- [Source code on GitHub](https://github.com/gregsadetsky/chrome-dont-add-custom-search-engines)

### The Search Engines

Name | Keyword | Example | Url
:--- | :------ | :------ | :--
Amazon | amzn | | `https://www.amazon.com/s/?field-keywords=%s`
AWS | aw | `aw s3` | `https://console.aws.amazon.com/%s`
Dictionary | dict | | `http://www.dictionary.com/browse/%s`
eBay | ebay | | `https://www.ebay.com/sch/i.html?_nkw=%s`
Github | gh | | `https://github.com/search?q=%s`
Gmail search | gm | | `https://mail.google.com/mail/u/0/#search/%s`
Google Drive | drive | | `https://drive.google.com/drive/search?q=%s`
Google Maps | maps | | `https://www.google.com/maps/search/%s/`
Google Images | img | | `https://www.google.com/search?tbm=isch&q=%s`
Hacker News | hn | | `https://hn.algolia.com/?query=%s`
IMDB | i | | `http://www.imdb.com/find?q=%s`
LinkedIn  | li | | `https://www.linkedin.com/search/results/index/?keywords=%s`
Thesaurus | thes | | `http://www.thesaurus.com/browse/%s`
Mailinator | maili | `maili myinbox` | `https://www.mailinator.com/v2/inbox.jsp?zone=public&query=%s`
Wikipedia English | wp | | `https://en.wikipedia.org/wiki/%s`
YouTube | yt | | `https://www.youtube.com/results?search_query=%s`
Stack Overflow | so | | `http://stackoverflow.com/search?q=%s`
Yelp | ye | | `http://www.yelp.com/search?find_desc=%s`

### Search Engines (specific to Canada / Québec)

Name | Keyword | Example | Url
:--- | :------ | :------ | :--
Amazon Canada | amznca | | `https://www.amazon.ca/s/?field-keywords=%s`
eBay Canada | ebayca | | `https://www.ebay.ca/sch/i.html?_nkw=%s`
Google CAD to USD | cu | cu 100 | `https://www.google.com/search?q=%s+cad+in+usd`
Google USD to CAD | uc | uc 100 | `https://www.google.com/search?q=%s+usd+in+cad`
Linguee en -> fr | lenfr | | `https://www.linguee.com/english-french/search?query=%s`
Linguee fr -> en | lfren | | `https://www.linguee.com/french-english/search?query=%s`
Wikipedia French | wpfr | | `https://fr.wikipedia.org/w/index.php?search=%s`
WordReference en -> fr | enfr | | `http://www.wordreference.com/enfr/%s`
WordReference fr -> en | fren | | `http://www.wordreference.com/fren/%s`

### Direct access shortcuts (i.e., Omnibox shortcuts that aren't search engines)

Name | Keyword | Url
:--- | :------ | :--
Gmail | m | `https://mail.google.com/mail/u/0/#inbox`
Google Calendar | c | `https://calendar.google.com/calendar/r`

### How to Add/Edit Search Engines

1. Open Chrome
2. Right click or control click the address bar
3. Select "Edit Search Engines..."
4. Scroll through to see if the search engine you want to add is already in there—you might just need to change the keyword
5. If it's not there, scroll to the top where you can add a new search engine just as you see it here. The "Add" link/button is on the upper right.

### How to Use Them
1. Go to your address bar by either a) clicking it b) typing control-l ("L" as in Lima) on Windows c) typing command-l ("L" as in Lima) on a Mac
2. Type the keyword (e.g. `w` for Wikipedia)
3. *Don't* press enter!
4. Press space
5. Type in your search query
6. *Now* press enter
