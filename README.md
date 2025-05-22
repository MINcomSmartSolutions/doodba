[![Doodba deployment](https://img.shields.io/badge/deployment-doodba-informational)](https://github.com/Tecnativa/doodba)
[![Last template update](https://img.shields.io/badge/last%20template%20update-v8.2.0-informational)](https://github.com/Tecnativa/doodba-copier-template/tree/v8.2.0)
[![Odoo](https://img.shields.io/badge/odoo-v18.0-a3478a)](https://github.com/odoo/odoo/tree/18.0)
[![LGPL-3.0-or-later license](https://img.shields.io/badge/license-LGPL--3.0--or--later-success})](LICENSE)
[![pre-commit](https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit&logoColor=white)](https://pre-commit.com/)

# Notes

- "main" branch is odoo 18.0 and will be used for ladeabrechnung (STROHM)
  - The images also will be tagged as 18.0 and latest if they are built from this branch
- "17.0" branch is odoo 17.0 and will be used for DynamicTariffs
  - The images also will be tagged as only 17.0 if they are built from this branch

## Modules

The aggregated list of modules that are finally installed in the image is:

| name                          |
| :---------------------------- |
| analytic                      |
| google_gmail                  |
| l10n_din5008                  |
| l10n_din5008_sale             |
| account_edi_ubl_cii           |
| spreadsheet                   |
| account                       |
| account_payment               |
| auth_signup                   |
| base                          |
| base_import                   |
| base_import_module            |
| base_install_request          |
| html_editor                   |
| l10n_de                       |
| onboarding                    |
| partner_autocomplete          |
| payment                       |
| phone_validation              |
| portal                        |
| privacy_lookup                |
| resource                      |
| resource_mail                 |
| sale_service                  |
| sale_sms                      |
| sms                           |
| snailmail                     |
| snailmail_account             |
| spreadsheet_dashboard_sale    |
| utm                           |
| web                           |
| web_editor                    |
| strohm_addon                  |
| spreadsheet_dashboard_account |
| auth_totp_mail                |
| mail                          |
| bus                           |
| base_iban                     |
| sale_edi_ubl                  |
| base_setup                    |
| product                       |
| payment_stripe                |
| sale                          |
| sale_management               |
| sale_async_emails             |
| sale_pdf_quote_builder        |
| http_routing                  |
| uom                           |
| web_tour                      |
| web_unsplash                  |
| iap                           |
| iap_mail                      |
| digest                        |
| mail_bot                      |
| spreadsheet_dashboard         |
| spreadsheet_account           |
| auth_totp_portal              |
| account_qr_code_sepa          |
| base_vat                      |
| auth_totp                     |
| sales_team                    |

# Structure

The doodba structure is quite complex and requieres a manual.

- [Doodba structure](structure.html)

See [General Doodba docs](https://github.com/Tecnativa/doodba) for more information.

# Doodba deployment

- Doodba is a Docker image for Odoo that is designed to be easy to use and extend our
  custom Odoo image easily.

- [Doodba copier template docs](https://github.com/Tecnativa/doodba-copier-template)
- [Doodba QA docs](https://github.com/Tecnativa/doodba-qa)
