# Brochure Generator: AI-Powered Company Brochure Creator

## Introduction
This project is a simple yet powerful tool that helps create a **company brochure** based on website content. It scrapes the landing page of a company's website, extracts key details, and then uses **GPT-4** to generate a structured, easy-to-read brochure.

The goal is to provide **quick, accurate, and well-formatted company summaries** for customers, investors, and potential employees. Instead of manually writing brochures, you can now generate them instantly!

---

## Features
- **Web Scraping**: Automatically extracts content from a company's website.
- **AI-Powered Summarization**: Uses OpenAI's GPT-4 to generate a well-structured brochure.
- **Frontend Interface**: A simple, user-friendly UI built with **Gradio**.
- **JSON Output for Customization**: Structured data output for easy modification.

---

## Tech Stack
- **Python**: Core programming language.
- **OpenAI GPT-4**: AI-based text generation.
- **BeautifulSoup**: Web scraping tool to extract text from websites.
- **Gradio**: Simple web interface for easy interaction.
- **dotenv**: For handling API keys securely.

---

## How It Works
### 1. Extracting Website Content
- The script scrapes the **landing page** of a company website.
- Removes unnecessary elements like images, scripts, and styles.
- Extracts text and **identifies relevant links** (e.g., About, Careers, Contact).

### 2. Processing with AI
- The extracted content is passed to **GPT-4**, which generates a structured brochure.
- The output is formatted in **Markdown**, making it easy to read or convert into a PDF.

### 3. Interactive Frontend (Gradio UI)
- Users can enter a company URL in the **Gradio interface**.
- The AI instantly processes and **returns a formatted brochure**.
- The output can be downloaded or copied for use in marketing materials.

---

## Installation & Setup
### 1. Clone the Repository
```bash
# Clone the repository to your local machine
git clone https://github.com/yourusername/brochure-generator.git
cd brochure-generator
```

### 2. Install Dependencies
```bash
# Install required Python packages
pip install -r requirements.txt
```

### 3. Set Up API Key
Create a `.env` file and add your OpenAI API key:
```ini
# OpenAI API key configuration
OPENAI_API_KEY=your-api-key-here
```

### 4. Run the Application
```bash
# Run the backend script
python app.py
```
Or, if using Gradio for the frontend:
```bash
# Run the frontend interface
python frontend.py
```

---

## Why This Project?
Creating brochures manually can be time-consuming. This project makes it easier by automating the process, ensuring **consistency, accuracy, and speed**. Whether you're a business owner, marketer, or investor, this tool simplifies company research and marketing material creation.

---

## Future Improvements
- Support for multiple pages (not just landing pages).  
- Enhanced styling options for output (PDF/HTML templates).  
- Option to customize the generated content further.

---

## Contributing
Contributions are welcome! If you'd like to improve this project, feel free to fork the repo and submit a pull request.

---

### Acknowledgments
We hope this tool makes it easier for businesses to generate professional-looking brochures effortlessly. Thank you for checking out the project!

