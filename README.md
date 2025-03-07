# GrantAIScraper

**Welcome to AI Grant Scraper**, a specialized tool designed to empower nonprofit organizations in optimizing grant applications, made during my internship with New Jersey Voice for Progress/American Muslims for Democracy. Built with **Streamlit** and the **LangChain library**, this tool uses AI-driven scraping to extract actionable insights from awarded grants, helping nonprofits identify key trends and keywords to enhance their chances of securing funding.  

---

## **Features**  
- **Grant Keyword Extraction**: Identify frequently used keywords and themes in successful grant applications.  
- **Dynamic Model Creation**: Define Pydantic models directly through the UI to tailor data extraction to specific grant types.  
- **Automated Data Structuring**: Transform unstructured web data into structured formats for easy analysis and actionable insights.  
- **Exportable Results**: Download structured data in JSON format for seamless integration into other analysis or grant-writing workflows.  

---

## **How It Works**  
### Model Creation**  
- Define your custom data model by specifying attributes (e.g., keywords, organization names, funding amounts).  
- Automatically generate a Pydantic model to ensure accurate data extraction from target websites.  

### Data Scraping**  
- Input the URL of a successful grant application or a related webpage.  
- The tool scrapes data using the defined model and parses HTML content to extract relevant information, such as funding criteria, application language, and success factors.  

### Data Analysis**  
- Extracted data is structured into JSON format, making it easy to analyze trends and incorporate insights into grant-writing strategies.  
- Directly view results in the app for quick insights or export them for detailed review.  

---

## **How to Use**  

1. **Define Your Data Model**  
   - Specify attributes such as keywords, funding amounts, or applicant details in a user-friendly table format.  

2. **Input Grant Sources**  
   - Enter the URL of the webpage containing awarded grant details or application criteria.  

3. **Extract Key Insights**  
   - Click the 'Generate Pydantic Model and Scrape' button to begin the scraping process. The tool retrieves and structures data based on your model.  

4. **Export or Analyze**  
   - Download the structured data in JSON format for use in grant optimization efforts, or view the insights directly within the app.  
