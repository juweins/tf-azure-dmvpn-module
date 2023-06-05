# Azure Dynamic Multipoint VPN (DMVPN) Terraform Module

This module creates a DMVPN on Azure. I create this module as part of my preparation for the Azure Network Engineer Associate exam. I will use this module to create a DMVPN for my lab environment.

# Status
Initial Alpha (0.0.1). The module is not yet ready for use.

**Currently under heavy development. I may refactor the code entirely to dynamically get in touch with the features**

**ATTENTION: Applying this module will create resources that may cost money. Make sure you understand what you are doing and destroy the resources after use.**

# What is a DMVPN?

A DMVPN is a dynamic VPN solution that allows you to create a meshed VPN network between multiple sites. The DMVPN is a Cisco proprietary solution that is based on the following technologies:

- GRE (Generic Routing Encapsulation)
- NHRP (Next Hop Resolution Protocol)
- mGRE (Multipoint GRE)
- IPsec (Internet Protocol Security)

You can find more information about the concept of DMVPN on the [Cisco website](https://www.cisco.com/c/en/us/products/security/dynamic-multipoint-vpn-dmvpn/index.html).

Note: This module transefers the DMVPN concept by using Azure native services. It is **not** a copy of the Cisco DMVPN solution.


