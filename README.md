# CityBook
[![Build Status](https://travis-ci.org/codeforamerica/citybook.png)](https://travis-ci.org/codeforamerica/citybook)  [![Stories in Ready](https://badge.waffle.io/codeforamerica/citybook.png?label=ready&title=Ready)](https://waffle.io/codeforamerica/citybook)

Make a searchable address book from a contact spreadsheet.
http://codeforamerica.github.io/citybook

CityBook aims to make it easier for administrative staff who maintain contact lists to create a searchable, mobile-responsive web app that uses their spreadsheet as a data source.

Based on the CfA [2015 Richmond Fellowship team's](http://rva.codeforamerica.org) [Search-RVAHealth project](https://github.com/codeforamerica/search-rvahealth).

### Development

Run `jekyll serve -w --config _config.yml,_config-dev.yml` for relative links on your local machine.
Run `jekyll build` before pushing to a pull request.

### What is this built with?

This project uses [Tabletop.js](https://github.com/jsoma/tabletop) for the spreadsheet access, [Handlebars](http://handlebarsjs.com/) for some templating, [List.js](http://www.listjs.com/) for the searchable list, and [Bootstrap](http://getbootstrap.com/) for the styles.

The instruction page template was generated by using the [Cayman theme](https://github.com/pietromenna/jekyll-cayman-theme) by [Jason Long](http://github.com/jasonlong).
