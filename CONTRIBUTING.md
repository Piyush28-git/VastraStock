# Contributing

Thanks for considering a contribution to VastraStock.

## Before starting

- Check existing issues to avoid duplicating work.
- For a large feature, open an issue first to discuss scope.
- Keep changes focused and explain the user problem they solve.

## Local development

The current MVP is a dependency-free HTML/CSS/JavaScript app. Open `index.html` in a modern browser to test it.

Before submitting a pull request, manually verify:

- A product can be added and duplicate SKUs are rejected.
- A purchase increases stock and updates weighted-average unit cost.
- A sale decreases stock.
- A sale larger than available stock is rejected.
- JSON export produces a backup.
- The browser console contains no errors during these workflows.

## Pull requests

Describe the motivation, implementation, and manual test steps. Include screenshots for significant UI changes. Do not include real customer, supplier, or financial data in fixtures or screenshots.