
[![Runboat](https://img.shields.io/badge/runboat-Try%20me-875A7B.png)](https://runboat.odoo-community.org/builds?repo=OCA/bank-statement-import&target_branch=13.0)
[![Pre-commit Status](https://github.com/OCA/bank-statement-import/actions/workflows/pre-commit.yml/badge.svg?branch=13.0)](https://github.com/OCA/bank-statement-import/actions/workflows/pre-commit.yml?query=branch%3A13.0)
[![Build Status](https://github.com/OCA/bank-statement-import/actions/workflows/test.yml/badge.svg?branch=13.0)](https://github.com/OCA/bank-statement-import/actions/workflows/test.yml?query=branch%3A13.0)
[![codecov](https://codecov.io/gh/OCA/bank-statement-import/branch/13.0/graph/badge.svg)](https://codecov.io/gh/OCA/bank-statement-import)
[![Translation Status](https://translation.odoo-community.org/widgets/bank-statement-import-13-0/-/svg-badge.svg)](https://translation.odoo-community.org/engage/bank-statement-import-13-0/?utm_source=widget)

<!-- /!\ do not modify above this line -->

# OCA bank statement import modules for Odoo

This repository hosts additionnal parsers and import features for bank statements.

<!-- /!\ do not modify below this line -->

<!-- prettier-ignore-start -->

[//]: # (addons)

Available addons
----------------
addon | version | maintainers | summary
--- | --- | --- | ---
[account_bank_statement_clear_partner](account_bank_statement_clear_partner/) | 13.0.1.0.0 |  | Clear all partners in bank statement lines
[account_bank_statement_import_camt_oca](account_bank_statement_import_camt_oca/) | 13.0.1.1.2 |  | CAMT Format Bank Statements Import
[account_bank_statement_import_move_line](account_bank_statement_import_move_line/) | 13.0.1.0.0 | [![pedrobaeza](https://github.com/pedrobaeza.png?size=30px)](https://github.com/pedrobaeza) | Import journal items into bank statement
[account_bank_statement_import_oca_camt54](account_bank_statement_import_oca_camt54/) | 13.0.1.0.0 |  | Bank Account Camt54 Import
[account_bank_statement_import_ofx](account_bank_statement_import_ofx/) | 13.0.1.0.0 |  | Import OFX Bank Statement
[account_bank_statement_import_online](account_bank_statement_import_online/) | 13.0.1.0.1 | [![alexey-pelykh](https://github.com/alexey-pelykh.png?size=30px)](https://github.com/alexey-pelykh) | Online bank statements update
[account_bank_statement_import_online_paypal](account_bank_statement_import_online_paypal/) | 13.0.1.0.0 | [![alexey-pelykh](https://github.com/alexey-pelykh.png?size=30px)](https://github.com/alexey-pelykh) | Online bank statements for PayPal.com
[account_bank_statement_import_online_ponto](account_bank_statement_import_online_ponto/) | 13.0.1.0.1 |  | Online Bank Statements: MyPonto.com
[account_bank_statement_import_online_qonto](account_bank_statement_import_online_qonto/) | 13.0.1.0.0 |  | Online Bank Statements: Qonto
[account_bank_statement_import_online_transferwise](account_bank_statement_import_online_transferwise/) | 13.0.1.0.0 | [![alexey-pelykh](https://github.com/alexey-pelykh.png?size=30px)](https://github.com/alexey-pelykh) | Online bank statements for Wise.com (TransferWise.com)
[account_bank_statement_import_paypal](account_bank_statement_import_paypal/) | 13.0.1.0.1 |  | Import PayPal CSV files as Bank Statements in Odoo
[account_bank_statement_import_split](account_bank_statement_import_split/) | 13.0.1.0.0 | [![alexey-pelykh](https://github.com/alexey-pelykh.png?size=30px)](https://github.com/alexey-pelykh) | Split statements by date during import
[account_bank_statement_import_transfer_move](account_bank_statement_import_transfer_move/) | 13.0.1.0.0 |  | Bank Account Transfer Line
[account_bank_statement_import_txt_xlsx](account_bank_statement_import_txt_xlsx/) | 13.0.1.0.4 | [![alexey-pelykh](https://github.com/alexey-pelykh.png?size=30px)](https://github.com/alexey-pelykh) | Import TXT/CSV or XLSX files as Bank Statements in Odoo

[//]: # (end addons)

<!-- prettier-ignore-end -->

## Licenses

This repository is licensed under [AGPL-3.0](LICENSE).

However, each module can have a totally different license, as long as they adhere to Odoo Community Association (OCA)
policy. Consult each module's `__manifest__.py` file, which contains a `license` key
that explains its license.

----
OCA, or the [Odoo Community Association](http://odoo-community.org/), is a nonprofit
organization whose mission is to support the collaborative development of Odoo features
and promote its widespread use.
