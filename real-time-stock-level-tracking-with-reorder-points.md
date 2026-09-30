# Feature: Real-Time Stock Level Tracking with Reorder Points

## Short Description
Core store-keeping functionality that continuously tracks the quantity of every SKU on hand, available, committed, and on order, and automatically triggers low-stock alerts or purchase recommendations when stock falls to a defined reorder point.

## Purpose
To maintain accurate physical stock visibility at all times and prevent stockouts or overstocking. This is a fundamental store-keeping capability that ensures the business always knows what is available, what needs replenishment, and when to reorder—directly supporting efficient day-to-day inventory control.

## Main Functions / Activities
- Maintain live quantities per SKU: On Hand, Available, Committed/Allocated, On Order
- Set and manage reorder points (minimum level) and preferred replenishment levels (maximum/target) per SKU
- Automatically generate low-stock alerts or notifications when quantity reaches the reorder point
- Support manual stock adjustments with reason codes and full history
- Record all stock movements (receipts, sales, transfers, adjustments) against the correct SKU
- Provide quick views of current stock status filtered by category, location, or low-stock status
- Allow bulk update of reorder points across multiple SKUs
- Keep an auditable movement history for every quantity change
