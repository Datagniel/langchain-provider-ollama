# Langchain-provider-ollama

## Project Info

[![Project License](https://img.shields.io/github/license/spyder-ide/langchain-provider)](./LICENSE)
[![Join the chat at https://gitter.im/spyder-ide/public](https://badges.gitter.im/spyder-ide/spyder.svg)](https://gitter.im/spyder-ide/public)
[![OpenCollective Backers](https://opencollective.com/spyder/backers/badge.svg?color=blue)](#backers)
[![OpenCollective Sponsors](https://opencollective.com/spyder/sponsors/badge.svg?color=blue)](#sponsors)

----

# Overview


## Installation

To use this completions provider you will need to install Spyder 6 (at least 6.0.0a3)

To install the provider package from source, you can use `pip` with something like:

    pip install git+https://github.com/Datagniel/langchain-provider-ollama.git

Also, you need to have Ollama preinstalled, which you can get from [here](https://ollama.com/download).

## Preview

![original langchain provider demo](https://raw.githubusercontent.com/spyder-ide/langchain-provider/master/langchain-provider.gif)

## Configuration

To configure the provider number of suggestions (1 - 10) or the model to use (`codellama` or `llama3.1`) you need to modify the CONF_DEFAULTS list in the LangchainProvider class in the provider.py script by hand, because I couldn't find out yet how the model selection works in the GUI. If someone wants to fix it, feel free to do so.

## Dependencies

This project depends on [Spyder](https://github.com/spyder-ide/spyder).

## Changelog

Visit our [CHANGELOG](CHANGELOG.md) file to know more about our new features and improvements.

## Development and contribution

Everyone is welcome to contribute! See our [Contributing guide](CONTRIBUTING.md) for more details.

## Sponsors

Spyder is funded thanks to the generous support of

[![Quansight](https://user-images.githubusercontent.com/16781833/142477716-53152d43-99a0-470c-a70b-c04bbfa97dd4.png)](https://www.quansight.com/)[![Numfocus](https://i2.wp.com/numfocus.org/wp-content/uploads/2017/07/NumFocus_LRG.png?fit=320%2C148&ssl=1)](https://numfocus.org/)

and the donations we have received from our users around the world through [Open Collective](https://opencollective.com/spyder/):

[![Sponsors](https://opencollective.com/spyder/sponsors.svg)](https://opencollective.com/spyder#support)

## More information

[Main Website](https://www.spyder-ide.org/)

[Download Spyder (with Anaconda)](https://www.anaconda.com/download/)

[Online Documentation](https://docs.spyder-ide.org/)

[Spyder Github](https://github.com/spyder-ide/spyder)

[Troubleshooting Guide and FAQ](
https://github.com/spyder-ide/spyder/wiki/Troubleshooting-Guide-and-FAQ)

[Development Wiki](https://github.com/spyder-ide/spyder/wiki/Dev:-Index)

[Gitter Chatroom](https://gitter.im/spyder-ide/public)

[Google Group](https://groups.google.com/group/spyderlib)

[@Spyder_IDE on Twitter](https://twitter.com/spyder_ide)

[@SpyderIDE on Facebook](https://www.facebook.com/SpyderIDE/)

[Support Spyder on OpenCollective](https://opencollective.com/spyder/)
