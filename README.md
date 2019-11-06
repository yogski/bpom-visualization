# bpom-visualization
Data visualization of bottled tea products registered in Indonesian Food &amp; Drug Administration Bureau (BPOM - Badan Pengawas Obat dan Makanan)

## Structure
This project consist of one .csv file as the dataset and one .ipynb (Jupyter Notebook) file.

## Data Visualization Flow
1. Data Source : the data is based on BPOM information system filtered with "minuman teh" keyword for product name. Link: http://cekbpom.pom.go.id/index.php/home/produk/r2isesetrjp2lvbjcb4617o7i0/13/row/5100/page/0/order/4/DESC/search/1/minuman%20teh
2. Data Conversion : data source is displayed as html table. The table is converted to csv using online tool: http://beautifytools.com/html-to-csv-converter.php
3. Data Cleansing : data is cleansed using VS Code Editor to ensure uniformity and consistency. Regex feature is used heavily.
4. Data visualization : Jupyter Notebook is used as primary tool for data visualization.
