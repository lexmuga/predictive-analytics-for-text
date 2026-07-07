<div class="center">

**GenAI Policy for MATH 103.1**

*Predictive Analytics for Text*

Version 1.0

</div>

# Policy Statement

Generative AI tools such as ChatGPT, GitHub Copilot, Gemini, Claude, and
similar systems may be used in MATH 103.1: Predictive Analytics for Text
as learning, coding, debugging, documentation, research-support, and
critique assistants.

The use of GenAI is not prohibited. However, its use must be visible,
bounded, auditable, and pedagogically meaningful.

This policy is guided by the principle that GenAI should support human
learning, not replace it. The key question is not merely how students
can use AI, but when, where, and how AI can meaningfully contribute to
human learning.

In this course, GenAI use is pedagogically meaningful when it helps
students better understand, implement, evaluate, interpret, and critique
text prediction experiments without replacing the student’s
responsibility as analyst, experimenter, and ethical decision-maker.

# Guiding Principle

**GenAI may assist the experiment, but it may not replace the
experimenter.**

MATH 103.1 treats text prediction as an experimental process. Students
must learn how to frame a problem, prepare text data, choose
representations, train models, evaluate results, interpret errors, and
defend conclusions. GenAI may help students during this process, but the
student remains responsible for the final work.

# Acceptable Uses of GenAI

Students may use GenAI tools for the following purposes, provided that
the use is disclosed when it materially affects submitted work and that
the student verifies the output before relying on it.

- **Concept clarification.** Students may ask GenAI to explain concepts
  such as tokenization, TF-IDF, embeddings, logistic regression, support
  vector machines, neural networks, macro-F1, cross-validation,
  overfitting, data leakage, model interpretation, or error analysis.

- **Coding support.** Students may ask GenAI to suggest Python code,
  explain syntax, debug errors, improve readability, or help organize
  Jupyter notebook cells.

- **Workflow critique.** Students may ask GenAI to critique a modeling
  plan, identify possible data leakage, suggest evaluation metrics, or
  compare alternative preprocessing choices.

- **Documentation support.** Students may use GenAI to improve comments,
  docstrings, markdown explanations, and report organization, provided
  that the final explanation reflects the student’s own understanding.

- **Reflection support.** Students may use GenAI to help formulate
  reflection questions or identify possible limitations of their work,
  but the actual reflection must be based on the student’s own
  experience and judgment.

- **Source and documentation navigation.** Students may ask GenAI to
  help locate relevant concepts in course notes, textbooks, or official
  documentation, but must independently verify technical claims,
  citations, quotations, or numerical information.

# Risk Levels for GenAI Use

To help students distinguish responsible assistance from inappropriate
substitution, GenAI use in this course is classified into three zones.

| **Zone** | **Status** | **Examples** |
|:---|:---|:---|
| **Zone** | **Status** | **Examples** |
| Green zone | Allowed; disclose when used in submitted work if it affected the submission. | Concept clarification, syntax explanation, grammar polishing, debugging guidance, formatting suggestions. |
| Yellow zone | Allowed only with verification, revision, and documentation. | AI-suggested code blocks, modeling workflows, feature engineering choices, metric selection, interpretation of results, literature or source summaries. |
| Red zone | Not allowed. | Fabricated results, fake citations, hidden AI-written reports, AI completion of an entire lab/project/exam answer, undisclosed AI-generated work that the student cannot explain. |

# Unacceptable Uses of GenAI

The following uses are not allowed:

- Submitting AI-generated code, explanations, or reports without
  understanding, testing, and revising them.

- Asking GenAI to complete an entire laboratory activity, project
  report, critique submission, or examination answer on the student’s
  behalf.

- Copying GenAI-generated interpretations of model results without
  checking whether they are supported by the actual output.

- Using GenAI to fabricate results, citations, experiment logs, GitHub
  history, MLflow runs, reflections, or data descriptions.

