# Chat with any CSV 📊

A Streamlit-based application that allows users to interact with CSV files through a conversational interface. Upload your CSV, ask questions about its contents, and get intelligent responses powered by a Large Language Model (LLM).

---

## Features
- **CSV Upload**: Upload and preview CSV files directly in the app.
- **Intelligent Query Handling**: Ask questions about your CSV's contents, and get accurate, AI-generated responses.
- **Chat Interface**: User-friendly chat interface for seamless interaction.
- **LLM Integration**: Utilizes Groq’s `llama3-70b-8192` model for intelligent and contextual responses.

---

## How It Works
1. **CSV Upload**:
   - Users upload CSV files, which are displayed in the sidebar for preview.
   - Validates the CSV file to ensure it is not empty.

2. **Question Answering**:
   - Users input prompts through a chat interface.
   - The app processes the query using a CSV agent integrated with the Groq LLM.

---

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Osama-Abo-Bakr/Chat-with-any-csv.git
   cd Chat-with-any-csv
   ```

2. **Install Dependencies**:
   - Create a virtual environment:
     ```bash
     python -m venv venv
     source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
     ```
   - Install required packages:
     ```bash
     pip install -r requirements.txt
     ```

3. **Set Up Environment Variables**:
   - Create a `.env` file in the project directory and add your credentials:
     ```plaintext
     GROQ_API_KEY=your_groq_api_key
     ```

---

## Usage

1. **Run the Application**:
   ```bash
   streamlit run app.py
   ```

2. **Upload and Interact**:
   - Use the sidebar to upload your CSV file.
   - Ask questions or provide prompts in the chat input.
   - View AI-generated responses based on the CSV data.

---

## Dependencies
- **[Streamlit](https://streamlit.io/)**: For building the interactive web application.
- **[LangChain](https://langchain.com/)**: For integrating the conversational agent.
- **[Pandas](https://pandas.pydata.org/)**: For reading and previewing CSV files.
- **[Groq](https://groq.com/)**: For large language model-based question answering.

---

## Future Improvements
- Add support for large CSV files with efficient processing.
- Enhance UI/UX with data visualization features.
- Enable exporting chat history for reference.
- Add support for additional file formats (e.g., Excel).

---

## Contributing
Contributions are welcome! Feel free to fork the repository and submit a pull request.

---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Author
**Osama Abo Bakr**  
GitHub: [Osama-Abo-Bakr](https://github.com/Osama-Abo-Bakr)

---

## Acknowledgments
- Special thanks to the developers of Streamlit, LangChain, Pandas, and Groq for their amazing tools!