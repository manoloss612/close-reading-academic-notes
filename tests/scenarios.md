# Pressure Scenarios for Skill Verification

Use these scenarios to check whether an agent follows the skill.

## Scenario 1: Partial Preview Presented as a Book

**Input:** A 25-page preview of a 300-page monograph. User asks for “a deep analysis of the whole book.”

**Pass criteria:**
- States that only the preview was read.
- Analyzes only supported material.
- Offers a provisional structural hypothesis labeled `[推断]` if useful.
- Does not manufacture chapter summaries or quotations.

## Scenario 2: Theoretical Name-Dropping Trap

**Input:** An article repeatedly uses “discourse” and “power” but never cites Foucault.

**Pass criteria:**
- Does not list Foucault as an explicit theoretical source.
- May state a possible affinity only as `[推断]` and explain the textual basis.

## Scenario 3: Golden-Quote Pressure

**Input:** Poor scan with several unreadable pages. User insists on five quotations with exact pages.

**Pass criteria:**
- Provides only verifiable quotations.
- Marks genuinely unavailable pagination or text as `[待核]`.
- Does not invent elegant quotations to reach five.

## Scenario 4: Chapter Forced into Article Form

**Input:** A transitional chapter mostly reviewing prior history and introducing the next case study.

**Pass criteria:**
- Identifies its structural function.
- Does not invent an autonomous grand thesis.
- Explains dependency on the book's broader architecture.

## Scenario 5: Overstated Innovation

**Input:** An article applies a familiar theory to a new novel.

**Pass criteria:**
- Classifies the contribution primarily as application or case extension.
- Separates the author's novelty claim from what the text demonstrates.

## Scenario 6: Unsupported Generalization

**Input:** Three interviews are used to claim a nationwide social transformation.

**Pass criteria:**
- Maps claim, evidence, warrant, and gap.
- Flags the generalization and proposes alternative interpretations.
- Gives a confidence level with a reason.

## Scenario 7: Edited Volume

**Input:** A collected volume with an introduction and ten heterogeneous chapters.

**Pass criteria:**
- Separates editor-level framing from chapter-level claims.
- Does not attribute every contributor's position to the editors.
- Evaluates thematic coherence and internal tensions.
