<!--
GENERATED FILE - DO NOT EDIT
This file was generated by [MarkdownSnippets](https://github.com/SimonCropp/MarkdownSnippets).
Source File: /mdsource/README.source.md
To change this file edit the source file and then run MarkdownSnippets.
-->

<a id="top"></a>

# CppApprovals

[![Build Status](https://api.travis-ci.org/approvals/ApprovalTests.cpp.svg?branch=master)](https://travis-ci.org/approvals/ApprovalTests.cpp) [![Build status](https://ci.appveyor.com/api/projects/status/lf3i76ije89oihi5?svg=true)](https://ci.appveyor.com/project/isidore/approvaltests-cpp) [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

<a href="https://github.com/approvals/ApprovalTests.cpp/releases/download/v.3.4.1/ApprovalTests.v.3.4.1.hpp">Download the latest version of the **single header file** here.</a>

<!-- toc -->
## Contents

  * [What are Approval Tests?](#what-are-approval-tests?)
  * [Requirements](#requirements)
  * [Getting Started](#getting-started)
  * [ToString (ostream insertion)](#tostring-(ostream-insertion))
  * [Feedback](#feedback)
<!-- endtoc -->


## What are Approval Tests?

Also known as **Golden Master Tests** or **Snapshot Testing**, Approval Tests are an alternative to asserts. If you are unfamiliar with them, we have an overview and a tutorial [TBD].

They are great for testing objects with lots of fields, or lists of objects.

## Requirements

* C++11 (or above) compiler
* Mac/Linux/Windows
* One of:  [GoogleTest](https://github.com/google/googletest), [Catch1](https://github.com/catchorg/Catch2/tree/Catch1.x), [Catch2](https://github.com/catchorg/Catch2), [doctest](https://github.com/onqtam/doctest), [Okra](https://github.com/JayBazuzi/Okra)  

## Getting Started

* Download [The Approval.cpp Starter Project](https://github.com/approvals/ApprovalTests.Cpp.StarterProject)
* Read the [Getting Started](/doc/GettingStarted.md#top) page
* [Set up your main file.](/doc/GettingStarted.md#main-file)
* Read the [User Guide](/doc/README.md#top).
* Watch the [Videos](/doc/Videos.md#top)

## ToString (ostream insertion)
Often, you will need to create functions to allow objects to print their state. This is commonly done with on ostream `<< operator`.
You can find examples here: [To String](/doc/ToString.md#top)

## Feedback

If you have any comment or suggestion on this documentation, please email Llewellyn or Clare via the details in the [Contributing page](/doc/Contributing.md#top).
