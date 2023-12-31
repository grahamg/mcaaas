# MCAAAS

*November 2023 - v0.0.1*

[![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

MCAAAS (McRib Availability As A Service) provides a modern, RESTful, scalable solution to the common problem of telling people if the popular fast food sandwich is currently available.

Please see https://mcaaas.io for API documentation and examples.

# Installation

	npm install

# Run

	npm start

# Test

	npm test

# Docker

	docker build -t mcaaas:1 .
    docker run -v $(pwd):/usr/src/app -p 9000:9000 mcaaas:1

# Clients

API clients are available in a number of languages:

| Language | Name             | Info                                              |
|:---------|:-----------------|:--------------------------------------------------|
| JS/Node  | `mcaaas-client ` | https://www.npmjs.org/package/mcaaas-client       |

# GUI Clients

| Platform          | Info                                                      |
|:------------------|:----------------------------------------------------------|
| Web               | https://github.com/grahamg/mcaaas                         |

# Contributing

## Adding new operations

To add a new MCAAAS operation:

1. Fork into your account
2. Branch into a feature branch `feature/your_operation`
3. See the operation files in `/lib/operations`.
4. Add specs, using `/spec/operations` as examples. We won't be merging operations without working specs.
5. Push to your fork and submit a PR.

All contributions are very welcome.
