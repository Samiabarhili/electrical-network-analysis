# C-Wire – Electrical Network Analysis Tool

Developed by Tiroumourougane Synthia, Achour Hajar and Samia Barhili.

## Overview

C-Wire is a tool for analyzing **power distribution in an electrical network** across different station levels (HVB, HVA, LV) and consumer types.

It processes input datasets and generates summaries of:

- station capacities
- energy consumption by consumer type
- execution time

## Features

- Analysis of station capacities
- Consumption aggregation by consumer category
- Automated data processing via Bash script
- Graph generation using Gnuplot

## Usage

```bash
chmod +x c-wire.sh
./c-wire.sh <csv_file> <station_type> <consumer_type> [power_plant_id]
```
Example:
```bash
./c-wire.sh input/c-wire_v25.dat hvb comp
```
## Requirements

- GCC
- Make
- Bash
- Gnuplot

## Documentation

Project documentation:
https://github.com/Samiabarhili/c-Wire-B/blob/main/Projet_C-Wire_preIng2_2024_2025.pdf
