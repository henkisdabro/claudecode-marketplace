# Google Analytics 4 Suite

Comprehensive toolkit for Google Analytics 4 implementation, reporting, and optimization with 15 specialized skills organized by implementation tier.

## Overview

Complete Google Analytics 4 expertise covering property setup, event tracking, user tracking, custom dimensions, audiences, privacy compliance, reporting, BigQuery integration, and advanced implementation techniques. From initial GA4 setup through enterprise-level BigQuery analysis, this suite provides complete GA4 mastery.

## Status: Production Ready (v1.0.0)

This suite includes 15 comprehensive skills organized into 5 progressive tiers covering all aspects of Google Analytics 4.

## Skill Organization by Tier

### Tier 1: Foundation (Getting Started)

#### 1. **ga4-setup** - Property Setup & Installation

Property creation, data stream configuration, and installation methods (gtag.js, GTM, CMS plugins).

**Use when:**
- Creating new GA4 properties
- Setting up data streams (web, iOS, Android)
- Installing tracking code
- Configuring Measurement IDs (G-XXXXXXXXXX)
- Troubleshooting installation issues
- Migrating from Universal Analytics

**Key Topics:**
- Account and property creation
- Data stream configuration
- Installation methods (gtag.js, GTM, plugins)
- Verification with DebugView and Realtime reports
- CMS platform integration (WordPress, Shopify)

#### 2. **ga4-events-fundamentals** - Event Architecture & Parameters

Event architecture, automatic collection, recommended events, and event parameters.

**Use when:**
- Understanding GA4 event model
- Learning event naming conventions
- Working with event parameters
- Configuring Enhanced Measurement
- Understanding automatic vs manually tracked events

**Key Topics:**
- GA4 event model fundamentals
- Automatic events (page_view, session_start, etc.)
- Enhanced Measurement events
- Event naming best practices
- Event parameters and limitations

#### 3. **ga4-gtag-implementation** - Direct gtag.js Implementation

Direct gtag.js implementation without Tag Manager.

**Use when:**
- Implementing GA4 without GTM
- Using gtag.js directly in HTML
- Simple website tracking needs
- Learning gtag.js syntax and commands
- Troubleshooting gtag.js issues

**Key Topics:**
- gtag.js installation and configuration
- Event tracking with gtag commands
- Configuration parameters
- User properties with gtag
- Debugging gtag implementations

### Tier 2: Configuration (Essential Tracking)

#### 4. **ga4-recommended-events** - E-commerce & Conversion Tracking

E-commerce tracking with recommended events (add_to_cart, purchase, etc.) and conversion events.

**Use when:**
- Implementing e-commerce tracking
- Tracking purchase funnels
- Setting up conversion events
- Working with product/item arrays
- Measuring revenue and transactions

**Key Topics:**
- E-commerce recommended events
- Product/item schema
- Purchase funnel tracking
- Revenue and currency handling
- Conversion event configuration

#### 5. **ga4-custom-events** - Business-Specific Event Tracking

Custom event creation for business-specific interactions and goals.

**Use when:**
- Tracking custom interactions unique to your business
- Creating events beyond recommended events
- Implementing video tracking
- Tracking file downloads
- Monitoring user engagement actions

**Key Topics:**
- Custom event naming conventions
- Custom event parameters
- Video tracking patterns
- File download tracking
- Form interaction tracking

#### 6. **ga4-user-tracking** - User ID & Cross-Device Tracking

User ID implementation for authenticated user tracking and cross-device analysis.

**Use when:**
- Implementing User ID for logged-in users
- Tracking users across devices
- Analyzing authenticated user behavior
- Setting up cross-device reporting
- Implementing user-scoped data

**Key Topics:**
- User ID setup and implementation
- Cross-device tracking methodology
- User properties configuration
- Authentication state tracking
- Privacy considerations for user tracking

### Tier 3: Advanced Configuration

#### 7. **ga4-custom-dimensions** - Custom Dimensions & Metrics

Custom dimensions (event, user, item-scoped) and custom metrics configuration.

