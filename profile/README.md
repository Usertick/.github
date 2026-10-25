<!--
  Usertick: GitHub organization profile README
  Published copy: the Usertick/.github repo, profile/README.md
  (renders at https://github.com/Usertick)

  This file is the source copy. To publish it, copy it to profile/README.md
  in the Usertick/.github repo. Image and link URLs point at production
  (usertick.com and cdn.usertick.com) so they resolve on the profile page.
  Every number below is checked against the product catalog
  (docs/private/product/) when it changes.
-->

<p align="center">
  <a href="https://usertick.com">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://cdn.usertick.com/brand/Usertick-wo-logo.svg">
      <img alt="Usertick" src="https://cdn.usertick.com/brand/Usertick-bo-logo.svg" height="64">
    </picture>
  </a>
</p>

<h3 align="center">Ask the right questions.
Act on every answer.</h3>

<p align="center">
  Usertick asks short surveys on your site, in email, behind a link or on a QR code, collects every answer in one inbox and shows your team what people are saying.
</p>

<p align="center">
  <a href="https://usertick.com"><img src="https://img.shields.io/badge/Start_free-ff3c00?style=for-the-badge&logoColor=white" alt="Start free"></a>
  <a href="https://docs.usertick.com"><img src="https://img.shields.io/badge/Read_the_docs-1a1a1a?style=for-the-badge" alt="Docs"></a>
  <a href="https://www.npmjs.com/package/@usertick/snippet"><img src="https://img.shields.io/npm/v/@usertick/snippet?style=for-the-badge&label=npm&color=555" alt="npm"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Question_types-25-555" alt="25 question types">
  <img src="https://img.shields.io/badge/Trigger_types-22-555" alt="22 trigger types">
  <img src="https://img.shields.io/badge/Runtime_dependencies-0-3aaa6a" alt="No runtime dependencies">
</p>

---

## About Usertick

Usertick runs short surveys wherever your users are and collects every response in one place. Teams read the answers in an inbox and in dashboards, and send them on to the tools they already work in, so product decisions follow what users said.

Setup starts with one line on a site, and the same account covers every channel.

## What Usertick does

| | |
| --- | --- |
| **Collect** | Usertick shows the right question on the right page at the moment it matters, and the same survey can run in an email, behind a link or on a printed QR code. |
| **Understand** | Every answer arrives in one inbox with the dashboards your team needs, and each response shows where it came from, including the country, the source and the device. |
| **Act** | Usertick sends responses to Slack, Microsoft Teams, Jira, Linear, HubSpot and Google Sheets, and to your own systems through webhooks and the REST API. |

## Install the widget

To add Usertick to a site, paste this line on every page and replace `YOUR_SITE_ID` with the site's ID. The dashboard shows the line with the ID filled in under **Settings > Sites**, in the **Show code** item of the site's row menu.

```html
<script async src="https://cdn.usertick.com/s/YOUR_SITE_ID.js"></script>
```

The tag needs no build step. A React, Vue or other single page app can import the [npm package](https://www.npmjs.com/package/@usertick/snippet) instead:

```js
import Usertick from '@usertick/snippet';

Usertick.init({ site_id: 'YOUR_SITE_ID' });
Usertick.on('submit', ({ survey_id, answers }) => analytics.track('survey_submit', answers));
Usertick.trigger('checkout_completed');
```

The widget draws its surveys inside a closed Shadow DOM, so its styles and the site's styles never affect each other.

## Ask anywhere your users are

- **Website:** surveys appear while visitors use your site, as a popup, a side tab or embedded in the page.
- **Email:** the first question appears inside the email itself.
- **Link:** a shareable link opens the survey on its own page, anywhere you post it.
- **QR code:** a code on print or packaging opens the same page when scanned.

## Why teams choose Usertick

- **One tool for the whole loop.** Surveys, the inbox, dashboards and the integrations live in one product, so there is nothing extra to connect or keep in sync.
- **Predictable pricing.** Every plan has one flat monthly price and a monthly response limit for the whole organization. Past the limit, collection stops unless the organization has bought extra responses, which never expire and cost a fixed price each.
- **Light on the page.** The tag loads asynchronously, so the page doesn't wait for it, and the widget has no runtime dependencies.
- **Careful with data.** The widget sends responses to Usertick, and tells the site's own analytics tools about a completed response only when the site turns that on. What a site passes to `identify()` goes with a response and never with a page view, and a hash from the site's server verifies it. One switch turns identity off for a site, and another makes a survey anonymous.

## Security and engineering

| Trust and security | Engineering |
| --- | --- |
| HTTPS only, from the tag to the collector | No runtime dependencies |
| Two-factor sign-in and role-based access | 25 question types and 22 trigger types |
| An activity log on every plan | Skip logic, keyboard and screen reader support |

---

<p align="center">
  <a href="https://usertick.com"><b>Start free</b></a> ·
  <a href="https://docs.usertick.com">Docs</a> ·
  <a href="https://usertick.com/pricing">Pricing</a> ·
  <a href="https://usertick.com/careers">Careers</a> ·
  <a href="https://usertick.com/contact-sales">Talk to us</a>
</p>

<p align="center">
  <sub>© 2026 Usertick Ltd.</sub>
</p>
