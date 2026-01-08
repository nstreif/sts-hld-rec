High-Level Design (HLD): Start to Scale Workbook
================================================

Key Design Truths
-----------------

These truths guide every design decision:

1.  **STS is dense** --- The workbook must focus on highest-impact concepts per chapter
2.  **Everything is connected** --- Focus on one main idea at a time to avoid overwhelming learners
3.  **Learners want fast action** --- Each part delivers standalone value

Core Design Principles
----------------------

### Self-contained with bridges

Each chapter and phase is self-contained with bridges to other relevant phases, not dependencies that block progress.

### Concrete deliverables

One concrete, shareable deliverable per chapter and phase.

### Modular design

Supports sequential or standalone use --- learners can jump in where they need to.

### Targeted work over comprehensive work

Users complete 15-30 minutes of focused work, not 60 minutes of exhaustive processing. Use triage and conditional sections to guide users to what matters most.

Design Rules for Complexity
---------------------------

When a chapter covers multiple concepts or requires detailed work:

### DO: Use Conditional Sections

-   Start with quick universal assessment
-   Let users self-select into deep dives
-   Each deep dive = 5-10 min max
-   Example: "Complete Deep Dive B only if Accountability scored 1-3"

### DON'T: Make Everyone Complete Everything

-   Avoid linear "fill this out, now this, now this" when content could be modular
-   Don't create 60-min exercises that could be 20-min targeted work
-   Don't force processing of irrelevant information

### The Triage Principle

If a chapter has 6+ concepts or decision points:

1.  Create a quick assessment that identifies 1-2 focus areas
2.  Build conditional deep dives for each area
3.  Let users engage with only 2-3 modules, not all 6+

### Time Budget Per Chapter

-   Universal sections: 5-10 minutes
-   Conditional deep dives: 5-10 minutes each
-   Total chapter time: 15-30 minutes (not 45-60)

Target User Profile (Workbook)
------------------------------

### Primary

Founder or operator scaling a company (likely solo or small team).

### Also serves

Leadership teams, scale-up facilitators, solo founders.

### NOT

Large teams (10+), passive readers, academic audiences.

Chapter Archetypes
------------------

Different chapters serve different functions. Use the appropriate archetype:

### 1\. Diagnostic/Assessment Chapters

**When to use**: Identifying what's broken or where to focus\
**Pattern**: Triage → Deep Dive\
**Examples**: Ch 1 (Barriers), Ch 2 (Right People/Right Things), Ch 10 (Cash)

**Structure**:

