# BGMI Tournament Management System

This project is a comprehensive web application built using Flask that helps efficiently manage BGMI (Battlegrounds Mobile India) tournaments. It features advanced points standings management, team tracking, and multiple export options with a professional gaming-themed UI.

![BGMI Tournament Manager](https://i.imgur.com/qIxfvXU.png)

## Features

### Core Functionality
- Sort and manage BGMI points standings with automatic calculations
- Add and remove teams with detailed statistics tracking
- Generate export files in multiple formats (PDF, Excel, Word)
- User-friendly interface designed specifically for eSports tournaments

### Advanced UI
- Professional gaming-themed interface with frost-glass effect
- Responsive design for all devices 
- Animated interactive elements
- Custom gaming typography and styling

### Tournament Management
- Track position points, finish points, and chicken dinners
- Automatic calculation of total points and ranking
- Real-time updates to standings

### Sharing & Export Options
- Create shareable links to tournament standings
- Social media sharing integration (WhatsApp, Telegram)
- Multiple export formats for tournament documentation

---

## Technologies Used
- **Backend Framework**: Flask (v2.3.2)
- **PDF Generation**: ReportLab (v3.6.14)
- **Excel Manipulation**: OpenPyxl (v3.1.2)
- **Word Document Support**: python-docx (v0.8.11)
- **Frontend**: HTML5, CSS3, Tailwind CSS, JavaScript

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/bgmi-tournament-manager.git
   cd bgmi-tournament-manager
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
bgmi-tournament-manager/
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

Developed by [Avinash Yadav](https://github.com/Avinash-yadav103).

