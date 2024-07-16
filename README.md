# Basics of Go(lang) Programming

## Table of Contents:
<ol>
  <li><a href="#1-introduction-to-go">Introduction to Golang</a></li>
  <li><a href="#2-the-way-go">The Way Golang</a></li>
  <li><a href="#3-mastering-concurrency-in-go">Mastering Concurrency in Golang</a></li>
  <li><a href="#4-operating-with-operators">Going Deeper with Golang</a></li>

  <li><a href="#sources">Sources</a></li>
</ol>

<div align="center">
  <h1>Curriculum Content</h1>
</div>

- [📘 Introduction to Golang](#-day-x)
  - [Why Golang ?](#why-golang-)
  - [Environment Setup](#environment-setup)
    - [Installing Golang](#installing-golang)
    - [Installing Visual Studio Code](#installing-visual-studio-code)
      - [How to use visual studio code](#how-to-use-visual-studio-code)
  - [Basic Golang](#basic-golang)
    - [Golang Syntax](#golang-syntax)
    - [Comments](#comments)
    - [Contants](#Contants)
    - [Variables](#variables)
      - [Scope of variables](#scope-of-variables)
    - [Data types](#data-types)
      - [Basic data types](#basic-data-types)
      - [Composite data types](#composite-data-types)
    - [Control flow](#control-flow)
      - [Statement for looping](#statement-for-looping)
      - [Iteration for nesting looping](#iteration-for-nesting-looping)
      - [Using for range loop](#using-for-range-loop)
    - [Control Structure](#control-structure)
      - [If else condition](#if-else-condition)
      - [Switch case condition](#switch-case-condition)
    - [Functions](#functions)
      - [Parameter and argument](#parameter-and-argument)
      - [Return mutiple values](#return-multiple-values)
      - [Defer, panic & recover, and tracing](#defer-panic-&-recover-and-tracing)
      - [Built-in function](#built-in-function)
      - [Higher order function](#higher-order-function)
      - [Closures](#closures)
    - [Array and slices](#array-and-slices)  
      - [Array literals and parameters](#array-literals-and-parameters)
      - [Slices](#slices)
      - [Bytes and slices](#bytes-and-slices)
    - [Struct](#struct)
      - [Structs with tags](#structs-with-tags)
      - [Anonymous fields and embedded structs](#anonymous-fields-and-embedded-structus)
      - [Method vs Functions](#method-vs-functions)
      - [Non-exported fields](#non-exported-fields)
      - [Garbage collection and setFinalizer](#garbage-collection-and-setfinalizer)
    - [Maps](#maps)
      - [Key-values item](#key-values-item)
      - [A Slices of maps](#a-slices-of-maps)
      - [Sorting and inverting a map](#sorting-and-inverting-a-map)
    - [Pointers](#pointers)
    - [Generics](#generics)
    - [Refection and interface](#reflection-and-interface)
      - [Changing structure values using reflection](#changing-structure-values-using-reflection)
      - [The sort.interface interface](#the-sort-interface-interface)
      - [Type assertions and type switches](#type-assertions-and-type-switches)
      - [Limitations of OOP in Go](#limitations-of-OOP-in-Go)
    - [Nil](#nil)
    - [Type assertions](#type-assertions)
- [📘 The Way Golang](#-day-x)
    - [Go mod and dependency managemenet](#go-mod-and-dependency-management)
    - [Package](#Package)
      - [Package and import](#package-and-import)
      - [Package initialization](#package-initialization)
      - [Package os](#package-os)
      - [Package string](#package-string)
      - [Package flag](#package-flag)
      - [Package strconv](#package-strconv)
      - [Package math](#package-math)
      - [Package container list](#package-container-list)
      - [Package sort](#package-sort)
      - [Package time](#package-time)
      - [Package reflect](#package-reflect)
      - [Package regexp](#package-regexp)
      - [Package encode decode base64](#package-encode-decode-base64)
      - [Package encode decode base64](#package-encode-decode-base64)
      - [Package hash sha1](#package-hash-sha1)
      - [A package working with a database](#a-package-working-with-database)
      - [Testing a go package](#testing-a-go-package)
      - [Gitlab runners and go](#gitlab-runners-and-go)
      - [Github actions and go](#github-actions-and-go)
    - [Reading and writing](#reading-and-writing)
      - [Reading-writing-file](#reading-writing-file)
      - [Reading-writing-file-with-buffer](#reading-writing-file-with-buffer)
      - [Reading-writing-file-with-slices](#reading-writing-file-with-slices)
      - [Read-CSV-file](#read-CSV-file)
    - [The json data format](#the-json-data-format)
    - [The XML data format](#the-xml-data-format)
    - [Error handling and testing](#error-handling-and-testing)
    - [Goroutine](#goroutine)
    - [Channels](#channels)
## Sources
