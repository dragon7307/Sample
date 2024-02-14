name: Bug Report
description: File a bug report
title: "[Bug]: "
labels: ["bug", "triage"]
projects: ["draconware-dev/Sample"]    
assignees:
  - dragon7307
body:
  - type: markdown
    attributes:
      value: |
        Thanks for taking the time to fill out this bug report!
  - type: textarea
    id: what-happened
    attributes:
      label: Describe the bug?
      description: What happened?
    validations:
      required: true
  - type: dropdown
    id: version
    attributes:
      label: Version
      description: What version of our software are you running?
      options:
        - 1.0.0 [Depreated]
        - 1.1.0 (Current)
      default: 0
    validations:
      required: true
  - type: dropdown
    id: os
    attributes:
      label: Which operating systems are you seeing the problem on?
      multiple: true
      options:
        - Windows
        - Mac
        - Linux
        - Other 
  - type: textarea
    id: logs
    attributes:
      label: Relevant log output
      description: Please copy and paste any relevant log output. This will be automatically formatted into code, so no need for backticks.
      render: shell
  - type: checkboxes
    id: terms
    attributes:
      label: Code of Conduct
      description: By submitting this issue, you agree to follow our [Code of Conduct](https://github.com/dragon7307/Sample/blob/main/.github/CODE_OF_CONDUCT.md)
      options:
        - label: I agree to follow this project's Code of Conduct
          required: true
