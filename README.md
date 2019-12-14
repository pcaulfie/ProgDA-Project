# Simulating A Dataset

## Project 2019 - Programming for Data Analysis

## Introduction
The objective of this project is to simulate a dataset. I decided to model my dataset on a real life scenario taken from the IT Industry. I chose to create a dataset of Installed Base data, which I hope to use at a later stage, to develop and test Machine Learning algorithms such as linear regression and classification. 

I have created a [Jupyter notebook](https://github.com/pcaulfie/ProgDA-Project/blob/master/Install%20Base%20Dataset.ipynb) to detail my work.


## Install Base Dataset

According to Kurvinen (2017), the typical data on install base includes a listing of products which are installed at a given customer site. Futhermore, it can include additional variables such as serial numbers, hardware and software revisions, warranty and service contracts. 

Installed base data can be used by many departments in an organisation, from field service engineers, sales, spare parts planners, quality etc . The dataset helps to answer questions such as:

* What is the current configuration of the product to be serviced?
* Where is the faulty product physically located and where is the part to be replaced located?
* Is the unit covered under warranty or service contract?
* When was the unit installed, upgraded and/or last serviced?

![Install Base Image](https://cdn.myonlinestore.eu/945f2dab-6be1-11e9-a722-44a8421b9960/images/World%20map%20installed%20base.png)

The dataset contains 200 rows and 8 columns.

The 8 columns contain the following fields:

Part Number: 5 Digit identifier for each product installed.
Serial Numbers: Unique ID's for each unit sold.
Install Date: The start-up / installation date recorded by the field service engineer. The date range is: January 2017 to December 2019 (36 months)
Factory Warranty Expiration Date: Factory Warranty expires 3 year after installation date.
Extended Warranty: Number of years of extended warranty cover purchased.
Customer ID Number: 5 Digit identifier for each customer.
Country: ISO 2 Digit Country Code, identifying the country where the product is installed.
Service Contract: Record of whether the customer has taken out a service contract on the hardware.

## Installation

- I recommend that you install the [Anaconda](https://www.anaconda.com/distribution/) distribution of python which contains all the libraries used, as well as an instance of Jupyter notebook.

### Clone

- Clone this repository to your local machine use the following link `https://github.com/pcaulfie/ProgDA-Project.git`

## License

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
- **[GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.en.html)**

## Contact

Paul Caulfield -  paul.caulfield@se.com & g00376342@gmit.ie

Project Link: [https://github.com/pcaulfie/ProgDA-Project](https://github.com/pcaulfie/ProgDA-Project)
