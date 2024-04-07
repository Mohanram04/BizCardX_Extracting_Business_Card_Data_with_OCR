# BizCardX: Automating Business Card Data Extraction

BizCardX is a powerful Streamlit application designed to streamline the process of extracting and managing business card information. With the ability to upload business card images, the app employs Optical Character Recognition (OCR) technology to effortlessly extract and organize essential details, such as the company name, cardholder name, designation, contact information, and more.

## Features

- **Image Processing**: Easily upload a business card image, and let the application process it using OCR.
- **Data Extraction**: Extracted information includes the cardholder's name, company name, designation, contact number, email address, website URL, and address details.
- **Data Storage**: Store multiple entries with their respective business card images and extracted data in a database.
- **Data Management**: Users can view, update, and delete entries directly through the application's intuitive user interface.
- **Efficiency**: Save time and reduce transcription errors with automated data extraction.

## Technologies

- **Python**: The application is developed in Python.
- **Streamlit**: The user interface is created using Streamlit, making it easy to build web apps.
- **easyOCR**: Utilizes the easyOCR library for Optical Character Recognition.
- **SQLite**: The SQLite database is used for storing extracted data.

## Getting Started

1. Clone the repository or download the code.
2. Install the required dependencies, including Streamlit and easyOCR.
3. Run the Streamlit app using `streamlit run Bizcard.py`.
4. Upload a business card image and start extracting data.

## Usage

- Upload a business card image by clicking the "Choose a Image" button.
- The app will automatically extract the relevant information from the image.
- You can view the extracted data on the right side of the application.
- Click "Update database" to save the extracted data to the database.
- Click "Delete the details in the database" to remove specific entries.

## Project Architecture

- The project uses Python for backend processing.
- Streamlit is responsible for creating the user interface.
- easyOCR is used for Optical Character Recognition.
- Data is stored in an SQLite database.

## Future Enhancements

- Add more options for data manipulation and analysis.
- Implement user authentication and access control.
- Support more languages for OCR.
- 
## NOTE - Use the below comments to run the application using google colab
!npm install localtunnel
!streamlit run Bizcard.py &>/content/logs.txt & npx localtunnel --port 8501
