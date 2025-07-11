# Flask Certificate Generation App

This project is a Flask web application that allows users to generate certificates using a predefined template. The application provides a user-friendly interface for entering details and generates a certificate that can be previewed and downloaded.

## Project Structure

```
flask-certificate-app
├── app.py
├── static
│   ├── fonts
│   │   ├── Poppins-Regular.ttf
│   │   └── Poppins-Bold.ttf
│   └── templates
│       └── certificate_template.png
├── templates
│   ├── index.html
│   └── preview.html
├── requirements.txt
└── README.md
```

## Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone <repository-url>
   cd flask-certificate-app
   ```

2. **Create a Virtual Environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Application**
   ```bash
   python app.py
   ```

5. **Access the Application**
   Open your web browser and go to `http://127.0.0.1:5000/` to access the certificate generation form.

## Usage Guidelines

- Fill in the required fields in the form, including your name, ID number, department, university, role, internship dates, and registration details.
- Click on the "Generate Certificate" button to create your certificate.
- You will be redirected to a preview page where you can view your generated certificate.
- If satisfied, you can download the certificate in your preferred format (PNG, JPG, PDF).
- If you wish to start over, you can click the "Cancel" button to clear the preview and return to the input form.

## License

This project is licensed under the MIT License. Feel free to modify and use it as per your requirements.