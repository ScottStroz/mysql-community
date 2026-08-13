name: Documentation Correction
description: Report an error, omission, or outdated information in the documentation.
title: "[Docs] "
labels:
  - documentation

body:
  - type: textarea
    id: location
    attributes:
      label: Location of the correction
      description: |
        Provide the URL of the web page, the section title, and the paragraph number
        or other precise location of the incorrect content.
      placeholder: |
        Web page: https://...
        Section: ...
        Paragraph: ...
    validations:
      required: true

  - type: textarea
    id: reason
    attributes:
      label: Why does this change need to happen?
      description: Explain what is incorrect, outdated, unclear, or missing and why it should be changed.
      placeholder: Explain the issue and why the documentation needs to be corrected.
    validations:
      required: true

  - type: textarea
    id: suggested_fix
    attributes:
      label: Suggested fix
      description: Describe the proposed correction. Include replacement wording where practical.
      placeholder: Provide the corrected wording or describe the recommended change.
    validations:
      required: true
