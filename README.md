<p align="center">
  <img src="chronex logo.png" width="140" alt="Chronex Logo" />
</p>

<h1 align="center">Chronex</h1>

<p align="center">
  Automated contradiction detection and test suite generation for large-scale game design documents.
</p>

<p align="center">
  <a href="https://chronex.dev">🔗 Live App</a> &nbsp;&nbsp;•&nbsp;&nbsp;
  <a href="https://youtu.be/aiIke5tNuQ8">▶️ Watch Demo</a>
</p>

---

## Demo

<p align="center">
  <a href="https://youtu.be/aiIke5tNuQ8">
    <img src="chronex thumbnail.png" alt="Watch Chronex Demo" width="700" />
  </a>
</p>

---

## The Problem

Game design documents are messy. Not because designers are careless — but because GDDs grow over months, across multiple people, and no one can hold the whole thing in their head at once.

One section says the max player level is 50. Another references level 60. A mechanic gets redefined three chapters later. A character constraint quietly contradicts a progression rule written six weeks ago.

None of this gets caught until it's in the build. By then it's expensive.

QA teams then spend days manually turning those same docs into test cases — working from specs that were never verified to be consistent in the first place.

---

## What is Chronex?

Chronex is an AI-powered auditing system that reads your game design documents, finds the logical contradictions, and generates a ready-to-use test suite from the verified rules.

You upload your docs. Chronex runs them through a multi-stage analysis pipeline — extracting facts, resolving entity identities, grouping related rules, and auditing them for conflicts. When it finds issues, it surfaces them in an interactive review interface where your team can adjudicate and resolve.

Once the rules are verified, Chronex auto-generates a full test case suite covering positive paths, negative paths, and boundary cases — exported and ready for QA.

No more manually translating docs into test plans. No more contradiction bugs that only show up in shipped builds.

---

## How It Works

1. Upload your GDD — PDF, DOCX, Markdown, or JSON
2. Chronex extracts structured logical facts from the document
3. Related rules are grouped and audited for contradictions
4. You review flagged conflicts through an interactive interface
5. A verified, contradiction-free rule set is produced
6. A full test suite is auto-generated from those verified rules

---

## Screenshots

**Upload Dashboard**
![Upload Dashboard](demo%20img.png)

**Generated Test Cases**
![Generated Test Cases](demo%20img%202.png)

**Conflicts Display**
![Conflicts Display](demo%20img%203.png)

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
