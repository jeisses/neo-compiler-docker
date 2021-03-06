<p align="center">
  <img 
    src="http://res.cloudinary.com/vidsy/image/upload/v1503160820/CoZ_Icon_DARKBLUE_200x178px_oq0gxm.png" 
    width="125px"
  >
</p>

<h1 align="center">neo-compiler-docker</h1>

<p align="center">
  Compile <b>NEO</b> smart contracts using Docker.
</p>

<p align="center">
  <a href="https://github.com/CityOfZion/neo-compiler-docker/releases">
    <img src="https://img.shields.io/github/tag/CityOfZion/neo-compiler-docker.svg?style=flat">
  </a>
  <a href="https://circleci.com/gh/CityOfZion/neo-compiler-docker/tree/master">
    <img src="https://circleci.com/gh/CityOfZion/neo-compiler-docker/tree/master.svg?style=shield">
  </a>
</p>

## What?

- A set of [Docker](https://www.docker.com/) images
- Each provide a cross-platform mechanism for compiling [NEO](https://neo.org/) smart contracts
- No need to setup NEO development environment 🎉

## Setup

Clone the repo, including **submodules**:

```
git clone --recursive git@github.com:CityOfZion/neo-compiler-docker.git
```

If you have already cloned the project, then use:

```
git submodule init
```
```
git submodule update
```

## Usage

This repo includes a number of different Docker images. The [Images](#images) section below describes what each Docker image does.

Each image has a README within the directory, which describes how to use it. Please note that for security reasons, all Docker images have to first be built locally.

## Images

### neo-boa-compiler

This image builds Python code (`.py`) into NEO AVM code (`.avm`), using the [neo-boa](https://github.com/CityOfZion/neo-boa) compiler.

### neoj-builder

This image builds Java code (`.java`) into Java bytecode (`.class`).

### neoj-compiler

This image compiles Java bytecode (`.class`) into NEO AVM code (`.avm`).

## Help

- Open a new [issue](https://github.com/CityOfZion/neo-compiler-docker/issues/new) if you encountered a problem.
- Or ping **@revett** on the [NEO Slack](http://slack.cityofzion.io/).
- Submitting PRs to the project is always welcome! 🎉
- Check the [Changelog](https://github.com/CityOfZion/neo-compiler-docker/blob/master/CHANGELOG.md) for recent changes.

## License

- Open-source [MIT](https://github.com/CityOfZion/neo-compiler-docker/blob/master/LICENSE).
- Main author is [@revett](https://github.com/revett).
- This project adheres to the [Contributor Covenant Code of Conduct](https://github.com/goreleaser/goreleaser/blob/master/CODE_OF_CONDUCT.md).
