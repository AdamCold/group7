## **DevOps Group Project By G7**


## Overview

This is a Java application that connects to a MySQL database containing world data. Developed by Htoo Myat Linn, Kyaw Ko Ko San, Bhone Myat, Wai Yan Moe, Zayar Phyo, and Pyae Sone, this application demonstrates essential database interactions and queries. It provides functionalities to retrieve and display information about countries and cities, filter data by continent, country, district and region, and showcase top-populated countries.


## Population and Demographics Feature

### Reports Generation
- Generate reports on country populations and demographics:
  - All countries in the world, continent, or region, organized by population.
  - Top 10 populated countries globally, in a continent, or in a region.
  - All cities worldwide, by continent, region, country, or district, sorted by population.
  - Top 10 populated cities globally, in a continent, region, country, or district.
  - All capital cities globally, by continent, or region, sorted by population.
  - Top 10 populated capital cities globally, in a continent, or region.
  - Population statistics of people, people living in cities, and people not living in cities, for each continent, region, and country.

### Language Statistics
- Provide statistics on the number of people speaking specific languages globally:
  - Including the percentage of the world population.
  - Languages include Chinese, English, Hindi, Spanish, and Arabic.

### Customized Reports
- Allow users to request reports with customizable parameters:
  - Choose specific continents, regions, countries, or districts.
  - Specify the number of top 10 populated entities (countries, cities, or capital cities).

### Data Retrieval
- Connects to a MySQL database to retrieve information on countries, cities, and demographics.
- Detailed reports with columns such as code, name, continent, region, population, capital, etc.

### Supported Reports:
#### Country Report
- Provides detailed information about countries, including code, name, continent, region, population, and capital.

#### City Report
- Displays essential data about cities, including name, country, district, and population.

#### Capital City Report
- Offers insights into capital cities, including name, country, and population.

#### Population Report
- Presents comprehensive population statistics for continents, regions, and countries:
  - Total population.
  - Population living in cities (with percentage).
  - Population not living in cities (with percentage).

### Additional Features
- Filter countries and cities by continent, country, district, or region.
- Identify top 10 populated entities globally or within specified parameters.

### Report Screenshots
Find the screenshots of generated reports in the following link:
[Final Reports Screenshots](https://github.com/AdamCold/group7/tree/master/final%20reports)

## Integration Test Coverage

This project emphasizes integration test coverage to ensure the reliability and correctness of key functionalities. Various scenarios including positive, negative, zero, and null inputs have been tested to enhance the reliability of the application. Additionally, invalid input scenarios have been included to handle unexpected situations. This update lays a foundation for further development and ensures the stability of the application.

## Usage

1. Clone the repository.
2. Set up the MySQL database with the required schema (details provided in the application).
3. Run the `App` class to explore country and city data interactively.

## Requirements

- Java Development Kit (JDK)
- MySQL Database

## Contributors

- [![Htoo Myat Linn](https://img.shields.io/badge/-Htoo_Myat_Linn-00cc00.svg)](https://github.com/AdamCold)

- [![Kyaw Ko Ko San](https://img.shields.io/badge/-Kyaw_Ko_Ko_San-00cc00.svg)](https://github.com/KyawKoKoSan)

- [![Bhone Myat](https://img.shields.io/badge/-Bhone_Myat-00cc00.svg)](https://github.com/bhonemyat88)

- [![Wai Yan Moe](https://img.shields.io/badge/-Wai_Yan_Moe-00cc00.svg)](https://github.com/WaiYanMoe-Devop)

- [![Pyae Sone](https://img.shields.io/badge/-Pyae_Sone-00cc00.svg)](https://github.com/SonePyae)

- [![Zayar Phyo](https://img.shields.io/badge/-Zayar_Phyo-00cc00.svg)](https://github.com/zayarphyo18)
  
## Version


- Master Build Status ![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/AdamCold/group7/main.yml?branch=master)

- Develop Build Status ![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/AdamCold/group7/main.yml?branch=develop)

- License [![LICENSE](https://img.shields.io/github/license/AdamCold/group7.svg?style=flat-square)](https://github.com/AdamCold/group7/blob/master/LICENSE)

- Release [![Releases](https://img.shields.io/github/release/AdamCold/group7/all.svg?style=flat-square)](https://github.com/AdamCold/group7/releases)

- [![codecov](https://codecov.io/gh/AdamCold/group7/graph/badge.svg?token=7I4F1K7UUK)](https://codecov.io/gh/AdamCold/group7)
