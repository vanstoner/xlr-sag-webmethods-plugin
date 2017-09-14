# Preface #

This document describes the functionality provided by the xlr-sag-webmethods-plugin.

See the **[XL Release Documentation](https://docs.xebialabs.com/xl-release/index.html)** for background information on XL Release and release concepts.

# CI status #

[![Build Status][xlr-sag-webmethods-plugin-travis-image] ][xlr-sag-webmethods-plugin-travis-url]
[![Build Status][xlr-sag-webmethods-plugin-codacy-image] ][xlr-sag-webmethods-plugin-codacy-url]
[![License: MIT][xlr-sag-webmethods-plugin-license-image] ][xlr-sag-webmethods-plugin-license-url]
[![Github All Releases][xlr-sag-webmethods-plugin-downloads-image] ]()


[xlr-sag-webmethods-plugin-travis-image]: https://travis-ci.org/xebialabs-community/xlr-sag-webmethods-plugin.svg?branch=master
[xlr-sag-webmethods-plugin-travis-url]: https://travis-ci.org/xebialabs-community/xlr-sag-webmethods-plugin
[xlr-sag-webmethods-plugin-codacy-image]: https://api.codacy.com/project/badge/Grade/b78313b1eb1b4b058dc4512b4d48c26f
[xlr-sag-webmethods-plugin-codacy-url]: https://www.codacy.com/app/rvanstone/xlr-sag-webmethods-plugin
[xlr-sag-webmethods-plugin-license-image]: https://img.shields.io/badge/License-MIT-yellow.svg
[xlr-sag-webmethods-plugin-license-url]: https://opensource.org/licenses/MIT
[xlr-sag-webmethods-plugin-downloads-image]: https://img.shields.io/github/downloads/xebialabs-community/xlr-sag-webmethods-plugin/total.svg


# Overview #

The xlr-sag-webmethods-plugin is a XL Release plugin that enables the Deployment of WebMethods bundles using the deployer command line tool

## Dependencies ##
You need to ensure the Deployer application is on the same server as XL Release

## Installation ##

Place the latest released version under the `plugins` dir.

This plugin (0.0.1+) requires XLR 7.1x+

## Types ##

+ Deploy Binary

   - binaryUrl - Location of the WebMethods binary file (File location or URI)
   - targetHost - Host to deploy to
   - projectName - Name of project to deploy
   - deployerLocation - path to deployer tool

 
   
