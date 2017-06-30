# File Structure Requirements

## Directories and Files

The directories and files that make up the website shall be structured by the following rules:

* Web pages \(\*.html, \*.aspx\) shall be placed in directories named based on content and services
* Directories containing Webpages **must** have an index page
* All stylesheets \(\*.css, \*.less\) are placed directly in the /css/ or /less/ directory (no sub-directories)
* All images \(\*.jpg, \*.gif, \*.png\) are placed in the /images/ directory
* All server-side includes shall be placed directly in the /ssi/ directory (no sub-directories)
  * only use an SSI if the information is used on more than one page. 
  * use a descriptive filename for the include.html
  * how to insert:
  ```vbscript
  <!-- #include virtual="/ssi/include.html" -->
  ```
* All documents \(\*.pdf, \*.xlsx, \*.docx, etc\) shall be placed in the /documents/ directory
* The documents directory will be organized as follows: /documents/[division]/[service(optional)]
* New directories must be approved
* Not allowed: “Backup”, “index(2).html”, “PDFS”, “Text_PDF_Files”, "archive"
* All paths should be [root relative](https://github.com/OSHPD-WebTeam/Standards-Policies-Procedures/blob/master/File-Structure.md#root-relative-paths)

### Root relative paths
A root relative path begins with the '/' (forward slash)  in href statements.

Correct &#10004; | Incorrect &#10006;
------- | ---------
/documents/Admin/exams/7SHAC.pdf | index.html
/FDD/FAQ/index.html  | ../FAQ/index.html
/images/FDD/Logo.png | http://oshpd.ca.gov/FDD/index.html
