<br/>
<p align="center">
  <h3 align="center">
    FastAPI Project
  </h3>

  <p align="center">
    Learn Basic FastAPI by Building Simple Booking Reservation Information System Prototype
    <br/>
  </p>
  <p align="center">
    <a href="https://dzalhaqi.github.io/api-docs-basic-booking-resevation-information-system/">
      View API docs
    </a>
  </p>
</p>

<p align="center">
  <p align="center">
    <img src="https://img.shields.io/github/downloads/dzalhaqi/fastapi-basic-booking-resevation-information-system/total"/>
    <img src="https://img.shields.io/github/contributors/dzalhaqi/fastapi-basic-booking-resevation-information-system?color=dark-green"/>
    <img src="https://img.shields.io/github/forks/dzalhaqi/fastapi-basic-booking-resevation-information-system?style=social"/>
    <img src="https://img.shields.io/github/issues/dzalhaqi/fastapi-basic-booking-resevation-information-system"/>
    <img src="https://img.shields.io/github/license/dzalhaqi/fastapi-basic-booking-resevation-information-system"/>
  </p>
</p>

## Table Of Contents

- [Table Of Contents](#table-of-contents)
- [About The Project](#about-the-project)
  - [Description](#description)
  - [Preview API Docs (using Redocly)](#preview-api-docs-using-redocly)
- [Built With](#built-with)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## About The Project

### Description
This project is build aims to improving my skill and knowledge about microservice with python using FastAPI library. This intelligent tourist system prototype is developed with the purpose of offering comprehensive booking information and reservations for various tourist spots. The system is capable of providing users with detailed tourist spot information, along with location grids. Moreover, it enables users to leave comments and ratings for the tours they experience. To ensure smooth operation, the prototype includes an administrator account with privileges to add and remove tour details, manage users, and provide listings. **However, it's important to note that the current version of the application does not utilize any database management system; instead, all data is temporarily stored in Python collections**.

### Preview API Docs (using Redocly)

![image](https://github.com/Dzalhaqi/fastapi-basic-booking-resevation-information-system/assets/52716202/a96dd3d8-76f1-4af1-9e8d-2667eabe82ab)


## Built With

Application deployed is build with **Python** using **FastAPI** library 

## Getting Started

To get a local copy up and running follow these simple example steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.

* python

for Windows OS
```sh
python --version 
```

for Unix Based OS (Linux, MacOS, etc)
```sh
python3 --version 
```

* git

```sh
git --version 
```

> note: if you don't have python installed, you can download it [here](https://www.python.org/downloads/) and if you don't have git installed, you can download it [here](https://git-scm.com/downloads)

### Installation

1. Clone the repo

```sh
git clone https://github.com/Dzalhaqi/fastapi-basic-booking-resevation-information-system.git
```

2. Create python environment

```sh
python -m venv env
```

3. Activate python environment

* for Windows OS
```sh
env\Scripts\activate
```

* for Unix Based OS (Linux, MacOS, etc)
```sh
source env/bin/activate
```

4. Install python library

```sh
pip install -r requirements.txt
```

5. Run the FastAPI server with uvicorn (default port 8000)

```sh
uvicorn main:app --reload
```

## License

Distributed under the MIT License. See [LICENSE](https://github.com/dzalhaqi/fastapi-basic-booking-resevation-information-system/blob/main/LICENSE) for more information.

## Acknowledgements

* [Muhammad Dzalhaqi](https://github.com/dzalhaqi/)
