# ClearPass Exchange: ClearPass SMTP

![version 2017.01a](https://img.shields.io/badge/Version-2017.01a-brightgreen.svg "version 2017.01a") [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) ![Aruba Security Group](https://img.shields.io/badge/Source-Aruba_Security_Group-orange.svg "Aruba Security Group")

## Overview

This is an enforcement profile and endpoint context server action configuration to send email messages via the SMTP server defined in ClearPass 'Messaging Setup'.

## Current Version

2017.01a (2017-12-07)

## Change Log

* 2017.01a (2017-12-07)
 _Minor cosmetic changes to documentation_
* 2017.01 (2017-12-04)
 _Initial Release. Tested with ClearPass 6.7.0_

## Requirements

This CSA can be used in ClearPass 6.7 and higher as it is dependent on the new EmailSend API endpoint added in 6.7.0

> **NOTE:** Full documentation for the EmailSend API endpoint is available in the ClearPass API Explorer, found at {{clearpass-fqdn}}/api-docs.

## Setup

### ClearPass: Importing Template

1. Download the enforcement profile export > [clearpass-exchange_clearpass-smtp_enfprof-csa.xml](clearpass-exchange_clearpass-smtp_enfprof-csa.xml)

2. Navigate to  **_Configuration » Enforcement » Profiles_**

3. Click **Import** at the top right, then browse to the downloaded XML file and click **Import**

This will import the Context Server Action and Enforcement profile (treat these as templates)

### ClearPass: Customization

1. Navigate to  **_Administration » Dictionaries » Context Server Actions_**, select the **Send Email** action and then click **Copy** to duplicate it

2. Give the CSA a new name to reflect it's use

3. On the *Content* tab, modify (or remove) the various values, then click **Save** to finish
> **NOTE:** An array must be used for 'to', 'cc_recipients', and 'bcc_recipients' regardless of how many values are being configured

4. Navigate to  **_Configuration » Enforcement » Profiles_**, select the **Send Email** enforcement profile and then click **Copy** to duplicate it

5. Give the enforcement profile a new name to reflect it's use

6. On the *Attributes* tab, change the **Action** attribute to the new Context Server Action and then click **Save**

## License and Other Information

Copyright (c) Hewlett Packard Enterprise Development LP. All Rights Reserved.

Licensed under the Apache License, Version 2.0 (the "License").

Author: @timcappalli, Aruba Security Group
Organization: Aruba, a Hewlett Packard Enterprise company
