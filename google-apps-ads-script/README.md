# Google Apps & Ads Script Toolkit

Comprehensive automation toolkit for Google Workspace and Google Ads with specialized skills for Apps Script and Ads Scripts.

## Overview

Professional automation toolkit covering Google Workspace automation (Sheets, Docs, Gmail, Drive, Calendar) and Google Ads campaign automation. Perfect for marketers, data analysts, and automation engineers building custom workflows across Google's ecosystem.

## Status: Production Ready (v1.0.0)

This toolkit includes 2 comprehensive skills for automating Google Workspace and Google Ads.

## Included Skills

### 1. **google-apps-script** - Google Workspace Automation

Comprehensive guide for Google Apps Script development covering all built-in services including SpreadsheetApp, DocumentApp, GmailApp, DriveApp, CalendarApp, and more.

**Use when:**
- Automating Google Sheets operations (reading, writing, formatting)
- Creating or editing Google Docs programmatically
- Managing Gmail messages and sending emails
- Working with Google Drive files and folders
- Automating Google Calendar events
- Implementing triggers (time-based, event-based)
- Building custom functions for Sheets
- Creating Google Workspace add-ons
- Handling OAuth scopes and authorization
- Making HTTP requests to external APIs with UrlFetchApp
- Using persistent storage with PropertiesService
- Implementing caching strategies with CacheService

**Key Features:**
- **SpreadsheetApp** - Complete Sheets automation (read, write, format, formulas)
- **DocumentApp** - Google Docs creation and editing
- **GmailApp & MailApp** - Email automation and management
- **DriveApp** - File operations and permissions
- **CalendarApp** - Calendar event management
- **Triggers** - Time-based and event-driven automation
- **UrlFetchApp** - External API integration
- **PropertiesService** - Persistent storage
- **CacheService** - Temporary data caching
- **Error handling** - Comprehensive error recovery patterns
- **Performance optimization** - Batch operations and best practices

**Common Use Cases:**
- Automated spreadsheet reports
- Email auto-responders
- Document generation from templates
- Form response processing
- Data synchronization across platforms
- Scheduled tasks and notifications

### 2. **google-ads-scripts** - Google Ads Automation

Expert guidance for Google Ads Scripts covering campaign automation, bidding strategies, reporting, and optimization.

**Use when:**
- Automating Google Ads campaign management
- Building custom bidding strategies
- Creating automated reports
- Implementing performance alerts
- Managing keywords and ads at scale
- Automating budget allocation
- Integrating Google Ads with Sheets
- Optimizing campaigns programmatically
- Pausing/enabling campaigns based on conditions
- Analyzing account performance

**Key Features:**
- **Campaign Management** - Automate campaign operations
- **Keyword Management** - Add, pause, remove keywords at scale
- **Ad Management** - Automated ad creation and testing
- **Bidding Automation** - Custom bidding strategies
- **Reporting** - Custom reports to Sheets or email
- **Performance Monitoring** - Alerts and notifications
- **Budget Management** - Automated budget allocation
- **Quality Score Optimization** - Monitor and improve QS
- **A/B Testing** - Automated ad and landing page tests
- **Integration** - Connect with external APIs and Sheets

**Common Use Cases:**
- Pause low-performing keywords automatically
- Automated bid adjustments based on performance
- Daily performance reports to email/Sheets
- Budget allocation across campaigns
- Weather-based campaign adjustments
- Inventory-based ad scheduling
- Competitive analysis automation

## Installation

```bash
/plugin install google-apps-ads-script@wookstar
```

This installs both Google Apps Script and Google Ads Scripts skills as a complete automation toolkit.

## Common Workflows

### Marketing Analytics Automation

1. **google-ads-scripts** - Extract Google Ads performance data
2. **google-apps-script** - Write data to Google Sheets
3. **google-apps-script** - Generate reports and send via Gmail
4. **google-apps-script** - Schedule daily/weekly with time-based triggers

### Campaign Performance Monitoring

1. **google-ads-scripts** - Monitor campaign metrics (CTR, CPA, ROAS)
2. **google-ads-scripts** - Pause underperforming campaigns/keywords
3. **google-ads-script** - Send alert emails for anomalies
4. **google-apps-script** - Log actions to Google Sheets for audit

### Automated Reporting Dashboard

1. **google-ads-scripts** - Pull Ads data (impressions, clicks, conversions)
2. **google-apps-script** - Aggregate data in Sheets
3. **google-apps-script** - Create charts and visualizations
4. **google-apps-script** - Email dashboard link to stakeholders

## Prerequisites

### For Google Apps Script
- Google Account with access to Google Workspace
- Basic JavaScript knowledge
- Familiarity with Google Sheets, Docs, Gmail, Drive, Calendar

