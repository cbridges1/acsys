# Prometheus

[![License](https://img.shields.io/github/license/aeon-software/prometheus)](LICENSE.md)
[![Commit](https://img.shields.io/github/last-commit/aeon-software/prometheus)](https://github.com/aeon-software/prometheus/commits)
[![Repo](https://img.shields.io/github/repo-size/aeon-software/prometheus)](https://github.com/aeon-software/prometheus)

<p align="center">
  <img alt="Prometheus UI" src="https://user-images.githubusercontent.com/34227411/88206375-c46acd00-cc13-11ea-8f60-f8564ab6c185.png">
</p>

Prometheus is a CMS built on NodeJS. This tool was created due to the lack of CMS options available for Cloud Firestore. Prometheus allows developers to configure a database through the Prometheus web app. Once this is done users can use Prometheus as a headless content management system that also configures restful apis (no coding involved). Prometheus serves as a simple interface for the Firestore database with the goal of more database support being added soon! Since this project is maintained and used by Aeon it will receive continuous updates. Feel free to submit a feature request for any features you want implemented!

## Getting Started

These instructions will get Prometheus up and running on your local machine for development and testing purposes.

## Prerequisites

- NodeJS >= 10.10
- NPM >= 6.x

## Currently Supported Databases

- Cloud Firestore

## Currently Supported Storage Services

- Google Cloud Storage

## Installing

Run `npm install`

Start development by running `npm run dev`

Build project by running `npm run build`

Run project in production mode by running `npm run start` (executing this after building will run the project at http://localhost)

## Configuration

To configure Prometheus you must first upload your service account JSON file. Instructions on how to get this file can be found [here](https://cloud.google.com/iam/docs/creating-managing-service-account-keys). Note that the database must be created with appropriate security rules before Prometheus can be used (Default production rules are recommended).

## Deployment Tips

In general it is best to configure Prometheus before deploying. This is necessary in a serverless environment due to Prometheus being a stateful application.

## Built With

- NodeJS (https://nodejs.org/en/)
- ReactJS (https://reactjs.org/)

## Contributing

There are many ways in which you can participate in the project, for example:

- Submit pull requests
- Submit bugs and feature requests
- Review source code changes
- Review the documentation

We encourage you to tell us what you want out of this project! Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Authors

- **Jalen Bridges** - _Initial work_ - [Prometheus](https://github.com/aeon-software/prometheus)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
