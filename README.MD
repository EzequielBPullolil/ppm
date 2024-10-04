# PPM
> Python package manager

A package manager for Python written in Go (Golang)

## Description

CLI-based package manager for Python, designed to emulate npm-like functionality, providing dependency management, version control, and project automation tools specifically tailored for Python environments.

## Use
### Init ppm
```sh
ppm init <project name>
```
### Installing dependencies
```sh
ppm install <dep>
```

### Remove dependencies
```sh
ppm remove <dep>
```

### List dependencies
```sh
ppm list <dep>
```

All of these actions will create a file called package.json, which will contain all the project dependencies along with their versions. Additionally, it will include a section called scripts that allows you to associate a keyword with a specific script



---

This project aims to be fully compatible with pip packages, ensuring seamless integration and support for existing Python dependencies and libraries.