### For Google Ads Scripts
- Google Ads account with API access
- JavaScript knowledge
- Understanding of Google Ads concepts (campaigns, keywords, bidding)
- Manager account recommended for managing multiple accounts

## Environment Setup

### Google Apps Script Setup

1. Open Google Sheets/Docs
2. **Extensions → Apps Script**
3. Write your script
4. Set up triggers if needed
5. Authorize OAuth scopes

### Google Ads Scripts Setup

1. Sign into Google Ads
2. **Tools & Settings → Bulk Actions → Scripts**
3. Click **+** to create new script
4. Write your script
5. Preview or schedule to run
6. Monitor execution logs

## Key Resources

**Official Documentation:**
- [Google Apps Script Docs](https://developers.google.com/apps-script)
- [Apps Script API Reference](https://developers.google.com/apps-script/reference)
- [Google Ads Scripts Docs](https://developers.google.com/google-ads/scripts)
- [Ads Scripts API Reference](https://developers.google.com/google-ads/scripts/docs/reference)

**Developer Tools:**
- [Apps Script IDE](https://script.google.com/)
- [Clasp CLI](https://github.com/google/clasp) - Command-line Apps Script tool
- [Apps Script Samples](https://github.com/googleworkspace/apps-script-samples)
- [Ads Scripts Examples](https://developers.google.com/google-ads/scripts/docs/examples)

**Community:**
- [Stack Overflow - google-apps-script](https://stackoverflow.com/questions/tagged/google-apps-script)
- [Stack Overflow - google-ads-scripts](https://stackoverflow.com/questions/tagged/google-ads-scripts)

## Integration Opportunities

These skills integrate well with other marketplace toolkits:

- **GTM Suite** - Track script-triggered events via GTM
- **GA Suite** - Send data to GA4 via Measurement Protocol
- **Documents Toolkit** - Process Excel files with Sheets automation
- **Developer Toolkit** - Build web interfaces for Apps Script apps

## Quick Start Examples

### Apps Script: Daily Report Automation

```javascript
function generateDailyReport() {
  const ss = SpreadsheetApp.getActiveSpreadsheet();
  const data = ss.getSheetByName('Data').getDataRange().getValues();

  // Process and analyze data
  const summary = analyzedData(data);

  // Email report
  MailApp.sendEmail({
    to: 'team@example.com',
    subject: 'Daily Report - ' + new Date().toDateString(),
    body: summary
  });
}
```

### Ads Scripts: Pause Low-Performing Keywords

```javascript
function pauseLowPerformingKeywords() {
  const keywords = AdsApp.keywords()
    .forDateRange('LAST_30_DAYS')
    .withCondition('Impressions > 1000')
    .withCondition('Ctr < 0.01')
    .get();

  while (keywords.hasNext()) {
    const keyword = keywords.next();
    keyword.pause();
    Logger.log('Paused: ' + keyword.getText());
  }
}
```

## Best Practices

### Apps Script
- Use batch operations to minimize API calls
- Implement error handling and logging
- Cache frequently accessed data
- Respect execution time limits (6 minutes)
- Minimize OAuth scopes requested

### Ads Scripts
- Test with preview mode before scheduling
- Monitor execution logs regularly
- Use label-based organization
- Implement proper error handling
- Respect API rate limits
- Document script logic for team visibility

## Troubleshooting

### Common Apps Script Issues
- **Execution timeout** - Split into smaller batches
- **Authorization error** - Check OAuth scopes
- **Quota exceeded** - Reduce API call frequency
- **Null reference error** - Validate objects exist

### Common Ads Scripts Issues
- **Script timeout** - Optimize selectors and loops
- **Permission denied** - Verify account access
- **Rate limit exceeded** - Add delays between API calls
- **Preview vs Live differences** - Test thoroughly before scheduling

## Version

Current version: **1.0.0**

## Category

Automation / Marketing / Productivity

---

**Created by:** Henrik Soederlund ([@henkisdabro](https://github.com/henkisdabro))
**Part of:** Claude Code Plugin Marketplace
**License:** Follow Google's terms of service for Apps Script and Ads API usage

## Directory Structure Note

This toolkit has a slightly different structure to accommodate both skills:

```
google-apps-ads-script/
├── README.md (this file)
├── google-apps-script/        ← Apps Script skill (at root level)
│   ├── SKILL.md
│   ├── assets/
│   ├── references/
│   └── scripts/
└── skills/
    └── google-ads-scripts/    ← Ads Scripts skill (in skills/)
        ├── SKILL.md
        ├── assets/
        ├── references/
        └── scripts/
```

Both skills are automatically loaded when the toolkit is installed.
