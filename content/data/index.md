---
title: Data Assessment
summary: Data Assessment Document that gives an overview of the data used for the project.

date: "2018-06-28T00:00:00Z"
editable: true
share: false
---

## Introduction

Our project uses data from [Linux Kernel Mailing List](https://lkml.org/).

## Data Overview and Examples

The data contains technical discussions on the design of and bugs in the Linux kernel. It is collected with a Python script and serves as our data source to develop our project. As of now, only a small portion of the data has been used to debug and evaluate our code. However, we might analyze all the available data from the mailing list in future works.

## Data Accessibility

The data is public on [LKML.ORG](https://lkml.org/). You can access the archived messages directly from the website.

## Data Formats and Challenges

The data is in email format which contains the time stamp, author's information, subject and content of the email. It contains both source codes and commit messages. Since the data contains some useless texts, we need to extract the clean messages. We use certain symbols as delimiters and leverage the power of regular expression to implement a parser for the raw data.

