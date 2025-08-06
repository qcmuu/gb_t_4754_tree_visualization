# GB/T 4754-2017 Tree Visualization

An interactive tree visualization tool for GB/T 4754-2017 (National Industry Classification Standard of People's Republic of China).

## Project Overview

This project provides a web-based interactive interface for browsing and searching the GB/T 4754-2017 classification system. GB/T 4754-2017 is China's national standard for industry classification, which categorizes all economic activities within the People's Republic of China, developed by the National Bureau of Statistics of China.

## Features

- **Hierarchical Tree Structure**: Display the complete GB/T 4754-2017 classification system in a tree format
- **Four-Level Classification Hierarchy**:
  - Category (门类) - Identified by letters (A-T)
  - Major (大类) - 2-digit numeric codes
  - Medium (中类) - 3-digit numeric codes
  - Subclass (小类) - 4-digit numeric codes
- **Bilingual Support**: Both Chinese and English names for all classifications
- **Real-time Search**: Search classification items by code or name (supports both Chinese and English)
- **Interactive Operations**:
  - Expand/collapse all nodes
  - Click nodes to expand/collapse sub-items
  - Clear search results
- **Statistics Display**: Real-time display of classification counts at each level
- **Responsive Design**: Adapts to different screen sizes

## File Structure

```
├── gb_t_4754_tree_visualization.html    # Main visualization interface
├── gb_t_4754_data_corrected.js         # GB/T 4754-2017 classification data
```

## Usage

1. **Direct Access**: Open `gb_t_4754_tree_visualization.html` in your browser
2. **Search Classifications**: Enter code or name keywords in the search box (supports both Chinese and English)
3. **Browse Hierarchy**: Click the arrows before nodes to expand/collapse sub-classifications
4. **Batch Operations**: Use "Expand All"/"Collapse All" buttons

## Data Source

- Based on the official GB/T 4754-2017 standard published by the National Bureau of Statistics of China
- Data has been cleaned and structured to ensure completeness and accuracy
- Includes both Chinese original names and English translations

## Technical Implementation

- **Frontend**: Pure HTML/CSS/JavaScript, no additional dependencies required
- **Data Format**: JSON structured data with bilingual support
- **Styling**: Modern responsive CSS design with purple gradient theme
- **Compatibility**: Supports modern browsers
- **Encoding**: UTF-8 support for Chinese characters

## Classification Statistics

GB/T 4754-2017 contains:
- 20 Categories (门类)
- 97 Major classes (大类)
- 473 Medium classes (中类)
- 1,380 Subclasses (小类)

## Key Differences from ISIC Rev.5

- **Regional Focus**: Specifically designed for China's economic structure
- **Bilingual Labels**: All classifications include both Chinese and English names
- **Local Industries**: Includes classifications specific to Chinese economic activities
- **Alignment**: Generally aligned with ISIC Rev.4 but with Chinese characteristics

## Related Projects

This repository also includes a similar visualization tool for ISIC Rev.5 (International Standard Industrial Classification):
- [isic_rev5_tree_visualization](https://github.com/qcmuu/isic_rev5_tree_visualization)

## License

This project is for educational and research purposes only. The GB/T 4754-2017 classification standard is copyrighted by the National Bureau of Statistics of China.

## Contributing

Issues and Pull Requests are welcome to improve this project.

---

*Last updated: January 2025*
