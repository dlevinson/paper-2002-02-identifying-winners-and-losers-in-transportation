# Identifying Winners and Losers in Transportation

## Contribution

This paper brings distributional equity into transportation evaluation alongside conventional efficiency measures. Applying several quantitative equity metrics to Twin Cities ramp-meter data, it recommends an equity impact statement that identifies who participates in decisions and how mobility, economic, environmental, and health outcomes are distributed across population groups.

## Bibliographic Information

- Row ID: `paper-2002-02`
- Authors: David M. Levinson
- Venue: *Transportation Research Record* 1812, 179-185, 2002
- DOI: `10.3141/1812-22`

## Audit Result

This paper should not be treated as `NO-DATA-OR-CODE`. The paper is primarily conceptual and methodological, but it also applies equity measures to Route 169 ramp-meter on/off data from Tuesday, March 21 and Tuesday, November 7, 2000. It cites the MnDOT ramp-meter equity/efficiency project for the calculation methodology.

The clean package therefore contains a compact Route 169 ramp-meter data/model subset rather than a broad dump of the ramp-meter project folder.

## Package Contents

- `paper/WinnersAndLosers.pdf`: local reference copy of the paper used for validation.
- `data/original/169Data/`: Route 169 ramp-decision, OD, segment, and Gini source files.
- `data/original/169Data_modernized/`: modern `.xlsx` conversions of the legacy `.xls` files in `169Data`.
- `data/workbooks/original/`: selected Route 169 equity/mobility/accessibility workbooks.
- `data/workbooks/modernized/`: LibreOffice `.xlsx` conversions of the selected legacy workbooks where conversion succeeded.
- `code/original/`: small C source files from the ramp-meter source folder.
- `documentation/source_reports/`: Task 2 report and appendices documenting the ramp-meter calculation methodology.
- `metadata/FILE_INVENTORY.csv`: package file inventory with checksums.
- `metadata/WORKBOOK_SHEET_INVENTORY.csv`: sheet-level inventory for converted workbooks.

## Exclusions

The larger project folders contain drafts, correspondence, presentations, proposal/admin files, reviewer responses, non-target I-94 material, broad MnDOT report material, and other ramp-meter papers. Those are not included here.

## Status

Ready for public package review as a compact Route 169 ramp-meter data/code/documentation package. No sensitive individual-level data were identified in the retained files. LibreOffice scratch files and empty audit manifests are excluded.

<!-- package-hardening-status:start -->
## Package Hardening Status

Generated: 2026-05-21 06:40:20 AEST

- Pipeline: `UPLOADED`
- Sidecars added/updated: `PACKAGE_STATUS.md`, `PACKAGE_MANIFEST.csv`, `LICENSE_STATUS.md`.
- Paper reference copies are for local audit convenience and are not public-upload assets without rights review.
- The repository license boundary is recorded in `LICENSE.md`.
<!-- package-hardening-status:end -->

## License

See `LICENSE.md`. Author-created code is MIT licensed; author-created derived
data and documentation are CC BY 4.0. Papers and public-agency/source
materials retain their original terms.
