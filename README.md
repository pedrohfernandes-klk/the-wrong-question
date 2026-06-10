THE WRONG QUESTION

THE WRONG QUESTION is a compact text-card app that hands you the question underneath the one you are asking.

It does not answer.
It relocates.

One button. One question. The premise you did not check. The cost you left off the list. The approval you are still waiting for. The loop hiding underneath the loop.

This is not an advice app. It is an interrogator.

What it does

THE WRONG QUESTION generates a single second-person question designed to interrupt the user’s current frame of thought.

Instead of giving solutions, it asks sharper questions such as:

What are you protecting by staying confused?
Who taught you this was the rule?
What would you do if you weren’t allowed to be busy?
What problem does this problem let you avoid?
What are you calling research because avoidance has bad optics?

The app is built for stuck decisions, repeated mental loops, over-explained problems, false dilemmas, and any sentence that starts with:

I just need to figure out how to...

Current build
999 questions
Single-card random output
Copy button
Clear button
About panel
No account
No saved data
No backend
No tracking
No external framework
Single-file HTML app
Concept

Most problems do not need a better answer.
They need a better question.

THE WRONG QUESTION exists to perform one move:

relocate the problem.

It looks for the hidden question beneath the visible one: the untested premise, the inherited rule, the false urgency, the concealed trade-off, the fear disguised as strategy, the old permission structure still running in the background.

The output should feel direct, useful, and slightly uncomfortable.

Not therapeutic fluff.
Not “live, laugh, ask.”
Not motivational wallpaper.

A good THE WRONG QUESTION card should be:

short enough to hit immediately;
clear enough to understand at once;
sharp enough to shift the frame;
broad enough to apply to many situations;
specific enough not to feel generic;
second-person throughout;
genuinely load-bearing.
Tone rules

The questions should sound like an intelligent interrogator, not a life coach.

Preferred qualities:

precise
dry
direct
psychologically useful
slightly severe
unsentimental
intellectually provocative
plain-language rather than ornate

Avoid:

therapy-poster softness
fake profundity
vague uplift
motivational clichés
mystical framing
overlong questions
cute wordplay for its own sake
questions that merely sound deep but do not move thought forward

The app’s best questions should expose the structure underneath the user’s question.

Example question patterns

Strong cards often use one of these moves:

1. Hidden premise

What are you assuming has to stay true?

2. Hidden cost

What would you lose if this finally worked?

3. Hidden reward

What is the hidden reward for staying stuck?

4. Hidden authority

Whose voice is inside the word “should” there?

5. Hidden avoidance

What answer are you avoiding by asking for advice?

6. Hidden identity

Which answer would make your current identity inconvenient?

7. Hidden permission

What are you waiting for permission to stop?

8. Hidden fear

What are you calling caution because you fear being seen trying?

9. Hidden loyalty

What are you loyal to that stopped being loyal to you?

10. Hidden absurdity

What part of this turns absurd the moment you say it plainly?

User experience

The app is intentionally simple:

The user brings a problem, decision, loop, or vague discomfort to mind.
They press ASK AWAY.
The app returns one question.
The user sits with it, copies it, clears it, or asks again.

The tool is not meant to produce a complete answer.
It is meant to change the angle of inquiry.

Visual identity

THE WRONG QUESTION uses a dark terminal-like interface with cyan interrogation-glow and orange-red emphasis. The visual tone is severe, compact, and slightly hostile, matching the idea of an interrogator that refuses to flatter the user’s original premise.

Core interface language:

ANGLE: WRONG
PREMISE: UNCHECKED
MERCY: OFF
the question under the question
File structure

The app is currently contained in a single HTML file:

index.html

The file includes:

HTML structure
CSS styling
embedded JavaScript
question deck
favicon
About panel
copy/clear logic
random card selection

No build process is required.

How to run locally

Download or clone the project, then open:

index.html

in any modern browser.

No server is required.

Deployment

Because the app is a static single-page HTML file, it can be hosted on any static hosting platform, including:

GitHub Pages
Netlify
Vercel
Cloudflare Pages
Neocities
WordPress custom HTML embed/page
any standard web host
Editing the question deck

The question deck lives inside the JavaScript array:

var CARDS = [
  "what would you do if you weren’t allowed to be busy?",
  "who taught you this was the rule?",
  ...
];

To add new questions:

Add each question as a quoted string.
Keep the question lowercase unless there is a specific reason not to.
End every card with a question mark.
Keep every card as a single second-person question.
Avoid duplicates.
Update the visible deck count in the About section if the total changes.
Content standards

Every new card should pass this test:

Does this question reveal the question underneath the user’s question?

If not, cut it.

A weak card merely sounds interesting.
A strong card changes the user’s mental position.

Relationship to SPARK TOOLS

THE WRONG QUESTION belongs to the broader SPARK TOOLS family of compact text instruments.

Where sibling apps generate statements, diagnoses, crooked definitions, bad advice, or evidence-flavoured satire, THE WRONG QUESTION fills the missing slot:

it makes questions.

Its role in the suite is to redirect thought before the answer-machine starts running.

Privacy

THE WRONG QUESTION runs locally in the browser.

It does not require:

login
account creation
database access
analytics
personal data
server-side storage

Nothing is saved by the app.

Copyright

© HRF 2026. All rights reserved.

The app, interface copy, question deck, concept, and design are protected creative materials. Do not reproduce, redistribute, modify, or commercially reuse without permission.
