# Introduction

## What?

A few common rules of API testing:

* An API should provide expected output for a given input
* The inputs should appear within a particular range and values crossing the range must be rejected
* Any empty or null input must be rejected when it is unacceptable
* Incorrectly sized input must be rejected
* ...

API testing is simple. Its implementatin is not. Complexity explodes, with consequences.

## Why?

Reduce risk across public and internal interfaces.

## How?

Overcome these challenges to building a meaningful and sustainable API testing practice:

* [Use case propagation](usecases.md)
* [Access to connected systems](access.md)
* [Synchronous and asynchronous methods](calls.md)
* [API versioning](versioning.md)