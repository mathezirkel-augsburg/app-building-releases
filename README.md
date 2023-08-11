# Mathezirkel App Building Releases

This repository's sole purpose is to build the open source client for accessing the database of and organizing the `Mathezirkel Augsburg` and the `Mathecamp`.

The main repository can be found [HERE](https://gitlab.com/mathezirkel/mathezirkel-app/client).

As the project is written in [Tauri](https://tauri.app/) which provides [cross-plattform-building scripts and support](https://tauri.app/v1/guides/building/cross-platform) only for Github actions, this repository mainly leverages the convenient and powerful Github-Actions capabilities to build the project for all the platforms and release the compiled results.

## Usage

This repository has no use in development. It just calls the necessary actions to compile and release the client if the process is triggered.

## Requirements

The Repository needs a token called `RELEASE_GITHUB_TOKEN` set under `Settings -> Secrets and Variables -> Actions -> New repository secret`. It needs write access to the Repository's Releases (Fine Grained Permission: Repository -> Contents -> Write).

## License

The code is published under GPL 3, see [LICENSE](LICENSE), however this repository doesn't hold relevant information and the [Main Repository on Gitlab](https://gitlab.com/mathezirkel/mathezirkel-app/client) should be considered.
