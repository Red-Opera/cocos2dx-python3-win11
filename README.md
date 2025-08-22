# cocos2d-x 4 (Python 3 & Windows 11 Compatible Fork)

This is a modified fork of the original [cocos2d-x](https://github.com/cocos2d/cocos2d-x) framework that has been updated to work with Python 3 and Windows 11.

## Original Repository

The original cocos2d-x repository can be found at: https://github.com/cocos2d/cocos2d-x

## Changes Made

This fork includes modifications to make the build system compatible with:
- Python 3 (instead of Python 2.7.5+)
- Windows 11 build environment

All other features and functionality remain the same as the original cocos2d-x framework.

## Build Requirements (Updated)

* **Windows 11**, VS 2022+
* **Python 3** (instead of Python 2.7.5+)
* NDK r16+ is required to build Android games
* Android Studio 3.0.0+ to build Android games(tested with 3.0.0)
* JRE or JDK 1.6+ is required for web publishing

## Getting Started

Follow the same setup process as the original repository, but use Python 3 instead of Python 2:

```bash
$ git clone https://github.com/Red-Opera/cocos2dx-python3-win11.git
$ cd cocos2dx-python3-win11
$ python download-deps.py  # Now works with Python 3
$ git submodule update --init
$ python setup.py  # Now works with Python 3
```

## Documentation

For complete documentation, examples, and guides, please refer to the original repository:
- [Original cocos2d-x Documentation](http://cocos2d-x.org/docs/)
- [API Reference](http://cocos2d-x.org/docs/api-ref/index.html)
- [Programmers Guide](http://cocos2d-x.org/docs/programmers-guide/2/index.html)

## License

This fork maintains the same MIT License as the original cocos2d-x project.
