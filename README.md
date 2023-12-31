# QX

QX is an application framework build with C++, OpenGL, GLFW and ImGUI.

[![GitHub issues](https://img.shields.io/github/issues/QX-Interactive/QX.svg)](https://github.com/QX-Interactive/QX/issues)
[![GitHub forks](https://img.shields.io/github/forks/QX-Interactive/QX.svg)](https://github.com/QX-Interactive/QX/network)
[![GitHub stars](https://img.shields.io/github/stars/QX-Interactive/QX.svg)](https://github.com/QX-Interactive/QX/stargazers)
[![GitHub license](https://img.shields.io/github/license/QX-Interactive/QX.svg)](https://github.com/QX-Interactive/QX/blob/main/LICENSE.md)
![GitHub release (with filter)](https://img.shields.io/github/v/release/QX-Interactive/QX)

## Installation

Click the `Use this template` button and then the `Create a new repository` button.

## Usage

Clone your newly created repository and start working on your application in the top-level Application folder.

## Branches

The project currently has two main branches: `main` and `develop`. Features will be using seperate branches, branched from the `develop` branch since `develop` will always be the latest version of the project. Feature branches will be created with the following structure: `feature/[FEATURE_NAME]`. This branch will be merged into `develop` after the feature has been completed. If the feature is fully tested and good to go we will create a release and merge `develop` into `main`.

## Support

This project is maintained by [@Bram-Reuling](https://github.com/Bram-Reuling). Please understand that we won't be able to provide individual support via email. We also believe that help is much more valuable if it's shared publicly, so that more people can benefit from it.

| Type                                  | Platforms                                                               |
| ------------------------------------- | ----------------------------------------------------------------------- |
| 🚨 **Bug Reports**                    | [GitHub Issue Tracker](https://github.com/QX-Interactive/QX/issues)    |
| 📚 **Docs Issue**                     | [GitHub Issue Tracker](https://github.com/QX-Interactive/QX/issues)    |
| 🎁 **Feature Requests**               | [GitHub Issue Tracker](https://github.com/QX-Interactive/QX/issues)    |
| 🛡 **Report a security vulnerability** | See [SECURITY.md](SECURITY.md)                                         |
| 💬 **General Questions**              | [GitHub Discussions](https://github.com/QX-Interactive/QX/discussions) |

## Roadmap

For releasing 1.0.0:
- [ ] Module system. (V0.1)
  - [ ] Allows user to add modules through git submodules. The system will find them automatically and link it so you can use it in your app.
- [ ] Core module
  - [ ] Logging utilities. (V0.2)
  - [ ] Window creation through GLFW. (V0.3)
  - [ ] Custom title bar. (V0.4)
  - [ ] Wrapper for ImGUI (Just creating some easy ways to show things on the screen.). (V0.5)
  - [ ] Light and Dark mode styles. (V0.6)
  - [ ] Multithreading support. (V0.7)
  - [ ] Reflection system. (V0.8)
- [ ] Wiki pages with tutorials on how to use the framework.

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/QX-Interactive/QX/tags).

## Authors and acknowledgment

- **Bram Reuling** - _Repository Owner_ - [Bram-Reuling](https://github.com/Bram-Reuling)

See also the list of [contributors](https://github.com/QX-Interactive/QX/graphs/contributors) who participated in this project.

## License

This project is licensed under the MIT license - see the [LICENSE.md](LICENSE.md) file for details.

## Changelog

For the changelog please see [CHANGELOG.md](CHANGELOG.md).
