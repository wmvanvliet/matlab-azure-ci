# Testing MATLAB CI integration with Azure DevOps

[![Build Status](https://dev.azure.com/marijnvanvliet/marijnvanvliet/_apis/build/status/wmvanvliet.matlab-azure-ci?branchName=main)](https://dev.azure.com/marijnvanvliet/marijnvanvliet/_build/latest?definitionId=3&branchName=main)

There is a MATLAB script here `myscript.m` and a script containing unit tests `testAll.m`.
Check out the code in `.azure/azure-pipelines.yml`. It configures Azure Pipelines to run the script and the test suite on every commit.
