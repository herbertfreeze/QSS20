---
jupytext:
  text_representation:
    extension: .md
    format_name: myst
kernelspec:
  display_name: Python 3
  language: python
  name: python3
---

(finalproject_components)=

# Project Components

## Milestone 1

**Due Friday 05-15, 11:59 PM EST.** Submit individually on Canvas.

Before starting milestone 1:

- Set up a free Overleaf account with your Dartmouth email and copy the [Milestone 1 template](https://www.overleaf.com/project/651a342638a4ad7a16a5bb9b) into your own account. **Only edit your local copy** (please do not change the template!)
- Read the report for [one Fall 2022 example project on your option](https://github.com/herbertfreeze/QSS20-S26/tree/main/finalproj_guidelines) and get a sense for its strengths and weaknesses.

Then fill in the template's sections.

Please submit your milestone 1 memo on Canvas. These will be graded.

---

## Milestone 2

**Due Tuesday 05-26, 11:59 PM EST.** Submit individually on Canvas as a link to your repo.

By Milestone 2 you should have a **public GitHub repository** for your project containing:

- An informative README that summarizes the project and points to each notebook.
- A `code/` directory with at least 2–3 working notebooks (data pull / clean / analyze).
- An `output/` directory with at least one figure or table you have generated.
- A link to where the data lives (in the repo, or in a cloud folder if too large).

Milestone 2 is just about getting the repo set up — you do not need to be close to finished. Submit the link to your public repo on Canvas.

---

## Final Deliverables

**Final presentations: Tuesday 06-02, in class (last day of class).**
**Paper + repo + website due: Sunday 06-07, 11:59 PM EST.**

Final deliverables are worth **45% of your grade** and consist of four pieces:

### 1. Paper (6 pages)

A short scientific writeup. Graded with the [project rubric](https://github.com/herbertfreeze/QSS20-S26/blob/main/finalproj_guidelines/final_project_rubric.csv) — same elements as before (intro/related work, data, methods, results writing, results figures/tables, discussion, code/repo), plus a new element:

- **Agentic Analysis** — A short section (or appendix) that includes your AI transcripts and a critical reflection on your coding session: what you asked the assistant, what you accepted, what you rejected, and where the assistant went wrong.

You are expected to use AI coding assistants for analysis *and* for website generation — the agentic workflow is part of what we are evaluating.

**Format.** Write the paper in LaTeX using a PNAS-style single-column template:

- Open the [PNAS Overleaf gallery](https://www.overleaf.com/gallery/tagged/pnas), select the *single-column mathematics article* template (second from left), and click **Open as Template** to copy it into your own Overleaf account.
- For reference, see the [PNAS author guidelines](https://www.pnas.org/authors/submitting-your-manuscript).
- Remove the DRAFT watermark by editing the `.cls` file and setting `display watermark` to `false`. A small deduction will apply if the watermark remains.
- The page limit is **6 pages** (excluding references and the Agentic Analysis section).

### 2. GitHub repo (public)

- Numbered notebooks that run in order (`00_pull.ipynb`, `01_merge.ipynb`, `02_analyze.ipynb`, …).
- README links each notebook with its inputs, what it does, and its outputs.
- Directories: `code/`, `data/` (or a cloud-storage link), `output/`.
- No spaces in filenames; no hardcoded paths.
- Define functions at the top of each notebook.
- Print diagnostics before/after merges.

### 3. Website (public demo)

A public-facing site that demos the entire project. It should tell the story end-to-end: **question → data → method → result → takeaway.** Embed your key figures so a visitor can grasp the project in 2–3 minutes.

- Must be **live and linkable** by the Sunday 06-07 deadline.
- **Pushes after the deadline receive a 0** for the website component.
- **Suggested stack: React + Vercel** — a tutorial walking through this setup will be released; you are free to use a different stack if you prefer (e.g., GitHub Pages with Jupyter Book or Quarto, Streamlit, static HTML).

### 4. Lightning Talk

In-class on **Tuesday 06-02**:

- **90–120 seconds, hard stop.**
- Plus one instructor question + 30 seconds to respond.
- Recommended: **≤ 3 slides**, or present live from your website.
- Goal: lead with your headline finding and defend it.

---

## Next week — optional consultations

I will release 10-minute consultation slots for the week of 05-26. These are **optional** but encouraged if you want to sanity-check your direction before the final stretch.

---

<!--
Please check the Course Schedule for the due date for each of these final project components:


## Milestone one

Before starting milestone one:
- Read the report for one Spring 2021 project and get a sense for its strengths and weaknesses. What can you learn from their report? What can you improve on?
- Copy to your own Overleaf account the milestone 1 template and **only edit your local copy** (please don't change the template!)
  - You need to first setup an Overleaf account with your Dartmouth email (free) and log in

Then fill in the template sections by exploring your data on possible questions, relevant data fields, and possible changes.

Please submit your milestone one memo on Canvas. These will be graded.


## Milestone two

Create a private GitHub repository for your project that contains:
- An informative README
- A `code/` directory for scripts
- An `output/` directory for graphs/figures
- A link to cloud storage where you keep the data (e.g., Dropbox, Google Drive)

Add the instructor + the TA(s) as collaborators:
- Our GitHub usernames: herbertfreeze; euniceyliu

Then assign us an issue to review some progress on code/analysis.
- You do NOT need to be close to finished for this. We just want to see that you've loaded the data and started to write some code


## Final submission components

1. A 15 minute final presentation (written in LaTeX)
	- This presentation is meant as an update on work in progress, not a polished, completed product. It will be graded **pass/fail**.
	- You will still have time to work on your paper after the final presentation: The paper is due about a week after the presentations.

2. A PNAS-style scientific report (written in LaTeX)
	- See here for more details on PNAS guidelines: https://www.pnas.org/authors/submitting-your-manuscript
	- The specific, single-column PNAS paper template (figures display better in with one column) for you to use can be found on Overleaf here: https://www.overleaf.com/gallery/tagged/pnas (you can edit this directly after opening it)
    - After you click on the link, select the single-column mathematics article template (second from left, titled *PNAS LaTeX Template for preparing single-column mathematics articles on Overleaf*) and click "Open as Template", which will copy over to your own Overleaf account
  - To remove the DRAFT watermark, go to the .cls style file and set display watermark to false (there'll be a small deduction if the watermark remains)
  - **Feel free to exceed the 10 pages if it leads to more legible figures.**

3. A private GitHub repository containing:
  - The raw source data you used for the project, including both instructor-provided and external data sources
	- A set of scripts (`.py` and `.ipynb` files) that transform the data and reproduce your entire analysis, from start to finish
	- An informative README for the repository with a project overview, a clear description of your workflow, and a detailed description for each file:
    - Inputs: e.g., raw data; a file containing credentials needed to access an API
    - What the file does: describe major transformations.
    - Outputs (if any): e.g., a cleaned dataset; a figure or graph

The final GitHub repo and 10-page report will be evaluated using the project rubric.
-->
