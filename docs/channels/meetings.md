---
sidebar_position: 4
title: Meetings
description: "How to bring meetings into CallVibe with Fireflies or the CallVibe Recorder, and use them."
---

# Meetings

Meetings are your online calls with customers, on Google Meet, Microsoft Teams, or Zoom, with a transcript and notes. There are two ways to bring them in. Both appear on the same **Meetings** page.

## Connect Fireflies

1. Open Settings > Integrations > Meeting providers > Fireflies.
2. Paste your Fireflies API key and connect. A URL and a secret appear.
3. In Fireflies, open Integrations > Webhooks. Paste the URL and the secret, and choose the event for when a meeting's notes are ready.
4. In CallVibe, select **Import last 30 days** to bring in earlier meetings.

## Connect the CallVibe Recorder

The CallVibe Recorder is a Chrome extension. It records your meeting audio without adding a bot to the meeting.

1. Install the extension in Chrome.
2. Open it and select **Connect to CallVibe**.
3. On the CallVibe page that opens, check the code matches the one in the extension, and approve.
4. Join your meeting. Google Meet and Teams record by themselves if your owner turned that on. Otherwise, click the CallVibe icon to record. Zoom always needs the click.

Owners set the recording rules in Settings > Meeting recorder. See [Meeting Recorder](../admin/meeting-recorder.md).

## Use

- Open **Meetings** in the sidebar to see your meetings.
- Open a meeting to read the transcript, key points, decisions, and action items.
- Meetings are linked to the contacts who were invited.
- Owners see every meeting. Other users see the meetings they recorded.
- Set what the AI looks for in meetings in Settings > AI Insights > Meetings.

:::note

Meeting minutes count towards your usage, the same as calls.

:::
