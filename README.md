# Multi PDF Chatbot

The **Multi PDF Chatbot** project is a sophisticated tool designed to enhance user interaction with PDF files. Leveraging the power of Langchain and Gemini AI APIs, this project facilitates seamless communication between users and their uploaded PDF documents. By integrating advanced techniques such as data chunking, binarization, and vector database management using FAISS, the Multi PDF Chatbot ensures efficient processing and retrieval of relevant information from PDF files.

## Key Features

- **Interactive Chat Interface**: Users can engage in conversational queries with the chatbot regarding the contents of the uploaded PDF files.

- **PDF Data Extraction**: The system extracts data from uploaded PDF files, breaking it down into smaller, more manageable chunks for efficient processing.

- **Binarization**: Data extracted from PDF files is binarized, allowing for streamlined storage and retrieval processes.

- **Vector Database Integration**: Utilizing FAISS, the extracted and binarized data is compiled into a vector database, optimizing search operations and clustering similar data together.

- **Prompt-Based Retrieval**: Users can input prompts specifying the information they seek within the PDF files, and the chatbot will retrieve relevant data based on these prompts.

## How It Works

1. **Data Extraction**: Upon uploading a PDF file, the system extracts text and other relevant data, dividing it into smaller units.

2. **Binarization**: Extracted data is binarized, converting it into a format suitable for storage and efficient retrieval.

3. **Vector Database Compilation**: Binarized data is compiled into a vector database using FAISS, allowing for fast and accurate search operations.

4. **User Interaction**: Users can interact with the chatbot by providing prompts related to the content of the PDF files.

5. **Data Retrieval**: Based on user prompts, the chatbot retrieves relevant information from the vector database and presents it to the user.

## Technologies Used

- **Langchain API**: Facilitates natural language processing for user queries and interactions.

- **Gemini AI API**: Enables intelligent data extraction and analysis from PDF files.

- **FAISS**: Fast Approximate Nearest Neighbor Search library for efficient vector database management.

## Usage

To utilize the Multi PDF Chatbot:

1. Upload one or more PDF files containing the desired information.
2. Interact with the chatbot by providing prompts or questions related to the content of the PDF files.
3. Press the process button to initiate data retrieval based on user prompts.
4. Review the information provided by the chatbot regarding the queried topics within the PDF files.

## Contributions and Support

Contributions to the project are welcome! If you encounter any issues or have suggestions for improvements, please feel free to submit a pull request or open an issue on GitHub.

For support or inquiries, you can reach out to the project maintainers through GitHub.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to modify and distribute it according to the terms of the license.

---

By integrating cutting-edge technologies and intuitive user interfaces, the Multi PDF Chatbot project aims to revolutionize the way users interact with and extract information from PDF documents. Whether for research, education, or business purposes, this tool provides a seamless and efficient solution for accessing valuable insights locked within PDF files.
