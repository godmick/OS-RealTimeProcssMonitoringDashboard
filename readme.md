# System Process Monitor

A simple *Flask-based web application* that displays system process data (CPU and memory usage) in a styled frontend.

## Features
- Fetches real-time system process data using psutil.
- Displays process details (PID, Name, CPU %, Memory Usage) in a styled table.
- Auto-refreshes every 5 seconds.
- Simple, clean, and responsive UI.

## Technologies Used
- *Backend*: Flask, psutil (Python)
- *Frontend*: HTML, CSS, JavaScript

## Installation
### 1. Clone the repository

git clone https://github.com/your-username/system-process-monitor.git


### 2. Install dependencies
Make sure you have Python installed. Then run:

pip install flask psutil

### 3. Run the Flask server
python app.py


### 4. Open the frontend
Simply open index.html in your browser.

## Project Structure

project-folder/
│-- app.py         # Flask backend
│-- templates/
│   ├── index.html # Frontend UI
│-- static/
│   ├── styles.css # Styles
│   ├── script.js  # JavaScript for fetching data
│-- README.md      # Project Documentation


## How It Works
1. The Flask server (app.py) provides an API endpoint: /api/data.
2. The frontend (index.html) fetches system process data using script.js.
3. The data is displayed in a styled table (styles.css).
4. The table updates every *5 seconds*.

## Preview
![Preview Image](https://via.placeholder.com/800x400.png?text=System+Process+Monitor)

## Contributing
Feel free to open an issue or submit a pull request!

## License
This project is *open-source* and available under the MIT License.

---
*Author:* [Adithiya RS](https://github.com/godmick)
	  [Meka Chandra Sai Charitha](https://github.com/vikramkumar18)
	  [Thota Uday Sai](https://github.com/udaysaithota34)

Here's readme file