**Use when:**
- Creating custom dimensions for additional data
- Implementing custom metrics
- Working with different dimension scopes
- Registering dimensions in GA4 interface
- Analyzing custom business data

**Key Topics:**
- Event-scoped custom dimensions
- User-scoped custom dimensions
- Item-scoped custom dimensions
- Custom metrics implementation
- Dimension registration and management

#### 8. **ga4-audiences** - Audience Building & Remarketing

Audience creation, segmentation, and remarketing list setup.

**Use when:**
- Building remarketing audiences
- Creating predictive audiences
- Segmenting users for analysis
- Connecting audiences to Google Ads
- Implementing audience triggers

**Key Topics:**
- Audience builder interface
- Predictive audiences (purchase probability, churn)
- Event-based audiences
- User property-based audiences
- Audience export to Google Ads

#### 9. **ga4-debugview** - Testing & Validation

DebugView usage, event validation, and troubleshooting techniques.

**Use when:**
- Testing GA4 implementation before launch
- Validating event tracking
- Debugging event parameter issues
- Troubleshooting data discrepancies
- Using Tag Assistant for testing

**Key Topics:**
- DebugView activation and usage
- Event parameter validation
- Google Tag Assistant
- Common implementation issues
- Testing workflows

### Tier 4: Integration & Privacy

#### 10. **ga4-gtm-integration** - GA4 via Google Tag Manager

Complete GA4 implementation through GTM including configuration and event tracking.

**Use when:**
- Implementing GA4 through Google Tag Manager
- Setting up GA4 configuration tag in GTM
- Creating event tags in GTM
- Using data layer with GA4
- Managing GA4 via GTM interface

**Key Topics:**
- Google Tag configuration in GTM
- Event tag setup in GTM
- Data layer variable mapping
- GTM trigger configuration for GA4
- GTM testing and debugging

#### 11. **ga4-measurement-protocol** - Server-Side Event Tracking

Measurement Protocol v2 for server-side event tracking and API-based data collection.

**Use when:**
- Implementing server-side tracking
- Sending offline conversion data
- Tracking server-side events (API calls, backend processes)
- Building custom tracking solutions
- Bypassing client-side limitations

**Key Topics:**
- Measurement Protocol API v2
- Required and optional parameters
- Event payload structure
- API authentication
- Server-side implementation patterns

#### 12. **ga4-privacy-compliance** - GDPR & Consent Mode

Privacy compliance with GDPR, Consent Mode v2, and data deletion.

**Use when:**
- Implementing GDPR compliance
- Configuring Google Consent Mode v2
- Managing cookie consent
- Handling data deletion requests
- Implementing privacy controls

**Key Topics:**
- Google Consent Mode v2
- Cookie consent integration
- IP anonymization (automatic in GA4)
- Data retention settings
- User data deletion API

### Tier 5: Analysis & Advanced Features

#### 13. **ga4-reporting** - Reports & Explorations

Reports interface, Explorations, and data analysis techniques.

**Use when:**
- Creating custom reports
- Building Explorations for analysis
- Understanding standard reports
- Analyzing user behavior
- Creating data visualizations

**Key Topics:**
- Standard reports overview
- Exploration techniques (funnel, path, cohort)
- Custom report creation
- Data visualization best practices
- Report sharing and scheduling

#### 14. **ga4-bigquery** - BigQuery Export & SQL Analysis

BigQuery export setup and SQL analysis for raw GA4 data.

**Use when:**
- Exporting GA4 data to BigQuery
- Writing SQL queries for GA4 data
- Performing advanced analysis
- Joining GA4 data with other sources
- Building custom dashboards from raw data

**Key Topics:**
- BigQuery export configuration
- GA4 BigQuery schema
- SQL query patterns for GA4 data
- Event and user tables structure
- Advanced SQL analysis techniques

#### 15. **ga4-data-management** - Admin Settings & Data Governance

Admin interface, data retention, filters, and property management.

**Use when:**
- Configuring data retention settings
- Managing user access and permissions
- Setting up data filters
- Implementing data streams
- Managing property settings

**Key Topics:**
- Data retention configuration
- Internal traffic filters
- User access management
- Data stream settings
- Property-level configuration

