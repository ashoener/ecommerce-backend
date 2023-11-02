# Ecommerce Backend

![License Badge](https://img.shields.io/badge/license-MIT-green)

## Description

Ecommerce Backend is a backend for an e-commerce website, allowing you to access and update a database containing products, categories, and tags.

## Table of Contents

- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [How to Contribute](#how-to-contribute)
- [Tests](#tests)
- [Questions](#questions)
- [License](#license)

## Installation

To install Ecommerce Backend, you must first clone the repository.

```bash
git clone https://github.com/ashoener/ecommerce-backend.git
cd ecommerce-backend
```

Afterwards, run the following command:

```bash
npm install
```

Once everything is installed, you need to specify what database to connect to. If you don't have a database, run the `db/schema.sql` file. Rename the `.env.example` file to `.env`, and fill in the connection information.

## Usage

If you would like to just try it out, run `npm run seed` to create tables with example information. Note that this will overwrite any tables you may already have.

Once everything is connected, you may run `npm run start` to start up the backend.

To get an idea of what routes are available, you may watch [this video](https://youtu.be/RUHaVoSY-sE).

## How to Contribute

If you would like to contribute, create a pull request. Be sure to include information about what your changes do.

## Tests

Currently, there are no tests included with this project. They may be created in the future.

## Questions

If you have any questions, you may contact me via [GitHub](ashoener) or by [email](mailto:a.b.shoener@gmail.com).

## License

This project is covered under the MIT license. You may view it [here](/LICENSE).
