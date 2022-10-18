### MiSTer Downloader Configuration

The [Downloader](https://github.com/MiSTer-devel/Downloader_MiSTer) tool can be configured for downloading all these files directly from your MiSTer.  If you are not getting the files automatically, add manually this database to `/media/fat/downloader.ini`.  Add these lines to the end of the file:

```ini
[YC_cores]
db_url = https://raw.githubusercontent.com/7407chrisl/MiSTer_FPGA/main/YC_db.json.zip

```