- Using GenAI to hide lack of participation in group work.

- Submitting work where the student cannot explain the code, modeling
  choices, evaluation results, or conclusions.

- Uploading confidential, private, sensitive, copyrighted, or restricted
  data to GenAI tools unless the data are publicly available or the
  instructor has explicitly permitted such use.

# Examination Rule

During examinations, GenAI use is prohibited unless the instructor
explicitly states otherwise in writing for a specific examination
component. Any permitted use will be announced together with the
examination instructions and will be governed by the same principles of
visibility, verification, and human responsibility.

# Required Disclosure

All GenAI use that materially affects a submitted notebook, critique,
report, code file, analysis, interpretation, reflection, or project
artifact must be disclosed through a GenAI Use Log.

A student who did not use GenAI should state: “No GenAI tool was used
for this submission.”

Material GenAI use means AI assistance that influenced the submitted
code, explanation, analysis, model choice, interpretation, report
structure, reflection, or final decision. Minor uses may be summarized
in one log entry when several prompts served the same purpose.

| **Required Information** | **Student Response** |
|:---|:---|
| **Required Information** | **Student Response** |
| GenAI tool used | ChatGPT, GitHub Copilot, Gemini, Claude, or other tool. |
| Purpose of use | Explanation, debugging, code suggestion, critique, documentation, source navigation, reflection, or other purpose. |
| Prompt or summary of prompt | What the student asked. For repeated minor uses, a concise summary is acceptable. |
| Useful output | What was helpful. |
| Rejected, revised, or corrected output | What was incomplete, wrong, misleading, unsuitable, or changed by the student. |
| Verification step | How the student checked correctness. |
| Human decision | What the student finally decided as analyst and experimenter. |

# Verification Requirement

Students must verify any AI-assisted output before using it.
Verification may include:

- checking the lecture notes or textbook;

- running the code and inspecting outputs;

- testing code on a small example;

- checking Python, pandas, PyTorch, or scikit-learn documentation;

- comparing model results across train, validation, and test sets;

- checking whether preprocessing caused data leakage;

- checking whether metrics match the prediction task and class
  distribution;

- explaining the result in the student’s own words;

- asking whether the result makes sense mathematically, statistically,
  and ethically.

A working code cell is not enough. Students must be able to explain why
the code is appropriate and how the result should be interpreted.

# Data Privacy and Source Integrity

Students must not upload confidential, private, sensitive, copyrighted,
or restricted data to GenAI tools unless the data are publicly available
or the instructor has explicitly permitted such use. When in doubt,
students should use small synthetic examples, anonymized excerpts, or
instructor-approved datasets.

GenAI-generated citations, quotations, dataset descriptions, legal
claims, technical claims, or numerical results must be verified against
reliable sources such as course notes, textbooks, official
documentation, peer-reviewed sources, or instructor-provided materials.
Students may not cite a source merely because a GenAI tool suggested it.

# Human Judgment Requirement

Every major laboratory or project submission must show evidence of human
judgment. Students must explain:

1.  the prediction problem being solved;

2.  the target variable and input text;

3.  the preprocessing and vectorization choices;

4.  the model or models used;

5.  the evaluation metric and why it is appropriate;

6.  the main errors or limitations of the model;

7.  how GenAI helped, misled, or was corrected;

8.  what final decisions were made by the student.

This requirement ensures that GenAI use remains pedagogically
meaningful.

# Application to Laboratory Notebooks

Each Jupyter notebook must contain a required section titled **GenAI Use
Disclosure**.

Required notebook template:

    ## GenAI Use Disclosure

    1. Did you use any GenAI tool for this notebook?
       Answer:

    2. What tool did you use?
       Answer:

    3. What did you use it for?
       Answer:

    4. Provide the prompt or a short summary of the prompt.
       Answer:

    5. What part of the AI response did you use?
       Answer:

    6. What part of the AI response did you reject, revise, or correct?
       Answer:

    7. How did you verify correctness?
       Answer:

    8. What final decision did you make as the student-researcher?
       Answer:

