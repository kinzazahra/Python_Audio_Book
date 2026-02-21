PDF to Audio Converter
A modern, immersive web application that transforms your reading experience by converting PDF documents into high-quality audio narration. This tool allows users to listen to their favorite books or documents on the go with customizable voice settings.

Built with ❤️ by Khurram Rashid & Kinza Zahra 🎧

Features
Seamless PDF Conversion: Quickly extract text from any PDF file and transform it into clear, natural-sounding audio.

Customizable Experience:

Voice Selection: Choose between Male and Female narrators to suit your preference.

Speed Control: Adjust the speaking rate (Slow, Normal, Fast) for the perfect listening pace.

Modern User Interface:

Dynamic Theming: Includes a built-in Dark Mode/Light Mode toggle for comfortable viewing in any environment.

Interactive Elements: Features a drag-and-drop upload area with real-time file name display and hover glow effects.

Responsive Design: A grid-based layout that works beautifully on both desktop and mobile devices.

Secure & Private: Your files are processed securely on the backend using Python-based libraries.

Downloadable Output: Once converted, you can listen to the audio directly in the browser or download it as an MP3 file.

🛠 Tech Stack
Frontend: HTML5, CSS3 (Custom Variables & Grid), Vanilla JavaScript.

Backend: Python (Flask Framework).

Core Libraries:

PyMuPDF (fitz): For high-performance PDF text extraction.

pyttsx3: For robust offline Text-to-Speech conversion.

Server: Gunicorn.

📂 Project Structure
Plaintext
Python_Audio_Book/
│
├── app.py              # Flask backend logic and audio processing
├── requirements.txt    # Python dependencies
├── Procfile            # Deployment configuration for web servers
├── uploads/            # Temporary storage for uploaded PDFs
│
├── static/
│   ├── css/styles.css  # Themed styling and responsiveness
│   ├── js/script.js    # UI interactions and progress handling
│   └── audio.mp3       # The generated output file
│
└── templates/          # HTML views
    ├── index.html      # Main converter interface
    └── result.html     # Audio player and download page
⚙️ Installation & Setup
Clone the Repository:

Bash
git clone <your-repo-url>
cd Python_Audio_Book
Install Dependencies:

Bash
pip install -r requirements.txt
Run the Application:

Bash
python app.py
Open your browser and navigate to http://localhost:5000.

🚀 How to Use
Upload: Drag and drop your PDF or click "Browse Files" to select a document.

Customize: Select your preferred voice (Male/Female) and narration speed.

Convert: Click "Convert to Audio" and wait for the progress bar to complete.

Listen & Download: Play the audio in the result card or download the MP3 to your device.

🔮 Future Improvements
Support for multiple languages.

Cloud storage integration for saving audiobooks.

Advanced text cleaning to skip headers, footers, and page numbers.

Made with ❤️ by Khurram Rashid & Kinza Zahra