-   Universal quick assessment (everyone completes)
-   Clear filter/decision point (e.g., "your two lowest scores")
-   Conditional deep dives (complete only what's relevant)
-   Action plan based on paths taken
-   Phase transition bridge (2-3 options max)

**Time**: 5-10 min assessment + 1-2 deep dives (5-10 min each) = 15-30 min total

### 2\. Template/Planning Chapters

**When to use**: Creating a specific artifact or plan\
**Pattern**: Linear build\
**Examples**: Ch 3 (Core Values), Ch 6 (OPSP), Ch 8 (Quarterly Theme)

**Structure**:

-   Brief concept primer
-   Step-by-step template completion
-   One cohesive deliverable
-   Phase transition bridge (2-3 options max)

**Time**: 20-30 min to complete template

### 3\. Framework Application Chapters

**When to use**: Applying a methodology to current situation\
**Pattern**: Framework → Application → Output\
**Examples**: Ch 4 (De-Hassle), Ch 5 (Brand Promise), Ch 7 (Top 1 of 5)

**Structure**:

-   Framework explanation with examples
-   Application worksheet/exercise
-   Concrete next action or deliverable
-   Phase transition bridge (2-3 options max)

**Time**: 15-25 min to apply framework

Chapter-Level Design Pattern
----------------------------

### For Diagnostic/Assessment Chapters:

#### 1\. Opening

Clear trigger ("Start here if...")

#### 2\. Concept Summary

Plain explanation of 3-4 key concepts (no fluff, just what's needed to complete the work)

#### 3\. Universal Assessment

Quick rating/triage exercise that everyone completes\
**Must include explicit filter**: "Complete only sections relevant to your [lowest scores/biggest issue/etc]"

#### 4\. Conditional Deep Dives

Modular sections (A, B, C...) that users complete selectively\
Each deep dive:

-   Starts with clear IF condition ("Complete this if X scored 1-3")
-   Is fully self-contained
-   Takes 5-10 minutes max
-   Produces specific insight or decision

#### 5\. Action Plan

Synthesizes only what user completed in deep dives\
No re-processing of universal assessment\
Format: Clear owner + specific action + timeframe

#### 6\. Phase Transition Bridge

Simple decision tree (2-3 options) guiding to most relevant next phase\
See "Phase Transition Logic" section below for patterns

### For Template/Planning Chapters:

#### 1\. Opening

Clear trigger ("Start here if...")

#### 2\. Concept Summary

Plain explanation of 3-4 key concepts (no fluff, just what's needed to complete the work)

#### 3\. Template/Worksheet

Step-by-step completion with:

-   Clear instructions for each section
-   Examples where helpful
-   Adaptation notes for solo vs. team use

#### 4\. Phase Transition Bridge

Simple decision tree (2-3 options) guiding to most relevant next phase\
See "Phase Transition Logic" section below for patterns

### For Framework Application Chapters:

#### 1\. Opening

Clear trigger ("Start here if...")

#### 2\. Concept Summary

Plain explanation of 3-4 key concepts (no fluff, just real examples and what's needed to complete the work)

#### 3\. Application Exercise

Guided worksheet to apply framework to user's situation

#### 4\. Output/Next Action

What to do with the completed work

#### 5\. Phase Transition Bridge

Simple decision tree (2-3 options) guiding to most relevant next phase\
See "Phase Transition Logic" section below for patterns

Phase Transition Logic
----------------------

Each chapter ends with a clean bridge guiding users to the most relevant next phase. Avoid overwhelming users with 5-7 conditional paths. Instead, offer 2-3 clear options based on what the chapter revealed.

### Standard Bridge Structure:

**Format:**
```
## What's Next?

[Brief context sentence based on chapter work]

### Stay in [Current Phase] if:
- [Condition 1 that suggests staying]
- [Condition 2 that suggests staying]
- [Condition 3 that suggests staying]

→ Next: Chapter X ([Title])

---

### Jump to [Most Common Next Phase] if:
- [Condition 1 for jumping]
- [Condition 2 for jumping]
- [Condition 3 for jumping]

→ Skip ahead: Chapter X-Y ([Phase Name])

---

[Optional 3rd path if relevant]

---

### If you're still unsure which phase to tackle next:
[Default guidance, usually stay in current phase]

→ [Specific recommendation]
```

### Common Phase Transitions:

**From Barriers Phase:**
- Most commonly → People Phase (fix foundational issues first)
- Sometimes → Strategy or Execution (if people are solid)

**From People Phase:**
- Most commonly → Strategy Phase (once team is right, give them direction)
- Sometimes → Execution Phase (if strategy exists but execution is broken)

**From Strategy Phase:**
- Most commonly → Execution Phase (turn plans into action)
- Sometimes → People Phase (if strategy reveals people gaps)

**From Execution Phase:**
- Most commonly → Cash Phase (measure what matters)
- Sometimes → Strategy Phase (if execution reveals strategic gaps)

**From Cash Phase:**
- Typically cycles back to other phases based on what metrics reveal

### Bridge Design Rules:

1. **Limit to 2-3 options max** — more creates decision paralysis
2. **Phase-level guidance** — point to phases, not individual chapters (exception: natural next chapter in current phase)
3. **Clear conditions** — each option explains WHEN to choose it
4. **Include a default** — "if unsure, do this"
5. **No exhaustive lists** — avoid "if X see Ch 3, if Y see Ch 7, if Z see Ch 10..."

Conditional Design Language
---------------------------

Use explicit permission-giving language for modular sections:

### Clear Filters

✅ "Complete only the deep dive sections below that relate to these two circles"\
✅ "Identify your two lowest scores---these are your focus areas"\
✅ "Skip any section that doesn't apply to your situation"

❌ "Work through this diagnostic" (implies do everything)\
❌ "Now let's map accountability for each area" (no escape hatch)

### Conditional Instructions

Format: "Complete this [section] if [condition]"

✅ "Complete Deep Dive A if Employees scored 1-3"\
✅ "Fill out this section only if you have a team of 3+"\
✅ "Skip to Section 4 if both circles scored 4-5"

### Time Signals

Help users estimate effort based on their path:

✅ "This quick assessment takes 5 minutes. Based on your results, you'll complete 1-2 deep dives (5-10 min each)."\
✅ "If all six areas scored 4-5, you're done! Skip to Section 4."

❌ "This diagnostic will take 45-60 minutes" (when it could be 20)

Phase/Chapter Structure
-----------------------
NOTE: Activities and archetypes listed here are a first draft---they can be changed.

### Phase: Barriers

-   Ch 1: Your Scaling Barrier Diagnostic (Diagnostic)
-   **Culminating Activity**: Barrier-to-Solution Map (Your #1 barrier + which phase(s) address it)

### Phase: People

-   Ch 2: Right People/Right Things/Right Way Assessment (Diagnostic)
-   Ch 3: Your Authentic Core Values One-Pager (Template)
-   **Culminating Activity**: FACE & PACE? (TBD)

### Phase: Strategy

-   Ch 4: Your De-Hassle Action Plan (Framework Application)
-   Ch 5: Your Measurable Brand Promise (Framework Application)
-   Ch 6: Your One-Page Strategic Plan (OPSP) (Template)
-   **Culminating Activity**: Strategic Snapshot (Brand Promise + OPSP + De-hassle priorities integrated)

### Phase: Execution

-   Ch 7: Your Top 1 of 5 Focus (Framework Application)
-   Ch 8: Your Quarterly Theme Campaign (Template)
-   Ch 9: Your Meeting Rhythm Calendar (Template)
-   **Culminating Activity**: TBD

### Phase: Cash

-   Ch 10: Your Cash Acceleration Plan (Diagnostic)
-   **Culminating Activity**: Growth Scorecard (Critical Number + CCC + Key metrics dashboard)

Deliverables & Flow
-------------------

### Integrated Artifacts

Every phase produces a single integrated artifact.\
**Every chapter produces a working tool or decision**, which may be:

-   Single-page template (Template chapters)
-   Multi-section diagnostic with action plan (Diagnostic chapters)
-   Framework application with output (Framework chapters)

### Flexible Entry via Conditional Sections

Skipped prior chapters? Two approaches:

-   **Template chapters**: Built-in "minimum input" fallbacks
-   **Diagnostic chapters**: Universal assessment works standalone; deep dives adapt to any situation

### Modular Engagement

Users should complete 15-30 min of targeted work, not 60 min of comprehensive work

-   Diagnostic chapters: Users engage with 2-3 deep dive modules, not all 6-7
-   Template chapters: Users complete full template (already time-bounded)
-   Framework chapters: Users work through framework once with real examples

### Shareable Outputs

Designed for review, reuse, and easy sharing.\
Not designed to be comprehensive documentation.

Writing Style
-------------

### Language

-   Plain language, no jargon unless necessary
-   Brief explanations, detailed instructions
-   Assume the reader is smart but busy
-   Chunk content for scannability
-   Use first-person ("your") to make it personal

### Formatting

-   Avoid over-formatting (excessive bold, bullets, headers)
-   Use minimum formatting appropriate for clarity
-   Lists and bullets only when structure requires it (rankings, multi-step processes)
-   Prose for reports, documents, explanations
-   CommonMark standard markdown for any formatting used

### Tone

-   Direct and actionable
-   Respectful of user's time
-   No unnecessary cheerleading or hand-holding
-   Honest about hard truths (e.g., "If the answer isn't yes, you know what needs to change")

Activities & Exercises
----------------------

### Adaptation Requirements

Must work for solo founders AND small teams (2-5 people)\
Include adaptation notes:

-   "Working solo? Try..."
-   "With a team? Consider..."

### Time Estimates

-   Keep realistic (15-30 min per chapter)
-   Signal time per section for diagnostic chapters
-   Be honest about effort required

### Minimum Viable Versions

Provide fallbacks for users who skipped prior chapters:

-   "If you haven't completed Chapter X, use this simplified version"
-   "Don't have data from earlier exercise? Estimate based on..."

What to Avoid
-------------

### Dependencies & Complexity

-   Referencing future chapters without context
-   Creating exercises that require large teams
-   Mixing multiple concepts in one exercise
-   Vague outputs ("reflect on..." without concrete deliverable)

### Forcing Comprehensive Work

-   **Bad**: "Rate all 6 areas, map all 6 accountabilities, assess all people"
-   **Good**: "Rate 6 areas, identify your 2 lowest, deep dive only there"

### Re-Processing Information

-   **Bad**: Assessment → Deep dives → Action plan that asks you to synthesize everything again
-   **Good**: Assessment filters to relevant deep dives → Action plan emerges from deep dives completed

### Overwhelming Bridge Options

-   **Bad**: Listing 5-7 conditional chapter-to-chapter paths ("If X see Ch 3, if Y see Ch 7, if Z see Ch 10...")
-   **Good**: 2-3 phase-level options with clear decision criteria

### Over-Formatting

-   Overly conversational or repetitive text
-   Excessive use of bullet points when prose would work
-   Bold emphasis on every other sentence
-   Headers for every paragraph

Quality Standards
-----------------

### Clarity over comprehensiveness

Focus on highest-impact concepts only

### Action over explanation

More doing, less reading

### One main idea at a time

Everything is connected, but present concepts sequentially

### Practical over theoretical

Real deliverables, not just insights

### Efficient over exhaustive

Users complete what's relevant, not everything possible

Summary
-------

-   **Modular, action-focused learning** --- Chapters use appropriate archetype (Diagnostic, Template, or Framework)
-   **Conditional engagement** --- Diagnostic chapters use triage to guide users to targeted deep dives
-   **Just-in-time impact** --- Each phase and chapter stands on its own
-   **Time-bounded work** --- 15-30 minutes per chapter, not 45-60
-   **Phase-focused bridges** --- Simple 2-3 option decision trees guide users to next phase, avoiding connection overload
-   **Supports fast scaling** --- Built for founders and teams who need results now
