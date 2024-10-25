# FridayHITT-Infrastructure

# Overview

# Resources

## VPCs

- **BstEuVPC VPC**: This is the Bastion VPC located in Ireland (EU). It will host all bastion servers in Europe, providing secure access to private resources.
    - CIDR Block: `10.10.1.0/24`

- **ProdEuVPC VPC EU**: This VPC is designated for production resources, ensuring secure and scalable hosting for applications.
    - CIDR Block: `10.10.2.0/24`

#### Bastion Subnets

- **Private**: 
  - `Bastion Private Subnet 1a`: `10.10.1.0/26` (eu-west-1a)
  - `Bastion PrivateSubnet 1b`: `10.10.1.64/26` (eu-west-1b)
  
- **Public**: 
  - `Bastion Public Subnet 1a`: `10.10.1.128/26` (eu-west-1a)
  - `Bastion Public Subnet 1b`: `10.10.1.192/26` (eu-west-1b)

#### Production Subnets

- **Private**: 
  - `ProductionPrivateSubnet1a`: `10.10.2.0/26` (eu-west-1a)
  - `ProductionPrivateSubnet1b`: `10.10.2.64/26` (eu-west-1b)
  
- **Public**: 
  - `ProductionPublicSubnet1a`: `10.10.2.128/26` (eu-west-1a)
  - `ProductionPublicSubnet1b`: `10.10.2.192/26` (eu-west-1b)


## Internet Gateway

**InternetGateway**: Allows internet access for VPCs


## Conclusion

This template serves as a foundational setup for a network infrastructure on AWS, ideal for scenarios requiring a bastion host to manage access to production resources.

## Developer
Christian Magalhaes

