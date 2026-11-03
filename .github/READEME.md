# APITesting202

API testing practice project with reusable AI prompts for test design.
Built by Dipali Chidrawar, QA Lead.

## Purpose

This repository shows how I test APIs and how I use generative AI to speed up test design,
with a human review step before anything is used.

## What's inside

```
APITesting202/
├── .github/
│   └── prompts/
│       └── reusable_prompts.md   # Reusable prompts for test design
├── [tests/]                      # API test scripts
├── [collections/]                # Postman collections, if any
└── README.md
```

## Tools and technologies

- API testing: [Postman / Playwright API testing]
- Language: [TypeScript / JavaScript]
- Version control: Git and GitHub
- AI assistant: [Claude / GitHub Copilot]

## AI-assisted test design

The file `.github/prompts/reusable_prompts.md` contains prompts I reuse for:

| Prompt | What it does |
|---|---|
| [Generate API test cases] | [Creates positive, negative and boundary cases from an API spec] |
| [Review test scripts] | [Checks scripts for missing assertions and edge cases] |
| [Prompt name] | [One-line description] |

### Human review

AI output is treated as a draft. Before any generated test case or script is used, I:

1. Check it against the API requirements or specification.
2. Remove wrong or made-up endpoints, fields and expected values.
3. Add missing negative cases, security checks and data validation.
4. Run it and confirm the results before committing.

## How to use the prompts

1. Open `.github/prompts/reusable_prompts.md`.
2. Copy the prompt you need.
3. Replace the placeholders, such as the API name, endpoint and request details.
4. Paste it into your AI assistant and review the output as described above.

## How to run the tests

```bash
# [Add your own steps, for example:]
npm install
npx playwright test
```

## Author

Dipali Chidrawar, QA Lead
GitHub: [dipalichidrawar01](https://github.com/dipalichidrawar01)
LinkedIn: [add your profile link]
