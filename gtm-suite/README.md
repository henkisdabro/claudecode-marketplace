# Google Tag Manager Suite

Complete toolkit for Google Tag Manager implementation, management, debugging, and optimization with 10 specialized skills.

## Overview

Comprehensive Google Tag Manager expertise covering fundamentals, setup, configuration, implementation, debugging, best practices, custom templates, and API automation. Whether you're installing GTM for the first time, implementing complex tracking, or building custom solutions, this suite provides complete GTM mastery.

## Status: Production Ready (v1.0.0)

This suite includes 10 comprehensive skills covering all aspects of Google Tag Manager.

## Included Skills

### Setup & Configuration

#### 1. **gtm-general** - GTM Fundamentals & Architecture

General guidance and overview for Google Tag Manager including architecture, concepts, and routing to specialized skills.

**Use when:**
- Learning GTM fundamentals and core concepts
- Understanding how GTM works and its architecture
- Planning GTM implementation strategy
- Deciding whether to use GTM vs other approaches
- Getting oriented with GTM capabilities
- Unsure which specific GTM skill applies to your question

**Key Topics:**
- What is Google Tag Manager and key benefits
- GTM architecture (accounts, containers, workspaces, versions)
- Core components (tags, triggers, variables, data layer)
- Container types (web, mobile, server-side)
- Common use cases and best practices
- GTM vs hardcoded tags comparison

#### 2. **gtm-setup** - Container Setup & Installation

Container creation, installation, and workspace management.

**Use when:**
- Creating new GTM containers
- Installing GTM snippet on websites
- Managing workspaces and environments
- Configuring GTM for different platforms
- Verifying installation

**Key Topics:**
- Account and container creation
- GTM snippet installation (head and body tags)
- Workspace and version management
- Environment configuration
- Multi-container setups

#### 3. **gtm-tags** - Tag Configuration

Tag setup for GA4, Google Ads, custom HTML, and marketing pixels.

**Use when:**
- Creating GA4 or Google Ads tags
- Implementing custom HTML tags
- Setting up marketing pixels (Facebook, LinkedIn, etc.)
- Configuring tag firing priority
- Managing tag templates

**Key Topics:**
- Google Analytics 4 tags
- Google Ads conversion and remarketing tags
- Custom HTML tags
- Third-party marketing tags
- Tag sequencing and priority

#### 4. **gtm-triggers** - Trigger Configuration

Trigger patterns for pageview, clicks, forms, custom events, and conditionals.

**Use when:**
- Setting up page view triggers
- Tracking click events
- Monitoring form submissions
- Creating custom event triggers
- Using trigger conditions and RegEx

**Key Topics:**
- Page view and DOM ready triggers
- Click and link click triggers
- Form submission triggers
- Custom event triggers
- Trigger conditions and filters
- History change triggers (for SPAs)

#### 5. **gtm-variables** - Variable Management

Variable configuration for data extraction and dynamic values.

**Use when:**
- Creating data layer variables
- Building custom JavaScript variables
- Using built-in variables
- Extracting URL parameters
- Creating lookup tables

**Key Topics:**
- Built-in variables
- Data layer variables
- Custom JavaScript variables
- URL and referrer variables
- Cookie and localStorage variables
- Lookup tables

### Implementation & Optimization

#### 6. **gtm-datalayer** - Data Layer Architecture

Data layer implementation for SPAs (React/Vue/Angular/Next.js) and e-commerce tracking.

**Use when:**
- Implementing data layer for single-page applications
- Setting up e-commerce tracking
- Passing custom data to GTM
- Handling SPA route changes
- Structuring data layer events

**Key Topics:**
- Data layer fundamentals and structure
- E-commerce data layer (enhanced and standard)
- SPA data layer patterns (React, Vue, Angular, Next.js)
- Custom event tracking
- Data layer best practices

#### 7. **gtm-debugging** - Preview Mode & Troubleshooting

GTM debugging with Preview mode, Tag Assistant, and troubleshooting techniques.

