[< Back to SYRAS homepage](readme.md)

# Release History 

## v0.19.17 - Second Beta (July 2020)

New Features

- **Screening Criteria Checklist** - this is a major feature addition described in detail in the Help Guides. 
- **SRA Dedupe** - a new deduplication matcher was implemented via SRA from Bond University which seems much more accurate than the previous "Title Search" method.
- **Remove Collaborator** - Admin can now remove a collaborator from the team, either before or after inviting them.
- **Enquiries Form** - there is now an "Enquiries" section under the Account screen. 
- **Agreed Includes** - The set of agreed "include" articles is now generated at the same time as the Disagreements Set. 
    This allows an administrator to export the initial set of positive articles, 
    then after disagreements review add the final set of re-agreed positive articles for export. 
- **Export All** - there is now an option to export all articles from a set, via a new tab in the export dialogue.
    This allows you to download the new "Agreed Includes" set, which you can then add to the final "includes" from a disagreements re-review.
    Previously it wasn't possible to export the final set of overall agreed "includes".
    This enables you to do it in two steps, while a single step export will be developed in a future version.
- **Import History** - the project page now keeps a list of the files imported so far. 
    This helps you keep track when importing many files from different sources.

Improvements

- The dedupe review process was significantly improved, especially with multiple-duplicates (triplicates etc).
- Dedupe is now a separate step from import to clarify the process, and allows more flexible workflows (e.g. importing several files before dedupe, or running dedupe twice).
- Dedupe has been sped up, and can handle a larger corpus (depending on the available hosting resources).
  (The exact title match was recorded in testing to achieve 15 million matches per second, meaning 10,000 articles could be checked in 3 seconds. 
  The deeper dedupes take much longer than this.).
- Dedupe now has a "progress" page showing how far it has got, and how long it will take. You can even log out and return and the dedupe will continue running in the background.
  The project page has been updated to show different controls, depending on whether there is a dedupe running, both to inform the user
  but also to prevent two dedupes being run at once. 
- Collaborators can now jump to their screening progress, via links in the team table and via the screening page progress bar.
- Admin can now also view their Collaborators' screening progress summaries, which enables them to view the shortlist of accepted articles instead of using the export files. (Collaborators still cannot view each others' summaries.)
- The screening progress summary page layout itself was improved.
- Admin is now prevented from inviting themselves to the team, to prevent any confusion.
- Updates to the file importers should improve compatibility with RIS, Endnote, Medline etc.
- Various technical improvements including speed and performance.
- The "Export Includes" tab in the Article Set Export dialogue now warns you if there is nothing to export, to reduce confusion. 

Fixes
- Notification messages sometimes appeared in the wrong tab, if multiple browser tabs were open for the same user.
- Email addresses were being treated as case sensitive which could lead to duplicate accounts and confusion.
- The issue which led to users seeing "Please close and re-open the project" has been addressed.
- Fixed authors and keywords lists getting merged into one comma-separated field during import
- Fixed Endnote XML export crashing, due to the above.
- Removed the extra .txt on the export files and set .ris or .xml as appropriate.


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

