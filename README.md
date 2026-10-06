# CTA Website Migration – Web Pages

This repository contains HTML pages for the Canadian Transportation Agency (CTA) website migration from Drupal to Adobe Experience Manager (AEM) on Canada.ca.

The pages follow the new website sitemap, starting with `home.html` and continuing through sections such as Accessible Transportation and other CTA content areas.

This repository provides one place to keep the HTML organized and updated throughout the migration.

## Repository Structure

Because the CTA website is bilingual, English and French pages will be kept in separate folders.

Example structure:

```text
├── en/
│   ├── home.html
│   ├── accessible-transportation/
│   ├── consultations/
│   ├── news/
│   ├── about-us/
│   └── ...

├── fr/
│   ├── home.html
│   ├── transports-accessibles/
│   └── ...
└── README.md
```

- `en/` – English pages
- `fr/` – French pages
- Folders and HTML files will follow the website sitemap where possible.

## Page Inventory

This section will be updated as pages are added or moved. It provides a quick reference for finding the English and French versions of each page.

### Main Pages

| Page | English | French | Status |
| --- | --- | --- | --- |
| Home | `en/home.html` | `fr/accueil.html` | In progress |
| Accessible Transportation | `en/home/accessible-transportation.html/` | `fr/accueil/transports-accessibles.html/` | In progress |
| Consultations | `en/home/consultations.html` | `fr/accueil/consultations.html` | Complete |
| About us | `en/home/about-us.html` | `fr/accueil/a-propos-de-nous.html` | Complete - need updated images |


### Accessible Transportation

| Page | English | French | Status |
| --- | --- | --- | --- |
| Accessible Transportation | `en/accessible-transportation.html/` | `fr/transports-accessibles.html` | In progress |
| Accessible transportation Guidance and Resources | `en/accessible-transportation/guidance-and-resources.html` | `fr/transports-accessibles/documents-orientation-et-ressources.html` | Complete |


### National transportation system

| National transportation system | `en/home/national-transportation-system.html/` | `fr/accueil/reseau-de-transport-national.html` | In progress |


### Complaint and dispute resolution

| Complaint and dispute resolution | `en/home/complaint-and-dispute-resolution.html/` | `fr/accueil/plainte-et-reglement-des-differends.html` | In progress |


### Decisions and determinations

| Decisions and determinations | `en/home/decisions-and-determinations.html/` | `fr/accueil/decisions-and-determinations.html` | In progress |


### Compliance monitoring and enforcement

| Compliance monitoring and enforcement | `en/home/compliance-monitoring-and-enforcement.html/` | `fr/accueil.html/surveillance-conformite-et-application-de-loi.html` | In progress |
| Compliance monitoring and enforcement | `en/home/compliance-monitoring-and-enforcement/monetary-penalty-framework.html/` | `TBD` | In progress |

### Consultations

| Consultations | `en/home/consultations.html/` | `fr/accueil/consultations.html` | In progress |


## Organization

When adding pages:

1. Follow the new website sitemap.
2. Place English content in `en/`.
3. Place French content in `fr/`.
4. Keep related pages grouped in their appropriate section folders.
5. Add new pages to the **Page Inventory** above.
6. Update files as content is reviewed and prepared for AEM.

## Status

🚧 **Work in progress**

The repository structure, HTML files, and page inventory will continue to be updated throughout the migration.

**Drupal → AEM / Canada.ca**
