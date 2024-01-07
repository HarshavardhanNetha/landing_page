---
title: Join the waiting list for the Qdrant Hybrid SaaS solution.
section_title: Request early access to the Qdrant Hybrid SaaS
form:
  - id: 0
    header: "Get <span style='color: var(--brand-primary);'>Early Access</span> to Qdrant Hybrid SaaS"
    label: All right! 😊 What is your e-mail? *
    placeholder: name@example.com
    type: email
    name: email
    required: True
  - id: 1
    label: May we have your name, please?
    type: text
    rows: 1
    placeholder: Dr. Smith
    name: name
  - id: 2
    label: What's the name of your company?
    rows: 1
    name: companyName
  - id: 3
    label: What's the size of your company?
    type: radio
    options:
    - 1
    - 2-10
    - 11-50
    - 51-200
    - 201-1000
    - 1001+
    name: companySize
  - id: 4
    label: Are you already using Qdrant?
    type: checkbox
    options:
    - Yes, in Qdrant Cloud
    - Yes, on-premise
    - We are using another solution at the moment
    - No, we are not using any vector search engine
    name: experienced
---