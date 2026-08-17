# Data directory

The notebook downloads raw source data into `data/raw/` during its first run.

Raw datasets are intentionally excluded from Git because they are reproducible and may be updated by their publishers. The notebook records the source URL, local filename, retrieval time and latest available year in `outputs/source_manifest.csv`.

To refresh one source, delete its cached file from `data/raw/` and rerun the notebook.

Do not commit or redistribute raw datasets without reviewing the original publisher's license and terms.
