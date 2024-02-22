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

### Requirements Met

All 32 requirements have been successfully implemented, which is 100%.


### Feature Implementation Table

| ID  | Requirement                                                                                                      | Met  | Screenshot |
| --- | ---------------------------------------------------------------------------------------------------------------- | ---- | ---------- |
| 1   | All the countries in the world organised by largest population to smallest.                                      | Yes  | [Screenshot](https://github.com/AdamCold/group7/blob/master/final%20reports/(1)%20population%20all%20countries%20in%20the%20world.png), [Screenshot](https://github.com/AdamCold/group7/blob/master/final%20reports/(1.1)%20population%20all%20countries%20in%20the%20world.png) |
| 2   | All the countries in a continent organised by largest population to smallest.                                   | Yes  | [Screenshot](https://github.com/AdamCold/group7/blob/master/final%20reports/(2)%20populated%20countries%20in%20the%20continent.png) |
| 3   | All the countries in a region organised by largest population to smallest.                                      | Yes  | [Screenshot](https://github.com/AdamCold/group7/blob/master/final%20reports/(3)%20populated%20countries%20in%20the%20region.png) |
| 4   | The top 10 populated countries in the world.                                                                     | Yes  | [Screenshot](https://github.com/AdamCold/group7/blob/master/final%20reports/(4)%20top%2010%20populated%20countries%20in%20the%20world.png) |
| 5   | The top 10 populated countries in a continent.                                                                   | Yes  | [Screenshot](https://github.com/AdamCold/group7/blob/master/final%20reports/(5)%20top%2010%20populated%20countries%20in%20continent.png) |
| 6   | The top 10 populated countries in a region.                                                                      | Yes  | [Screenshot](https://github.com/AdamCold/group7/blob/master/final%20reports/(6)%20top%2010%20populated%20countries%20in%20region.png) |
| 7   | All the cities in the world organised by largest population to smallest.                                         | Yes  | [Screenshot](https://github.com/AdamCold/group7/blob/master/final%20reports/(7)%20All%20the%20cities%20in%20the%20world%20by%20largest%20population%20to%20smallest.png), [Screenshot](https://github.com/AdamCold/group7/blob/master/final%20reports/(7.1)%20All%20the%20cities%20in%20the%20world%20by%20largest%20population%20to%20smallest.png) |
| 8   | All the cities in a continent organised by largest population to smallest.                                      | Yes  | [Screenshot](https://github.com/AdamCold/group7/blob/master/final%20reports/(8)%20All%20the%20cities%20in%20a%20continent%20by%20largest%20population%20to%20smallest.png), [Screenshot](https://github.com/AdamCold/group7/blob/master/final%20reports/(8.1)%20All%20the%20cities%20in%20a%20continent%20by%20largest%20population%20to%20smallest.png) |
| 9   | All the cities in a region organised by largest population to smallest.                                         | Yes  | [Screenshot](https://github.com/AdamCold/group7/blob/master/final%20reports/(9)%20All%20Cities%20in%20a%20region%20by%20Population.png), [Screenshot](https://github.com/AdamCold/group7/blob/master/final%20reports/(9.1)%20All%20Cities%20in%20a%20region%20by%20Population.png) |
| 10  | All the cities in a country organised by largest population to smallest.                                        | Yes  | [Screenshot](https://github.com/AdamCold/group7/blob/master/final%20reports/(10)%20All%20Cities%20in%20a%20Country%20by%20Population.png) |
| 11  | All the cities in a district organised by largest population to smallest.                                       | Yes  | [Screenshot](https://github.com/AdamCold/group7/blob/master/final%20reports/(11)%20All%20Cities%20in%20a%20District%20%20by%20Population.png), [Screenshot](https://github.com/AdamCold/group7/blob/master/final%20reports/(11.1)%20All%20Cities%20in%20a%20District%20%20by%20Population.png) |
| 12  | The top 10 populated cities in the world.                                                                        | Yes  | [Screenshot](https://github.com/AdamCold/group7/blob/master/final%20reports/(12)%20Top%2010%20populated%20cities%20in%20a%20world.png) |
| 13  | The top 10 populated cities in a continent.                                                                     | Yes  | [Screenshot](https://github.com/AdamCold/group7/blob/master/final%20reports/(13)%20Top%2010%20populated%20cities%20in%20a%20continent.png) |
| 14  | The top 10 populated cities in a region.                                                                        | Yes  | [Screenshot](https://github.com/AdamCold/group7/blob/master/final%20reports/(14)%20Top%2010%20populated%20cities%20in%20a%20region.png) |
| 15  | The top 10 populated cities in a country.                                                                       | Yes  | [Screenshot](https://github.com/AdamCold/group7/blob/master/final%20reports/(15)%20Top%2010%20populated%20cities%20in%20a%20country.png) |
| 16  | The top 10 populated cities in a district.                                                                      | Yes  | [Screenshot](https://github.com/AdamCold/group7/blob/master/final%20reports/(16)%20Top%2010%20populated%20cities%20in%20a%20district.png) |
| 17  | All the capital cities in the world organised by largest population to smallest.                                | Yes  | [Screenshot](https://github.com/AdamCold/group7/blob/master/final%20reports/(17)%20All%20the%20capital%20cities%20in%20the%20world%20organised%20by%20largest%20population%20to%20smallest.png), [Screenshot](https://github.com/AdamCold/group7/blob/master/final%20reports/(17.1)%20All%20the%20capital%20cities%20in%20the%20world%20organised%20by%20largest%20population%20to%20smallest.png) |
| 18  | All the capital cities in a continent organised by largest population to smallest.                             | Yes  | [Screenshot](https://github.com/AdamCold/group7/blob/master/final%20reports/(18)%20All%20the%20capital%20cities%20in%20a%20continent%20organised%20by%20largest%20population%20to%20smallest.png), [Screenshot](https://github.com/AdamCold/group7/blob/master/final%20reports/(18.1)%20All%20the%20capital%20cities%20in%20a%20continent%20organised%20by%20largest%20population%20to%20smallest.png) |
| 19  | All the capital cities in a region organised by largest to smallest.                                             | Yes  | [Screenshot](https://github.com/AdamCold/group7/blob/master/final%20reports/(19)%20All%20the%20capital%20cities%20in%20a%20region%20organised%20by%20largest%20to%20smallest..png) |
| 20  | The top 10 populated capital cities in the world.                                                               | Yes  | [Screenshot](https://github.com/AdamCold/group7/blob/master/final%20reports/(20)%20The%20top%2010%20populated%20capital%20cities%20in%20the%20world%20.png) |
| 21  | The top 10 populated capital cities in a continent.                                                             | Yes  | [Screenshot](https://github.com/AdamCold/group7/blob/master/final%20reports/(21)%20The%20top%2010%20capital%20cities%20in%20Europe%20.png) |
| 22  | The top 10 populated capital cities in a region.                                                                | Yes  | [Screenshot](https://github.com/AdamCold/group7/blob/master/final%20reports/(22)%20The%20top%2010%20capital%20cities%20in%20the%20Sotheast%20Asia%20.png) |
| 23  | The population of people, people living in cities, and people not living in cities in each continent.          | Yes  | [Screenshot](https://github.com/AdamCold/group7/blob/master/final%20reports/(23)%20Population%20Detailed%20by%20Continent.png) |
| 24  | The population of people, people living in cities, and people not living in cities in each region.             | Yes  | [Screenshot](https://github.com/AdamCold/group7/blob/master/final%20reports/(24)%20Population%20Detailed%20by%20Region.png), [Screenshot](https://github.com/AdamCold/group7/blob/master/final%20reports/(24.1)%20Population%20Detailed%20by%20Region.png) |
| 25  | The population of people, people living in cities, and people not living in cities in each country.            | Yes  | [Screenshot](https://github.com/AdamCold/group7/blob/master/final%20reports/(25.1)%20Population%20of%20the%20capital%20cities%20in%20a%20continent.png), [Screenshot](https://github.com/AdamCold/group7/blob/master/final%20reports/(25.2)%20Population%20of%20the%20capital%20cities%20in%20a%20continent.png) |
| 26  | The population of the world.                                                                                    | Yes  | [Screenshot](https://github.com/AdamCold/group7/blob/master/final%20reports/(26)%20Population%20of%20the%20capital%20cities%20in%20a%20region.png) |
| 27  | The population of a continent.                                                                                  | Yes  | [Screenshot](https://github.com/AdamCold/group7/blob/master/final%20reports/(27)%20Top%2010%20populated%20capital%20cities.png) |
| 28  | The population of a region.                                                                                     | Yes  | [Screenshot](https://github.com/AdamCold/group7/blob/master/final%20reports/(28)%20Top%2010%20populated%20capital%20cities%20in%20Europe.png) |
| 29  | The population of a country.                                                                                    | Yes  | [Screenshot](https://github.com/AdamCold/group7/blob/master/final%20reports/(29)%20Top%2010%20populated%20capital%20cities%20in%20Southeast%20Asia.png) |
| 30  | The population of a district.                                                                                   | Yes  | [Screenshot](https://github.com/AdamCold/group7/blob/master/final%20reports/(30)%20The%20population%20of%20people%20(living%2C%20not%20living)%20in%20Europe.png) |
| 31  | The population of a city.                                                                                       | Yes  | [Screenshot](https://github.com/AdamCold/group7/blob/master/final%20reports/(31)%20The%20population%20of%20people%20(living%2C%20not%20living)%20in%20Southeast%20Asia.png) |
| 32  | The number of people who speak certain languages globally, from greatest to smallest, including percentages.    | Yes  | [Screenshot](https://github.com/AdamCold/group7/blob/master/final%20reports/(32)%20The%20population%20of%20people%20(living%2C%20not%20living)%20in%20Myanmar.png) |


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

## Contribution Spreadsheet

| Name     | Week-1       | Week-2  | Week-3  | Week-4  | Week-5  |
|----------|--------------|---------|---------|---------|---------|
| 40632019 |  16.67%      |16.67%   |16.67%   |16.67%   |    16.66%     |
| 40632016 |  16.67%      |16.67%   |16.67%   |16.67%   |   16.66%      |
| 40632024 |  16.67%      |16.67%   |16.67%   |16.65%   |    16.67%     |
| 40616703 |  16.67%      |16.67%   |16.65%   |16.67%   |    16.67%     |
| 40616707 |  16.67%      |16.65%   |16.67%   |16.67%   |   16.67%      |
| 40632011 |  16.65%      |16.67%   |16.67%   |16.67%   |    16.67%     |
| **Total**| **100%**     |**100%** |**100%** |**100%** |      **100%**   |


## Badges

- Master Build Status ![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/AdamCold/group7/main.yml?branch=master)

- Develop Build Status ![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/AdamCold/group7/main.yml?branch=develop)

- License [![LICENSE](https://img.shields.io/github/license/AdamCold/group7.svg?style=flat-square)](https://github.com/AdamCold/group7/blob/master/LICENSE)

- Release [![Releases](https://img.shields.io/github/release/AdamCold/group7/all.svg?style=flat-square)](https://github.com/AdamCold/group7/releases)

- [![codecov](https://codecov.io/gh/AdamCold/group7/graph/badge.svg?token=7I4F1K7UUK)](https://codecov.io/gh/AdamCold/group7)
