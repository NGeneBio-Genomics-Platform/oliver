<h1 align="center">Oliver</h1>
<p align="center">
  <a href="https://www.npmjs.com/package/oliver" target="_blank">
    <img alt="Version" src="https://img.shields.io/static/v1?label=version&message=alpha&color=orange">
  </a>
  <a href="https://github.com/stjudecloud/oliver/blob/master/LICENSE.md" target="_blank">
    <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-yellow.svg" />
  </a>
</p>

> An opinionated Cromwell orchestration manager.

## Install

```sh
# Package install
python setup.py install
```

## Development

```sh
# Clone the repository
git clone git@github.com:stjudecloud/oliver.git
cd oliver

# Link the package with your current Python environment
python setup.py develop

# Ensure pre-commit is installed to automatically format
# code using `black`.
brew install pre-commit
pre-commit install
```

## Usage

```sh
oliver --help
```

Currently, the following commands are supported.


| Command     | Description                                                |
| ----------- | ---------------------------------------------------------- |
| `configure` | Configure Oliver with default options.                     |
| `config`    | Set or get a single config value from Oliver.              |
| `cosmos`    | Get cosmos DB entries for a workflow.                      |
| `inspect`   | Describe the state of a Cromwell workflow.                 |
| `kill`      | Kill a workflow running on a Cromwell server.              |
| `logs`      | Find all reported logs for a given workflow.               |
| `outputs`   | Find all reported outputs for a given workflow.            |
| `retry`     | Resubmit a workflow with the same parameters.              |
| `runtime`   | Get the runtime attributes used for a specific call.       |
| `status`    | Report various statistics about a running Cromwell server. |
| `submit`    | Submit a workflow to the Cromwell server.                  |

## Documentation

Please refer to the guides in the `docs/` folder for more in-depth
documentation.

| Guide Name     | Link                             |
| -------------- | -------------------------------- |
| Advanced Usage | [Link](./docs/ADVANCED_USAGE.md) |
| Configuration  | [Link](./docs/CONFIGURATION.md)  |

## Author

👤 **St. Jude Cloud Team**

* Website: https://stjude.cloud
* Twitter: [@StJudeResearch](https://twitter.com/StJudeResearch)
* Github: [@stjudecloud](https://github.com/stjudecloud)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](https://github.com/stjudecloud/oliver/issues). You can also take a look at the [contributing guide](https://github.com/stjudecloud/oliver/blob/master/CONTRIBUTING.md).

## 📝 License

Copyright © 2020 [St. Jude Cloud Team](https://github.com/stjudecloud).<br />
This project is [MIT](https://github.com/stjudecloud/oliver/blob/master/LICENSE.md) licensed.