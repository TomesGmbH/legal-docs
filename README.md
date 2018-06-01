# Legal documents for Idana
This repository contains the legal documents for Idana in all languages.

## Editing

### Legal Team

If you're a member of the legal team, it's easy to get started. First, make sure you're logged in with your Github account. When you have a change which you wish to make, simply find the `en-US.md` version of the document that you wish to change. Open it and press the `Edit` button. If you have never gone through this process before, you will be asked to "fork" the repository (you should).

On the edit page, you'll be presented with a "raw" version of the legal document. Edit the text you wish to change. When you are done editing, there will be a section at the bottom of the page to save your work. Under "Commit summary", enter a brief (tweet-length) description of the change(s) you're making. In the "Extended description" field, explain what the changes are and why they're needed. When you're done, commit your changes.

At this point, you'll be presented with a form to submit a pull request. The bottom section of the page will show all of the change you've made to the document, and all you should need to do is press the "Send Pull Request" button.

Once you've submitted a pull request, your colleagues can review the work under the Pull Requests tab on the right-hand side, and a contributor to the repo can merge your changes.

### Markdown
All available documents are written in the [Markdown syntax](https://guides.github.com/features/mastering-markdown/). This has several advantages:
* differences between the various version can be identified quickly using git
* Markdown can be converted easily into different required output formats

In some languages, the date format contains dots like `15. travnja 2014.` but this may end up as an ordered list according to the syntax. The workaround is using a backslash to escape a dot after the leading digit(s) like `15\. travnja 2014.`

### Localizers

As a localizer, you're encouraged to find and fix translation issues. All document translations should match the precise meaning in the corresponding `en-US.md` version of the document. Additionally, we're always interested in finding errors in markup, broken links, etc.

File a pull request that updates your locale's markdown file to match the `en-US.md` version as closely as possible. When you're done, submit a pull request. Someone at Mozilla will review your changes. If there are no problems, your changes will be merged.

## Required output formats
* HTML for the websites and the Idana Desktop App
* HTML with restricted tag set for the Idana Web App
* Plain text for the Idana Desktop App Installer

## Available documents and languages

### Deutsch
* [Allgemeine Geschäftsbedingungen (AGB) zur App Idana](idana-app/terms/de-DE.md)
* [Datenschutzerklärung zur App Idana](idana-app/privacy-policy/de-DE.md)

### Englisch
* [General Terms and Conditions for the Idana app](idana-app/terms/en-US.md)
* [Data protection policy for the Idana app](idana-app/privacy-policy/en-US.md)