---
name: Simple Starter Template
about: This is a simple starter template
title: "[Simple Template]"
labels: simple
assignees: ''
body:
  - type: markdown
    attributes:
      value: |
        This is a simple issue.
        It was created using a workflow_dispatch event.
        The workflow that created this issue is located in the .github/workflows directory.
        The issue was created using the GitHub API.
  - type: input
    id: greeting
    attributes:
      label: Greeting Message
      description: Provide a greeting message
      placeholder: ex. hello
    validations:
      required: false
---


