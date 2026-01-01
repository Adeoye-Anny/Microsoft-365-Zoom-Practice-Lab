# Microsoft 365 + Zoom Practice Lab (Hands-on Project)

### Overview
In this lab, I practiced core Microsoft 365 apps (Outlook, Word, Excel, Teams, OneDrive) by simulating real help desk requests, then hosted and troubleshot Zoom meetings to resolve common audio/video issues. The goal was to build practical user-support experience I can explain clearly to recruiters.

### Lab Environment
  Device: Windows 11 PC (or VM)
### Tools used:
  * Microsoft 365: Outlook, Word, Excel, Teams, OneDrive
  * Zoom Desktop Client
  * Optional: Web browser (Edge/Chrome) for admin portals and test links

### Objectives
  * Handle typical end-user requests across Outlook, Word, Excel, Teams, and OneDrive.
  * Host a Zoom meeting and fix common meeting issues (no audio, bad mic, camera not working, screen share problems).
  * Document steps and capture proof screenshots for a GitHub portfolio.


# Part A: Microsoft 365 Simulated User Requests
### 1. Outlook: Email + Calendar Support Tasks
#### Task A1: Create email signature and apply it to new messages and replies
What I did
  * Opened Outlook.
  * Went to File → Options → Mail → Signatures.
  * Created a signature with my name, role, and phone format.
  * Set it as default for New messages and Replies/forwards.
  * Sent myself a test email to confirm it works.

✅ Screenshot to upload: Outlook signature settings showing the signature created and selected as default.
Filename suggestion: outlook-signature-default.png


#### Task A2: Fix “Outlook search not returning results”
What I did
  * Confirmed the user issue: searched a known email subject and got no results.
  * Checked indexing status:
    * Search bar → Search Tools → Indexing Status
  * If indexing was incomplete, I waited briefly and re-tested.
  * If still broken, I repaired Office:
    * Control Panel → Programs → Microsoft 365 → Change → Quick Repair
  Reopened Outlook and tested search again.

✅ Screenshot to upload: Indexing Status window OR the “Quick Repair” screen.
Filename: outlook-indexing-status.png or office-quick-repair.png


#### Task A3: Create a meeting invite and share availability
What I did
  * Opened Outlook Calendar.
  * Clicked New Meeting.
  * Added attendees and checked Scheduling Assistant.
  * Set time and sent invite.
  * erified the invite appeared on calendar.

✅ Screenshot to upload: Scheduling Assistant view showing attendees and time slots.
Filename: outlook-scheduling-assistant.png


### 2. OneDrive: File Sync + Sharing Troubleshooting
#### Task B1: Confirm OneDrive is syncing correctly
What I did
  * Clicked the OneDrive cloud icon in the system tray.
  * Opened Help & Settings → Settings.
  * Confirmed the correct account is signed in.
  * Tested sync:
    * Created a folder OneDrive-Lab
    * Added a small file
    * Confirmed green check marks (synced)
✅ Screenshot to upload: OneDrive tray panel showing “Up to date” and the account name.
Filename: onedrive-up-to-date.png


#### Task B2: Fix “Files not syncing”
What I did
  * Checked common causes:
    * Internet connection stable
    * OneDrive not paused
    * Enough disk space
  * Restarted OneDrive:
    * Help & Settings → Close OneDrive
    * Relaunched OneDrive from Start menu
  * If still failing, I reset OneDrive:
    * Ran: onedrive.exe /reset
  * Re-tested sync by uploading a file again.

✅ Screenshot to upload: OneDrive error message (if any) OR after reset showing sync working.
Filename: onedrive-sync-fix.png


#### Task B3: Share a file with view-only permissions
What I did
  * Right-clicked a file in OneDrive folder.
  * Selected Share.
  * Set permission to Can view.
  * Copied the link and tested it in an incognito browser window.

✅ Screenshot to upload: Share dialog showing “Can view” setting.
Filename: onedrive-share-view-only.png


### 3. Word: Formatting + Recovery Scenario
#### Task C1: Fix document formatting (headings + consistent style)
What I did
  * Opened a messy document.
  * Applied Heading 1, Heading 2 styles consistently.
  * Used Format Painter to standardize text.
  * Inserted page numbers and updated margins.

