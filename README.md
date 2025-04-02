# Olympics-Wikipedia

A comprehensive web application for analyzing 120 years of Olympic Games data, providing interactive visualizations and detailed statistics about athletes, countries, and events.

![Olympics Logo](https://1000logos.net/wp-content/uploads/2021/03/Olympics-logo.png)

## Overview

Olympics-Wikipedia is a data-driven web application that offers an interactive platform to explore and analyze Olympic Games data spanning over 120 years. The application provides detailed insights into various aspects of the Olympics, including medal tallies, country-wise performance, athlete statistics, and historical trends.

## Features

- **Medal Tally Analysis**
  - View overall medal counts
  - Filter by year and country
  - Track historical performance

- **Overall Analysis**
  - Key statistics about editions, hosts, sports, events, nations, and athletes
  - Interactive visualizations of participating nations over time
  - Event and athlete participation trends
  - Sport-wise event distribution heatmap

- **Country-wise Analysis**
  - Detailed medal tally for each country
  - Performance trends over the years
  - Sport-wise success analysis through heatmaps

- **Athlete Analysis**
  - Age distribution analysis for medalists
  - Sport-specific age distributions
  - Height vs. Weight analysis by sport
  - Gender participation trends

## Tech Stack

- **Frontend**: Streamlit
- **Data Processing**: Pandas
- **Visualization Libraries**:
  - Plotly
  - Seaborn
  - Matplotlib
- **Data Format**: CSV

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/senseiiesnes/Olympics-Wikipedia.git
   cd Olympics-Wikipedia
   ```

2. **Create a virtual environment:**
   ```bash
   python3 -m venv env
   source env/bin/activate  # On Windows, use `env\Scripts\activate`
   ```

3. **Install the required dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Run the application:**
   ```bash
   streamlit run app.py
   ```

2. **Access the web interface:**
   - Open your web browser
   - Navigate to the URL shown in the terminal (typically http://localhost:8501)

## Project Structure

- `app.py`: Main application file containing the Streamlit interface
- `preprocessor.py`: Data preprocessing utilities
- `helper.py`: Helper functions for data analysis
- `athlete_events.csv`: Main dataset containing Olympic events data
- `noc_regions.csv`: Dataset containing country/region information

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the MIT License.

## Acknowledgments

- Data source: Olympic Games historical data
- Olympics logo used with permission
