<img src="https://github.com/victorizbitskiy/zspool_pdf/blob/main/logo/logo.svg" height="100px"/>

![ABAP 7.40+](https://img.shields.io/badge/ABAP-7.40sp08+-brightgreen)
![lint](https://github.com/victorizbitskiy/zspool_pdf/actions/workflows/main.yml/badge.svg)

**ATTENTION**: The project is still under development and subject to change.

## `SAP Spool PDF`

Submitting a report to the spool and receiving PDF.

# Table of contents
1. [What it is?](#what-it-is)
2. [What is this for?](#what-is-this-for)
3. [Installation](#installation)

## What it is?

`SAP Spool PDF` is a few classes to help you submit a report to spool and get PDF file easily.

## What is this for?

It is often necessary to get a PDF in xstring/binary format. To do this, you can send a report from your z-report to the sap-spool (in the background), and then read PDF by the spool ID. The **cl_bp_abap_job** class exists in ABAP to run reports in the background. But this class only supports passing report parameters via variant (let me know if I'm wrong).
This is not always convenient, since a variant must either be created before the report is run, or it must be created at runtime.  

`SAP Spool PDF` позволяет в фоне запустить любой отчет создающий PDF. Параметры отчета можно передать непосредственно и/или через вариант.

## Installation

Installation is done with [abapGit](http://www.abapgit.org).


