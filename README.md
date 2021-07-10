# Password Lists

## Introduction

Password lists are going back to the roots of information security. They compile a list of popular passwords. Often to optimize bruteforce attacks to identify (weak) passwords as quickly as possible.

## Background

We are using a dedicated infrastructure to collect, import, and analyze leaked passwords. This system helps us to determine and alert customers affected by certain data breaches. It also supports us to do further analysis of password structures, to understand motivations and decisions by users. Details about collecting, processing and importing password leaks are discussed [in our article](https://www.scip.ch/en/?labs.20210715).

## Approach

Our password lists are based on our statistical analysis and are an important part of our [Red Teaming projects](https://www.scip.ch/en/?offense). The goal is to provide ideal password lists for targets with a specific cultural or technological background:

* general and overall lists
* by countries (tld, association, meta data)
* by popular domains (domains, sub-domains)
* by popular organizations (tld, domains, sub-domains)
* numeric passwords (PINs, years, DDMM)

## Structure

The password lists are ordered by descending popularity. The most popular passwords of a dedicated group are on top of the list. We do only include passwords which were used by at least two different accounts to prevent highly unique or otherwise personally identifying passwords. All passwords are known to be leaked and available to the public.

More information about statistical details are available [in our article](https://www.scip.ch/en/?labs.20210415).
