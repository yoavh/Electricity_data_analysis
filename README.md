# Electricity Data Analysis

This project provides tools and analysis scripts for processing and analyzing electricity consumption data. It is designed to help users understand power usage patterns, visualize consumption, and support electricity reform research.

## Project Structure

- `data/` — Contains raw electricity meter data files (e.g., CSV files from smart meters).
- `electricity_reform/` — Main Python package for analysis.
  - `Power_consumption_analysis.ipynb` — Jupyter notebook for interactive data analysis and visualization.
  - `__init__.py` — Package initialization file.
- `pyproject.toml`, `poetry.lock`, `poetry.toml` — Project configuration and dependency management files (managed by Poetry).

## Getting Started

### Prerequisites

- Python 3.8+
- [Poetry](https://python-poetry.org/) for dependency management

### Installation

1. Clone the repository:
	```powershell
	git clone https://github.com/yoavh/Electricity_data_analysis.git
	cd Electricity_data_analysis
	```
2. Install dependencies using Poetry:
	```powershell
	poetry install
	```

### Usage

1. Place your electricity meter CSV files in the `data/` directory.
2. Open the `Power_consumption_analysis.ipynb` notebook in Jupyter or VS Code.
3. Follow the notebook instructions to load, process, and visualize your data.

## Features

- Load and preprocess smart meter data
- Analyze power consumption patterns
- Visualize electricity usage trends
- Support for custom data files

## Contributing

Contributions are welcome! Please open issues or submit pull requests for improvements or bug fixes.

## License

This project is licensed under the MIT License.
