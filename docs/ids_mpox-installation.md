# Mpox Surveillance packages - Insatllation Guide

Package version: 0.0.1
DHIS2 version: D2.40 (and above)
System default language: English

Components:
1. [IDS-MPOX Surveillance Aggregate package](#ids-mpox-surveillance-aggregate-package)
2. [IDS-MPOX Surveillance Dashboard package](#ids-mpox-surveillance-dashboard-package)
3. IDS-MPOX Case Surveillance - CRF (Case Report form) tracker
4. IDS-MPOX Case Surveillance - CIF (Case Investigation Form) tracker
5. IDS-MPOX - Complete package

## Installation

Installation of the modules consists of several steps:

1. [Selection](#selection-of-required-component) of the required component
2. [Preparing](#preparing-the-metadata-file) the metadata file.
3. [Importing](#importing-metadata) the metadata file into DHIS2.
4. [Configuring](#configuration) the imported metadata.
5. [Adapting](#adapting-the-tracker-program) the program after being imported

It is recommended to first read through each section of the installation guide before starting the installation and configuration process in DHIS2. Identify applicable sections depending on the type of your import:

1. Import into a blank DHIS2 instance
2. Import into a DHIS2 instance with existing metadata (eg. IDS or VPD packages).

The steps outlined in this document should be tested in a test/staging DHIS2 instance and only then applied to a production environment.

## Requirements

In order to install the module, a DHIS2 administrator user account is required.

Great care should be taken to ensure that the server itself and the DHIS2 application are well secured, access rights to collected data should be defined. Details on securing a DHIS2 system are outside the scope of this document, and we refer to the [DHIS2 documentation](https://docs.dhis2.org/).

## Metadata files

The **metadata reference** and **metadata json** files provide technical details on package version and content.
While not always necessary, it can often required to make certain modifications to the metadata file before importing it into DHIS2.

## Selection of required component

### IDS-MPOX Surveillance Aggregate Package

The package contains:
- 1 weekly data set
- 6 data elements
- 11 indicators
- 1 dashboard

It can be installed as a standalone package. The output data can be accessed on the dashboard that is included or integrated in other dashboards and reporting tools.

### IDS-MPOX Surveillance Dashboard package




