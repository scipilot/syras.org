[< Back to SYRAS homepage](readme.md)

# Release History 

## v0.19 Second Beta (May 2020)

New Features

- **Screening Criteria Checklist** - this is a major feature addition described in detail in the Help Guides. 
- **SRA Dedupe** - a new deduplication matcher was implemented via SRA from Bond University which seems much more accurate than the previous "Title Search" method.
- **Remove Collaborator** - Admin can now remove a collaborator from the team, either before or after inviting them.
- **Enquiries Form** - there is now an "Enquiries" section under the Account screen. 

Improvements

- The dedupe review process was improved, especially with multiple-duplciates (triplicates etc).
- Dedupe is now a separate step from import to clarify the process, and allows more flexible workflows (e.g. importing several files before dedupe, or running dedupe twice).
- Collaborators can now jump to their screening progress, via links in the team table and via the screening page progress bar.
- Admin can now also view their Collaborators' screening progress summaries, which enables them to view the shortlist of accepted articles instead of using the export files. (Collaborators still cannot view each others' summaries.)
- The screening progress summary page layout itself was improved.
- Admin is now prevented from inviting themselves to the team, to prevent any confusion.
- Updates to the file importers should improve compatibility with RIS, Endnote, Medline etc.
- Various technical improvements

Fixes
- Notification messages sometimes appeared in the wrong tab, if multiple browser tabs were open for the same user.
- Email addresses were being treated as case sensitive which could lead to duplicate accounts and confusion.
- The issue which led to users seeing "Please close and re-open the project" has been addressed.

## v0.18 Initial Beta Updates (Feb 2020)

Since the release of the initial beta and the guides several improvements were made. 

New Features

- Project Invitations are now shown at the top of the Project List page, if you just log in without using the link in the email. This helps if the invitation emails get lost in spam.

General Improvements

- Screening Export tweaks:
  - Export no longer truncates the title at 50 chars
  - Added ".tsv" file extension
  - Clarified the export dialogue layouts and added more help contents
- Article Set Split tweak: spaced out the "XofY of Z" naming to "X of Y of Z" on request.
- Any user is now logged out after 30 minutes of idle inactivity. 
- Technical improvements (including restarts causing less disturbance to active users)


Fixes

- The "Review" links in the Screening Status page were broken while reviewing a split subset.
- The user preferences and project configuration for all logged-in users sometimes got lost during a project reboot, including after crash-recovery. This would display a warning to logout/in again. 
- Fixed the project home page locking up after assigning a new collaborator if someone had already started screening. 
- Fixed confusion in the dedupe review table where a multiple-duplicate (triplicate or more) could show the wrong title for the duplicates.

