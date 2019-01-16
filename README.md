# Fix Ordering Questions
### *Package Name*: fix-ordering-questions
### *Child Type*: Post-import
### *Platform*: All
### *Required*: Required

This child module is built to be used by the Brigham Young University - Idaho D2L to Canvas Conversion Tool. It utilizes the standard `module.exports => (course, stepCallback)` signature and uses the Conversion Tool's standard logging functions. You can view extended documentation [Here](https://github.com/byuitechops/d2l-to-canvas-conversion-tool/tree/master/documentation).

## Purpose

When an ordering question appears in a Brightspace/D2L course the Canvas Import Tool converts this type of question into a multiple choice question with no answers. This child module goes through the imported Canvas course and fixes the ordering questions that were converted to multiple choice questions and changes them to matching questions.

## How to Install

```
npm install fix-ordering-questions
```

## Run Requirements

This child module must be run with any other quiz related child modules.

## Process

Describe in steps how the module accomplishes its goals.

1. Does this thing
2. Does that thing
3. Does that other thing

## Log Categories

List the categories used in logging data in your module.

- Ordering Question Fixed

## Requirements

* The child module shall fix all incorrectly converted ordering questions.