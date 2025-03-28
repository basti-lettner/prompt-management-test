---
prompt_name: order_confirmation
variables:
  - customer_name: string
  - order_id: string
  - delivery_date: date
description: "Template for confirming an order with expected delivery date."
---

Hello {{ customer_name }}, your order (ID: {{ order_id }}) is confirmed for delivery on {{ delivery_date }}.
