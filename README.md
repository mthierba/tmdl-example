# Tabular Model Definition Language (TMDL)

TMDL is Microsoft's new language for defining tabular models for Analysis Services and Power BI. It targets professional developers and is designed to be human-readable and editable in any text editor. Furthermore, TMDL projects work well with source control and collaborative workflows.

TMDL is currently in Public Preview.

* [TMDL Overview](https://pbi.onl/tmdl-docs)

## TMDL History

| TOM Version | TMDL Release | Max CompatLevel | Date        | TE / pbi-tools | Notes |
| ----------- | ------------ | --------------- | ----------- | -------------- | ----- |
| 19.76.0     | Preview-10   | 1606            |  2-Feb-2024 | TBD | Minor API Change: `MetadataFormattingOptions.IndentationSize` _(was: 'IndentationLevelLength')_ |
| 19.74.2     | Preview-9    | 1606            |  4-Jan-2024 | [2.22.0](https://github.com/TabularEditor/TabularEditor/releases/tag/2.22.0) / [1.0.0-rc.8](https://github.com/pbi-tools/pbi-tools/releases/tag/1.0.0-rc.8) |
| 19.72.0     | Preview-8    | 1605            |  8-Dec-2023 |   | BREAKING: Dropped separate TMDL NuGet packages (merged into main TOM DLL); Serialization Options |
| 19.69.6.2   | Preview-7    | 1605            |  6-Nov-2023 | 2.21.1 / 1.0.0-rc.7 |
| 19.69.2.2   | --           | 1604            | 16-Oct-2023 |
| 19.69.2.1   | Preview-6    | 1604            |  9-Oct-2023 |
| 19.67.0     | Preview-5    | 1604            |  5-Sep-2023 | 2.20.2 / 1.0.0-rc.5 |
| 19.65.12.3  | Preview-4    | 1604            | 15-Aug-2023 |
| 19.65.7.2   | Preview-3    | 1604            |  6-Jul-2023 |
| 19.65.4     | --           | 1604            |  8-Jun-2023 | 2.19.0 / 1.0.0-rc.5+preview.1 |
| 19.64.0     | Preview-2    | 1604            |  5-May-2023 | 2.18.2 / 1.0.0-rc.4 |
| 19.61.1.4   | Preview-1    | 1604            | 10-Apr-2023 | 2.18.1 / 1.0.0-rc.3 |
