# AI-Agent Pilot Checklist: 12 Questions to Answer Before You Start

An AI-agent pilot is easier to evaluate when the team agrees on its boundaries before the first test. A successful demonstration can show that a workflow is possible; it does not establish that the workflow is ready for routine use.

This checklist helps a small team turn an idea into a bounded pilot with explicit owners, acceptance criteria, review steps, and a recorded decision.

### 1. What business task are we testing?

Name one task and its intended user. For example, drafting a first-pass response for a support agent is clearer than automating customer service. Keep the task narrow enough that the team can observe inputs, outputs, exceptions, and review effort.

### 2. Who owns the pilot and its decision?

Assign an accountable owner, the people running the tests, and the reviewers who can accept or reject the result. Also name who may authorize a scope change. A pilot should not expand simply because the initial output looks promising.

### 3. Which inputs may the agent use?

List approved systems, files, and data categories. Identify information that must be excluded, anonymized, or handled through a separate process. Record access restrictions in the pilot plan rather than relying on memory.

### 4. What output should the agent produce?

Describe the expected format, destination, and quality requirements. State whether the output is a draft, a recommendation, a record update, or another bounded artifact. Make it clear when a person must approve the output before it reaches its destination.

### 5. What is explicitly outside scope?

Write down prohibited actions, unsupported request types, restricted destinations, and tasks that require a different approval path. These boundaries help reviewers distinguish an exception from an ordinary test result.

### 6. When must the agent stop or hand off?

Define triggers for human handoff, such as missing information, conflicting instructions, sensitive data, low confidence, repeated failure, or a request outside the approved task. Include pause and rollback steps for the workflow and its integrations.

### 7. Which tests will demonstrate acceptable behavior?

Use ordinary cases, boundary cases, missing-input cases, and deliberately unsupported requests. Give each test an expected result and a reviewer. Keep a record of the input or test identifier, observed output, decision, and relevant notes.

### 8. What are the acceptance criteria?

Set measurable criteria before reviewing the results. Depending on the task, these may cover accuracy, completeness, format compliance, appropriate handoffs, review time, exception rates, or unresolved high-priority issues. Avoid treating a single aggregate score as proof that every requirement was met.

### 9. Where is human review required?

Map review to risk and workflow stage. A reviewer may need to check every external message, every transaction, only flagged exceptions, or a defined sample. Record who reviews, what they inspect, and what they may approve.

### 10. What evidence will we retain?

Keep the approved plan, test results, reviewer decisions, exceptions, changes, and unresolved issues together. Apply the organization’s retention and access requirements. Do not place sensitive content in a tracking sheet merely to make the evidence easier to collect.

### 11. How will we evaluate operational effort?

Track oversight time, correction effort, exception handling, software usage, and setup work alongside output quality. A workflow that produces acceptable drafts but creates excessive review effort may need a different scope.

### 12. What decision will the pilot support?

Define the available decisions in advance: stop, revise and retest, continue a bounded pilot, or consider a separately approved expansion. Record the decision, rationale, owner, conditions, and next review date. A readiness score can organize discussion, but it should not make the decision automatically.

### Turn the answers into a pilot record

A compact pilot record can combine the charter, task boundaries, acceptance criteria, review matrix, exception log, evidence checklist, decision record, and a 30-day plan. The record should remain editable as the team learns, with changes visible to the people responsible for approval.

I created the **AI-Agent Pilot Planning Kit** as an editable starting point for this work. It includes an 8-page DOCX planning guide and an XLSX scorecard with eight weighted criteria, a 100-row test log, summary metrics, and a readiness chart. The score supports structured review; it is not automated approval or proof of safety, compliance, savings, or business outcomes.

Download the free two-page scope-and-test preview: [Open the pilot preview](../AI-Agent-Pilot-Kit-Free-Preview.pdf)

Compare both planning kits: [Compare the planning kits](../README.md#planned-digital-downloads)
