

# Stocks Analysis AI Agent

This project is a **Streamlit-based application** that integrates **AI agents** to analyze stock market data. It allows users to input a stock name, retrieve its financial details, and view its historical price movements using interactive visualizations.

---

## Key Features
- **AI-Driven Analysis**: Utilizes AI agents for financial and web-based insights.
- **Interactive Stock Charts**: Displays stock price movements with candlestick charts.
- **Financial Metrics**: Provides details such as current price, forward P/E, and investment recommendations.
- **Company Overview**: Summarizes business descriptions for better understanding.
- **Predefined Stock Symbols**: Supports popular stocks like NVIDIA, APPLE, TESLA, TCS, etc.

---

## Technologies Used
- **Programming Language**: Python
- **Web Framework**: Streamlit
- **APIs and Libraries**:
  - `yfinance` for stock market data
  - `plotly` for visualizations
  - `phidata` for agent orchestration
  - `googlesearch-python` and `duckduckgo-search` for web tools
  - `groq` for AI model integration

---

## Installation

1. Clone the repository:
   ```bash
   git clone (https://github.com/afrojmirza/Stocks-Analysis-AI-Agent.git)
   cd Stocks Analysis AI Agent
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## Configuration

- Set the `GROQ_API_KEY` in the `app.py` file for initializing AI agents:
  ```python
  GROQ_API_KEY = "<your_api_key>"
  ```

---

## Usage

1. Run the Streamlit application:
   ```bash
   streamlit run app.py
   ```

2. Open your browser and navigate to:
   ```
   http://localhost:8501
   ```

3. Input a company name (e.g., APPLE, TCS) and click **Analyze** to view:
   - Current financial metrics
   - Historical price movements
   - Business summaries (if available)

---

## Project Structure

- `app.py`: Main application logic
- `requirements.txt`: Python dependencies for the project
- `assets/`: Contains project screenshots

---

## Screenshots

###  Home Page
![Home Page](https://github.com/afrojmirza/Stocks-Analysis-AI-Agent/blob/e0711f4f9747f584ea863da4c67903d885d9c08e/nvidia%20stock.png))



---

## Future Enhancements

- Add support for additional stock exchanges.
- Improve AI agents for more detailed insights.
- Include real-time notifications for stock alerts.

---

## License

This project is open-source and available under the [MIT License](LICENSE).  
