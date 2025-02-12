# Civic Tech Toronto Resources

## 1. Overview

Welcome to the **Civic Tech Toronto Resources** repository! This is a work-in-progress collection of regionally relevant resources intended to support civic technologists, local government members, community organizations, and others engaged in the civic tech ecosystem within the **Toronto** area.

This repository serves as a curated knowledge hub, storing resources in **Markdown files with YAML frontmatter**, making them easily consumable by **static site generators** such as **Jekyll** or **Hugo** for eventual publication on a public-facing website.

## 2. Scope & Guidelines

This repository is intended to house **Toronto-specific** civic tech resources. As such, the following criteria apply to content contributions:

1. **Non-commercial** – No promotion of for-profit interests.
2. **Non-partisan** – Resources must not advocate for any political party or candidate.
3. **Non-editorial** – Resources should be factual and informative, avoiding personal opinions or editorial content.
4. **Relevant to Civic Tech Toronto members** – Resources should support civic technology work, community initiatives, or public interest technology efforts in Toronto.
5. **Regionally Significant** – Only Toronto-area resources should be included. Broader civic tech-related resources should be contributed to the separate **Civic Tech Toolkit resources** repository.

## 3. Structure

### Documents Structure

All resources are stored as **Markdown files with YAML frontmatter** to ensure structured metadata. A sample resource file format may look like this:

```yaml
---
title: "Open Data Toronto"
description: "A portal for open government data provided by the City of Toronto."
url: "https://open.toronto.ca/"
tags:
  - type/data/opendata
---
```

### Tagging Structure

The tagging structure is designed to categorize resources effectively, making them easier to search and filter.
Tags are organized into a namespaced categories of `type` and `topic`. Each resource can have multiple tags to represent its content and purpose.

Type refers to the utilty of the item, specifying the nature of the resource, with further subtypes refining specificity:

- `type/data`
- `type/data/opendata`
- `type/community`
- `type/community/conference`

Topic refers to the subject of the item, indicating the subject matter:

- `topic/transit`
- `topic/opendata`

The tagging structure is subject to change – please feel free to disregard this structure as necessary.

### Directory Structure

```
resources/
├── _templates/      # Document structure templates
├── .obsidian/       # An Obsidian vault configuration folder to support management.
├── entities/        # The folder of entries resources.
├── LICENCE          # The licence \(·_·)/
└── README.md        # This file  -(·.·-)
```

Also subject to change, suggestions are welcome.

## 4. Governance

This repository is currently in a **pilot phase**, managed on behalf of the **Civic Tech Toronto Steering Committee Archivist**. Governance processes for reviewing and accepting contributions are **to be determined** as part of this pilot initiative.

## 5. Future Plans

- Establish a formal governance model for resource curation and moderation.
- Develop an automated process to generate and publish the resources on a public-facing website.
- Expand resource metadata for improved discoverability and user experience.

## 6. License

The content is **provisionally** licensed with a CREATIVE COMMONS ATTRIBUTION-NONCOMMERCIAL-SHAREALIKE 4.0 License [CC BY-NC-SA 4.0 License](LICENSE.md), you can read more at [https://creativecommons.org/licenses/by-nc-sa/4.0/](https://creativecommons.org/licenses/by-nc-sa/4.0/)

## 7. Contributions & Get Involved

Contributions are welcome! If you'd like to suggest a resource, you can:

1. reach out to [\#org-archives](https://civictechto.slack.com/archives/C08A7SC2TC2) slack channel via the Civic Tech Toronto slack.
2. submit a **pull request** or open an **issue** with details.

### CivicTech Toronto

Civic Tech Toronto is a community-driven initiative, and we welcome participation! If you have suggestions, ideas, or want to contribute visit [civictech.ca](https://civictech.ca/).
