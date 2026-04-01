## Fix discount allocation path type reference

Corrected `$.totals.shipping` to `$.totals.fulfillment` in the `allocation.path` field description in the discount extension schema. The checkout schema's `Total.type` enum uses `fulfillment`, not `shipping`.

### Changes
- Fixed incorrect type reference in discount allocation path description

### Files Updated
- `spec/unreleased/json-schema/schema.discount.json`
