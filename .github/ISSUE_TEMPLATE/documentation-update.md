---
name: Documentation Update
about: Describe this issue template's purpose here.
title: ''
labels: ''
assignees: ''

---

name: 📝 Documentation Update
description: Improve Documentation
title: "[Documentation Update]: "
body:
  - type: checkboxes
    id: existing-issue
    attributes:
      label: Is there an existing issue for this?
      description: Please search to see if an issue already exists for the updates you want to make.
      options:
        - label: I have searched the existing issues
          required: true
  - type: textarea
    id: issue-description
    attributes:
      label: Issue Description
      description: Please provide a clear description of the documentation update you are suggesting.
      placeholder: Describe the improvement or correction you'd like to see in the documentation.
    validations:
      required: true
  - type: textarea
    id: suggested-change
    attributes:
      label: Suggested Change
      description: Provide details of the proposed change to the documentation.
      placeholder: Explain how the documentation should be updated or corrected.
    validations:
      required: true
 
  
  - type: checkboxes
    id: terms
    attributes:
      label: Record
      options:
        - label: "I agree to follow this project's Code of Conduct"
          required: true
        - label: "I want to work on this issue"
          required: False
        - label: "I'm willing to provide further clarification or assistance if needed."
          required: False