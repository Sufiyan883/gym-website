# gym-website
It is gym webiste using flask for uni project

# Gym Management System

A basic Gym Management System website built using Flask, HTML, and CSS. This project demonstrates how to create a simple web application with multiple pages, manage routes using Flask, and serve dynamic content using templates. The website is styled with CSS to provide a clean and user-friendly interface.

## Features

1. **Home Page**
   - Displays a welcoming message.
   - Highlights the key features of the gym.

2. **About Us Page**
   - Shares details about the gym's mission.
   - Introduces the gym team and facilities.

3. **Membership Page**
   - Showcases various membership plans.
   - Lists the services offered by the gym.

## Project Structure

```
Gym-Management-System/
├── app.py               # Main Flask application file
├── templates/           # HTML templates folder
│   ├── base.html        # Base template with shared layout
│   ├── home.html        # Home page template
│   ├── about.html       # About Us page template
│   └── membership.html  # Membership page template
├── static/              # Static assets folder
│   ├── css/             # CSS files
│   │   └── styles.css   # Main stylesheet
│   └── images/          # Image files
└── README.md            # Project documentation (this file)
```

## Requirements

Ensure you have the following installed:
- Python 3.x
- Flask

You can install Flask using pip:
```bash
pip install flask
```

## How to Run the Project Locally

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/Gym-Management-System.git
   cd Gym-Management-System
   ```

2. **Run the Application**:
   Execute the following command in the project directory:
   ```bash
   python app.py
   ```

3. **Access the Website**:
   Open your browser and navigate to `http://127.0.0.1:5000` to view the application.

## Customization

- Update the `templates/` folder to change the content of the pages.
- Modify the `static/css/styles.css` file to adjust the styling of the website.
- Add or replace images in the `static/images/` folder as needed.

## Contribution

Feel free to fork this repository and submit pull requests for any improvements or bug fixes. Contributions are welcome!

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

If you encounter any issues or have suggestions, please open an issue in the repository or contact the project maintainer.