# Application to Weekly Critique Submissions

For weekly critique submissions, GenAI may be used to clarify readings,
generate questions, or improve writing. However, the critique must
reflect the student’s own analysis.

Students may not submit a generic AI-generated summary of a reading,
notebook, or model result. A valid critique should show:

- the student’s own understanding;

- a specific insight, question, or objection;

- connection to the week’s lecture or lab;

- evidence of independent judgment;

- disclosure of GenAI use, if any.

# Application to the Capstone Project

For the capstone project, GenAI may be used as a coding assistant,
debugging assistant, research-support assistant, documentation
assistant, or critique partner. However, the final project must include:

1.  a reproducible notebook or code repository;

2.  clear data documentation;

3.  train-validation-test split or equivalent validation design;

4.  model evaluation;

5.  error analysis;

6.  interpretation of results;

7.  GenAI Use Log;

8.  reflection on Human-AI collaboration.

Students must be prepared to explain their project orally or in writing.
The instructor may conduct brief oral or written checks asking students
to explain selected code cells, modeling choices, evaluation results, or
GenAI-assisted portions of their submission.

# Group Work Accountability

In group submissions, each member remains responsible for understanding
the parts of the work they contributed to and for accurately disclosing
any GenAI assistance used in those parts. The group GenAI Use Log should
identify whether AI-assisted work affected code, analysis, writing,
visualization, debugging, project planning, or interpretation.

A group may not use GenAI to mask non-participation. Each member may be
asked to explain the parts of the submitted work for which they claim
responsibility.

# Academic Integrity and Consequences

Failure to disclose GenAI use that materially affected the submitted
code, explanation, analysis, report, interpretation, reflection, or
project artifact may be treated as an academic integrity concern.

Minor or first-time disclosure problems may require revision,
resubmission, or oral explanation. Serious cases, including fabricated
results, fabricated citations, hidden AI-generated submissions, or
inability to explain submitted work, may be handled under the
university’s academic-integrity procedures.

More importantly, submitting AI-generated work without understanding
violates the purpose of the course. The course is designed to develop
the student’s ability to conduct, interpret, and critique machine
learning experiments involving text data.

The issue is not whether GenAI was used. The issue is whether the
student used GenAI responsibly and whether the final submission
demonstrates genuine learning.

# Instructor’s Evaluation Standard

Student work will be evaluated not only on whether the code runs or
whether the answer appears correct, but also on whether the submission
shows the following:

| **Criterion** | **Description** |
|:---|:---|
| **Criterion** | **Description** |
| Technical correctness | The code, model, and results are correct and appropriate. |
| Reproducibility | The workflow can be rerun and checked. |
| Conceptual understanding | The student can explain what was done and why. |
| Evaluation quality | Metrics and validation design are appropriate. |
| Error analysis | The student examines mistakes and limitations. |
| Source integrity | Claims, citations, and external information are verified. |
| GenAI transparency | AI use is clearly disclosed. |
| Human judgment | The final decisions are made and justified by the student. |

# Closing Statement

GenAI tools such as ChatGPT, GitHub Copilot, Gemini, Claude, and similar
systems may be used in MATH 103.1 as learning, coding, debugging,
documentation, research-support, and critique assistants. However, GenAI
use must be visible, bounded, auditable, and pedagogically meaningful.

Students must disclose material GenAI use through a GenAI Use Log and
must verify any AI-assisted output before including it in a submission.
Students remain fully responsible for the correctness, reproducibility,
interpretation, and ethical defensibility of their work. GenAI may
assist the experiment, but it may not replace the experimenter.

In this course, responsible GenAI use is part of learning modern
predictive analytics. Students are expected to use AI tools critically,
transparently, and ethically while developing their own competence as
analysts, experimenters, and interpreters of text prediction models.
