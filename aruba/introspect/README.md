
# Aruba ClearPass and IntroSpect Integration

![version 2018.01](https://img.shields.io/badge/Version-2018.01-brightgreen.svg "version 2018.01") ![type Configuration Profiles](https://img.shields.io/badge/Type-Configuration%20Profiles-blue.svg "type Configuration Profiles") ![Aruba Security Group](https://img.shields.io/badge/Source-Aruba_Security-orange.svg "Aruba Security Group")


## Overview
Importing this XML will create all the required enforcement profiles, context server actions and also define the endpoint context server.

1. Download [clearpass-integration_aruba-introspect_all-profiles.xml](https://github.com/aruba/clearpass-exchange-snippets/raw/master/aruba/introspect/clearpass-integration_aruba-introspect_all-profiles.xml)

2. Open this file in your favorite editor

3. Use the Find and Replace function to replace __`<<introspect-fqdn-or-ip>>`__ with the actual FQDN or IP address of the IntroSpect Analyzer (there are 14 occurences in the file)

4. Replace __`<<introspect-integration-password>>`__ and __`<<introspect-integration-email>>`__ with actual user details created in IntroSpect (see the section “User Account on IntroSpect” of the Integration Guide)

5. Save the file and import into ClearPass (Configuration > Enforcement > Profiles, Import)

## Download
[clearpass-integration_aruba-introspect_all-profiles.xml](https://github.com/aruba/clearpass-exchange-snippets/raw/master/aruba/introspect/clearpass-integration_aruba-introspect_all-profiles.xml)

## Related Documentation
Integration Guide coming soon!

## Current Version
2018.01 (2018-08-23)


## License and Other Information
Copyright (c) Hewlett Packard Enterprise Development LP. All Rights Reserved.

