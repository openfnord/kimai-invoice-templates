# Kimai Invoice-Templates

A place for sharing your Kimai invoice templates with the community, a place to find ideas.

This repository contains two branches:
- the [main branch for Kimai 2.x](https://github.com/kimai/invoice-templates)
- the [v1 branch for Kimai 1.x](https://github.com/kimai/invoice-templates/tree/v1)

## List of all templates

### PDF

- [DIN 5008 compliant template](din5008-invoice)
- [Invoice grouped by projects](grouped-by-projects)

### HTML

- [Example](html-example)

### Docx

- [Company invoice](docx-company)

### Excel

- [Excel letter](xlsx-letter-de)
- [Basic spreadsheet](xlsx-simple)

### CSV

- [Export](export)

### OpenOffice Spreadsheet

- [Basic spreadsheet](oo-spreadsheet)

### Programmatic

- [JSON](data-transfer)
- [XML](data-transfer)
- [TEXT](data-transfer)

## Installation

If not existing, create the directory `var/invoices/` in your Kimai installation.

```
cd /var/www/kimai/var/
mkdir invoices
```

Then copy the files from any subdirectory into this new directory (`/var/www/kimai/var/invoices/`).

They should show now up in your "Invoice templates" administration, in the **"Invoice document"** dropdown.

Please read the official documentation at [https://www.kimai.org/documentation/invoices.html](https://www.kimai.org/documentation/invoices.html) to find out more about building your own invoice templates.

## Sharing your template

- Fork this repository
- Create a new branch
- Add a new subdirectory with a unique name of your template
- Add a `README.md` file explaining your template
- Add a `screenshot.png` (or .jpg) image if possible
- Add the template file to the directory
- Edit the main [README.md](https://github.com/kimai/invoice-templates/blob/main/README.md) and add a link to your new directory under the appropriate format section
- Commit and Push your changes
- Open a PR
- Wait for feedback and merge 😃

By submitting your template you accept that it will be shared under the MIT license.


## Other forked Repos for this project

Hopefully I found all repos of the Kimai project so the whole eco system is preserved now for further development

- https://github.com/openfnord/kimai-android  (android app for kimai)
- https://github.com/openfnord/kimai (web based kimai server)
- https://github.com/openfnord/kimai-invoice-templates (templates for kimai server, this)
- https://github.com/openfnord/kimai-docker (dockerized kimai web based server)
- https://github.com/openfnord/kimai-api-php (api for web based server)

- https://github.com/openfnord/kimai-homepage (homepage of kimai project)
- https://github.com/openfnord/kimai-images (logos and images) 
