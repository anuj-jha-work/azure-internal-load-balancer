# Azure Internal (Private) Load Balancer Implementation

## Overview
Deployment of an Azure Internal Load Balancer to route traffic within a Virtual Network, isolating application logic and backend tiers from public access.

## Key Implementation Steps
* Configured an Internal Load Balancer bound to a private subnet IP address.
* Mapped backend Virtual Machines within the internal tier to receive private network traffic.
* Established custom health probes to monitor private service endpoint availability.
* Verified secure internal routing and traffic distribution within the VNet.