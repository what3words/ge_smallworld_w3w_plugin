# What3Words Java API - GE Smallworld Plugin

[![License: MIT](https://img.shields.io/badge/license-MIT-blue)](./LICENSE.md)

What3words GE Smallworld is a plugin for GE Smallworld that brings the functionality of the what3words Java API to the GE Smallworld platform. GE has a long and successful track record in utilities. It has similar capabilities to most GIS software. Because it specialises in network infrastructure, you get value-added tools specifically for networking.
GE Smallworld is completely written in Magik. Magik is an object-oriented programming language and can be stand-alone applications on their own. The what3words Java API module uses the Magik-Java Interoperability, a supported mechanism to call code written in Java™ from GE Smallworld. This provides an efficient way of exposing Java to Magik, allowing access to existing Java code and third-party libraries written in Java.

Your project could be separated into two parts, the Java module part which is used to implement the what3words class, and the Magik part where the plugin is implemented. The Java class is available [here](https://github.com/Aramideh/What3Words/blob/main/Module/Java/Java%20Project/src/com/aramideh/sadeq/what3words/sw_what3words.java).

You can use the plugin to:

* select different languages on the toolbar;
* search what3words address on the toolbar;
* use the AutoSuggestion functionality on the search bar to find the right what3words address;
* convert a what3words address typed on the search bar to a point feature on the map (convert to coordinate);
* tap on the map to get any what3words address (convert to what3words address);
* display the what3words address on the selection status bar pane at the bottom of the map;
* use the backward or forward buttons on the what3word toolbar to search for a what3words selection;
* display all the what3words addresses that have been searched using the what3words history viewer plugin;
* display the what3words grid on the map by enabling the grid icon.


## Installation
Please follow these instructions [here](https://developer.what3words.com/tutorial/how-to-add-the-what3words-java-api-for-ge-smallworld#installation).

**Note: This plugin has been tested on GE Smallworld 5.2.8**

## Usage

The plugin is documentated [here](https://developer.what3words.com/tutorial/how-to-add-the-what3words-java-api-for-ge-smallworld).

## License - MIT

Versions 1-3, Copyright (C)@Aramideh
Version 4, Copyright (C) 2023, what3words Limited

## Contributors

This plugin has been developed by @Aramideh.