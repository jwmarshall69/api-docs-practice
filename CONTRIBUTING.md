# CONTRIBUTING

This repository is a **beginner-friendly API documentation practice** project.  
Use these guidelines to keep writing consistent and easy to review.

## Writing Principles
- Audience-first, task-first, example-heavy
- Plain language and scannable sections
- Every endpoint needs a runnable example

## Parameter Tables
| Name | In | Type | Required | Default | Description |
|---|---|---|---|---|---|
| `limit` | query | integer | No | 25 | Results per page (1–100) |

## Errors
| Status | Name | When | Fix |
|---|---|---|---|
| `401` | Unauthorized | Missing/invalid token | Send `Authorization: Bearer …` |
