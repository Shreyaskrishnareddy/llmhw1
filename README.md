# llmhw1

![Python](https://img.shields.io/badge/python-3.8+-blue.svg) ![License](https://img.shields.io/badge/license-MIT-blue.svg)
[Add relevant technology badges based on dependencies detected]

## 🚀 Overview

The llmhw1 project utilizes the OpenAI API to create a system for mapping grocery items to aisle categories. It reads an Excel file containing a list of grocery items and aisle categories, then uses a chat completion model to match each grocery item with the most appropriate aisle category. The project is designed to run on Google Colab, utilizing the Google Drive API to access files and the `openai` library to interact with the OpenAI API.

## ✨ Key Features

- **Grocery Item-Aisle Category Mapping**: The project uses a chat completion model to match each grocery item with the most appropriate aisle category.
- **Excel File Processing**: The project reads an Excel file containing a list of grocery items and aisle categories.
- **OpenAI API Integration**: The project utilizes the OpenAI API to create a chat completion model for mapping grocery items to aisle categories.
- **Google Drive API Integration**: The project uses the Google Drive API to access files stored on Google Drive.

## 🛠️ Technology Stack

### Core Technologies
- **Python 3.8+**: The primary language used for development.
- **OpenAI API**: Used for chat completion and mapping grocery items to aisle categories.
- **Google Drive API**: Used for accessing files stored on Google Drive.
- **Google Colab**: Used as the development environment.

### Dependencies
- **google**: Used for interacting with the Google Drive API.
- **openai**: Used for interacting with the OpenAI API.
- **json**: Used for handling JSON data.
- **os**: Used for interacting with the operating system.
- **pandas**: Used for data processing and manipulation.

## 🚀 Quick Start

### Prerequisites
- **Google Drive Account**: Required for accessing files stored on Google Drive.
- **OpenAI API Key**: Required for interacting with the OpenAI API.

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/username/llmhw1.git
   cd llmhw1
   ```

2. **Set up environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Configuration**
   - **OpenAI API Key**: Set the `GROQ_API_KEY` environment variable to your OpenAI API key.
   - **Google Drive API Key**: Set the `GOOGLE_DRIVE_API_KEY` environment variable to your Google Drive API key.

### Usage

1. **Run the project**
   ```bash
   python aisle_Mapping_validation.py
   ```
   This will run the project and map each grocery item to the most appropriate aisle category.

## 📊 Project Structure

```markdown
llmhw1/
requirements.txt
aisle_Mapping_validation.py
README.md
```

## 🔧 Development

### Running Tests
There are no test files in this project.

### Code Quality
There are no linting or formatting configuration files in this project.

## 🚀 Deployment

There are no deployment configuration files in this project.

## 📖 API Documentation
There are no API endpoints defined in this project.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

None.