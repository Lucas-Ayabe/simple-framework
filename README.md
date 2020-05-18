# Simple Framework

Just a simple CSS framework created for studies.

## Getting started

This section helps you a installing the framework, how to use and teachs you some concepts used.

### Instalation

To install download this repository or clone with the command:

```
git clone https://github.com/Lucas-Ayabe/simple-framework.git
```

### Using

After installing this framework in your project, import the simple.min.css file
located in _assets/css_ folder.

#### Concepts

This framework was writted following some concepts like CSS namespaces, a modified BEM metodology, some OOCSS inspiration and applying some concepts of SMACSS to organize the folders and files.

The BEM modifiers are modified from .block\_\_element--modifier to .block\_\_element.-modifier

The namespaces used in this project are:

| NAMESPACE | NAME      | DESCRIPTION                                                                                                                          |
| --------- | --------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| a-        | abstract  | a abstract component. A class that serves as a basis for other components and should be avoided from using directly or modifying it. |
| c-        | component | a component. A visual UI piece that are independent and reusable in any context.                                                     |
| o-        | object    | a layout component. A structural component, that acts as structure of the layout.                                                    |
| u-        | utility   | a utility class. Used for granular modifications like changing the color of a text or a background, avoid using it too often.        |

## Styles

Here is a summary of the styles created for the framework

The core file of the framework, here are where all the imports occours.

**CONTENTS**

**CONFIG**

**functions**

Useful functions.

**mixins**

Useful mixins.

**vars**

Variables for colos, typography, spaces, reponsive, radius,
shadows and aspect ratios.

**BASE**

**reset**

Set some default styles to some elements.

**LAYOUT**

All the classes in this category has a .o- (object) namespace class.

**container**

Styles to the contaienr component.

**flow**

Styles to uniform vertical spacement.

**full-bleed**

effect in which the element occupies 100% of the viewport inside a container.

**grid**

Styles for the grid system.

**media**

Styles to the media object component.

**page**

Styles to a fluid layout or the sticky footer technic.

**section**

Good spaced vertical wrappers.

**ABSTRACT COMPONENTS**

All the classes in this category has a .a- (abstract) namespace class. The
abstract classes are classes that serve as a basis for other components and
therefore care should be taken when changing them and, if possible, not
doing so. Its concrete use is discouraged by this documentation.

**box**

Simple container that serve as basis for the following components:

- card
- form

**COMPONENTS**
All the classes in this category has a .c- (component) namespace class.

**bloquote**

Bloquote styles.

**button**

Buttons and their variations.

**card**

Card component styles.

**field**

Field component styles.

**form**

Form component styles.

**subtitle**

Subtitles and their variations.

**table**

Tables and their variations.

**title**

Titles and their variations.

**UTILITIES**

All the classes in this category has a .u- (utilitie) namespace class.

**colors**

Utilities for colors, like text-color utilities and
background-color utilities.

**PLUGINS**

All the styles in this category are destined to custom styles to 3rd-party
plugins.

Note: Comments must have to be a maximum of 80 characters.

## Tools

Builded with [parcel](https://parceljs.org/)
