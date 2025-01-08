## API-INTEGRATION-AND-DATA-VISUALIZATION

**Company**: CODETECH IT SOLUTIONS  

**Name**  : SURESH KUMAR P 

**Id**: CT08HDL

**Domain**: PYTHON PROGRAMMING

**Batch Duration**: Dec 30th 2024 to Jan 30th, 2025 

**Mentor Name** : NEELA SANTHOSH


# US Domestic Airline Flights Performance Dashboard

This project is a web-based interactive dashboard built with Python's Dash framework. It visualizes various performance metrics and delay statistics for US domestic airline flights, using data sourced from [IBM Developer Skills Network](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DV0101EN-SkillsNetwork/Data%20Files/airline_data.csv).

## Features

The dashboard includes the following features:

1. **Yearly Airline Performance Report**:
   - Monthly flight cancellations by category.
   - Average monthly flight time by reporting airline.
   - Percentage of diverted airport landings per reporting airline.
   - Number of flights from each origin state (visualized on a US map).
   - Number of flights to each destination state, categorized by airline.

2. **Yearly Airline Delay Report**:
   - Average monthly delays by:
     - Carrier
     - Weather
     - National Airspace System (NAS)
     - Security
     - Late aircraft

## Prerequisites

Ensure you have the following installed:
- Python (>=3.7)
- Required Python libraries: Dash, Plotly, Pandas

Install the dependencies using:
```bash
pip install dash plotly pandas
```

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/airline-performance-dashboard.git
   cd airline-performance-dashboard
   ```

2. Run the application:
   ```bash
   python app.py
   ```

3. Open your web browser and go to:
   ```
   http://127.0.0.1:8050/
   ```

## Project Structure

- **`app.py`**: Main application file containing the dashboard logic.
- **Data**: Data is fetched directly from the source URL at runtime.

## Key Components

- **Dropdowns**: 
  - Report type (Performance vs Delay statistics)
  - Year selection
- **Visualizations**: 
  - Bar, line, pie, choropleth map, and treemap charts

## Example Screenshots

- Performance Report:
  ![Performance Report Screenshot](link-to-your-screenshot)

- Delay Report:
  ![Delay Report Screenshot](link-to-your-screenshot)

## Contributing

Feel free to submit issues or pull requests. All contributions are welcome!

## License

This project is licensed under the MIT License.

---

### Credits

Data provided by the IBM Developer Skills Network.

```

Replace the "link-to-your-screenshot" placeholders with links to actual screenshots of your app if available. Update the repository URL and license as needed.



