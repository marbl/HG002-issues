---
name: Problem Regions
about: Use this template to describe regions larger than 50 bases in the v1.0 assembly
  which are problematic.
title: ''
labels: ''
assignees: ''

---

name: Bug Report
description: File a bug report
title: "[Bug]: "
labels: ["bug", "triage"]
projects: []
assignees:
  - octocat
body:
  - type: markdown
    attributes:
      value: |
        Thanks for taking the time to fill out this bug report!
  - type: input
    id: contact
    attributes:
      label: Contact Details
      description: How can we get in touch with you if we need more info?
      placeholder: ex. email@example.com
    validations:
      required: false
  - type: textarea
    id: problem-region
    attributes:
      label: Region in V1.0
      description: Have you checked whether this region overlaps with a previously reported issue or a pending patch to v1.0?
      placeholder: Describe what evidence you've seen that the assembly has errors.
      value: ""
    validations:
      required: true
  - type: dropdown
    id: version
    attributes:
      label: Version
      description: What version of the hg002 assembly is this region in?
      options:
        - 1.0
      default: 1.0
    validations:
      required: true
