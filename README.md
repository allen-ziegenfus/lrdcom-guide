# Hitchhiker's Guide to Liferay.com
Providing insights into maintaining and updating Liferay.com.

## Table of Contents
1. [General](#general)
    - [Redirects](#redirects)
    - [SAML](#saml)
2. [Setting Up Local](#setting-up-local)
3. [Theme (osb-community-theme)](#theme)
4. [Portlets](#portlets)
    - [osb-www-asset-publisher-portlet](#osb-www-asset-publisher-portlet)
    - [osb-www-marketing-events-portlet](#osb-www-marketing-events-portlet)
5. [Microsites](#microsites)
6. [Landing Pages] (#landing-pages)

## General
### Redirects
### SAML

## Setting Up Local
- Get portal to link up with your SQL database by changing `portal-setup-wizard.properties` in '/bundles' with this line: 

    ```
    jdbc.default.url=jdbc:mysql://localhost/[your-database-name-here]?useUnicode=true&characterEncoding=UTF-8&useFastDateParsing=false
    ```

- Database dumps can be found here: 
https://files.liferay.com/private/lrdcom/ (log in with your LR user/pass)
- OSB community theme needs these to be deployed first in order to make it work:
    - hubspot-portlet
    - osb-www-hook
    - portal-compat-hook
    - marketplace-portlet

## Theme - osb-community-theme

## Portlets

### osb-www-asset-publisher-portlet

### osb-www-marketing-events-portlet

## Microsites

## Landing Pages



