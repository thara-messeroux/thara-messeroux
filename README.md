## 👋🏾 Salut, I'm Thara (she/her)

I'm a Product Designer and Software Engineer. I design and build digital products end to end, from user research and Figma prototypes to accessible, production-ready front-end experiences. I also ship LLM features on the OpenAI API. MS in Computer Science, Northeastern University.

Today I lead product design and front-end development at [Northeastern Global News](https://news.northeastern.edu), bringing together research, design systems, accessibility, analytics and A/B testing. My work there has increased page views by 136% and topic engagement by 64%.

Previously Software Engineer at Audible, an Amazon company, across web and native iOS: a full-stack internal tool in React, TypeScript, Java and AWS for 30,000+ users, then the Audible iOS app in Swift, SwiftUI, UIKit and Objective-C. Before that, Computer Scientist at NAVAIR.

I'm especially interested in human-centered AI, design systems, B2C products, and spatial computing (AR/VR/XR). Currently starting a Graduate Certificate in AI Applications at Northeastern.

Outside of work I love music, dancing, travel, and finding inspiration in art and architecture.

### Mosaic, an LLM-powered reflection app

[Repo](https://github.com/thara-messeroux/mosaic) | [Live app](https://mosaic-blond.vercel.app)

React, TypeScript, Supabase, OpenAI. The AI engineering decisions I made:

- Every model call runs server-side in a Supabase Edge Function, so the API key never reaches the browser
- Structured JSON outputs, parsed and validated on the way back, with explicit handling for model refusals, empty responses and malformed JSON
- System prompts carrying explicit behavioral guardrails, since the app handles personal reflections
- Token caps, temperature control and a per-user daily call limit to keep costs bounded
- A multi-turn adaptive flow where each question is generated from the answers so far
- Postgres schema with row level security across every table, and separate anon and service-role clients

### Also pinned

- **TrailTales** Python and Django, PostgreSQL, full CRUD, relational models and schema migrations
- **Commencement CMS** Node, Express, MongoDB, session-based auth, designed and built end to end
- **NGN category landing prototypes** responsive HTML and CSS directions built for editorial review at Northeastern Global News
- **Mastermind** a Python codebreaking game with an algorithmic opponent, covered by unit tests

### Working with

`TypeScript` `React` `Next.js` `JavaScript` `HTML/CSS` `Python` `Django` `Node` `Express` `PostgreSQL` `MongoDB` `Supabase` `OpenAI API` `Swift` `Java` `PHP` `AWS` `Figma`

### Elsewhere

[Portfolio](https://tharamesseroux.com) | [LinkedIn](https://www.linkedin.com/in/tharamesseroux/) | messeroux.t@northeastern.edu
