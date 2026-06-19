<!--
  Usertick — GitHub organization profile README
  Lives in the special repo:  Usertick/.github  →  profile/README.md
  (Renders at https://github.com/Usertick)

  This file is the source copy. To publish: copy it to profile/README.md
  in the Usertick/.github repo. Image and link URLs point at production
  (usertick.com / cdn.usertick.com) so they resolve on the profile page.
-->

<p align="center">
  <a href="https://usertick.com">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://usertick.com/brand/Usertick-wo-logo.svg">
      <img alt="Usertick" src="https://usertick.com/brand/Usertick-bo-logo.svg" height="64">
    </picture>
  </a>
</p>

<h3 align="center">Ask anything, anywhere in your product. Then act on it.</h3>

<p align="center">
  Listen better, act faster, and build what truly matters.
</p>

<p align="center">
  <a href="https://usertick.com"><img src="https://img.shields.io/badge/Start_free-ff3c00?style=for-the-badge&logoColor=white" alt="Start free"></a>
  <a href="https://usertick.com/docs"><img src="https://img.shields.io/badge/Read_the_docs-1a1a1a?style=for-the-badge" alt="Docs"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Hosted_in-the_UK-555" alt="Hosted in the UK">
  <img src="https://img.shields.io/badge/UK_GDPR-compliant-3aaa6a" alt="UK GDPR compliant">
  <img src="https://img.shields.io/badge/Widget-~28KB_gzipped-555" alt="~28KB gzipped">
  <img src="https://img.shields.io/badge/Dependencies-zero-3aaa6a" alt="Zero dependencies">
</p>

---

## Hi 👋 We're Usertick

Your users keep telling you what to fix and what to build next. Usertick catches it on the page, in the flow, right when it happens, so you decide from what they actually said instead of guessing.

It starts as a one-line widget you drop on any site. It grows into one place where every answer lands, gets read, and gets sent on to the tools your team already works in.

## What Usertick does

Ask, listen, understand, and act, all in one place.

| | |
|---|---|
| **🗨️ Ask in the moment** | Pop the right question on the right page, exactly when it matters. |
| **📊 See what they mean** | Every answer in one place, with the dashboards your team needs. |
| **🌍 Know who's behind it** | Country, source and segment on every response, so a number always has a face. |
| **🔌 Act on it anywhere** | Send responses straight into the tools your team already works in. |

## Try it in one line

Drop this on any site. Replace `comp_abc123` with the company id from your dashboard:

```html
<script async src="https://cdn.usertick.com/loader.js" data-id="comp_abc123"></script>
```

That's it. No build step, nothing waiting on your developers. You can be reading real answers by the end of the day.

Running a React, Vue or other SPA? Import it instead:

```js
import Usertick from 'usertick';

Usertick.init({ company_id: 'comp_abc123' });
Usertick.on('submit', ({ survey_id, answers }) => analytics.track('survey_submit', answers));
Usertick.trigger('checkout_completed');
```

The widget renders inside a closed Shadow DOM, so it can't clash with your site and your site can't clash with it.

## Ask anywhere your users are

One setup covers every surface. The same survey runs on your site, in an email, behind a link, or on a printed QR code.

- **🌐 Website** — on the page, in the flow, the moment it matters.
- **✉️ Email** — embed the first question right inside your campaigns.
- **🔗 Link** — one shareable link, answers from anywhere.
- **📱 QR code** — scan from print or packaging to a branded survey.

## Why teams switch, and stay

- **One tool, not five.** Feedback, dashboards, and analytics live in one place. Nothing to stitch together or keep in sync.
- **Pricing that doesn't punish success.** We never charge more for getting more answers. Every paid plan comes with high response limits.
- **It stays out of the way.** Visitors barely notice it, it won't slow your page down, and it can't break your design.
- **Honest about data.** Privacy-first from the ground up, hosted in the UK, so you can listen to your users without the legal headaches.

## Built right

| Trust & security | Under the hood |
|---|---|
| UK-hosted (London), UK GDPR & DPA 2018 | ~28 KB gzipped, zero runtime dependencies |
| Encrypted in transit and at rest | 17 question types, 13 trigger types |
| Role-based access + tamper-proof audit log | Skip logic, full keyboard & screen-reader support |

## Pricing

Simple and predictable. What you pay grows with what you can do, not with how many people reply.

| Free | Pro | Business | Enterprise |
|---|---|---|---|
| **$0** | **$19**/mo | **$79**/mo | Contact sales |
| 200 responses/mo | Higher limits | Everything in Pro, more scale | Custom terms & security |

Yearly billing saves 20%. See the [full comparison →](https://usertick.com/pricing)

---

<p align="center">
  <a href="https://usertick.com"><b>Start free</b></a> ·
  <a href="https://usertick.com/docs">Docs</a> ·
  <a href="https://usertick.com/pricing">Pricing</a> ·
  <a href="https://usertick.com/careers">Careers</a> ·
  <a href="https://usertick.com/contact-sales">Talk to us</a>
</p>

<p align="center">
  <sub>Built for teams who'd rather know than guess. © 2026 Usertick UK Ltd.</sub>
</p>
