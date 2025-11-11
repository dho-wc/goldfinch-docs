A place to capture prompt dev and other documents outside of the main repo where they'll be used.

## Resources for the MCP

- `resource_estate-planning-faqs.md` is straight from the landing page FAQs. This will provide the model with guided answers to user questions that align with our own public statements.
- `resource_product-information.md` is also from the landing page and focused on features, product promises, and pricing info.

## System prompt

This should be applied as the Agent's overarching system prompt.

## Question guide

`raw_questions_external__model_guidance.json` is an expanded version of the original questionnaire schema with guidance added. This document can be used to derive a guide as well as produce a flattened answer schema for the Agent. This will keep all necessary interview data in a single source of truth.