# MultiLanguage Invoice Extractor

Extract key information from multi-language invoices with ease.

## Features

Multilingual support: Handles invoices in various languages, leveraging the power of Gemini Pro Vision.
User-friendly interface: Streamlit app provides a straightforward way to upload invoices and input prompts.
Flexible querying: Answer any invoice-related questions using natural language.
Customizable prompts: Tailor prompts to extract specific information.
Clone the repository:
git clone https://github.com/MayankGuptaaa/invoice-extractor
Install dependencies:
pip install -r requirements.txt
Set up environment variables:
Create a .env file in the project directory.
Add your Google API key:
GOOGLE_API_KEY=your_api_key
Run the app:
streamlit run app.py
## Usage

Upload an invoice image (JPG, JPEG, or PNG).
Enter a prompt or question about the invoice.
Click "Tell me about the invoice."
View the extracted information.
## Technology Stack

Python
Streamlit
Gemini Pro Vision
dotenv
