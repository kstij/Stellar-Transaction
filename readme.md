[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />

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
        <li><a href="#runnning-the-application">Running The Application</a></li>
      </ul>
    </li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project


This project aims to create a web application that interacts with the Stellar blockchain network, allowing users to manage their Stellar accounts. The application provides functionalities to fetch Stellar account balances and to send XML payments to other Stellar wallets. It is built using Python and Flask, leveraging the power and flexibility of these technologies to provide a seamless user experience.

### Built With

This section should list any major frameworks/libraries used to bootstrap your project. Leave any add-ons/plugins for the acknowledgements section. Here are a few examples.

* Stellar SDK for Python: The Stellar SDK is utilized to interact with the Stellar network, perform transactions, and fetch account information.
* Python: The core programming language used for the backend logic.
* Flask: A lightweight WSGI web application framework for Python, used to build the web interface and handle HTTP requests and responses.
* HTML/CSS/: For creating the front-end interface of the web application.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

### Prerequisites

Before you can run the project, ensure you have the following installed on your system:

* Python 3.6+
* pip (Python package installer)
* Flask

### Installation

_Follow these steps to set up the project:._

1. Clone the repo
   ```sh
   git clone https://github.com/yourusername/stellar-wallet-management.git
   cd stellar-wallet-management
   ```
2. It's recommended to use a virtual environment to manage dependencies. Create and activate a virtual environment:
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```
3. Install Dependencies
   ```sh
   pip install -r requirements.txt
4. Install Dependencies
   ```sh
   pip install flask stellar-sdk

   ``` 
### Runnning the Application

_Follow these steps to set up the project:._

1. Create a Virtual Enviornment
   ```sh
   python -m venv env
   ```
2. Activate Virtual Environment
   ```sh
   .\env\Scripts\activate
   ```
3. Let Flask know where the aplication is
   ```sh
   $env:FLASK_APP = "stellar-app"
   ```
4. Run Flask App
   ```sh
   Flask run
   ```
[linkedin-url]: https://linkedin.com/in/kshitijvarma21
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555