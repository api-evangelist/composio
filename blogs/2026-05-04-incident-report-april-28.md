---
title: "Incident Report: April 28th"
author: Composio
date: 2026-05-04
source_url: https://composio.dev/blog/incident-report-april-28
provider: Composio
tags:
  - Incident Report
  - Reliability
  - Webhooks
  - Triggers
---

# Incident Report: April 28th

**Author:** Composio
**Date:** May 4, 2026
**Reading Time:** 7 min

---

## Overview

Between April 28-30, Composio's platform experienced significant disruptions affecting core APIs and webhook triggers. The company reported approximately 53 minutes of cumulative API degradation and a 36-hour outage impacting roughly 700 customers using Slack, Outlook, Notion, and HubSpot webhook triggers.

## Root Cause

A database maintenance job responsible for cleaning processed messages from the trigger processing pipeline had been silently failing since April 6. The cleaner job encountered timeouts due to the table's unbounded growth, creating a self-reinforcing cycle that eventually degraded platform performance across all services.

## Key Timeline Events

- **April 28, 7:20 AM:** Initial API degradation detected
- **April 28, 12:48 PM:** Slack webhook triggers disabled as precautionary measure
- **April 29, ~7:00 AM:** Root cause identified
- **April 29, 7:56 AM:** Another disruption occurred during cleanup operations
- **April 30, 12:30 AM:** Migration to isolated database completed

## Remediation Actions Completed

The team has implemented several production changes:

- Moved webhook triggers to a dedicated, isolated database
- Created real-time monitoring dashboard for trigger health
- Audited all maintenance jobs and added missing monitoring

## Future Prevention Plans

- Replace the database-backed queue with a purpose-built message queue
- Establish mandatory status updates within 30 minutes of detecting issues
- Implement stricter approval processes for high-risk recovery operations

---

Source: <https://composio.dev/blog/incident-report-april-28>
