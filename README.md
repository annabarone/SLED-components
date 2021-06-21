# SLED Skillet Components

This repository houses skillets regarding SLED-specific configurations. The configurations include: 

    * Common K-12-specific configuration base objects  
    * DNS Proxy, Local DNS CNAME, and SSL Decryption Safe Search Enforcement components
    * A Security Rule restricting traffic to/from CA, MX, US, and Cloud EDLs 
    * SAML Provider no-decrypt policy 
    * Chromebook-specific websites no-decrypt policy

> **Note**: Most of these components rely on configuration pieces of [IronSkillet](https://github.com/PaloAltoNetworks/iron-skillet),
> so you must configure IronSkillet first. 
 
### Using the Sub-Skillets

The sub-skillets in this repository were meant to be brought into a master Playlist Includes skillet for any variety of 
use-cases. A Skillet Builder can choose to pick as many of the sub-skillets as necessary and bring into a master
skillet by referencing this repository as a submodule. 

For additional help on creating Playlist Includes skillets, see the [Skillet Builder Tutorials](https://skilletbuilder.readthedocs.io/en/latest/index.html).

### K-12 Skillet

The Safe Search Configuration sub-skillet components were wrapped in a Quickplay Solution called the K-12 Skillet. 
For more information on this, see the [K-12 Skillet README](https://github.com/PaloAltoNetworks/K12Skillet/blob/master/README.md).
