## 🏠 AI Real Estate Agent 

The AI Real Estate Agent automates property search and market analysis using Firecrawl's Extract endpoint and Agno AI Agent's insights. It helps users find properties matching their criteria while providing detailed location trends and investment recommendations. This agent streamlines the property search process by combining data from multiple real estate websites and offering intelligent analysis.

### Features
- **Smart Property Search**: Uses Firecrawl's Extract endpoint to find properties across multiple real estate websites
- **Multi-Source Integration**: Aggregates data from 99acres, Housing.com, Square Yards, Nobroker, and MagicBricks
- **Location Analysis**: Provides detailed price trends and investment insights for different localities
- **AI-Powered Recommendations**: Uses GPT models to analyze properties and provide structured recommendations
- **User-Friendly Interface**: Clean Streamlit UI for easy property search and results viewing
- **Customizable Search**: Filter by city, property type, category, and budget

### How to Get Started
1. **Clone the repository**:
   ```bash
   git clone https://github.com/Gorav22/AI-Real-Estate-Agent
   cd AI-Real-Estate-Agent
   ```

2. **Install the required packages**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up your API keys**:
   - Get your Firecrawl API key from [Firecrawl's website](https://www.firecrawl.dev/app/api-keys)
   - Get your Gemini API key from [AI Studio](https://makersuite.google.com/app/apikey)

4. **Run the application**:
   ```bash
   streamlit run app.py
   ```

### Using the Agent
1. **Enter API Keys**:
   - Input your Firecrawl and Gemini API keys in the sidebar
   - Keys are securely stored in the session state

2. **Set Search Criteria**:
   - Enter the city name
   - Select property category (Residential/Commercial)
   - Choose property type (Flat/Individual House)
   - Set maximum budget in Crores

3. **View Results**:
   - Property recommendations with detailed analysis
   - Location trends with investment insights
   - Expandable sections for easy reading

### Features in Detail
- **Property Finding**:
  - Searches across multiple real estate websites
  - Returns 3-6 properties matching criteria
  - Provides detailed property information and analysis

- **Location Analysis**:
  - Price trends for different localities
  - Rental yield analysis
  - Investment potential assessment
  - Top performing areas identification