## Installation

```bash
/plugin install ga-suite@wookstar
```

This installs all 15 GA4 skills as a complete suite.

## Common Workflows

### Initial GA4 Setup

1. **ga4-setup** - Create property and install tracking code
2. **ga4-events-fundamentals** - Understand event architecture
3. **ga4-debugview** - Validate implementation with DebugView
4. **ga4-data-management** - Configure data retention and filters

### E-commerce Implementation

1. **ga4-setup** - Ensure GA4 is properly installed
2. **ga4-recommended-events** - Implement e-commerce events
3. **ga4-custom-dimensions** - Add product-specific dimensions
4. **ga4-debugview** - Test purchase funnel
5. **ga4-reporting** - Create e-commerce reports

### GTM-Based Implementation

1. **ga4-gtm-integration** - Set up GA4 configuration tag in GTM
2. **ga4-events-fundamentals** - Plan event tracking strategy
3. **ga4-custom-events** - Create custom event tags in GTM
4. **ga4-debugview** - Test with GTM Preview mode
5. **ga4-reporting** - Validate data in GA4 reports

### Enterprise Analytics Setup

1. **ga4-setup** - Create production and development properties
2. **ga4-user-tracking** - Implement User ID for authenticated users
3. **ga4-custom-dimensions** - Set up business-specific dimensions
4. **ga4-privacy-compliance** - Implement Consent Mode v2
5. **ga4-bigquery** - Configure BigQuery export
6. **ga4-measurement-protocol** - Add server-side tracking
7. **ga4-audiences** - Build remarketing audiences
8. **ga4-reporting** - Create comprehensive dashboards

## Prerequisites

- Google account with access to Google Analytics
- Website or app to track
- Basic understanding of web analytics concepts
- For GTM implementation: Google Tag Manager container installed
- For BigQuery: Google Cloud Platform account with billing enabled

## Key Resources

