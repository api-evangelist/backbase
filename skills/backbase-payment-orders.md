---
name: payment-orders
description: Manage payment orders via the Backbase API, allowing clients to list, create, retrieve, update, and delete payment order resources as defined in the Backbase payment order OpenAPI specification.
api: openapi/payment-order-client-api-v2.0.0.yaml
operations:
  - getPaymentOrders
  - postPaymentOrders
  - getPaymentOrderById
  - putPaymentOrderById
  - deletePaymentOrderById
---
## Steps
1. **List Payment Orders** – Call `GET /paymentOrders` (operationId `getPaymentOrders`).
2. **Create a Payment Order** – Call `POST /paymentOrders` (operationId `postPaymentOrders`).
3. **Retrieve a Payment Order** – Call `GET /paymentOrders/{id}` (operationId `getPaymentOrderById`).
4. **Update a Payment Order** – Call `PUT /paymentOrders/{id}` (operationId `putPaymentOrderById`).
5. **Delete a Payment Order** – Call `DELETE /paymentOrders/{id}` (operationId `deletePaymentOrderById`).
