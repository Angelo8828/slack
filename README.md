# Slack for PHP

[![Build Status](https://travis-ci.org/maknz/slack.svg?branch=master)](https://travis-ci.org/maknz/slack)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/maknz/slack/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/maknz/slack/?branch=master)

A simple PHP package for sending messages to [Slack](https://slack.com) with [incoming webhooks](https://my.slack.com/services/new/incoming-webhook), focussed on ease-of-use and elegant syntax.

This version was directly forked from [Maknz's Slack Library for PHP](https://github.com/maknz/slack). The original project is no longer maintained and not working anymore for PHP projects having Guzzle below version 7.0. This will contain release 1.8.0, that will contain support for future versions of Guzzle. I will not change nor add to any of the original source code

Please see this [comparison tool](https://github.com/maknz/slack/compare/master...Angelo8828:slack:master) to check the changes I made. Please see original repository to see how it works

## Requirements

* PHP versions above 5.5 or HHVM

## Installation

You can install the package using the [Composer](https://getcomposer.org/) package manager. You can install it by running this command in your project root:

```sh
composer require angelo8828/slack
```
