# LogFilter

A lightweight, extensible tool for parsing and filtering log files with custom rules and output formats.

## Purpose

LogFilter processes log files (e.g., application logs, server logs) and extracts relevant data based on user-defined rules. It supports regex-based filtering, custom output templates, and export to JSON or CSV. Built for developers and sysadmins who need to analyze logs without heavy dependencies.

## Features

- Parse logs with custom regex patterns.
- Filter entries by timestamp, severity, or custom keywords.
- Output results to console, JSON, or CSV.
- Configurable via a simple YAML file.
- Cross-platform (Windows, macOS, Linux).
- No external dependencies beyond Python 3.8+.

## Installation

```bash
git clone https://github.com/yourusername/logfilter.git
cd logfilter
pip install -r requirements.txt
