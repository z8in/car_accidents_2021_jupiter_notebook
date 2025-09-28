## Notes

### Note - There is a typo in naming this repo it is not Jupiter, of course :)

- This Jupyter Notebook analyzes **car accidents in Serbia for the year 2025 (up to 31.08.2025)**.  
- Data is sourced from the official [Serbian Open Data Portal](https://opendata.stat.gov.rs/).
- The workflow includes:
  - Cleaning and preparing the dataset (renaming columns, removing unused ones).
  - Counting and visualizing different types of accidents using bar plots.
  - Converting Excel-style longitude/latitude values (e.g., `20,366,175`) into decimal degrees for mapping.
  - Filtering accident locations to plausible geographic bounds of Serbia.
  - Overlaying accident locations on a background map (`map.png`) to visualize spatial distribution.
- Outputs include:
  - A bar chart of accident types and their frequencies.
  - A scatter map of accident locations across Serbia.
- Requirements:
  - Python 3.8+
  - Libraries: `pandas`, `matplotlib`, `openpyxl` (for reading Excel files).
  - A `map.png` file placed in the project directory for spatial plotting.