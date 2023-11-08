# Slack for PHP

[![Build Status](https://travis-ci.org/maknz/slack.svg?branch=master)](https://travis-ci.org/maknz/slack)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/maknz/slack/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/maknz/slack/?branch=master)

A simple PHP package for sending messages to [Slack](https://slack.com) with [incoming webhooks](https://my.slack.com/services/new/incoming-webhook), focussed on ease-of-use and elegant syntax.

This version was directly forked from [Maknz's Slack Library for PHP](https://github.com/maknz/slack). The original project is no longer maintained and not working anymore for PHP projects having Guzzle below version 7.0.

Please see this [comparison tool](https://github.com/maknz/slack/compare/master...Angelo8828:slack:master) to check the changes I made. Please see original repository to see how it works. I will not change nor add to any of the functionalities of the original source code

## Usage Notes

Please use `Angelo8828` on namespaces instead of `Maknz`. For example, use `Angelo8828\Slack\Client` instead of `Maknz\Slack\Client`

## Releases/Requirements

The project will contain 2 releases

`1.9.0` - for PHP versions above 5.5 or HHVM.

`2.0` - for PHP versions above 7.2

For the functionalities, there should be no difference between `1.9.0` and `2.0`. The only difference between the two is that `2.0` has updated PHPUnit, to have the package's automated test modernized and updated

## Installation

You can install the package using the [Composer](https://getcomposer.org/) package manager. You can install it by running this command in your project root:

```sh
composer require angelo8828/slack
```
