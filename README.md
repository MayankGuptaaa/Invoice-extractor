# MultiLanguage Invoice Extractor

Extract key information from multi-language invoices with ease.

## Features

- **Multilingual Support:** Handles invoices in various languages, leveraging the power of Gemini Pro Vision.
- **User-Friendly Interface:** Streamlit app provides a straightforward way to upload invoices and input prompts.
- **Flexible Querying:** Answer any invoice-related questions using natural language.
- **Customizable Prompts:** Tailor prompts to extract specific information.
## Getting Started

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/MayankGuptaaa/invoice-extractor
2. **Install Dependencies**
    ```bash
    pip install -r requirements.txt
3. **Set Up Environment Variables**

   - Create a `.env` file in the project directory.
   - Add your Google API key:

     ```env
     GOOGLE_API_KEY=your_api_key
     ```
4. **Run the App**

   ```bash
   streamlit run app.py

## Usage

1. Upload an invoice image (JPG, JPEG, or PNG).
2. Enter a prompt or question about the invoice.
3. Click "Tell me about the invoice."
4. View the extracted information.

## Technology Stack

- Python
- Streamlit
- Gemini Pro Vision
- dotenv
