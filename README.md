# PHUZZ – Research Paper Reproduction

## Overview

This repository contains my reproduction of selected experiments using PHUZZ, a coverage-guided web application fuzzer for PHP.

The reproduction was performed as part of my MSc Cyber Security coursework at the University of Exeter.

## Original Research

- **Original repository:** https://github.com/gehaxelt/phuzz
- **Paper:** What All the PHUZZ Is About: A Coverage-guided Fuzzer for Finding Vulnerabilities in PHP Web Applications
- **Authors:** Sebastian Neef, Lorenz Kleissner and Jean-Pierre Seifert
- **DOI:** https://doi.org/10.1145/3634737.3661137

## Reproduction Environment

- Ubuntu on Windows Subsystem for Linux (WSL)
- Docker Desktop
- Docker Compose
- Visual Studio Code

## Experiments Performed

- DVWA – SQL Injection testing
- XVWA – Web vulnerability testing
- Examination of detected vulnerability candidates and recorded exceptions

## Implementation

The reproduction uses the original PHUZZ framework and its Docker-based testing environment. Any modifications and additional configurations are documented separately.

## Results

The experiments generated vulnerability candidate records and exception/error logs that were examined to evaluate the reproduction.

## Acknowledgement

The PHUZZ framework was developed by the original researchers. This repository documents my reproduction work and does not claim authorship of the original framework.