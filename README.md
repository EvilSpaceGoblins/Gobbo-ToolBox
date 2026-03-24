# Gobbo ToolBox (Main Public Repository)

## Overview
This repository is the central meta-project for the Gobbo Tools suite and provides references, information, and issue workflows for:

- **Indu Gobbo** (Planetary Interaction, Moon Mining, Industry)
- **Trader Gobbo** (Market and Trading Assistant)
- **Locator Gobbo** (Character Finder and Tracker)
- **Gobbo Manager** (API/Account Manager / Backoffice)

Goal: a single entry point for users and contributors who want to access and contribute to the Gobbo ecosystem.

## Applications

### Indu Gobbo
- Planning & optimization of Planetary Interaction (PI)
- Moon mining analysis & profit calculation
- Industry/blueprint calculation and production overview
- Factional and regional market dashboard

### Trader Gobbo
- Purchasing/updating market scans, shopping lists, in-transit items
- Market monitoring + opportunity analysis
- ESI-based order synchronization (individual character orders)
- Trade tracking with UUID linking to InTransit/logs

### Locator Gobbo
- Search and display of character locations in EVE
- Coordinates, region/station, online status
- Movement history

### Gobbo Manager
- Management of API tokens, user accounts, permissions
- Monitoring + scheduler tasks for all Gobbo modules

## Links
- Indu Gobbo: https://github.com/EvilSpaceGoblins/induBro
- Trader Gobbo: https://github.com/EvilSpaceGoblins/traderGobbo
- Locator Gobbo: https://github.com/EvilSpaceGoblins/locatorGobbo
- Gobbo Manager: https://github.com/EvilSpaceGoblins/gobbo-manager

## Issue Workflow
Please use the specific issue templates (for each application) when opening new issues:
- `indu-gobbo.yml`
- `trader-gobbo.yml`
- `locator-gobbo.yml`
- `gobbo-manager.yml`

### What is a bug?
- Functionality breaks on specific pages (e.g. login, data fetch, market view)
- Exceptions in backend logs (`OperationalError`, 500 errors)
- Sync/ESI call failures

### What are feature requests?
- New cross-module workflow (e.g. auto-trade, forecasting)
- UI enhancements (e.g. filter, export, dark mode)
- Additional ESI scopes or API endpoints

### Not now / Not relevant
- Content that is just “nice ideas” without implementation intent (use `[idea]` label)
- Personal support requests (please use Discord/Discussions)

## Support & Contact
- GitHub Issues: This Repository
- GitHub Discussions: https://github.com/orgs/EvilSpaceGoblins/discussions

## Features

### 🔧 General
- **Market Integration**: Automatic price updates from EVE Tycoon API (Jita/The Forge region)
- **Optimization Tools**: Identify opportunities to improve your operations
- **EVE ESI Integration**: Secure authentication and data retrieval through EVE Online's ESI API
- **Multi-Module Architecture**: Expandable for future industry features

### 🌍 Planetary Interaction
- **Multi-character Support**: Add multiple characters to a single account using EVE universe IDs
- **Colony Overview**: View all your planetary colonies, their layouts, and outputs in one place
- **Production Flow Analysis**: Calculate current ISK values and potential yields at ~87.6% processing efficiency
- **Smart Facility Monitoring**: Know which facilities are REALLY producing.
- **Storage Monitoring**: Track facility contents and capacity
- **Extractor Management**: Monitor extractor cycles and depletion times

### 🌙 Moon Mining
- **Moon Survey Parser**: Paste moon survey data directly from EVE
- **Ore Refinement Calculator**: Automatic conversion of moon ores to refined materials
- **Profitability Analysis**: Calculate profit/loss with fuel costs and current market prices
- **Dual Efficiency Modes**: Support for Metenox Moon Drill (40%) and Athanor/Tatara (100%) extraction
- **Secondary Outputs**: Optional inclusion of mineral byproducts (Pyerite, Mexallon)
- **Market Price Updates**: Recalculate profitability with latest Jita prices anytime

### 🚀 Industry
- **Industry Profitability Check**: Check what is currently profitable to produce ISK/Hour or Revenue
- **Industry Calculator**: Instant profitability calculation for any industry job.
- **Industry Job Checker**: Import and check the status of your industry jobs across all of your characters
- **Visualisation**: Visualize your blueprint, production cycles and industry input/output item flow

### 🤖 Discord Notifications
- **Direct Chat Notification**: Sends your updates when your PI or Industry will stop or run into bottlenecks