✅ Screenshot to upload: Word Styles pane showing Heading styles applied.
Filename: word-styles-headings.png

#### Task C2: Recover an unsaved Word document
What I did
  * Opened Word.
  * Went to File → Info → Manage Document → Recover Unsaved Documents.
  * Restored the latest version and saved it properly.

✅ Screenshot to upload: Recover Unsaved Documents window.
Filename: word-recover-unsaved.png

### 4. Excel: Basic Help Desk Requests
#### Task D1: Fix #VALUE! and incorrect formulas
What I did
  * Opened an Excel sheet with calculated totals.
  * Identified #VALUE! caused by text values in numeric cells.
  * Cleaned data:
    * Removed spaces
    * Converted number-stored-as-text
  * Re-tested formulas and confirmed correct totals.

✅ Screenshot to upload: Before/after showing the corrected formula result.
Filename: excel-formula-fix.png

#### Task D2: Create a simple table + filter
What I did
  * Selected a dataset.
  * Pressed Ctrl + T to convert it into a table.
  * Enabled filters and tested sorting by a column.

✅ Screenshot to upload: Table with filter arrows visible.
Filename: excel-table-filters.png

### 5. Teams: Meeting and Chat Support
#### ask E1: Create a Teams meeting and share the link
What I did
  * Opened Teams.
  * Went to Calendar → New meeting.
  * Set title/time and copied the meeting link.
  * Joined from another device/browser to test.

✅ Screenshot to upload: Teams meeting details page showing the meeting link option.
Filename: teams-meeting-link.png

#### Task E2: Fix Teams mic not working
What I did

  * Checked Teams device settings:
    * Settings → Devices
  * Confirmed correct microphone selected.
  * Verified Windows privacy:
    * Settings → Privacy → Microphone access
  * Tested with a Teams test call (if available) or joined a meeting and checked mic meter.

✅ Screenshot to upload: Teams Devices settings showing selected mic/speaker.
Filename: teams-device-settings.png

# Part B: Zoom Hosting + Troubleshooting
### 1. Hosted a Zoom meeting (as the organizer)
What I did
  * Opened Zoom desktop app.
  * Clicked New Meeting.
  * Enabled Waiting Room and confirmed host controls.
  * Practiced:
    * Admit/remove participants
    * Mute all
    * Lock meeting
    * Share screen

✅ Screenshot to upload: Zoom host controls bar visible during meeting.
Filename: zoom-host-controls.png


### 2. Troubleshot common Zoom issues
#### Issue 1: “I can’t hear anyone”
Fix steps I used
  * Checked Zoom audio output:
    * Click ^ next to speaker icon → Select Speaker
  * Tested speaker audio.
  * Confirmed Windows volume mixer isn’t muted.

✅ Screenshot to upload: Audio menu showing speaker selection.
Filename: zoom-select-speaker.png

#### Issue 2: “My microphone isn’t working”
Fix steps I used
  * Clicked ^ next to mic → Select Microphone.
  * Tested mic input meter.
  * Checked Windows microphone privacy settings.
  * Closed apps that might be using the mic (Teams, browser tabs, etc.).

✅ Screenshot to upload: Microphone selection menu + input meter.
Filename: zoom-select-microphone.png

#### Issue 3: “Camera not working / black screen”
Fix steps I used
  * Zoom ^ next to camera → selected correct camera.
  * Checked if another app is using the camera (Teams, camera app).
  * Confirmed Windows camera privacy access is enabled.
  * Restarted Zoom and re-tested.

✅ Screenshot to upload: Zoom video settings showing selected camera preview.
Filename: zoom-video-settings.png

#### Issue 4: “I can’t share my screen”
Fix steps I used
  * Verified host permissions:
  * Host controls → Security → Allow participants to share (if needed)
  * Tested sharing the entire screen vs a single window.
  * Confirmed no restricted policy or conflicting app overlay.

✅ Screenshot to upload: Zoom Security menu settings related to screen sharing.
Filename: zoom-screen-share-permissions.png

### Results
By completing these tasks, I demonstrated practical end-user support skills across Microsoft 365 and Zoom, including configuring apps, troubleshooting common user issues, validating fixes, and documenting the process in a recruiter-friendly format.
