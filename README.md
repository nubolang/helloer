# Helloer

Helloer is a demo package for Nubo's package manager.

## Installation

```
nubo add github.com/nubolang/helloer@v1.0.0
```

Using `@` for versioning is not required. It has a fallback value `latest`. A version can be a version number (aka Tag), a short or a long commit hash.

## Usage

```nubo
import helloer from "pkg:nubolang/helloer" // when importing the root, Nubo will import the nubolang/helloer/helloer.nubo by default

helloer.sayHello()
```
