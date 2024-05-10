# Odoo Invoice XML Module

## Overview
This Odoo module facilitates the automatic generation, signing, and transmission of invoice XML files. It is designed to help businesses automate the processing of invoices and integrate with external systems requiring specific XML formats under the XADES_BES standard.

## Features
- **XML Generation**: Automatically generate XML representations of invoices.
- **XML Signing**: Digitally sign XML files using the XADES_BES standard.
- **Server Communication**: Send signed XML files to designated server endpoints and handle responses.

## Target Audience
- **Business Owners**: Automate invoice processing and ensure compliance with digital invoicing standards.
- **IT Administrators**: Simplify the management of invoice data transmission to external systems.
- **Developers**: Integrate and extend the module's capabilities within an existing Odoo setup.

## Prerequisites
- Odoo 17.0 or later
- Python 3.8 or later
- Access to server credentials for XML transmission

## Installation

### Dependencies
Ensure that the necessary Python dependencies are installed:
```bash
pip install lxml signxml requests
