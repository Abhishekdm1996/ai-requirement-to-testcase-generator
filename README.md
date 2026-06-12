# AI-Powered Requirement to Test Case Generator

## Overview

As a QA Engineer, I often spend time analyzing requirements and creating test cases manually.

This project automates that process by using AI to generate structured test cases whenever a new requirement is added to Google Sheets.

The goal is to reduce manual effort and help QA engineers focus more on analysis, validation, and improving product quality.

---

## Problem Statement

Creating test cases from requirements is a repetitive and time-consuming activity.

I wanted to explore whether AI could automatically analyze requirements and generate an initial set of test cases.

---

## Solution

This workflow automatically:

1. Reads a new requirement from Google Sheets
2. Detects the new entry using n8n
3. Sends the requirement to Gemini AI
4. Generates structured test cases
5. Writes the generated test cases into a separate Test Cases sheet

---

## Workflow Architecture

Google Sheets (Requirements)

↓

n8n Trigger

↓

Gemini AI

↓

JavaScript Formatter

↓

Google Sheets (Test Cases)

---

## Tech Stack

* n8n
* Gemini AI
* Google Sheets
* JavaScript

---

## Features

* Automatic test case generation
* Requirement-to-test-case traceability
* Reduced manual QA effort
* Easily extendable to Jira, Notion, Azure DevOps, and TestRail

---

## Demo

A Loom demonstration of the workflow is available on LinkedIn.

---

## Future Enhancements

* Jira Integration
* Notion Integration
* Azure DevOps Integration
* Risk-based test case prioritization
* API test case generation
* Automation script generation

---

## Author

Abhishek D M

Senior QA Engineer | AI-Powered Testing Enthusiast

LinkedIn:
https://www.linkedin.com/in/abhishek-d-m-4a7aa818a
