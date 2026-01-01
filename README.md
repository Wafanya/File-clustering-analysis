# Multi-Product Document Analyzer

A comprehensive web-based tool for analyzing document clustering data across multiple products (PDF Guru, PDF Leader, and TheBestPDF).

## Features

- **Multi-Product Support**: Switch between PDF Guru, PDF Leader, and TheBestPDF datasets
- **Category Analysis**: 
  - Level 1 and Level 2 category distributions
  - Interactive pie charts with detailed tooltips
- **Advanced Filtering**:
  - Filter by country (with preset groups like EU, Tier 1, etc.)
  - Filter by device type
  - Filter by feature usage
  - Filter by date range (trial/subscription dates)
- **Comprehensive Analysis Views**:
  - Handwritten text detection
  - Image types analysis
  - Scan/Photo classification
  - Language distribution
  - Personal data detection
- **User Records Browser**: Search and browse individual user records
- **Global Search**: Search by User ID or Email across all products

## How to Use

### Online Version (GitHub Pages)

The tool is hosted on GitHub Pages and can be accessed at:
**https://wafanya.github.io/File-clustering-analysis/**

Simply open the link in your browser - no installation required!

### Local Version

1. Clone this repository:
   ```bash
   git clone https://github.com/Wafanya/File-clustering-analysis.git
   cd File-clustering-analysis
   ```

2. Start a local web server (required due to CORS restrictions):
   ```bash
   python3 -m http.server 8000
   ```

3. Open in your browser:
   ```
   http://localhost:8000
   ```

## Data Files

The repository includes:
- **Merged CSV files**: `guru_merged_full.csv`, `leader_merged_full.csv`, `best_merged_full.csv`
- **User mappings**: JSON files containing user-level data mappings
- **Analysis data**: Pre-computed analysis JSON files for quick loading

## Usage Tips

1. **Select a Product**: Use the product buttons in the header to switch between datasets
2. **Apply Filters**: Use the filter dropdowns to narrow down the analysis
3. **Explore Categories**: Click on Level 1 categories to see detailed statistics
4. **Search Users**: Use the global search bar to find specific users by ID or email
5. **View Details**: Navigate to "User Browser" to see individual record details

## Technical Details

- Pure HTML/CSS/JavaScript (no external dependencies)
- Responsive design for desktop and mobile
- LocalStorage for persisting user preferences
- Efficient data filtering and aggregation

## License

This project is for internal use.
