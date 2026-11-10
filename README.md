# Awesome Reddit [![Awesome Lists](https://srv-cdn.himpfen.io/badges/awesome-lists/awesomelists-flat.svg)](https://github.com/brandonhimpfen/awesome-lists)

[![Support Open Work](https://img.shields.io/badge/Support-Open%20Work-0A0A0A?style=flat&logo=github)](https://github.com/brandonhimpfen/support) 
[![GitHub Sponsor](https://srv-cdn.himpfen.io/badges/github/github-flat.svg)](https://github.com/sponsors/brandonhimpfen) 
[![Buy Me a Coffee](https://srv-cdn.himpfen.io/badges/buymeacoffee/buymeacoffee-flat.svg)](https://buymeacoffee.com/brandonhimpfen) 
[![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://ko-fi.com/brandonhimpfen) 
[![PayPal](https://srv-cdn.himpfen.io/badges/paypal/paypal-flat.svg)](https://www.paypal.com/donate/?hosted_button_id=3LLKRXJU44EJJ) <br />
[![X](https://srv-cdn.himpfen.io/badges/twitter/twitter-flat.svg)](https://x.com/ListsAwesome) 
[![Facebook](https://srv-cdn.himpfen.io/badges/facebook-pages/facebook-pages-flat.svg)](https://www.facebook.com/awesomelists)

> A curated list of resources for the Reddit Data API, Reddit Developer Platform (Devvit), PRAW, bot frameworks, OAuth2 authentication, moderation tools, and social analytics pipelines.

Reddit is a global social network composed of user-curated communities (subreddits) organized around discussion threads, voting systems, and content sharing. Programmatic access to Reddit enables custom moderation bots, real-time comment streaming, sentiment research, cross-platform publishing, and interactive apps built directly inside subreddits using Devvit. This list is intended for bot developers, community moderators, social media analytics engineers, computational social scientists, and Reddit Developer Platform leads.

_Support ongoing maintenance and curation via [GitHub Sponsors](https://github.com/sponsors/brandonhimpfen)._

## Contents

- [Official APIs & Developer Platform](#official-apis--developer-platform)
- [API Wrappers & Client Libraries](#api-wrappers--client-libraries)
- [Bot Frameworks & Moderation Automation](#bot-frameworks--moderation-automation)
- [Data Extraction & Research Pipelines](#data-extraction--research-pipelines)
  - [Archive & Historical Datasets](#archive--historical-datasets)
  - [Scraping & Stream Listeners](#scraping--stream-listeners)
- [User Experience & Browser Extensions](#user-experience--browser-extensions)
- [Related Awesome Lists](#related-awesome-lists)

## Official APIs & Developer Platform

Official platform endpoints, developer documentation, OAuth2 mechanisms, and serverless app runtimes.

- [Reddit Developer Platform (Devvit)](https://developers.reddit.com/) — Official serverless developer platform for building interactive apps, custom posts, and automated bots natively hosted on Reddit.
- [Reddit Data API Documentation](https://www.reddit.com/dev/api/) — Official REST API reference for authentication, post submissions, comment threads, vote handling, and user moderation.
- [Reddit OAuth2 Portal](https://www.reddit.com/prefs/apps) — Developer dashboard for registering applications, generating client credentials, and configuring redirect URIs.
- [Reddit Ads API](https://ads-api.reddit.com/) — Official programmatic API for managing sponsored campaigns, ad groups, custom targeting, and conversion tracking.

## API Wrappers & Client Libraries

Language-native wrappers simplifying OAuth2 handshakes, rate limiting handling, and object mapping over Reddit endpoints.

- [PRAW (Python Reddit API Wrapper)](https://github.com/praw-dev/praw) — The de facto Python package for interacting with Reddit's API with built-in rate-limit management and model abstraction.
- [snoowrap](https://github.com/notablemind/snoowrap) — Fully-featured JavaScript/TypeScript wrapper for Node.js and modern browser environments providing request batching and promise chains.
- [SnooCore.js](https://github.com/k2052/SnooCore) — Lightweight JavaScript wrapper built specifically around OAuth2 endpoints for serverless and browser applications.
- [Snoopy](https://github.com/snoopy-megadb/snoopy) — PHP client library providing fluent object-oriented interfaces for accessing public subreddits and user data.

## Bot Frameworks & Moderation Automation

Automated moderation suites, community bots, auto-responders, and content queues.

- [AutoModerator](https://www.reddit.com/wiki/automoderator/) — Reddit's built-in rule engine for applying regular expressions, domain filters, karma thresholds, and removal actions automatically.
- [Reddit-Bot-Template](https://github.com/praw-dev/praw-bot-template) — Standardized Python starter project for writing, testing, and deploying PRAW-based community bots.
- [ModMail Assistant](https://developers.reddit.com/) — Devvit app framework for organizing moderator mailboxes, tagging threads, and sending canned template responses.
- [ModSupport Bot Suite](https://github.com/redditdev) — Collection of open-source utilities for automated user flair assignment, submission lock scheduling, and ban log auditing.

## Data Extraction & Research Pipelines

Tools and datasets for extracting historical threads, processing real-time comment streams, and analyzing community trends.

### Archive & Historical Datasets

- [Pushshift Reddit Archive](https://github.com/pushshift/api) — Historical dataset archive indexing billions of Reddit posts and comments for academic and social science research.
- [Arctic Shift Data Platform](https://arctic-shift.com/) — Modern data access portal for downloading and querying historical Reddit submission archives and comment dumps.

### Scraping & Stream Listeners

- [Async PRAW](https://github.com/praw-dev/asyncpraw) — Asynchronous variant of PRAW built on `asyncio` for high-throughput comment streaming and parallel task monitoring.
- [Reddit Comment Streamer](https://github.com/praw-dev/praw) — Event-driven listening script for monitoring subreddits in real time for specific keywords or sentiment triggers.

## User Experience & Browser Extensions

Open-source browser extensions, alternative web clients, and third-party interface enhancements.

- [RES (Reddit Enhancement Suite)](https://github.com/honestbleeps/Reddit-Enhancement-Suite) — Community-driven browser extension introducing inline image previews, account switching, user tagging, and advanced layout controls.
- [Teddit](https://codeberg.org/teddit/teddit) — Lightweight, privacy-focused open-source web frontend for Reddit built with JavaScript disabled by default.
- [Libredit](https://github.com/libredit/libredit) — Alternative open-source frontend written in Rust focusing on high-speed rendering and zero tracking.

## Related Awesome Lists

- [Awesome TikTok](https://github.com/brandonhimpfen/awesome-tiktok) — Video processing automation, research scraping toolkits, and live stream connectors.
- [Awesome YouTube](https://github.com/brandonhimpfen/awesome-youtube) — Video processing, YouTube Data API, live streaming, and channel automation toolkits.
- [Awesome JavaScript](https://github.com/brandonhimpfen/awesome-javascript) — Web runtimes, node automation libraries, and asynchronous event pipelines.
- [Awesome Python](https://github.com/brandonhimpfen/awesome-python) — Data scraping frameworks, media processing, and machine learning toolkits.

## Contribute

Contributions are welcome. Please ensure your submission fully follows the requirements outlined in [`CONTRIBUTING.md`](CONTRIBUTING.md), including formatting, scope alignment, and category placement.

Pull requests that do not adhere to the contribution guidelines may be closed.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)
