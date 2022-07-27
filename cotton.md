# Export Markdown tables from Google Sheets

The **Cotton Markdown Tables** add-on for Google Sheets is a new add-on that improves data sharing workflows.

## INSTALL OPTIONS

Coming soon.

## PERMSSIONS

In order to provide useful features, this add-on requires permissions from you. The following describes the purpose of permissions for this add-on:

  + **Google Drive:** 
    + *"See, edit, create, and delete all of your Google Drive files"*
    + This permssion allows the add-on to create a `Cotton Markdown Tables` folder and save Markdown table documents on your Google Drive. Additionally, this feature allows the add-on to jump directly to the saved Markdown file or download the Markdown file to your desktop. No user data sent to pffy-cloud.

  + **Google Sheets:**
    + *"View and manage spreadsheets that this application has been installed in"*
    + This permssion allows the add-on to only read the content of the spreadsheet that is currently open. Reading this information helps the add-on determine how to convert betweeen spreadsheet formatting and Markdown syntaxes. No user data sent to pffy-cloud.
 
  + **Script UI:**
    + *"Display and run third-party web content in prompts and sidebars inside Google applications"*
    + This permssion allows the add-on to provide user interaction for better usability. HTML, CSS, JavaScript and frameworks (e.g., jQuery) are implemented in the sidebar to help the add-on copy text to your clipboard, view saved files in your Google Drive, or download saved files to your desktop. No user data sent to pffy-cloud.

### Remove permissions

Permissions [can be removed][revoke] at any time from your Google Account.

## Features

### Export options

You have six options for exporting data from Google Sheets to Markdown tables:

  1. **Export active range:** The most basic selection in a spreadsheet.
  2. **Export all active ranges:** This allows you to multi-select seperate ranges and export all the converted tables into a single Markdown table document.
  3. **Export entire sheet:** This method includes all the data within a sheet without user selection.
  4. **Export all sheets:** This method exports each sheet in the spreadsheet and places them into a single document.
  5. **Export selected named ranges:** Choose which predefined named ranges you want and save all the generated Markdown tables in a single Markdown document.
  6. **Export all named ranges:** Combine all the named ranges in a spreadsheet into a single Markdown document.

<img title="Cotton Markdown tables add-on menu" src="png/cotton-menu.png" />


### Deliverables 

After you export Markdown tables with Cotton, you have three deliverables. 

You can:

  * Copy the Markdown text to clipboard
  * View the Markdown file in Google Drive
  * Download the Markdown file to your desktop

<img title="Cotton Markdown tables add-on prompt" src="png/cotton-prompt.png" />


## Privacy Policy

  + [https://a.pffy.dev/about/privacy][privacy]

## Terms of Service

  + [https://a.pffy.dev/about/terms][terms]

## Compliance

The Cotton Markdown Tables spreadsheet editor add-on is free. Printing this web page (either as paper for PDF) and retaining a copy for your records is sufficient documentation for your organization's site license or domain license.

## Disclaimers

Google Sheets, Google Drive, and other Google software or features are trademarks of Google, an Alphabet company. jQuery belongs to the OpenJS Foundation and jQuery contributors.

[revoke]: https://myaccount.google.com/permissions
[terms]: https://a.pffy.dev/about/terms
[privacy]: https://a.pffy.dev/about/privacy

{% include footer.md %}
