<!-- [![CircleCI](https://circleci.com/gh/panicboat/api-skelton.svg?style=shield)](https://circleci.com/gh/panicboat/api-skelton)
[![codecov](https://codecov.io/gh/panicboat/api-skelton/branch/master/graph/badge.svg)](https://codecov.io/gh/panicboat/api-skelton) -->

# api-skelton

API Skelton for panicboat.

# Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

## Initialize ( at onece )

```bash
docker-compose run skelton rails new . --api --force --database=mysql --skip-bundle
```

### Slack

- [Incoming Webhook](https://panicboat.slack.com/apps/A0F7XDUAZ)

### CircleCI

- [Environment Variables](https://app.circleci.com/settings/project/github/panicboat/api-skelton/environment-variables)
  - CODECOV_TOKEN
  - SLACK_WEBHOOK_URL

### CodeCov

- [Repositories](https://codecov.io/gh/panicboat)

## Prerequisites

What things you need to install the software and how to install them.

- [Docker](https://www.docker.com/)

## Installing

A step by step series of examples that tell you how to get a development env running.

```bash
make init
make seed
make up
```

# Running the tests

Explain how to run the automated tests for this system.

```bash
make init
make spec
```

## And coding style tests

Explain what these tests test and why.

***in preparation***

# Deployment

Add additional notes about how to deploy this on a live system.

***in preparation***

# Built With

- [api-engine](https://github.com/panicboat/api-engine)

# Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

# Versioning

We use [SemVer](https://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/panicboat/api-skelton/tags).

# Authors

- [@panicboat](https://twitter.com/panicboat) - *Initial work*

See also the list of contributors who participated in this project.

# License
This project is licensed under the [MIT License](https://opensource.org/licenses/MIT). - see the [LICENSE.md](LICENSE.md) file for details

# Acknowledgments

- [Trailblazer](https://github.com/trailblazer/trailblazer)
