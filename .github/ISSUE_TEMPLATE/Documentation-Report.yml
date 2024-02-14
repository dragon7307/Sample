name: Documentation Error Report
description: File a documentation error report
title: "[Documentation]: "
labels: ["documentation", "triage"]
projects: ["draconware-dev/Sample"]    
assignees:
  - dragon7307
body:
  - type: markdown
    attributes:
      value: |
        Thanks for taking the time to fill out this documentation error report!
        If you want to report some grammatical or syntactical issues, consider opening a Pull Request to fix it yourself, since it is often easier to fix such an issue yourself than to describe it.  
  - type: textarea
    id: what
    attributes:
      label: Describe the documentation error?
      description: What is the error? Give line numbers, source files, or Methods or Classes where appropriate.   
    validations:
      required: true
  - type: dropdown
    id: version
    attributes:
      label: Version
      description: What version of our software does this error occur in?
      options:
        - 1.0.0 [Depreated]
        - 1.1.0 (Current)
      default: 0
    validations:
      required: true
  - type: checkboxes
    id: terms
    attributes:
      label: Code of Conduct
      description: By submitting this issue, you agree to follow our [Code of Conduct](https://github.com/dragon7307/Sample/blob/main/.github/CODE_OF_CONDUCT.md)
      options:
        - label: I agree to follow this project's Code of Conduct
          required: true
