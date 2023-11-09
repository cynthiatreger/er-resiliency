# ExpressRoute Resiliency

No breaking news, just an illustrated recap of the the recommendations and attention points highlighted in the [Microsoft Expressroute documentation](https://learn.microsoft.com/en-us/azure/expressroute/).

## 0. What is ExpressRoute?
An ExpressRoute is a dedicated connection into the Microsoft backbone network providing connectivity for VNets, connectivity for public Azure resources and connectivity for Office 365. This article focuses on ExpressRoute Private Peering only (connectivity for VNets).

ExpressRoute connectivity is provided in partnership with [service providers](https://learn.microsoft.com/en-us/azure/expressroute/expressroute-locations-providers#partners).

ExpressRoute Architecture
2 Microsoft edge routers (MSEE)
Each MSEE uplinks to two core routers
Each MSEE has separate physical connectivity (fiber) to the provider
The provider is required to have redundant connectivity to the customer edge or their MPLS edge
In the case of private peering, Gateways have a minimum 2 instances that connect to both MSEEs

## 1. ExpressRoute models



### 1.1. ExpressRoute Service Provider model

### 1.2. ExpressRoute Direct model

## 2. ExpressRoute Components (and Locations)

### 2.1. ExpressRoute Circuit

### 2.2. ExpressRoute Gateway

### 2.3. ExpressRoute Connection

## 3. ExpressRoute Data Flow

## 4. Prevent Service Provider Failure

## 5. Prevent MSEE maintenance impact

## 6. Prevent Availability Zone Failure





