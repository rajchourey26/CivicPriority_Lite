# CivicPriority_Lite
CivicPriority Lite — a text-only AI notebook that analyzes citizen complaints and ranks development priorities for constituency planning.

**Turning citizen complaints into ranked development priorities with Gemma 4**

CivicPriority Lite is a text-only AI proof-of-concept built for the **Build with Gemma Hackathon 2026**. It demonstrates how citizen complaints received through public meetings, grievance portals, letters, or messaging channels can be transformed into structured development priorities using an AI-assisted pipeline.

The notebook classifies complaints, estimates urgency, assigns categories, calculates priority scores, and generates a short MP-style action brief. The goal is to help constituency offices identify the most important issues faster and more transparently.

---

## Problem Statement

Members of Parliament and constituency teams receive many citizen complaints every day, but these complaints are often:
- fragmented,
- unstructured,
- multilingual,
- repeated across channels,
- and difficult to prioritize manually.

This makes it hard to identify which problems should be addressed first and where limited resources should be allocated.

---

## Solution

CivicPriority Lite uses a simple AI pipeline to:
- analyze citizen complaints,
- classify issues into development categories,
- estimate urgency,
- generate short summaries,
- calculate a priority score,
- and produce a ranked list of civic priorities.

The notebook is intentionally lightweight and text-only so it can be demonstrated quickly in a hackathon setting.

---

## Key Features

- **Text-only input** for fast prototyping.
- **Complaint classification** into categories such as water, roads, electricity, health, and sanitation.
- **Structured JSON-style output** for easier downstream processing.
- **Priority scoring** based on urgency, repetition, and vulnerable-group impact.
- **Ranked output table** for policymaker review.
- **Simple bar chart** for quick visual interpretation.
- **MP-style summary** for decision support.

---

## Notebook Workflow

The notebook follows this flow:

1. Import required libraries.
2. Create a small sample complaint dataset.
3. Define a Gemma-style prompt template.
4. Build a parsing and inference wrapper.
5. Define a scoring function.
6. Run sample complaints through the pipeline.
7. Rank complaints by priority.
8. Visualize issue frequency.
9. Generate an action brief for policymakers.

---

## Sample Output

The notebook produces output such as:
- issue category,
- urgency level,
- location,
- affected group,
- short summary,
- suggested action,
- priority score,
- ranked priority table.

---

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- JSON parsing
- Kaggle Notebook environment

---

## Why This Project

This project is designed to show how AI can support public service planning by converting citizen voice into structured, actionable development priorities.

It is simple enough to demo under hackathon time pressure, while still showing a realistic civic use case for Gemma-based reasoning and structured outputs.

---

## Limitations

This is a proof-of-concept, so it intentionally simplifies many things:
- only a few complaint categories are used,
- input is text-only,
- the model logic is mocked in the demo version,
- multilingual support is limited,
- real deployment and live inference are future work.

---

## Future Improvements

Possible next steps include:
- real Gemma 4 API integration,
- multilingual complaint handling,
- better location extraction,
- ward-level trend analysis,
- dashboard visualization,
- automated report export,
- and real-world deployment for constituency offices.

---

## Hackathon Submission

- **Notebook:** Kaggle public notebook
- **Project Name:** CivicPriority Lite
- **Track:** People’s Priorities — AI for Constituency Development Planning
- **Live Demo:** The notebook itself serves as the live demo

---

## License

This project is created for hackathon demonstration purposes. You may adapt it for research or educational use.

---

## Acknowledgements

Built for the **Build with Gemma Hackathon 2026** using the Gemma 4 concept for structured civic intelligence.
