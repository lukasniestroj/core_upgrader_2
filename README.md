# TYPO3 Extension core_upgrader2

[![Latest Stable Version](https://img.shields.io/packagist/v/wapplersystems/core-upgrader.svg)](https://packagist.org/packages/ichhabrecht/core-upgrader)
[![Build Status](https://img.shields.io/travis/WapplerSystems/core_upgrader/master.svg)](https://travis-ci.org/WapplerSystems/core_upgrader)

Run upgrade wizards for multiple TYPO3 versions (to 12.4) at once.

## Features

This extension allows to upgrade the TYPO3 core from v7.6 to v10.4 with this extension and the rest by the v12 core in one step.

## Installation

Simply install the extension with Composer or download from [TER](https://extensions.typo3.org/extension/core_upgrader2/).

`composer require wapplersystems/core-upgrader`

## Usage

1. Now you can list all update wizards:

   `typo3 upgrade:list`

1. Now you can run all update wizards:

   `typo3 upgrade:run`

