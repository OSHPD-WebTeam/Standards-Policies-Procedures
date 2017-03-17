# File Structure Requirements

## Directories and Files

The directories and files that make up the website shall be structured by the following rules:

- Web pages \(\*.html, \*.aspx\) shall be placed in directories named based on content
- Directories containing Webpages **must** have an index page
- All stylesheets \(\*.css, \*.less\) are placed directly in the /css/ or /less/ directory (no sub-directories)
- All images \(\*.jpg, \*.gif, \*.png\) are placed in the /images/ directory
- All server-side includes shall be placed directly in the /ssi/ directory (no sub-directories)
- All documents \(\*.pdf, \*.xlsx, \*.docx, etc\) shall be placed in the /documents/ directory
- The documents directory will be organized as follows: /documents/[division]/[service(optional)]
- New directories must be approved
- Not allowed: “Backup”, “index(2).html”, “PDFS”, “Text_PDF_Files” 

## Naming Conventions

Directories and files are named with strict, yet flexible conventions.

- All files and directories shall be named with full words, no abbreviations allowed
- All file and directory names shall use a hyphen to separate words
- Spaces, underscores, and camelCase are not allowed
- Names of directories are based on the structure of services and content
- Names of documents must have the date first, formatted as follows: YYYYMMDD-[File-Name].pdf

Please see the table below for examples

Correct | Incorrect
------- | ---------
/Hospital-Financial-Data/ | /HospFinData/
------------------------- | /Hospital_Financial_Data/
------------------------- | /HospitalFinancialData/
------------------------- | /Hospitalfinancialdata/
/20170211-Document-X.pdf | /DocumentX_Dec2017.pdf
------------------------ | /Jan17DocumentX.pdf
