# Cloud ERP

## Description
In this project, all details of AWS invoices (VAT, Declaration, Marketplace, Credit Note) issued monthly in PDF format to customers receiving "AWS reseller" service are parsed and converted into information according to company accounting rules, and transactions such as uploading the invoices to the FTP accounts of banks are carried out so that automatic payment instructions, if any, can be applied.

## Diagram
![diagram](erp.jpg)

## Tech Stack
* Coding
    * BASH
    * Python
    * Go
* Amazon Web Services
    * https://github.com/BeratNzp/project-diagrams/blob/master/erp.jpg
* Other
    * Bitbucket Pipeline
    * AWS CDK
    * Terraform
    * PostgreSQL