**Use when:**
- Testing GTM configuration before publishing
- Debugging tags not firing
- Using Google Tag Assistant
- Troubleshooting tag firing issues
- Validating data layer values

**Key Topics:**
- Preview mode usage
- Google Tag Assistant
- Debug console
- Common issues and solutions
- Testing workflows

#### 8. **gtm-best-practices** - Performance, Security & Standards

GTM best practices for performance, security, naming conventions, and privacy.

**Use when:**
- Optimizing GTM performance
- Implementing security best practices
- Establishing naming conventions
- Ensuring privacy compliance
- Auditing GTM containers

**Key Topics:**
- Performance optimization
- Naming conventions
- Security best practices
- Privacy and consent management
- Container organization
- Documentation standards

### Advanced Features

#### 9. **gtm-custom-templates** - Sandboxed JavaScript Templates

Building custom tag, variable, and trigger templates with sandboxed JavaScript.

**Use when:**
- Creating custom tag templates
- Building reusable variable templates
- Developing custom trigger templates
- Publishing templates to Community Gallery
- Using sandboxed JavaScript APIs

**Key Topics:**
- Custom template fundamentals
- Sandboxed JavaScript APIs
- Template editor and permissions
- Template testing and validation
- Community Template Gallery publishing

#### 10. **gtm-api** - REST API Automation

GTM REST API v2 for programmatic container management with Python/Node.js.

**Use when:**
- Automating GTM container management
- Bulk operations on tags, triggers, variables
- Migrating configurations between containers
- Building GTM management tools
- Integrating GTM with CI/CD pipelines

**Key Topics:**
- GTM API v2 authentication
- Container management operations
- Tag, trigger, variable CRUD operations
- Workspace and version management
- Python and Node.js client libraries

## Installation

```bash
/plugin install gtm-suite@wookstar
```

This installs all 10 GTM skills as a complete suite.

## Common Workflows

### Initial GTM Setup

1. **gtm-general** - Understand GTM fundamentals and architecture
2. **gtm-setup** - Create container and install GTM snippet
3. **gtm-tags** - Configure Google Analytics 4 tag
4. **gtm-triggers** - Set up page view trigger
5. **gtm-debugging** - Test with Preview mode

### E-commerce Tracking Implementation

1. **gtm-datalayer** - Implement e-commerce data layer
2. **gtm-variables** - Create data layer variables for products
3. **gtm-tags** - Configure GA4 e-commerce tags
4. **gtm-triggers** - Set up custom event triggers
5. **gtm-debugging** - Validate data with Preview mode

### SPA (Single-Page Application) Tracking

1. **gtm-datalayer** - Implement SPA data layer pattern
2. **gtm-triggers** - Configure history change triggers
3. **gtm-variables** - Create custom JavaScript variables
4. **gtm-tags** - Set up virtual page view tracking
5. **gtm-debugging** - Test route changes

### GTM Container Optimization

1. **gtm-debugging** - Audit current configuration
2. **gtm-best-practices** - Review naming conventions and organization
3. **gtm-best-practices** - Optimize performance
4. **gtm-tags** - Clean up unused tags
5. **gtm-variables** - Consolidate duplicate variables

## Prerequisites

- Google account with access to Google Tag Manager
- Website or app to implement tracking on
- Basic understanding of HTML and JavaScript
- Access to website source code or CMS (for GTM snippet installation)

## Key Resources

