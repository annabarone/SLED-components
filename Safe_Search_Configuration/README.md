# Safe Search Configuration Skillet Components

This directory houses skillets regarding K-12-specific configurations. The configurations include: 

### Common K-12-specific configuration base objects  
This skillet configures the following components:

    * Deny tag
    * Team Cymru Bogons EDLs
    * Approved Search Engines and Block Search Term Custom URL Categories
    * Outbound URL Sanctioned Search URL Filtering Security Profile
    * Non-Safe-Search Security Profile Group
    * Block Quic Security Rule
    * Critical Education Site No-Decrypt Decryption Rule
    * Safe Search URL Block Response Page
    * SLED WildFire verdicts for SMTP Report
    * SLED Clients sinkholed Report

### Safe Search Enforcement components
The DNS Proxy Safe Search skillet configures the following components:

    * Sanctioned DNS Server Addresses and Address Groups
    * DNS Proxy with Safe Search Network Component 
    * An Allow Outbound DNS To Sanctioned Servers Security Rule
    * An Allow Outbound To FW DNS Proxy Security Rule
    * A Block Outbound DNS Security Rule
    * An Allow Outbound Web Browsing to/from Search Engines Security Rule

The Local DNS CNAME Safe Search skillet configures the following components:

    * Local DNS Server Address and Address Groups
    * An Allow Outbound DNS To Internal Servers Security Rule
    * An Allow Inbound DNS To Internal Servers Security Rule
    * A Block Outbound DNS Security Rule
    * An Allow Outbound Web Browsing to/from Search Engines Security Rule

The SSL Decryption Safe Search skillet configures the following components:

    * Sanctioned DNS Server Addresses and Address Groups
    * An Allow Outbound DNS To Sanctioned Servers Security Rule
    * A Block Outbound DNS Security Rule
    * An Allow Outbound Web Browsing to/from Search Engines Security Rule
    * Approved Search Engine decrypt Decryption Policy

### A Security Rule restricting traffic to/from CA, MX, US, and Cloud EDLs 
This skillet configures the following components:

    * Microsoft, Amazon, and Google Cloud EDLs
    * CA, MX, US, and Cloud EDLs Inbound Restricting Security Rule
    * CA, MX, US, and Cloud EDLs Outbound Restricting Security Rule

### SAML Provider no-decrypt policy 
This skillet configures the following components:

    * RFC1918 Addresses for 10.0.0.0/8 and 172.16.0.0/12 subnets
    * SAML Provider Custom URL Category
    * SAML Provider No-Decrypt Decryption Policy

### Chromebook-specific website no-decrypt policy
This skillet configures the following components:
    
    * Chomebook Bypass Custom URL Category
    * Chromebook Bypass No-Decrypt Decryption Policy