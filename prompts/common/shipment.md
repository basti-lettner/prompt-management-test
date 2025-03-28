---
prompt_name: shipment
variables:
  - customer_name: string
  - shipment_id: string
description: "Template for confirming an order with expected delivery date."
---

Hello {{ customer_name }}, your shipement ID is {{ shipment_id }}.
