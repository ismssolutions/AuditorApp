# Independant Auditor Application

## Description
Tool for independent auditors to verify that document and document package hashes are valid.  Based upon a previously entered hash on the bitcoin blockchain 

## Application Functionality
The application requires both a _Document_ and _Transaction ID_. Both should be supplied by ISMS's Vendor Verifier application. The application will produce a SHA-256 Hash from the document supplied and extract the hash from the bitcoin transaction supplied. Both hashes are compared and if they match the document is validated. 

## Dependancies
- Javascript enabled browser
- jquery (v 1.12.4)
- Stanford Javascript Crypto Library (v 1.0.6)
- Bootstrap (3.3.7)
- Valid Catenis Enterprise bitcoin transaction entries

## Prerequisites
- BlockTrail API access Key (https://www.blocktrail.com/dev/signup)
- ISMS provided Bitcoin Blockchain Transaction ID
- ISMS provided Document (or document package)

## Usage
Clone repository and run on any desktop computer using a browser with JavaScript enabled.

## Requirement Prior to Running The Application

Search for 'Replace with your own Blocktrail API key' and updated the value in the source of the AuditorTool.html file. look for the following line:
```shell
DocValidator.blkTrailApiKey = 'replaceWithYourKey';
```
## License

This Independant Auditor Application is released under the [MIT License](LICENSE). Feel free to fork, and modify!

Copyright © 2017, ISMS written by Blockchain of Things Inc.