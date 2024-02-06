<h1 align="center">Web Scraping with Python</h1>
<a name="readme-top"></a>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#author">Author</a></li>
  </ol>
</details>

<!--ABOUT THE PROJECT-->
## About the Project

![web_scraping](https://github.com/kira-vik/WebScraping-with-Python/assets/35596661/8111a3f6-9d79-4df9-9aed-6a690b5af3de)

This project gets us started on how to scrape multiple web pages using the BeautifulSoup library, and storing the scraped data in a Pandas Dataframe. The generated dataframe is then exported into an external file, which in this case is a CSV file. The web scraping playground used for this project is [books.toscrape.com](https://books.toscrape.com/), where we retrieve details of the books in the catalog such as the book title, the price, and the star rating. This project helps build skill and understand the mechanism of how web scraping works.

This project has been developed in VS Code, but it is okay to use your code editor of choice.

### Built With

- VS Code
- Python 3.11.0
- Jupyter Notebooks

<p align="right">
     [<a href="#readme-top">back to top</a>]
</p>

<!--GETTING STARTED-->
## Getting Started

### Prerequisites

Here are a few of the resources that you will need to properly set up the project and get it running in your system.

- [Python](https://www.python.org/downloads/)
- A code editor
- Jupyter Notebooks
- Alternatively, check out [Google Colab](https://colab.google/)

### Installation

Clone the repository by running the following command in your project directory:

```bash
git clone {project-link}
```

You can open the cloned repository in VS Code using the command in your project directory:

```bash
code . {project-path}
```

Set up a virtual environment to keep necessary dependencies isolated to this particular project:

```bash
python -m venv {virtual_env_name}
```

Activate the virtual environment:

- On Windows:

```bash
{virtual_env_name}\Scripts\activate
```

- On macOS/Linux:

```bash
source {virtual_env_name}/bin/activate
```

Download the required libraries using the command in your project terminal:

```bash
pip install -r requirements.txt
```

Head over to [books.toscrape.com](https://books.toscrape.com/) to get better acquainted with the website, and understand which elements in the site are of interest.
Finally, you can run the code cell by cell since it has been written in Jupyter Notebooks.

<p align="right">
     [<a href="#readme-top">back to top</a>]
</p>

<!--AUTHOR-->

## Author

Victor Weke - @[kira-vik](https://github.com/kira-vik)

Project Link: [JSON data to Pandas Dataframe](https://github.com/kira-vik/JSON-data-to-Pandas-Dataframe)

<p align="right">
     [<a href="#readme-top">back to top</a>]
</p>
