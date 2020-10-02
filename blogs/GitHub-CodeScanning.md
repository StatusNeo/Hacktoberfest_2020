<h1 align="center">Code Scanning on GitHub</h1>

<p align="center">
  <img src="img/codescanning.png" height=300 width=500>
</p>
  
GitHub is working immensely to improve security issues in the open source repositories hosted on its platform, further evolving from its traditional **Source Code Management** approach to **DevSecOps** using its in-house Continuous Integration platform, **GitHub Actions**.

> Securing Software, Together

With above motto in mind, GitHub has released its new feature called **Code Scanning** in [Beta](https://github.com/features/security) - releasing publicly soon after taking feedback from those who are using it in early access.

## What is Code Scanning?

Code Scanning is an upcoming GitHub Native tool to find security vulnerabilities and coding errors in the repositories.

For any error/vulnerability found, GitHub creates an alert in the repository which can be removed only after the triggering cause has been fixed.

Code Scanning is automated using GitHub Actions and can be setup using **time-driven** triggers or **event-driven** triggers

## The CodeQL Engine

Code Scanning uses [CodeQL](https://securitylab.github.com/tools/codeql) Engine for semantic code analysis.

QL is an object-oriented programming and query language that powers CodeQL.

CodeQL supports both compiled and interpreted languages including - C/C++, C#, Golang etc.

## Third-Party Support

GitHub's Code Scanning is compatible with third-party tools given that they follow the open standard **SARIF** protocol (Static Analysis Results Interchange Format)