**Official Documentation:**
- [Google Tag Manager Developer Guide](https://developers.google.com/tag-platform/tag-manager)
- [GTM Help Center](https://support.google.com/tagmanager)
- [GTM API Reference](https://developers.google.com/tag-platform/tag-manager/api/v2)
- [Community Template Gallery](https://tagmanager.google.com/gallery/)

**Expert Content:**
- [Simo Ahava's Blog](https://www.simoahava.com/) - GTM and GA4 expertise
- [Analytics Mania](https://www.analyticsmania.com/) - GTM tutorials

**Developer Tools:**
- [Google Tag Assistant](https://chrome.google.com/webstore/detail/tag-assistant-companion/jmekfmbnaedfebfnmakmokmlfpblbfdm) - Chrome extension for debugging
- [dataLayer Inspector+](https://chrome.google.com/webstore/detail/datalayer-inspector/kmcbdogdandhihllalknlcjfpdjcleom) - Chrome extension for data layer inspection

## Integration with Other Suites

This GTM suite integrates seamlessly with other marketplace toolkits:

- **GA Suite (ga-suite)** - Implement GA4 tracking via GTM
- **Shopify Developer (shopify-developer)** - GTM implementation on Shopify stores
- **Google Apps & Ads Script (google-apps-ads-script)** - Export GTM data to Sheets for reporting

## Skill Cross-References

All GTM skills reference each other for comprehensive workflows:

- **gtm-general** routes to all specialized skills
- **gtm-datalayer** works with **gtm-variables** for data extraction
- **gtm-tags** uses **gtm-triggers** for firing conditions
- **gtm-debugging** validates implementations across all skills
- **gtm-best-practices** provides optimization guidance for all skills
- **gtm-api** enables automation of configurations from all skills

## Environment Setup

### GTM Account Creation

1. Visit [tagmanager.google.com](https://tagmanager.google.com)
2. Create account (organization level)
3. Create container (website/app level)
4. Copy container snippet

### GTM Installation

**Standard Installation (all pages):**

```html
<!-- Google Tag Manager -->
<script>(function(w,d,s,l,i){w[l]=w[l]||[];w[l].push({'gtm.start':
new Date().getTime(),event:'gtm.js'});var f=d.getElementsByTagName(s)[0],
j=d.createElement(s),dl=l!='dataLayer'?'&l='+l:'';j.async=true;j.src=
'https://www.googletagmanager.com/gtm.js?id='+i+dl;f.parentNode.insertBefore(j,f);
})(window,document,'script','dataLayer','GTM-XXXXXX');</script>
<!-- End Google Tag Manager -->

<!-- Google Tag Manager (noscript) -->
<noscript><iframe src="https://www.googletagmanager.com/ns.html?id=GTM-XXXXXX"
height="0" width="0" style="display:none;visibility:hidden"></iframe></noscript>
<!-- End Google Tag Manager (noscript) -->
```

Replace `GTM-XXXXXX` with your container ID.

## Best Practices

### Container Organization
- Use descriptive naming conventions
- Organize tags with folders (if using GTM 360)
- Document complex implementations in notes
- Regular container audits

### Testing & Publishing
- Always test with Preview mode before publishing
- Use meaningful version names and descriptions
- Test on multiple browsers and devices
- Verify data in destination platforms (GA4, Ads, etc.)

### Performance
- Minimize custom HTML tags
- Use asynchronous loading where possible
- Consolidate similar tags
- Monitor page load impact

### Security & Privacy
- Implement consent management
- Sanitize user inputs in custom JavaScript
- Follow data privacy regulations (GDPR, CCPA)
- Regular security audits

## Troubleshooting

**Common Issues:**

1. **Tags not firing** → Use **gtm-debugging** skill
2. **Data layer errors** → Use **gtm-datalayer** skill
3. **Trigger conditions not working** → Use **gtm-triggers** skill
4. **Variable returning undefined** → Use **gtm-variables** skill
5. **Performance issues** → Use **gtm-best-practices** skill

## Version

Current version: **1.0.0** (Production Ready)

## Category

Analytics / Marketing / Tracking

---

**Created by:** Henrik Soederlund ([@henkisdabro](https://github.com/henkisdabro))
**Part of:** Claude Code Plugin Marketplace
**License:** Follow Google's terms of service for Tag Manager usage

## Planned Future Additions

- **Agents:** GTM specialist, GTM debugger, GTM implementation agents
- **Commands:** /gtm-init, /gtm-audit, /gtm-migrate, /gtm-test commands
- **MCP Servers:** Potential GTM API MCP server integration

Suggestions welcome via GitHub issues!
