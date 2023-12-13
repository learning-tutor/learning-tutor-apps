# Project Dependency Management

[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)

This document outlines the steps to manage dependencies for multiple projects using a task-based approach.

## Installation

[Task](https://taskfile.dev/installation/)

Install taskfile with this command:
```bash
npm install -g @go-task/cli
```

## Clone Dependencies

To clone all dependencies of all projects, use the following command:

```bash
task clone
```

## Install Dependencies
After cloning the repositories, you need to install the dependencies for all projects. Run the following command:

```bash
task install
```

## Run Projects in Docker
```bash
task docker
```

