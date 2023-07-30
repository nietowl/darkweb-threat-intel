# Dark Web Datasets

This repository contains CSV datasets extracted from the dark web, including forums, chat rooms, marketplaces, data leaks, and ransomware groups.

## Data Sources

### Forums

- `chat_forums.csv` - Contains a list of discussion forums and chat rooms extracted from Tor sites, including name, description, status, and .onion URL.

### Chat Rooms

- `chat_rooms.csv` - Contains a list of chat room sites and IRC channels extracted from Tor, including connection details. 

### Markets 

- `markets.csv` - Contains a list of dark web marketplaces selling illicit items like drugs, counterfeits, exploits, and stolen data. Includes name and product count.

### Data Leaks

- `data_leaks.csv` - Contains posts from data leak sites offering hacked databases, credentials, sensitive documents, and other cybercrime data dumps.

### Ransomware Groups

- `ransomware_groups.csv` - Contains sites operated by ransomware extortion groups to name-and-shame victims and auction off stolen data.

## Overview

The CSV files provide structured extracts of content found on Tor dark web sites related to cybercrime activities. The data provides insight into the scope and operations of forums, marketplaces, and extortion groups that reside on hidden services.

Analyses of interest could include:

- Tracking relationships between entities based on cross-referenced .onion URLs.
- Monitoring changes in product availability and pricing on marketplaces over time.
- Identifying data breach victims based on details in leaked data sets.

New scrapes should be committed frequently to keep the repository current.

## Legal Notice

This data is provided for academic research purposes only. Usage for any unlawful purpose is strictly prohibited.
