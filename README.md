# nz
![GitHub repo file count](https://img.shields.io/github/directory-file-count/golangast/contributefrontend) 
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/golangast/contributefrontend)
![GitHub repo size](https://img.shields.io/github/repo-size/golangast/contributefrontend)
![GitHub commit activity](https://img.shields.io/github/commit-activity/w/golangast/contributefrontend)
![Go 100%](https://img.shields.io/badge/Go-100%25-blue)

## nz
- [nz](#nz)
  - [nz](#nz-1)
  - [License is GNU Version 3](#license-is-gnu-version-3)
  - [General info](#general-info)
  - [How to use this tool](#how-to-use-this-tool)
  - [Setup](#setup)
  - [To run this project for development, download it and run the following](#to-run-this-project-for-development-download-it-and-run-the-following)
  - [To run a command](#to-run-a-command)
  - [Repository overview](#repository-overview)


## License is GNU Version 3 
To ensure people can share but need to keep original code for the public use. This way your are still recognized for your
contributions.

## General info
Nic and Zach's project


## How to use this tool
## Setup
To run this project for development, download it and run the following
---
```
go mod init "github.com/golangast/nz"

go mod tidy

go install github.com/spf13/cobra-cli@latest

export PATH="~/go/bin:$PATH" //if you dont add it to your bashrc file then its just temparory anyways

cobra-cli init
```
---

to create command

---
```
         cobra add yourcommandnamehere 
example: cobra add second
```
---

To Run the application

---
```
go run main.go start
```
---

To run a command
---
```
example: go run main.go first
```
---


## Repository overview

---
```
├── assets/ is where you want to edit the frontend files. Dont worry about anything else.
```
---