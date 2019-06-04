# Hue Smart Connector

A Mule extension that provide access to a hue bridge.

## About

Developed as part of self-education on the topic of application network using MuleSoft products. This was indented to explore the possibilities of "clean" XML-based connectors, what can be done and what limitations that exist.

* Proof-of-concept
* Built in Anypoint Studio 7.4 Pre-release
* Tested on Runtime 4.1.1 - Enterprise Edition, but no enterprise components used

## Build project

To build project inside Anypoint Studio or with Maven:

```s
# mvn clean install
```

```s
PROCESS LAYER
                   _______________________
                   \Common API/Data Model/
             _______\___________________/
------------|---------------------------|  
SYSTEM LAYER|                           |
            | hue-system-api ———————————ⓒ— hue-connector ——\
            |___________________________|                    \
--------------------------------------------------------------\------
                                                         ‚~~~~~\~~~~.
                                                        /            \
                                                       (  Hue Bridge  )
                                                        \            /
                                                         `~~~~~~~~~~´
```

## Changelog

1.0.73 Initial release.

## Contact

jrogby@mail.com
