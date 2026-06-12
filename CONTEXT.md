# Paper Reading Skills

This context defines the vocabulary for paper-reading skills that turn a reading motivation into a concrete research workflow and durable artifacts.

## Language

**Field Map Workflow**:
A complete domain-mapping workflow for entering a research direction, starting from scope boundaries and ending with paper clusters, gap analysis, and a human-readable report.
_Avoid_: Field map as a single markdown file, quick paper list

**Field Boundary**:
The explicit inclusion and exclusion criteria that define which research questions, papers, methods, systems, and benchmarks belong inside the user's current research scope.
_Avoid_: Topic, area, background

**Field Boundary Gate**:
The required clarification step before collecting papers; it is passed only when the research target, in-scope areas, out-of-scope areas, time or venue limits, user goal, and stop condition are explicit.
_Avoid_: Optional preface, rough topic note

**Proposed Field Boundary**:
An AI-drafted Field Boundary offered to the user for critique and revision before the Field Boundary Gate is passed.
_Avoid_: User questionnaire, final scope

**Field Map Workspace**:
A durable artifact set for exactly one research direction explored through a Field Map Workflow.
_Avoid_: Output folder, notes dump

**Seed Paper**:
A representative starting paper selected to anchor the field map, usually from surveys, classic works, high-citation recent papers, benchmark papers, or related systems.
_Avoid_: Random paper, first batch paper

**Seed Set**:
An initial set of roughly 8-12 Seed Papers chosen for coverage across overview, foundational, recent high-impact, benchmark, dataset, evaluation, system, or application perspectives.
_Avoid_: Top ten papers, arbitrary reading list

**Paper Position Record**:
A structured note for one paper that captures the paper's position in the field, including its problem, assumptions, method route, evaluation, contribution type, related works, contrasting works, and gaps left.
_Avoid_: Paper summary, reading notes

**Position-Oriented Reading**:
A paper-reading mode that reads only deeply enough to place a paper in the Field Map Workflow and complete its Paper Position Record.
_Avoid_: Full close reading, exhaustive summary

**Candidate Pool**:
A broad, auditable collection of papers discovered from citations, references, keyword expansion, benchmarks, leaderboards, and related-work trails before selecting which papers to read closely.
_Avoid_: Final paper set, reading list

**Selected Expansion Set**:
The roughly 25-35 non-seed papers chosen from the Candidate Pool for Paper Position Records.
_Avoid_: All discovered papers, search results

**User-Provided Paper**:
A paper directly uploaded or linked by the user, which takes priority over network-discovered papers during Field Map Workflow discovery.
_Avoid_: Local corpus, existing library

**Network Discovery**:
The default paper discovery mode when the user has not provided papers, using web search, citation trails, survey bibliographies, benchmark pages, and other online sources.
_Avoid_: Repository search, offline literature lookup

**Research Cluster**:
A group of papers that share a core problem, method route, assumptions, or evaluation setting within the field map.
_Avoid_: Category, bucket, theme

**Primary Research Cluster**:
The one Research Cluster that best explains a paper's main field position.
_Avoid_: Main category

**Secondary Research Cluster**:
An additional Research Cluster that a paper meaningfully informs without being its main field position.
_Avoid_: Tag, loose theme

**Research Opportunity**:
A possible future research direction derived from gaps across the mapped papers, such as conceptual, method, evaluation, system, or theoretical gaps.
_Avoid_: Idea, future work note

**Research Opportunity Candidate**:
A Research Opportunity backed by paper evidence and phrased so it can become a possible research question, with risks and objections recorded.
_Avoid_: Speculation, loose future work

**Field Map Report**:
A zero-build static HTML report inside a Field Map Workspace that organizes the boundary, seed set, search strategy, clusters, paper table, opportunities, and next actions for human reading.
_Avoid_: Web app, dashboard

## Example Dialogue

Dev: "Should `field map` just output `research_clusters.md`?"

Domain expert: "No. Use **Field Map Workflow** for the full process. It creates one **Field Map Workspace**, starts with the **Field Boundary**, uses **Seed Papers** to expand the literature set, groups papers into **Research Clusters**, and ends by naming **Research Opportunities**."
