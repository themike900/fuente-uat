---
name: 🧪 Test Result
description: Report the result of a test case — success or failure.
title: "[Test Result] TC-ID – Short description"
labels: ["test-result"]
assignees: []

body:

- type: input
  id: test_case_id
  attributes:
    label: Test Case ID
    description: Enter the ID of the test case (e.g. REG-001)
    placeholder: REG-001

- type: textarea
  id: result
  attributes:
    label: Result
    description: Was the test successful or not? You may write in English or Dutch.
    placeholder: ✅ Success OR ❌ Failed

- type: textarea
  id: notes
  attributes:
    label: Notes
    description: Any observations, screenshots, or device/browser info.
    placeholder: Worked fine on Android Chrome / Screenshot attached


