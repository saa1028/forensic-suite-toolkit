# Forensics WP Corpus

This directory is the simplified corpus layout used as evidence for the next `forensic-suite-toolkit` VM update.

## Source Websites

- `https://www.yagami.vip`
- `https://forensics.xidian.edu.cn`
- `https://forensics.didctf.com`

## Directory Layout

- `data/raw_html/`
  - original HTML snapshots grouped by source domain
  - `data/raw_html/yagami`
  - `data/raw_html/xidian`
  - `data/raw_html/didctf`
- `data/text/`
  - text extracted from the raw HTML snapshots
  - `data/text/yagami`
  - `data/text/xidian`
  - `data/text/didctf`

## Tables

- `wp_links.csv`
  - WP/writeup source information
  - includes source site, title, original URL, DIDCTF detail URL, and DIDCTF external link when available

- `tool_frequency_total.csv`
  - cleaned total tool-frequency table with source breakdown
  - columns: `tool`, `mentions_total`, `didctf`, `didctf_external`, `xidian`, `yagami`
  - intended as the main evidence table for prioritizing tools in the VM

- `didctf_tool_database.csv`
  - DIDCTF tool database extracted from the tool collection page
  - includes project name, description, tags, download link, GitHub link, and website link when available

## Notes

The DIDCTF source bucket combines saved DIDCTF pages and downloaded DIDCTF external writeup pages into one domain-level directory.

The three tables in this directory are the main artifacts for the next update phase. Historical intermediate tables were intentionally removed from the main view so the corpus stays easy to use.
