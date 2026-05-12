# Gobbo ToolBox (Main Public Repository)

## Overview
This repository is the central meta-project for the Gobbo Tools suite and provides references, information, and issue workflows for:

- **Indu Gobbo** (Planetary Interaction, Moon Mining, Industry, Shipyard)
- **Trader Gobbo** (Market and Trading Assistant)
- **Locator Gobbo** (Character Finder and Tracker)
- **Gobbo Manager** (API/Account Manager / Backoffice)

Goal: a single entry point for users and contributors who want to access and contribute to the Gobbo ecosystem.

## Applications

### Indu Gobbo
- Planning & optimization of Planetary Interaction (PI)
- Moon mining analysis & profit calculation
- Industry/blueprint calculation and production overview
- Shipyard: Custom ship building orders, catalog management, and Discord integration
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
- `shipyard.yml`
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
