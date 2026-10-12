---
name: bigcommerce-order-refund
description: Quote and issue a refund against a BigCommerce order, or void an uncaptured payment.
api: BigCommerce Payment Actions API
operations:
- createOrderRefundQuotes
- createOrderRefund
- getOrderRefunds
- voidOrderPayment
---
# Refund an order

1. `createOrderRefundQuotes` with the items to refund, to get the refundable amount and allowed payment providers.
2. `createOrderRefund` with the quoted items and `payments` drawn from the quote.
3. `getOrderRefunds` to confirm the refund recorded.
4. For an authorised but uncaptured payment, `voidOrderPayment` instead.

Rules: refunds are not idempotent — always read `getOrderRefunds` before retrying. No refund window is stated in the docs read for this profile; do not assume one.
