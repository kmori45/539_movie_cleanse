## Math 539 Movie Selection Data Cleansing Scripts

Use these scripts to turn raw data into usable tables for analysis.

## Instructions: File data load

The following files need to be in the "data" folders (all files are available in the team google drive):

### media_load folder

- SIA_media_content_entire_yr.csv (from Panasonic)
- SIA_media_data_entire_yr.csv (from Panasonic)

### media_usage folder

- sia_media_usage_master.csv (from Panasonic)

### other folder

- top_actors.csv (this file contains the list of top grossing actors scraped from box office mojo)
- airport-codes.csv (this file is a cached copy of all airports and their ICAO codes)

## Scripts

### 01_master_media_usage_gen.R

This script generates a master media key file based on the flight usage data.

### 02_master_media_usage_format.R

This script merges the media key file with the usage data

### 03_total_media_load.R

This script takes the media loads and creates distinct entries (watched and non-watched) for all tails.
