# Hi, I'm Murali

I test software and I build it.

I am an SDET and QA automation engineer in Melbourne. I spent 3.5 years in QA and test automation at TCS on two enterprise clients, EY and PG&E, and I hold a Master of Information Technology from RMIT University (2026). I also build and ship my own apps end to end, so I can write the feature as well as test it.

Open to SDET, QA automation, test analyst and software developer roles. Full Australian work rights, available now, anywhere in Australia.

[LinkedIn](https://www.linkedin.com/in/muraligmd/) | [Email](mailto:muraligmd8@gmail.com)

## Projects

### Va8Se10, group expense splitting web app

**Live site:** [va8se10.vercel.app](https://va8se10.vercel.app) | **Code:** private repo. I am happy to give read access, just ask.

Solo build in TypeScript, React and Express, about 11,000 lines, with hand written SQL and no ORM.

- 500+ automated tests across five layers: unit, API, end to end, smoke and property based
- 17 SQL data checks run as a build gate, so a passing suite cannot ship broken data
- GitHub Actions pipeline: typecheck, lint, format, tests, deploy to Vercel, then smoke tests on the live site
- A nightly run repeats every test and fails on any flaky one
- 26 defects logged, each with a root cause and a prevention rule

`TypeScript` `React` `Express` `SQLite` `Playwright` `Vitest` `fast-check` `GitHub Actions` `Vercel`

### SCOUT, real time school safety platform

[App repo](https://github.com/GitItMurali/P000415SE-SCOUT-School-Safety-Dashboard-Prototype-) | [End to end test suite](https://github.com/GitItMurali/scout-e2e-tests)

RMIT capstone, built by a team of 5 for an industry client. I was QA Lead and a full stack developer. The project earned a High Distinction.

- 100+ end to end test cases tracked in Jira with Zephyr Scale
- Cucumber and Playwright suite that posts each result back to Zephyr Scale automatically
- Built login and role based access, SMS and email alerts through Twilio and SendGrid, and the reporting dashboards
- Added caching that cut database reads by about 99 percent

`React` `Node.js` `Firebase` `Playwright` `Cucumber` `GitHub Actions` `Jira` `Zephyr Scale`

### How U Doin, Android time and habit tracker

[Repo](https://github.com/GitItMurali/how-u-doin)

Solo build in React Native and Expo, about 7,000 lines of TypeScript. Everything is stored on the phone.

- On device SQLite with versioned migrations that upgrade stored data without losing history
- Scheduled reminders and an automatic daily reset that runs in the background
- PIN and fingerprint lock, with a lockout after five wrong tries

`TypeScript` `React Native` `Expo` `SQLite`

### Free GPT Collective, multi model AI web app

[Repo](https://github.com/GitItMurali/free-gpt-collective) | [Try it](https://gititmurali.github.io/free-gpt-collective/)

One HTML file in vanilla JavaScript. No backend and no build step.

- Sends a question to 7 AI models across 4 providers
- Falls back to the next model on rate limits, auth errors, timeouts or empty replies
- Council mode collects every answer, then one model merges them into a single verdict
- Resume mode checks job fit and writes a tailored resume and cover letter as Word files

`JavaScript` `HTML` `CSS` `LLM APIs`

## What I work with

| Area | Tools |
|---|---|
| Test automation | Selenium with Java, Playwright with TypeScript, Cucumber (BDD), JUnit, Vitest, Postman |
| Testing | Functional, regression, integration, system, exploratory, API, mobile, cross browser |
| Development | TypeScript, JavaScript, Java, SQL, React, Node.js, Express, React Native |
| Delivery | GitHub Actions (CI/CD), Git, Jira, Zephyr Scale, Azure DevOps, HP ALM, Agile and Scrum |

## Experience

**Systems Engineer (QA and Testing), Tata Consultancy Services** | May 2019 to Oct 2022

- Cut a regression cycle from about 3 days to 1 day, roughly 65 percent, with Selenium and Java (EY)
- Raised 5 to 15 defects per sprint on a billing platform invoicing millions of customers (PG&E)
- Stepped up to lead the test team for a period, working next to the appointed team lead
