# Derby Spend Explorer

An interactive dashboard for exploring Derby City Council supplier payments over £500, from January 2024 to August 2026.

**Live dashboard:** https://YOUR-USERNAME.github.io/derby-spend-explorer/

## What it shows

- **Biggest changes:** a summary of how spending in January to August 2026 compares with the same months of 2025, including the biggest movers by directorate, programme and supplier.
- **Explore the data:** filters for period, directorate, department, supplier type and supplier name, with monthly and cumulative trends, ranked lists, and large payments and credits. Headline figures and rankings compare the chosen period with the same period a year earlier.

## Data source

Derby City Council, "Supplier payments over £500", monthly files:
https://www.derby.gov.uk/council-and-democracy/open-data-freedom-of-information/open-data-transparency/

You can compare any figure in the dashboard with the council's original files.

## Licence and attribution

Contains public sector information licensed under the [Open Government Licence v3.0](https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/).

This is an independent analysis. It was not produced, checked or endorsed by Derby City Council, and its figures may differ from the council's own reports.

## What was changed, and why

No payment amount has been altered. The steps taken are listed at the bottom of the "Explore the data" tab and include:

- Each file's own "Grand Total" row is removed, so it is never counted as a payment.
- October 2025 was supplied twice and is counted once.
- Older directorate names are grouped under today's names.
- Sole traders' names are withheld to protect individuals. Entries the council has redacted are shown as published.
- Refunds and credits are netted off, so "total spend" is net spend, excluding VAT.

## Using this repository

The whole dashboard is a single file, `index.html`. It needs no build step or server, so you can open it directly in a browser.
