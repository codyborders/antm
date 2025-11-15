# Diagram Slices

This folder now exposes four Mermaid specs (plus PDFs) so readers can choose the level of detail they need:

1. `antm_erd_overview` – a lightweight bridge diagram showing how the three sales facts, inventory, and the highest-volume logs hook into the `customer`, `item`, `date`, and fulfillment dimensions.
2. `antm_erd_retail_core` – the full star-schema expansion for store, catalog, web, and inventory facts plus all conformed dimensions (customer, household, address, promotion, etc.).
3. `antm_erd_experiments_logs` – experimentation, event, and customer-service logs with their joins back to core reference tables.
4. `antm_erd_metadata` – administrative DuckDB tables for storage, snapshots, ownership, and query history.

Each `.mmd` can be rebuilt via the local `@mermaid-js/mermaid-cli` toolchain: `npm --prefix diagrams install` (first run) then `npx --prefix diagrams mmdc -i diagrams/<file>.mmd -o diagrams/<file>.pdf`.
