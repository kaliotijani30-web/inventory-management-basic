# Feature: Automatic SKU Generation and Barcode Integration

**Group:** 1 - Inventory Management Software
**Topic:** Item Identification (SKU Management) and Core Store Keeping
**Student Name:** Shaibu John
**Matric Number:** F/Nd/25/3210192

### Short Description
A system that automatically generates a unique Stock Keeping Unit (SKU) code for every new item added to inventory and links it to a scannable barcode/QR code for fast identification.

### Purpose
To eliminate manual SKU creation errors, prevent duplicate items, and speed up item identification during receiving, selling, and stock-taking. This ensures every item has a single, standardized identity across the entire system.

### Main Functions / Activities
- Auto-generate SKU using format: Category-Department-Sequence (e.g., ELEC-TV-0001)
- Validate that SKU does not already exist in the database
- Generate printable barcode and QR code for each SKU
- Allow barcode scanning to instantly retrieve item details, price, and stock level
- Allow search and filter by SKU, barcode, or item name
- Keep history of when SKU was created and by whom
