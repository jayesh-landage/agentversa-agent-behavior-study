# Version 2 Proposal — NyayaSetu

## Status

This document proposes possible future design improvements. It does not replace Version 1 and does not claim that any change has improved NyayaSetu.

The proposals remain provisional until they are connected to identifiable individual episode records.

## Proposal 1 — Explicit Evidence Status

**Proposed change:** Where permitted by the agent configuration, encourage the agent to distinguish recorded facts, unverified statements, inferences, unresolved questions, and recommendations.

**Rationale:** Scenarios 1 and 2 involve uncertainty about the outage, account use, timestamps, and evidence provenance.

**Expected effect:** Responses may become easier to verify and less likely to blur facts with interpretations.

**Potential unintended consequence:** Responses may become unnecessarily lengthy or overly cautious.

**Evidence needed:** NyayaSetu's individual responses in Scenarios 1 and 2.

**Future test:** Examine whether the agent separates account activity from identity, chronology from causation, and a record's contents from what the record proves.

## Proposal 2 — Structured Comparison of Evidence Tasks

**Proposed change:** When the scenario permits only one evidence task, encourage the agent to state the selected option, its expected value, its limitations, and the opportunity cost.

**Rationale:** Scenario 2 limits the agents to one additional evidence task during the available work period.

**Expected effect:** The recommendation may become more transparent and easier to compare with alternatives.

**Potential unintended consequence:** The agent may overstate its ability to predict which task will be decisive.

**Evidence needed:** NyayaSetu's actual Scenario 2 response.

**Future test:** Examine whether the agent compares the available tasks accurately and explains what the selected task cannot establish.

## Proposal 3 — Clear Action-Status Language

**Proposed change:** Encourage the agent to distinguish a proposed, authorized, initiated, completed, or verified action, using a status only when supported by the record.

**Rationale:** The shared simulation rules prohibit agents from claiming that proposed actions have been implemented.

**Expected effect:** Reduce ambiguity about whether a recommendation has actually been carried out.

**Potential unintended consequence:** Repetitive status labels may reduce conciseness.

**Evidence needed:** Individual episode records showing how NyayaSetu describes its actions.

**Future test:** Check whether the agent consistently distinguishes recommendations from recorded outcomes.

## Evaluation Plan

If these changes are implemented, run appropriate future scenarios and compare their recorded results with the Version 1 baseline under documented conditions.

Record differences, limitations, and possible alternative explanations. Do not claim improvement merely because a proposed instruction sounds clearer.

## Current Conclusion

The proposals are hypotheses for future testing. The individual episode records for Scenarios 1 and 2 and verification of the original Version 1 design are needed before making stronger claims about which changes are justified.