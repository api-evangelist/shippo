# Shippo GraphQL

## Description

Shippo is a multi-carrier shipping API that provides complete shipping functionality including address validation, rate shopping across 80+ carriers, label generation, package tracking, returns management, and batch operations. Shippo's API is REST-only; this GraphQL schema is a conceptual representation of the Shippo data model derived from the public REST API surface.

## Endpoint

Shippo does not offer a native GraphQL endpoint. The canonical REST base URL is:

```
https://api.goshippo.com
```

Authentication is via Bearer token in the `Authorization` header.

## Documentation

- API Reference: https://docs.goshippo.com/shippoapi/public-api
- Getting Started: https://support.goshippo.com/hc/en-us/articles/4404415886491-Shippo-API-Quick-Start-Guide
- Developer Portal: https://goshippo.com/products/api
- LLMs.txt: https://docs.goshippo.com/llms.txt

## Schema Source

Conceptual — derived from Shippo's public REST API specification (https://docs.goshippo.com/spec/shippoapi/public-api.yaml) and official documentation. Types map 1-to-1 with Shippo REST resources.

## Key Types

| Type | Description |
|---|---|
| Shipment | A shipping request combining origin, destination, and parcels |
| Address | A validated postal address with contact info |
| Parcel | Physical package dimensions and weight |
| Rate | A carrier-quoted price for a specific service level |
| Transaction | A purchased shipping label (rate + payment) |
| Label | Generated shipping label attached to a Transaction |
| TrackingStatus | Real-time tracking event for a shipment |
| Carrier | A supported shipping carrier (USPS, FedEx, UPS, DHL, etc.) |
| CarrierAccount | A connected carrier account credential |
| Order | A merchant order driving one or more shipments |
| OrderItem | A line item within an Order |
| Manifest | A carrier scan form consolidating multiple shipments |
| Pickup | A scheduled carrier pickup |
| Refund | A label void/refund request |
| Batch | A bulk label creation job |
| BatchShipment | An individual shipment record within a Batch |
| UserParcel | A saved/reusable parcel template |
| CustomsItem | A line item on a customs declaration |
| CustomsDeclaration | Customs documentation for international shipments |
| Location | A physical facility location (origin/destination) |
| PickupWindow | A time window for a scheduled Pickup |
| CarrierData | Carrier-specific metadata and service options |
