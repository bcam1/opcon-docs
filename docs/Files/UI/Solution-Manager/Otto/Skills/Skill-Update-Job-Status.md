---
lang: en-us
title: Otto Skill - Update Job Status
viewport: width=device-width, initial-scale=1.0
---

# Update Job Status

The **Update Job Status** skill allows you to perform an action to update the status of a daily job on a specified schedule for a specified date.

## Skill Details

### Parameters

The **Update Job Status** skill requires the following parameters:

- **Action**: The action to update the job status - must be one of: `release`, `restart`, `forcerestart`
- **Date**: The specified date for the job.
- **Job Name**: The name of the job to update.
- **Schedule Name**: The name of the daily schedule for the updated job.

## Example

`Update job TestJob to status "released" on schedule TestSchedule for today`

`Please update the job with the name "TestJob" to the status "released" on the schedule "TestSchedule" for today.`
