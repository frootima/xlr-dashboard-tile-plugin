# XL [Deploy|Release] [Description|Interface] plugin v1.0.0

[![Build Status][xlr-dashboard-tile-plugin-travis-image]][xlr-dashboard-tile-plugin-travis-url]
[![License: MIT][xlr-dashboard-tile-plugin-license-image]][xlr-dashboard-tile-plugin-license-url]
![Github All Releases][xlr-dashboard-tile-plugin-downloads-image]

[xlr-dashboard-tile-plugin-travis-image]: https://travis-ci.org/xebialabs-community/xlr-dashboard-tile-plugin.svg?branch=master
[xlr-dashboard-tile-plugin-travis-url]: https://travis-ci.org/xebialabs-community/xlr-dashboard-tile-plugin
[xlr-dashboard-tile-plugin-license-image]: https://img.shields.io/badge/License-MIT-yellow.svg
[xlr-dashboard-tile-plugin-license-url]: https://opensource.org/licenses/MIT
[xlr-dashboard-tile-plugin-downloads-image]: https://img.shields.io/github/downloads/xebialabs-community/xlr-dashboard-tile-plugin/total.svg

## Preface

This document describes the functionality provided by the XL Release [Description|Interface] plugin.

See the [XL Release reference manual](https://docs.xebialabs.com/xl-release) for background information on XL Release and release automation concepts.
or
See the [XL Deploy reference manual](https://docs.xebialabs.com/xl-deploy) for background information on XL Deploy and deployment automation concepts.

## Overview

## Requirements

Note:  XLD or XLR version should not be lower than lowest supported version.  See <https://support.xebialabs.com/hc/en-us/articles/115003299946-Supported-XebiaLabs-product-versions>.

## Installation

## Features/Usage/Types/Tasks

## References

Note:  The required XL Deploy or XL Release version should not be lower than the lowest supported.  See https://support.xebialabs.com/hc/en-us/articles/115003299946-Supported-XebiaLabs-product-versions

* [HOW-TO: Create Custom Tile](https://docs.xebialabs.com/xl-release/how-to/create-custom-tiles.html)

#### Travis configuration

* After creating git repository, sync Travis with GitHub (https://travis-ci.org/profile/xebialabs-community) and enable the project by setting switch to on.

* travis encrypt TRAVIS-HIPCHAT-PASSWORD --add  notifications.hipchat.rooms

* travis setup releases

* Replace last several lines with  

```
file: build/libs/xlr-dashboard-tile-plugin-1.0.0.jar
  skip_cleanup: true
  on:
    all_branches: true
    tags: true
    repo: xebialabs-community/xlr-dashboard-tile-plugin
```
    
    




