---
sidebar_position: 2
title: Quickstart
description: "Set up CallVibe fast: create your organization account, connect a channel (calls, WhatsApp, email, or meetings), start the worker, and validate call data flow."
---

# Quickstart

Get CallVibe running in a few steps.

## 1. Create Your Account

- Go to Sign Up and create your organization account.
- Complete the business details step.
- Verify your email.
- Sign in at the login page.

:::note

Some new accounts need a quick verification before they can sign in. If you see "We're Reviewing Your Account", the CallVibe team will confirm your business details, usually within 1-2 business days. See [Account and Access](./user-guide/account-and-access.md#signup-and-approval).

:::

## 2. Connect an Integration

Open Settings > Integrations and connect one provider:

- A telephony provider such as SalesTrail, Smartflo, Exotel, Kaleyra, 8x8, Zadarma, RingCentral, Callyzer, Bonvoice, or Zoom Phone
- Incoming webhook, for any phone system that can send calls
- WhatsApp
- Email (Ascendia)
- Meetings (Fireflies, or the CallVibe Recorder Chrome extension)
- Upload Center, to import historical recordings

For full requirements, see [Integrations Overview](./integrations/overview.mdx). For each channel, see [Channels](/docs/category/channels).

## 3. Start Worker

After credentials are saved:

- Open the Worker card in Integrations
- Click Start worker
- Confirm status changes to running

:::tip

The worker starts only when at least one provider is configured, so complete step 2 before starting it. It is needed for calls from a phone provider. WhatsApp, email, and meetings do not need it.

:::

## 4. Validate Data Flow

- Open the Data health panel at the top of Integrations and click Check again
- Open Calls and verify recent records
- Open Overview and confirm summary metrics
- Open Outlook and Intelligence for trends and quality scores
- Open WhatsApp, Email, and Meetings to check those channels

## 5. Invite Team Members

- Open Team & access
- Invite users as owner or agent
- Map agent names for scoped access

Next: [Platform Navigation](./user-guide/platform-navigation.md)
