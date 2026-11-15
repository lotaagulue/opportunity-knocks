# Security policy

Opportunity Knocks is a Chrome extension for ESPN Fantasy Football. This
repository is for support and feedback; the extension's code is private.

## Reporting a vulnerability

Please **don't open a public issue** for a security problem. Report it
privately instead:

1. Go to this repository's **Security** tab.
2. Choose **Report a vulnerability** (GitHub's private reporting).
3. Describe what you found, how to reproduce it, and which version of the
   extension you're using (shown at the bottom of Settings).

You'll get a reply within 7 days. Fixes ship as a new extension version
on the Chrome Web Store, and you'll be credited in the release notes
unless you'd rather not be.

## In scope

- The extension itself (the side panel and its background script)
- How it handles your ESPN session, your AI provider keys and the data it
  saves on your device
- The public data file it downloads
  (`https://opportunity-knocks-data.vercel.app/v1/`)

## Out of scope

- ESPN's own services and API
- Your AI provider's service (Anthropic, OpenAI, Google or a custom one)
- Problems that need someone who already controls your computer or your
  Chrome profile

## What the extension does with your data

See the privacy policy: https://opportunity-knocks-data.vercel.app/privacy
