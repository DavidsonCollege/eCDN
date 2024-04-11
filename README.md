# Davidson College Ersatz CDN

This repo hosts files (primarily images) for utilization in websites, SaaS solutions, and other business process across the College.

### Directory information

Directory | Purpose
--- | ---
college-branding | Official Davidson College logos and branding images
comms-data | json data used for the [campuscomms](https://campuscomms.davidson.edu/) website
departmental-logos | official college departmental logos
davidson-one | logos and icons used in the Davidson One app
oracle-cloud | logos and icons used in Oracle HCM and other Oracle Cloud services
eCards | images used in the Send Card Kuali application that sends eCards. These images are referenced in the HTML mailer
external-apps | non-Davidson application logos (facebook, twitter, zendesk, etc)
ai-innovation | logos and icons for AI Innovation Initiative


### Usage

The URL template for the images is:

`https://davidsoncollege.github.io/eCDN/{directory}/{file}`

`{directory}` = a directory listed above
`{file}` = file found in the directory

Example: https://davidsoncollege.github.io/eCDN/davidson-one/DavOne_NewsIcons_B.svg

### Notes

1. No files should be stored in the root directory
2. Do not nest directories. Only a top-level directory with images.

