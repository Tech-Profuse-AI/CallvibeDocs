---
sidebar_position: 1
title: Calls
description: "What the CallVibe Calls page shows: every call with its customer, agent, sentiment, quality score, category, and recording, plus filters and the call detail view."
---

# Calls

The **Calls** page lists every call your team has made or received, with the AI's analysis next to each one. Use it to find a call, check how it went, and listen to it. Open it from Calls in the sidebar. At the top right, pick the period (for example Last 7 days) and use **Export** to download the list.

<ThemedScreenshot
  alt="Calls page"
  light="/img/calls-page.png"
  dark="/img/calls-page.png"
/>

## What You See

The list is titled **Call records** and shows how many calls match your filters. Use **Columns** to choose which columns to show. Each row is one call, with these columns:

- **Customer:** Who the call was with, with their number underneath.
- **Agent:** The team member on the call.
- **Call:** The direction (Inbound or Outbound) and whether it was Answered.
- **Sentiment:** How the customer felt during the call.
- **Quality:** The AI's score for the call, shown out of its maximum, for example 47/50.
- **Category:** The type of call, such as a sales enquiry or a support request.
- **AI status:** The outcome the AI gave the call, such as Appointment Booked or Needs Attention, or whether it has been analysed yet.
- **Source** and **Channel:** Where the call came from.
- **When** and **Duration:** The time of the call and how long it lasted.
- **Recording:** Whether the audio is available to play.

## Find a Call

The main filters sit at the top: **Search** (customer, number, or agent), **Direction** (All, Inbound, Outbound), **Sentiment**, and **Agent**. Select **More filters** for the rest. Your active filters show as small tags above the list, and you can remove each one.

All filters:

- **Search** by customer, number, or agent.
- **Direction:** Inbound or Outbound.
- **Outcome:** Answered or Unanswered.
- **Sentiment**, **Agent**, **Category**, **Channel**, and **Provider**.
- **Recording:** Calls with or without audio.
- **Follow-up:** Pending, In progress, or Done.
- **Flagged:** Only calls the AI flagged for attention.
- **Quality at least** and **Quality at most:** A score range.

## Open a Call

Click a call to open its detail view. It shows:

- **Call details:** Agent, time, duration, channel, number, and call ID.
- **AI analysis:** What the AI heard on the call, such as the summary, sentiment, category, and the other insights you set up in [AI Insights](../admin/ai-insights.md).
- **Follow-up:** What the call asked someone to do next, and its status.
- **Transcript:** The full conversation, with the recording to play back.

Use the previous and next arrows to move through calls without going back to the list.

## What You Get From It

- A quick view of how each call went, without listening to it.
- Calls that need attention, through sentiment, quality, and the Flagged filter.
- A follow-up on every call that needs one.
- Call numbers across your team on **Overview**, and quality trends on **Intelligence**.
- Calls shown on the contact's timeline, with their chats, emails, and meetings.

To bring calls in, see [Integrations Overview](../integrations/overview.mdx). To check calls are arriving, see [Data Health](../integrations/overview.mdx#data-health).
