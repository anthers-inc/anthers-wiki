# Anthers Wiki

**Empty on purpose.** This will hold the public documentation that [the Anthers platform](https://github.com/anthers-inc/anthers) renders in its own wiki — how the support model works, where your money actually goes, how creators publish and get paid, and the reasoning behind the parts that are unusual.

## Why it is a separate repository

Documentation that explains a platform's money model should be readable, quotable and correctable by the people it describes, without cloning the platform to find it. Keeping it apart also keeps the two release cadences apart: correcting a sentence should not need a deploy of the application.

## Why it is empty rather than seeded

There is a lot of internal documentation behind Anthers, and **none of it can simply be moved here.** It is written for people who already hold the context — it cites internal document numbers, records decisions that were later reversed, and argues with itself in the places where the model was still being worked out. That is exactly what internal notes should do and exactly what public documentation should not.

So this starts empty, and gets written rather than ported.

## What is settled

- The platform renders this content in its in-app wiki.
- It is public, and it is meant to be correctable by the people it is about.

## What is not settled

- **The format.** The app currently compiles MDX in the browser. MDX is executable — it compiles to JavaScript and runs — so content living in a separate repository is a materially different trust posture from content in the application's own tree. Plain Markdown compiled at build time is the likelier answer, and it is also the cheaper one.
- **How the app gets it** — fetched at runtime through an API route, or vendored at build time.
- **The structure**, and where the boundary sits between what belongs here and what belongs in the marketing pages.

## In the meantime

[anthers.org](https://anthers.org) has the current explanations, and its FAQ is the most complete public account of the model.

Anthers is a Colorado nonprofit corporation. The platform is free software under the GNU Affero General Public License v3.0 or later.
