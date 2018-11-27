
# ClearPass Exchange: Check Point Firewall R80.XX

![version 2018.01](https://img.shields.io/badge/Version-2018.01-brightgreen.svg "version 2018.01") ![type Extension Authorization Source](https://img.shields.io/badge/Type-Extension%20Auth%20Source-blue.svg "type Extension Auth Source") ![Aruba Security Group](https://img.shields.io/badge/Source-Aruba_Security-orange.svg "Aruba Security Group")

## Overview
Importing this XML will create the Context Server Actions allowing ClearPass to integrate with a Check Point firewall running software version R80.XX

1. Download the XML profile > [clearpass-exchange_checkpoint_csa_r80.xml](https://github.com/aruba/clearpass-exchange-snippets/raw/master/firewall/check-point/clearpass-exchange_checkpoint_csa_r80.xml)
2. Open this file in your favorite editor
3. Use the Find and Replace feature of the editor to replace ```<<Check Point Firewall IP>>``` and ```<<Shared Secret>>``` with the actual values to be used for the integration (There are 3 such occurrences of each).
4. Save the file and import into ClearPass (Administration > Dictionaries > Context Server Actions, Import) 

## Download
[clearpass-exchange_checkpoint_csa_r80.xml](https://github.com/aruba/clearpass-exchange-snippets/raw/master/firewall/check-point/clearpass-exchange_checkpoint_csa_r80.xml)

## Current Version
2018.01 (2018-11-27)

## License and Other Information
Copyright (c) Hewlett Packard Enterprise Development LP. All Rights Reserved.

