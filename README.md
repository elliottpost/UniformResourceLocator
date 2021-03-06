# Uniform Resource Locator

[![Latest Version](https://img.shields.io/github/release/userfrosting/UniformResourceLocator.svg)](https://github.com/userfrosting/UniformResourceLocator/releases)
[![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg)](LICENSE.md)
[![Join the chat at https://chat.userfrosting.com/channel/support](https://demo.rocket.chat/images/join-chat.svg)](https://chat.userfrosting.com/channel/support)
[![Donate](https://img.shields.io/badge/Open%20Collective-Donate-blue.svg)](https://opencollective.com/userfrosting#backer)

| Branch | Build | Windows Build | Coverage | Style |
| ------ |:-----:|:-------------:|:--------:|:-----:|
| [master][UniformResourceLocator] | [![][URI-master-build]][URI-travis] | [![][URI-appveyor-master]][URI-appveyor] | [![][URI-master-codecov]][URI-codecov] | [![][URI-style-master]][URI-style] |
| [develop][URI-develop] | [![][URI-develop-build]][URI-travis] | [![][URI-appveyor-master]][URI-appveyor] | [![][URI-develop-codecov]][URI-codecov] | [![][URI-style-develop]][URI-style] |

<!-- Links -->
[UniformResourceLocator]: https://github.com/userfrosting/uniformresourcelocator
[URI-develop]: https://github.com/userfrosting/uniformresourcelocator/tree/develop
[URI-version]: https://img.shields.io/github/release/userfrosting/UniformResourceLocator.svg
[URI-master-build]: https://travis-ci.org/userfrosting/UniformResourceLocator.svg?branch=master
[URI-master-codecov]: https://codecov.io/gh/userfrosting/UniformResourceLocator/branch/master/graph/badge.svg
[URI-develop-build]: https://travis-ci.org/userfrosting/UniformResourceLocator.svg?branch=develop
[URI-develop-codecov]: https://codecov.io/gh/userfrosting/UniformResourceLocator/branch/develop/graph/badge.svg
[URI-releases]: https://github.com/userfrosting/UniformResourceLocator/releases
[URI-travis]: https://travis-ci.org/userfrosting/UniformResourceLocator
[URI-codecov]: https://codecov.io/gh/userfrosting/UniformResourceLocator
[URI-style-master]: https://github.styleci.io/repos/128138460/shield?branch=master&style=flat
[URI-style-develop]: https://github.styleci.io/repos/128138460/shield?branch=develop&style=flat
[URI-style]: https://github.styleci.io/repos/128138460
[URI-appveyor]: https://ci.appveyor.com/project/userfrosting/uniformresourcelocator
[URI-appveyor-master]: https://ci.appveyor.com/api/projects/status/cu1hfuar357788u1/branch/master?svg=true
[URI-appveyor-develop]: https://ci.appveyor.com/api/projects/status/cu1hfuar357788u1/branch/develop?svg=true

Louis Charette 2018

The _Uniform Resource Locator_ module handles resource aggregation and stream wrapper related tasks for [UserFrosting](https://github.com/userfrosting/UserFrosting).

# Problem to Solve

It's easy to find files when they are located in a single place. It's another task when looking for files scattered across multiple directory. Step into the world of package and dependencies and the nightmare begins.

![](images/Graph.png)

It's like trying to find someone in a one story house vs. a 25 stories office building when you don't know on which floor the person is. This package goal is to help you locate things in that office building without having to search floor by floor each time. In other words, it is a way of aggregating many search paths together.

# Documentation

* [Main Documentation](docs/)
* [API docs](docs/api.md)
* [Working example / tutorial](docs/Example.md).

## Building doc

```
vendor/bin/phpdoc-md generate src/ > docs/api.md
```

## [Style Guide](STYLE-GUIDE.md)

## [Testing](RUNNING_TESTS.md)

# References

- [The Power of Uniform Resource Location in PHP](https://web.archive.org/web/20131116092917/http://webmozarts.com/2013/06/19/the-power-of-uniform-resource-location-in-php/)
- [When we should we use stream wrapper and socket in PHP?](https://stackoverflow.com/questions/11222498/when-we-should-we-use-stream-wrapper-and-socket-in-php)
- [rockettheme/toolbox](https://github.com/rockettheme/toolbox)
