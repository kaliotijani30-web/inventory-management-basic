# Feature: Automated SKU Generation & Variant Identification

## Short Description
A system that automatically creates unique, structured Stock Keeping Unit (SKU) codes for every product and its variants (size, colour, style, etc.) based on predefined business rules, while also supporting manual override and bulk generation for existing items.

## Purpose
To eliminate duplicate or inconsistent product identifiers, reduce human error during item creation, and provide a reliable, machine-readable way to uniquely identify every stockable item across the inventory system. This forms the foundation of accurate item identification and enables all downstream store-keeping activities.

## Main Functions / Activities
- Define and store SKU naming templates/rules (e.g., Category-Brand-Attribute-Sequence)
- Auto-generate unique SKUs when a new item or variant is created
- Bulk-generate missing SKUs for existing catalogue items
- Support multiple identifiers per item (primary SKU + UPC/EAN/barcode + vendor part number)
- Validate uniqueness of every generated SKU before saving
- Allow controlled manual editing of SKUs with audit logging
- Link parent products to their variant SKUs for hierarchical identification
- Export/import SKU master data for synchronisation with other systems
