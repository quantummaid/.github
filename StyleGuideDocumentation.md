# QuantumMaid Style Guide for Documentation and Tutorials
The following guide aims to give authors of QuantumMaid documentation and tutorials
an orientation point on how to write their documents in a consistent and aesthetically
pleasing way.

## General rules
Documentation and tutorials in QuantumMaid projects follow the [Microsoft Writing Style Guide](https://docs.microsoft.com/en-us/style-guide/welcome/).

## Casing
The following words are written in camel case unless there is a reason to divert from this rule:
*QuantumMaid*, *HttpMaid*, *EventMaid*, *MapMaid*, *ReflectMaid*, *DocuMaid*, *GitHub* etc.

Names are to be capitalized: *Java*, *Kotlin*, *Maven*, *Slack*, *Gitter*, *Twitter*, *(AWS) Lambda*, 
*Spring*, etc.

The word *usecase* is written as such.

## File names
File names are written as `inline code`: `pom.xml`, `MyType.class`, `README.md`, etc.

## Code
Code identifiers in normal text are written as `inline code`. This especially applies to `String`, `Object`, `List`
and `Map` when referencing the code element. On the other hand, when they are used to reference the concept,
they are not written as `inline code` and not capitalized: *a string*, *an object*, *a list*, etc.

### Strings
Strings in normal text are wrapped in double quotes and then written as `inline code`: `"This is a string"`.

### Imports and Package Declaration
Whole classes that are meant to be copied by hand need to include all imports and the package declaration.

### Static Imports
Static imports in code examples may only be used if their origin is obvious in
the context of the code example (it has been used before, the code example contains the static import declaration,
it has been indicated in the preceding text, etc.).

## Acronyms
The following acronyms are always written as such: *HTTP*, *JSON*, *XML*, *YAML*, *DDD*, *JVM*, *JDK*, *JWT*,
*AWS*.


## Website
The QuantumMaid website has to be always written as such: https://quantummaid.de
