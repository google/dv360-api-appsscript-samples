# DV360 API Samples in Apps Script

This repository contains usage samples for the Display & Video 360 (DV360)
API, written in Google Apps Script.

**DISCLAIMER**: The code samples shared here are _not_ formally supported
by Google and are provided only as a reference. See [LICENSE](LICENSE.md)
for more information.

Contributions are highly encouraged; see [CONTRIBUTING.md](CONTRIBUTING.md).

## Table of Contents

[Bulk Resource Management](#bulk-resource-management)

## Bulk Resource Management

This folder contains samples for bulk DV360 resource management using Google
Sheets. If you are interested in using this solution at scale, please get in
contact with your DV360 representative to get a copy of a template Spreadsheet
that is preconfigured for bulk management.

### Configuration and Setup

1.  Create a new Google Cloud Platform (GCP) Project that will be linked to your
    script.
2.  [Open the GCP console](https://console.cloud.google.com/) and navigate to
    _APIs & Services > Library_ and enable the _Display & Video 360 API_.
3.  Create an Apps Script project that is linked to a Google Spreadsheet by
    navigating to _Tools > Script Editor_ within the desired Spreadsheet.
    Alternatively open the script directly from the
    [Apps Script Project Dashboard](https://script.google.com/home/all).
4.  Within the Script Editor, navigate to _Resources > Advanced Google Services_
    and toggle the switch for _Google Sheets API_.
5.  Within the Script Editor, navigate to _Resources > Cloud platform project_
    and link the GCP project created in step #1 using its _project number_. You
    can retrieve the project number ny navigating to the GCP console's _Home_
    and copying the number out of the _Project info_ card.
