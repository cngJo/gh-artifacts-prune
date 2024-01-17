# gh artifactrs-prune

A GitHub (`gh`) CLI extension to prune action artifacts from a repository.

## Installation

Use the `gh extension install` command to install this extension:

```console
gh extension install cngJo/gh-artifacts-prune
```

## Usage

> [!NOTE]  
> GitHub's API has a maximum page size of 100 items. 
> You might need to run the command multiple times when you have more than 100 artifacts.
> There will be a warning if the maximum page size is reached.

```console
gh artifacts-prune [<REPOSITORY>] [-n|--no-interaction]
```

If no repository is given, the repository of the current directory is used.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

<div align="center">
    <span>&copy; 2023 - 2024, Johannes Przymusinski</span>
</div>