**Official Documentation:**
- [Google Analytics 4 Help Center](https://support.google.com/analytics/topic/9303319)
- [GA4 Developer Guide](https://developers.google.com/analytics/devguides/collection/ga4)
- [Measurement Protocol v2](https://developers.google.com/analytics/devguides/collection/protocol/ga4)
- [BigQuery Export Schema](https://support.google.com/analytics/answer/7029846)
- [gtag.js Reference](https://developers.google.com/tag-platform/gtagjs/reference)

**Expert Content:**
- [Simo Ahava's Blog](https://www.simoahava.com/) - GA4 expertise
- [Analytics MCP](https://github.com/googleanalytics/google-analytics-mcp) - Official Google Analytics MCP server
- [GA4 BigQuery SQL Cookbook](https://www.ga4bigquery.com/) - SQL query examples

**Developer Tools:**
- [Google Analytics Debugger](https://chrome.google.com/webstore/detail/google-analytics-debugger/jnkmfdileelhofjcijamephohjechhna) - Chrome extension
- [Tag Assistant](https://tagassistant.google.com/) - Testing and debugging
- [GA4 Query Explorer](https://ga-dev-tools.google/ga4/query-explorer/) - Test Data API queries

## Integration with Other Suites

This GA suite integrates seamlessly with other marketplace toolkits:

- **GTM Suite (gtm-suite)** - Implement GA4 via Google Tag Manager
- **Shopify Developer (shopify-developer)** - GA4 tracking on Shopify stores
- **Google Apps & Ads Script (google-apps-ads-script)** - Export GA4 data to Sheets, integrate with Ads
- **Developer Toolkit (developer-toolkit)** - Use Chrome DevTools for debugging GA4

## Skill Progression Path

**Beginner Path:**
1. ga4-setup → ga4-events-fundamentals → ga4-debugview → ga4-reporting

**Intermediate Path:**
1. ga4-gtag-implementation → ga4-recommended-events → ga4-custom-events → ga4-custom-dimensions

**Advanced Path:**
1. ga4-gtm-integration → ga4-measurement-protocol → ga4-privacy-compliance → ga4-bigquery

**Enterprise Path:**
1. All Foundation & Configuration skills → ga4-user-tracking → ga4-custom-dimensions → ga4-audiences → ga4-bigquery → ga4-measurement-protocol

## Environment Setup

### GA4 Property Creation

1. Visit [analytics.google.com](https://analytics.google.com)
2. Admin → Create → Property
3. Enter property details (name, timezone, currency)
4. Create data stream (Web, iOS, or Android)
5. Copy Measurement ID (G-XXXXXXXXXX)

### GTM Installation (Recommended)

1. Install GTM container on website (see **gtm-suite**)
2. In GTM: Tags → New → Google Tag
3. Enter Measurement ID
4. Trigger: Initialization - All Pages
5. Publish container

### BigQuery Setup (For Enterprise)

1. Create Google Cloud Platform project
2. Enable BigQuery API
3. In GA4: Admin → BigQuery Linking
4. Configure daily/streaming export
5. Link to GCP project

## Best Practices

### Implementation
- Start with automatic events before custom tracking
- Use DebugView extensively during development
- Follow Google's recommended event naming
- Implement Enhanced Measurement for quick wins
- Plan custom dimensions before implementation

### Privacy & Compliance
- Implement Consent Mode v2 for EU traffic
- Configure appropriate data retention
- Set up internal traffic filters
- Document tracking and privacy policies
- Regularly audit data collection

### Reporting & Analysis
- Create custom Explorations for deeper insights
- Export to BigQuery for advanced analysis
- Build audiences for remarketing
- Monitor key events as conversions
- Regular reporting schedule

### Performance
- Minimize event parameter count (25 max per event)
- Use recommended events when possible
- Batch events when using Measurement Protocol
- Monitor quota limits for API usage

## Troubleshooting

**Common Issues by Skill:**

1. **No data in reports** → **ga4-setup**, **ga4-debugview**
2. **Events not firing** → **ga4-events-fundamentals**, **ga4-debugview**
3. **E-commerce not tracking** → **ga4-recommended-events**, **ga4-debugview**
4. **Custom dimensions not appearing** → **ga4-custom-dimensions**, **ga4-data-management**
5. **BigQuery export issues** → **ga4-bigquery**, **ga4-data-management**
6. **Consent Mode not working** → **ga4-privacy-compliance**, **ga4-debugview**

## Version

Current version: **1.0.0** (Production Ready)

## Category

Analytics / Data / Reporting

---

**Created by:** Henrik Soederlund ([@henkisdabro](https://github.com/henkisdabro))
**Part of:** Claude Code Plugin Marketplace
**License:** Follow Google's terms of service for Analytics usage

## Planned Future Additions

- **Agents:** GA4 analyst, GA4 implementation specialist, GA4 optimizer agents
- **Commands:** /ga4-init, /ga4-audit, /ga4-report, /ga4-migrate commands
- **MCP Servers:** Official Analytics MCP server integration (available at github.com/googleanalytics/google-analytics-mcp)

Suggestions welcome via GitHub issues!

## Learn More

**New to GA4?** Start with:
1. **ga4-setup** - Get GA4 installed
2. **ga4-events-fundamentals** - Understand how GA4 works
3. **ga4-debugview** - Validate your setup
4. **ga4-reporting** - Start analyzing data

**Migrating from Universal Analytics?**
1. **ga4-setup** - Create parallel GA4 property
2. **ga4-events-fundamentals** - Understand event-based model differences
3. **ga4-gtm-integration** - Implement via GTM if using GTM currently
4. **ga4-reporting** - Map UA reports to GA4 equivalents

**E-commerce Store Owner?**
1. **ga4-setup** - Install GA4
2. **ga4-recommended-events** - Implement e-commerce tracking
3. **ga4-audiences** - Build remarketing lists
4. **ga4-reporting** - Track revenue and conversions

**Enterprise Implementation?**
1. Complete Foundation tier (skills 1-3)
2. Complete Configuration tier (skills 4-6)
3. Complete Advanced tier (skills 7-9)
4. Complete Integration & Privacy tier (skills 10-12)
5. Complete Analysis tier (skills 13-15)
