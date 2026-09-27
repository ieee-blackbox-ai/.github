<div align="center">

# BLACKBOX AI

### Reverse Engineer the Intelligence

**A machine learning investigation series**
IEEE Student Branch · Geethanjali College of Engineering and Technology

[Event site](https://ieee-blackbox-ai.github.io) · Cheeryala, Keesara, Telangana

</div>

---

## The premise

Most machine learning competitions hand you a dataset and ask for accuracy.

BLACKBOX AI runs the other way round. Teams are given access to a **hidden ML system** and
a limited number of queries to spend on it. The training data, the preprocessing, the
engineered features, the algorithm and the decision thresholds are all private. The task is
to work out what is inside — by experiment, under a finite information budget.

```
Query  ->  Observe  ->  Hypothesise  ->  Experiment  ->  Infer  ->  Reconstruct
```

The competition tests something most contests never reach: **experimental reasoning under
uncertainty.** Designing the query that separates two competing explanations is worth more
than running a thousand random ones.

AI assistants are allowed, deliberately. They can help you write code, plot results and
reason about what you observed — but they cannot tell you what the black box will output.
That information exists on one server, on one campus, and nowhere else.

---

## The series

| Edition | Focus | When | Status |
|:--|:--|:--|:--|
| **BLACKBOX AI 1.0** | Classical ML — trees, ensembles, hidden pipelines | 6–7 October 2026 | **Registration open** |
| **BLACKBOX AI 2.0** | Deep learning | To be announced | Planned |
| **BLACKBOX AI 3.0** | To be announced | To be announced | Planned |

Each edition keeps the same core idea and raises the ceiling. The platform, the challenge
authoring system and the participant workflow in this organisation are built to carry
forward across all of them.

---

## Current edition — 1.0

<table>
<tr><td><b>Dates</b></td><td>6–7 October 2026, on campus</td></tr>
<tr><td><b>Entry</b></td><td>Free</td></tr>
<tr><td><b>Teams</b></td><td>2–3 students</td></tr>
<tr><td><b>Prize pool</b></td><td>₹25,000</td></tr>
<tr><td><b>Track</b></td><td>Classical machine learning</td></tr>
</table>

Six stages over two days, each going deeper than the last:

| | Stage | |
|:--|:--|:--|
| **0** | Baseline | No elimination — just a read on where everyone starts |
| **1** | Observe | Your first black box, and the first cut |
| **2** | Investigate | Past surface behaviour into the hidden pipeline |
| **3** | Break | Find where the system is confidently wrong |
| **4** | Reconstruct | Build a model that reproduces it |
| **F** | The Unknown | A fresh system, the same for every finalist — then defend your reasoning to the panel |

Full details and registration: **[ieee-blackbox-ai.github.io](https://ieee-blackbox-ai.github.io)**

---

## What lives in this organisation

| Repository | What it is |
|:--|:--|
| [`ieee-blackbox-ai.github.io`](https://github.com/ieee-blackbox-ai/ieee-blackbox-ai.github.io) | Public event site |
| `blackbox-platform` | Competition server and challenge source — private |
| `blackbox-ai-participant-template` | The repository every team forks: issue forms for hypotheses and experiments, PR-based submissions. Public from the start of the event |
| `.github` | This profile |

When the event starts, every team forks the participant template and submits through pull
requests and issues on it, which the judges mark. What counts is the commit each pull request
stood at when its round ended, and submission windows are short - so work opened in public
after a round closes cannot change that round's result.

---

## Organisers

Run by the **IEEE Student Branch** at Geethanjali College of Engineering and Technology,
under the guidance of **Dr. Neha Nandal**, Advisor, IEEE-CS, GCET.

<div align="center">
<sub>Hard competition · simple operations · fair evaluation · private black boxes · auditable results</sub>
</div>
