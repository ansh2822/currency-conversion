# Currency Conversion

![Project Currency Preview](screenshot.png)

A simple web application for converting currencies using React.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [API Used](#api-used)

## Introduction

This Currency Conversion App is a web-based tool that allows users to quickly and easily convert one currency to another. It's built using React and utilizes an external currency exchange rate API to fetch the latest currency conversion rates.

## Features

- Convert between various currencies.
- Swap the "From" and "To" currencies with a single click.
- Real-time currency conversion using the latest exchange rates.

## Getting Started

### Prerequisites

Before you begin, make sure you have the following software installed on your machine:

- Node.js: You can download and install it from [nodejs.org](https://nodejs.org/).

### Installation

1. Clone the repository to your local machine:
   `git clone https://github.com/ansh2822/Currency_Convert.git`

2. Navigate to the project directory:
   `cd currency-conversion-app`

3.Install the project dependencies:
`npm install`

## Usage

1.Start the development server:
`npm start`

2.Open your web browser and visit http://localhost:3000 to use the Currency Conversion App.

3.Select the currency you want to convert from in the "From" dropdown.

4.Enter the amount you want to convert.

5.Select the currency you want to convert to in the "To" dropdown.

6.Click the "Convert" button to see the converted amount.

## API Used

This project uses an external API for fetching the latest currency exchange rates. The API used is:
[Currency Exchange Rate API](https://cdn.jsdelivr.net/gh/fawazahmed0/currency-api@1/latest/currencies)
