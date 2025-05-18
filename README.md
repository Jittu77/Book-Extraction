📚 Book Information Extraction to CSV
This project is a Python Jupyter Notebook that extracts book information from an online source (such as a books website like books.toscrape.com) and exports the data into a CSV file. It utilizes web scraping techniques using requests, BeautifulSoup, and pandas.

🚀 Features
Scrapes multiple pages of book listings

Extracts details like:

Title

Price

Stock availability

Rating

Saves the extracted data to a structured CSV file

Easy-to-understand and customizable code

🧰 Technologies Used
Python 3

Jupyter Notebook

requests – for HTTP requests

BeautifulSoup – for HTML parsing

pandas – for tabular data management and CSV export

📦 Installation
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/book-extraction-to-csv.git
cd book-extraction-to-csv
Create a virtual environment (optional but recommended):

bash
Copy
Edit
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install required packages:

bash
Copy
Edit
pip install -r requirements.txt
If requirements.txt is not provided, install manually:

bash
Copy
Edit
pip install requests beautifulsoup4 pandas
Launch the notebook:

bash
Copy
Edit
jupyter notebook
📄 Usage
Open the notebook book_extration_to_csv_file (1).ipynb.

Run all cells.

The scraped data will be saved as a CSV file (books.csv by default).

You can change the number of pages to scrape or customize the URL in the notebook.

📝 Example Output (books.csv)
Title	Price	Availability	Rating
A Light in the Attic	£51.77	In stock	Three
Tipping the Velvet	£53.74	In stock	One
Soumission	£50.10	In stock	One

⚠️ Disclaimer
This notebook is for educational purposes. Please respect the website's terms of service before scraping large amounts of data.

📬 Contact
For suggestions or questions, feel free to reach out via GitHub Issues or email.
