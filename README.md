<p align="center">
  <img src="chronex logo.png" width="140" alt="Chronex Logo" />
</p>

<h1 align="center">Chronex</h1>

<p align="center">
  Automated contradiction detection and test suite generation for large-scale game docs.
</p>

<p align="center">
  <a href="https://chronex.dev">🔗 Live App</a> &nbsp;&nbsp;•&nbsp;&nbsp;
  <a href="https://youtu.be/aiIke5tNuQ8?si=HNe-thbdHVmf8HGy">▶️ Watch Demo</a>
</p>

---

## Demo

<p align="center">
  <a href="https://youtu.be/aiIke5tNuQ8?si=HNe-thbdHVmf8HGy">
    <img src="chronex thumbnail.png" alt="Watch Chronex Demo" width="700" />
  </a>
</p>

---

## The Problem

Game docs are messy. Not because designers are careless — but because they grow over months, across multiple people, and no one can hold the whole thing in their head at once.

One section says the max player level is 50. Another references level 60. A mechanic gets redefined three chapters later. A character constraint quietly contradicts a progression rule written six weeks ago.

None of this gets caught until it's in the build. By then it's expensive.

QA teams then spend days manually turning those same docs into test cases — working from specs that were never verified to be consistent in the first place.

---

## What is Chronex?

Chronex is an AI-powered tool that reads your game docs, finds where the rules contradict each other, and once you've resolved those conflicts, generates a ready-to-use test suite from what's left.

You upload your docs. Chronex does a deep read through all of it and flags every place where something doesn't add up — two rules that clash, a value defined differently in two places, things like that. It then shows you those conflicts one by one inside the platform so you can review and resolve them yourself, without going anywhere else.

Once you've worked through the conflicts, Chronex takes those clean verified rules and turns them into a full test suite — ready to hand straight to QA.

No more manually building test plans from scratch. No more logic bugs that slip through because nobody caught the contradiction in the doc.

---

## Why Chronex?

Most existing tools either check code or do a surface-level text search. 
Chronex works at the spec level — before any code is written — which is 
where fixing things is cheapest.

A few things that make it different:

- **Built for game docs, not software specs.** Every other test generation 
  tool out there — BrowserStack, TestCollab, Keysight — works from PRDs, 
  user stories, or Jira tickets. Clean, structured, software-style inputs. 
  Nobody is solving this for game docs, lore files, and multi-author 
  design specs.

- **It generates test cases from verified rules only.** Other tools take 
  whatever's in your doc and run with it. Chronex only generates the test 
  suite after contradictions are cleared — so your tests actually reflect 
  what the game is supposed to do, not a broken spec.

- **It catches contradictions across the whole doc, not just adjacent 
  lines.** A rule on page 4 conflicting with something on page 47 — 
  Chronex finds it.

- **It understands context.** It doesn't flag a conditional rule as a 
  contradiction to an unconditional one. It knows the difference.

- **You resolve everything inside the platform.** No exports, no manual 
  cross-referencing, no switching between tools.

---

## How It Works

1. Upload your game docs — PDF, DOCX, Markdown, or JSON
2. Chronex reads through and finds all the contradictions
3. You review and resolve each conflict directly inside the platform
4. Chronex takes your verified rules and generates the test suite
5. Download and hand it straight to QA

---

## Screenshots

<br>

**Upload Dashboard**

![Upload Dashboard](demo%20img.png)

<br>

**Conflicts Display**

![Conflicts Display](demo%20img%203.png)

<br>

**Generated Test Cases**

![Generated Test Cases](demo%20img%202.png)

<br>

---

## Built With

- Python / Flask
- React / Next.js
- Supabase
- Cerebras & Groq
- Sentence Transformers

---

## Author

**Pranav Tomar**  
B.Tech, Electronics and Computer Science Engineering  
Vidyalankar Institute of Technology, University of Mumbai
