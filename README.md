# Covid-19 
### Project description 
In this project we download a dataset with COVID-19 deaths, import it into an SQL database, and run a series of queries to explore the data.

We are going to download the dataset, format it a bit in Excel and get it into SQL where we will start querying it.

### Getting the Dataset
https://ourworldindata.org/covid-deaths

We download the coronovirus-data-explorer.csv from 28-Jan-2020 to 30-Apr-2021.


### Importing the dataset into an SQL database

We will format a bit the dataset in Excel. We create 2 Excels: 1 with COVID deaths and the other with COVID vaccinations.
We go to Microsoft SQL Server Management Studio and import these 2 Excels.

### Performing data exploration

We explore our 2 tables (CovidDeaths and CovidVaccinations):
- Total Cases vs Total Deaths (Shows likelihood of dying if you contract covid in your country)
- Total Cases vs Population (Shows what percentage of population infected with Covid)
- Countries with Highest Infection Rate compared to Population
- Countries with Highest Death Count per Population
- Breaking things down by Continent (Showing contintents with the highest death count per population)
- Global Numbers
- Total Population vs Vaccinations (Shows Percentage of Population that has recieved at least one Covid Vaccine)
- Using CTE to perform Calculation on Partition By in previous query
- Using Temp Table to perform Calculation on Partition By in previous query
- Creating View to store data for later visualizations
