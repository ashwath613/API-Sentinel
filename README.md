# API Sentinel

Api Sentinel is a backend-focused API security testing platform built with Python and FastAPI.

It helps developers find common security issues in APIs by automatically discovering endpoints and testing them for possible vulnerabilities. and also provoide detailed report for induvial endpoints in the console for bettter understandings about upcomming vulnerabilities and errors

## What It Does

- Discovers API endpoints from an OpenAPI specification or API URL
- Identifies HTTP methods, parameters, and endpoint details
- Runs automated security tests
- Detects common API security vulnerabilities
- Assigns severity, confidence, and risk scores
- Stores scan results using PostgreSQL
- Provides a web dashboard for reviewing results
- Generates developer-friendly security reports
- Supports security regression testing after fixes

## Security Checks

API Sentinel currently checks for:

- Broken Object Level Authorization (BOLA)
- Authentication Bypass
- Broken Authorization
- SQL Injection
- Reflected XSS
- SSRF
- Missing Rate Limiting
- Mass Assignment
- Input Validation Issues
- Sensitive Data Exposure
- Missing Security Headers

## How It Works

```text
API URL / OpenAPI Specification
            |
            v
     Endpoint Discovery
            |
            v
        Risk Mapping
            |
            v
      Security Testing
            |
            v
      Finding Analysis
            |
            v
     Risk and Severity
            |
            v
      Database Storage
            |
            v
   Dashboard and Report
