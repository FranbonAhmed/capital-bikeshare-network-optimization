# Data Setup

Download the **2025 Capital Bikeshare trip-history CSV files** from the Capital Bikeshare system-data page and extract them into:

```text
data/raw/
```

The notebook searches for filenames containing:

```text
capitalbikeshare-tripdata
```

Required columns:

```text
start_station_name
start_lat
start_lng
```

The source assignment reported reading 12 monthly files with **6,662,647 rows and 13 columns**.
