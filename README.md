# FridayHITT-Infrastructure

# Overview

# Resources

## VPCs

- **BstEuVPC VPC**: This is the Bastion VPC located in Ireland (EU). It will host all bastion servers in Europe, providing secure access to private resources.
    - CIDR Block: `10.1.0.0/16`

- **ProdEuVPC VPC EU**: This VPC is designated for production resources, ensuring secure and scalable hosting for applications.
    - CIDR Block: `10.2.0.0/16`

#### Production Subnets

- **Private**: 
  - `ProductionPrivateSubnet1a`: `10.2.1.0/24` (eu-west-1a)
  - `ProductionPrivateSubnet1b`: `10.2.2.0/24` (eu-west-1b)
  
- **Public**: 
  - `ProductionPublicSubnet1a`: `10.2.3.0/24` (eu-west-1a)
  - `ProductionPublicSubnet1b`: `10.2.4.0/24` (eu-west-1b)


## Internet Gateway

** InternetGateway**: Allows internet access for VPCs


## Conclusion

This template serves as a foundational setup for a network infrastructure on AWS, ideal for scenarios requiring a bastion host to manage access to production resources.

## Developer
Christian Magalhaes

