# DataCatalog

### Inserting Data FileDataCatalog

To insert data via a single process:

1. Execute the `crawl` script:
    ```bash
    cd $ADLKIT_INSTALL_DIR
    python -m adlkit.data_catalog.bin.crawl './data/*.h5' --label=baseline --data_sets=tensor_1,tensor_2
    ```
