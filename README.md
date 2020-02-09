# deleteOldGmailEmails

## What this script does

This script goes through your Gmail inbox and deletes old unlabelled emails with a certain subject or from a certain sender.

It only deletes the unlabelled ones so that adding a label is an easy way for you to mark an email as non-deletable, but you can
override this.

There are functions to delete emails with subjects or from senders older than a week and a month and you can easily add more.

You can run everything manually or set up triggers to do it regularly and automatically.

You have to write the subjects and senders you want to delete. The search matches subjects that start with the given subjects (useful for e.g. newsletters where the date varies) and senders that are equal to the given senders.

You'll receive emails telling you what's been deleted.

This script can also send you emails telling you which of the senders in your lists aren't sending emails any more and which senders are sending you too many emails, so that you can update your lists accordingly (or unsubscribe).

## How to use this script
- Copy the script
- Sign in to your Google account and go to https://script.google.com
- Paste the script
- Save it (save icon) and enter a project name e.g. "DeleteOldEmails"
- Optionally, rename the script so that it's not called "Code.gs" (click on the arrow next to the script name on the left)
- Add the subjects that you want to delete when they're older than a week to WEEK_SUBJECT
- Add the senders that you want to delete when they're older than a week to WEEK_FROM
- Add the subjects that you want to delete when they're older than a month to MONTH_SUBJECT
- Add the senders that you want to delete when they're older than a month to MONTH_FROM
- Save your changes

Now it's ready to run :)
- To run the functions manually, select the function you want to run in the dropdown menu at the top and hit the "Run" button.
- To set up triggers and run the functions automatically, go to "Edit" > "Current project's triggers" > "No triggers set up. Click here to add one now." and select which function you want to run when. You can add more functions clicking on "Add new trigger".

Note that you'll have to accept some permissions the first time it runs.
