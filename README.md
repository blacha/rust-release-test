# Testing rust release processes 

Using [release-please](https://github.com/googleapis/release-please) and github actions to automatically

- Create a pull request to releases when changes are detected

On release:
- Create CHANGELOG.md from [conventional commits](https://www.conventionalcommits.org/en/v1.0.0/)
- Create git tags.
- Update Cargo.toml/Cargo.lock with the new version
- Build binaries for multiple systems and add them to the github release