
# ClearPass Exchange: Check Point Firewall R80.10/20 & R80.30 and higher

![version 2020.01](https://img.shields.io/badge/Version-2020.01-brightgreen.svg "version 2020.01") ![type Extension Authorization Source](https://img.shields.io/badge/Type-Extension%20Auth%20Source-blue.svg "type Extension Auth Source") ![Aruba Security Group](https://img.shields.io/badge/Source-Aruba_Security-orange.svg "Aruba Security Group")

## Overview
Importing this XML will create the Context Server Actions allowing ClearPass to integrate with a Check Point firewall running software version R80.10/20 & R80.30.

1. If running R80.10 or 20, download the XML profile > [clearpass-exchange_checkpoint_csa_r80_10_20.xml](https://github.com/aruba/clearpass-exchange-snippets/raw/master/firewall/check-point/clearpass-exchange_checkpoint_csa_r80_10_20.xml). If running R80.30 or higher, download the XML profile > [clearpass-exchange_checkpoint_csa_r80_30.xml](https://github.com/aruba/clearpass-exchange-snippets/raw/master/firewall/check-point/clearpass-exchange_checkpoint_csa_r80_30.xml)

2. Open this file in your favorite editor

3. Use the Find and Replace feature of the editor to replace ```<<Check Point Firewall IP>>``` and ```<<Shared Secret>>``` with the actual values to be used for the integration (There are 3 such occurrences of each).

4. Save the file and import into ClearPass (Administration > Dictionaries > Context Server Actions, Import)

5. For sending Roles to Check Point where nested square-brackets is interpreted as nested arrays, download the SQL template and folow the directions in the Integration Guide to learn how to strip [] from default ClearPass Roles such as [User Authenticated].



## Download
[clearpass-exchange_checkpoint_csa_r80_30.xml](https://github.com/aruba/clearpass-exchange-snippets/raw/master/firewall/check-point/clearpass-exchange_checkpoint_csa_r80_30.xml)

[clearpass-sql_bracket-strip.xml](https://github.com/aruba/clearpass-exchange-snippets/raw/master/firewall/check-point/clearpass-sql_bracket-strip.xml)

## Current Version
2020.01 (2020-06-29)

## License and Other Information
Copyright (c) Hewlett Packard Enterprise Development LP. All Rights Reserved.

