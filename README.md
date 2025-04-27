# GrantAIScraper

**Welcome to AI Grant Scraper**, a specialized tool designed to empower nonprofit organizations in optimizing grant applications, made during my internship with New Jersey Voice for Progress/American Muslims for Democracy. (https://njmvp.org)
Built with **Streamlit** and the **LangChain library**, this tool uses AI-driven scraping to extract actionable insights from awarded grants, helping nonprofits identify key trends and keywords to enhance their chances of securing funding.  

---

## **How It Works**  
### Model Creation
- Define your custom data model by specifying attributes (e.g., keywords, organization names, funding amounts).  
- Automatically generate a Pydantic model to ensure accurate data extraction from target websites.  

### Data Scraping
- Input the URL of a successful grant application or a related webpage.  
- The tool scrapes data using the defined model and parses HTML content to extract relevant information, such as funding criteria, application language, and success factors.  

### Data Analysis 
- Extracted data is structured into JSON format, making it easy to analyze trends and incorporate insights into grant-writing strategies.  
