# GHActions-demo

The purpose of this repository is to demonstrate basic GitHub Actions.

# Scripts

Two simple scripts inspired from the tutorial : say "Hello" and "Goodbye" to the name given as a parameter. This is a reusable workflow.

# Test jobs

The idea is to define jobs, and have multiple parameters following the context :

- jobs.xml : contains the basic test definition, with parameters : list of names, and greetings (hello and/or goodbye) to show
- main.yml : set of tests executed on push event
- cron.yml : set of schedule tests
- manual.yml : set of tests manually triggered

## Matrix

Matrix is used to run jobs in parallel for different names

## Input

Usage of inputs for manual run
