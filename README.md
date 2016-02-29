# amcx-theme
amcx-theme for open edX dogwood release (comprehensive theming)

[![Build Status](https://travis-ci.org/IONISx/edx-theme.svg?branch=master)](https://travis-ci.org/IONISx/edx-theme)
[![Dependencies Status](https://david-dm.org/IONISx/edx-theme.svg)](https://david-dm.org/IONISx/edx-theme)
[![Dev Dependencies Status](https://david-dm.org/IONISx/edx-theme/dev-status.svg)](https://david-dm.org/IONISx/edx-theme#info=devDependencies)

> Open edX responsive theme using [Bootstrap](http://getbootstrap.com/).

![Screenshot](https://raw.githubusercontent.com/IONISx/edx-theme/docs/images/responsive.png)

## About this Open edX theme

It is based on [Bootstrap](http://getbootstrap.com/), it uses bootstrap's Sass library – which is used by Open edX).

## How to use this theme (devstack)

First, open your '/edx/app/edxapp/edx-platform/themes' directory and clone this repo in as amcx-theme. 

Next, open your 'lms.env.json' file and edit 'COMPREHENSIVE_THEME_DIR' to '/edx/app/edxapp/edx-platform/themes/amcx-theme'

Save this file, and run 'paver updaate_assets lms' then 'paver lms'.

Point your browser to 127.0.0.1:(your port) and enjoy.
