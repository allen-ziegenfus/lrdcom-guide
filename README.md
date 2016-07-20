# Hitchhiker's Guide to Liferay.com
Providing insights into maintaining and updating Liferay.com.

## Table of Contents
1. [General](#general)
2. [Templates](#templates)
3. [Structures](#structures)
4. [Setting Up Local](#setting-up-local)
5. [Theme (osb-community-theme)](#theme)
6. [Portlets](#portlets)
    - [osb-www-asset-publisher-portlet](#osb-www-asset-publisher-portlet)
    - [osb-www-marketing-events-portlet](#osb-www-marketing-events-portlet)
7. [Microsites](#microsites)
8. [Landing Pages] (#landing-pages)

## General

## Templates

## Structures

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



