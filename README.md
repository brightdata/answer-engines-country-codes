# answer-engines-country-codes

This repository contains country code lists used by various answer engines. Each CSV file corresponds to a different engine and contains the country codes and country names that engine recognizes or supports.

## CSV Files

- `chatgpt_countries.csv`
- `copilot_countries.csv`
- `gemini_countries.csv`
- `perplexity_countries.csv`

### Structure

All CSV files have the following columns:

- `Country Code`: The ISO 3166-1 alpha-2 country code (e.g., `US`, `GB`, `IN`).
- `Country`: The country name as recognized by the engine (may vary slightly between files).

### Purpose

These files are useful for comparing country support and naming conventions across different answer engines. They can be used for data validation, analytics, or integration with services that require country code mappings.
