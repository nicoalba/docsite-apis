# MkDocs sample docsite (GitHub Pages)

This project showcases a static documentation website built using [MkDocs](https://mkdocs.org/) and hosted via GitHub Pages.

## 🛠 Tech stack

- **MkDocs**: A static site generator geared towards project documentation.
- **GitHub Pages**: A free hosting service for static websites provided by GitHub.

## 🚀 Features

- Clean and simple theme for documentation.
- Automatically generated navigation and search functionality.
- Lightweight and fast for viewing project documentation.

## Live demo

The live version of the site is available at: [https://nicoalba.github.io/sample-docsite-pages/](https://nicoalba.github.io/sample-docsite-pages/)

## Running locally

### Prerequisites

Before running the project locally, make sure you have the following installed:

1. **Python 3**: You need Python 3 to run MkDocs. Download and install Python 3 from [python.org](https://www.python.org/downloads/).
2. **MkDocs**: Install MkDocs using pip (Python's package manager):
   
    ```bash
    pip install mkdocs
    ```

## Steps to run locally

1. **Clone the repository**:
    
    To get the project files, clone the repository to your local machine using the following command:
    
    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    ```

2. Navigate to the project folder: Change to the project directory where the mkdocs.yml file is located:

    ```bash
    cd your-repo-name
    ```

3. Install dependencies (if necessary): If you're using additional extensions or themes for MkDocs, make sure they are installed:

    ```bash
    pip install -r requirements.txt
    ```

    (Note: If you don't have a requirements.txt file, you can skip this step.)

4. Run the MkDocs development server: To preview your site locally, run the following command:

    ```bash
    mkdocs serve
    ```

5. Access your site: Open your web browser and go to http://127.0.0.1:8000/ to view your documentation locally.
