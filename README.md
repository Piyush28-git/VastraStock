# VastraStock

**A lightweight inventory and sales tracker for small textile businesses.**

VastraStock is an open-source starter project designed around practical textile workflows: adding products, receiving purchases, recording sales, and checking stock.

## Current status

This is an early browser-based MVP. It is useful for trying the workflow with sample data, but it is **not** a production accounting, tax, multi-user, or cloud-synchronised system.

## Features

- Add products with a unique SKU, category, opening stock, unit cost, and selling price.
- Record purchases and update stock using weighted-average unit cost.
- Record sales and prevent sales beyond available stock.
- View product count, on-hand units, inventory cost value, and recorded sales revenue.
- Review transaction history.
- Export a JSON backup.

## Run locally

No build tools or dependencies are required.

1. Download or clone this repository.
2. Open `index.html` in a modern browser.
3. Add a few products and try purchase and sale entries.

The app saves data in this browser's local storage on the current device. Clearing browser data can delete it; use the JSON export regularly.

## Example workflow

1. Add SKU `SAR-001`, name `Cotton saree`, opening quantity `10`, unit cost `₹400`, and selling price `₹550`.
2. Record a purchase of 5 units at ₹420. The app updates the weighted-average cost.
3. Record a sale of 3 units at ₹550. Available stock decreases to 12.

## Project structure

```
.
├── index.html
├── README.md
├── LICENSE
├── CONTRIBUTING.md
├── SECURITY.md
├── .gitignore
└── .github/
    ├── ISSUE_TEMPLATE/
    └── workflows/
```

## Roadmap

- [ ] CSV import and export
- [ ] Multiple godowns / locations
- [ ] Supplier and customer records
- [ ] Barcode support
- [ ] Role-based access and cloud backup
- [ ] Automated browser tests
- [ ] GST-aware invoicing after appropriate accounting review

## Contributing

Bug reports, usability feedback, and focused pull requests are welcome. Please read [CONTRIBUTING.md](CONTRIBUTING.md).

## Security and data handling

See [SECURITY.md](SECURITY.md). Do not enter sensitive customer or financial data into this prototype.

## License

MIT. See [LICENSE](LICENSE).
