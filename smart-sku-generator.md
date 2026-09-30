# Feature Name
Hierarchical Smart SKU Generator & Syntax Configurator

## Short Description
A rule-based configuration engine that automatically generates standardized, human-readable Stock Keeping Unit (SKU) strings by encoding core product attributes (such as category, brand, variant, and supplier code) according to a predefined organizational syntax.

## Purpose
To eliminate manual SKU creation errors, enforce strict cataloging consistency across large inventories, and allow staff and systems to instantly decipher basic product attributes directly from the SKU string without needing a database lookup.

## Main Functions/Activities
- **Attribute-to-Segment Mapping:** Configures custom segments (e.g., [Category]-[Brand]-[Color]-[Size]) to build uniform SKU patterns.
- **Automated Collision Prevention:** Automatically checks the database for existing codes to prevent duplicate or overlapping SKU generation.
- **Bulk Variant Matrix Generation:** Generates multi-variant SKUs simultaneously for items that come in multiple sizes, colors, or materials.
- **Prefix and Delimiter Customization:** Allows store managers to set standard separators (hyphens, dots, underscores) and category prefix codes.
