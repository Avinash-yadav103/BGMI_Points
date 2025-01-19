# BGMI Points Standings Sorter

This project is a web application built using Flask that helps to efficiently sort BGMI points standings. It is designed to reduce time and manpower when creating PDFs for large tournaments.

## Features
- Sort and manage BGMI points standings easily.
- Generate PDFs of sorted standings for tournament use.
- Supports importing and exporting data in Excel format.
- User-friendly interface to streamline tournament management.

---

## Technologies Used
- **Backend Framework**: Flask (v2.3.2)
- **PDF Generation**: ReportLab (v3.6.14)
- **Excel Manipulation**: OpenPyxl (v3.1.2)
- **Word Document Support**: python-docx (v0.8.11)

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/bgmi-points-sorter.git
   cd bgmi-points-sorter
   ```

2. Set up a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the Flask application:
   ```bash
   flask run
   ```

---

## Usage

1. Open the application in your browser at `http://127.0.0.1:5000/`.
2. Upload Excel files with team data and points standings.
3. Use the application to sort and format the standings.
4. Generate PDFs for the standings with a single click.

---

## Prerequisites

Ensure the following are installed on your system:
- Python 3.7 or higher
- Pip (Python package manager)

---

## File Structure

```
bgmi-points-sorter/
│
├── app.py              # Main Flask application
├── templates/          # HTML templates for the web interface
├── static/             # Static files (CSS, JS, images)
├── data/               # Folder for uploaded and generated files
├── requirements.txt    # List of dependencies
└── README.md           # Project documentation
```

---

## Dependencies

The project uses the following Python libraries:
- **Flask**: Web framework for building the application.
- **ReportLab**: For creating PDFs.
- **OpenPyxl**: For reading and writing Excel files.
- **python-docx**: For Word document processing.

Install these libraries using the following command:
```bash
pip install Flask==2.3.2 reportlab==3.6.14 openpyxl==3.1.2 python-docx==0.8.11
```

---

## Contribution

Contributions are welcome! Feel free to fork the repository and create a pull request with your changes.

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Author

Developed by [Your Name](https://github.com/your-username).

