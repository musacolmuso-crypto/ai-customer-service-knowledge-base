# Preliminary Findings — Round 1

## Test Scope

The first evaluation round consisted of five simulated customer-service enquiries covering:

- Short-stay vs long-stay classification
- Nationality and travel duration
- Long-stay identification
- Visa validity vs authorised duration of stay
- Family member of a French national

## Initial Accuracy

**Total accuracy score: 8/10 (80%)**

Three responses were classified as fully correct and two as partially correct.

> This is a preliminary result based on a small sample and should not be interpreted as the final performance of the system.

---

## Finding 1 — Strong Core Classification

The AI generally performed well when identifying the principal visa category.

It successfully distinguished:

- Short stays from long stays
- Visa validity from authorised duration of stay
- Temporary visits from longer-term residence
- Situations requiring additional customer information

This suggests that source-grounded AI could potentially support first-level enquiry classification.

---

## Finding 2 — Overgeneralisation

The AI occasionally transformed category-specific information into general rules.

For example, restrictions or procedures applicable to particular visa categories were sometimes presented as though they applied universally.

### Operational Risk

In a regulated customer-service environment, an answer can appear plausible and largely correct while still containing a misleading qualification.

Human validation therefore remains important.

---

## Finding 3 — Response Over-Expansion

The AI frequently provided more information than the customer requested.

For example, a simple enquiry about a three-week visit generated additional information concerning:

- Long-term residence
- Residence permits
- Exceptional procedures
- Specific nationality cases
- Marriage-registration requirements

Although much of the information was relevant to the broader subject, it was not necessary to resolve the customer's immediate enquiry.

### CX Impact

Excessive information can:

- Increase cognitive load
- Confuse customers
- Generate additional questions
- Increase opportunities for AI error
- Increase Average Handling Time rather than reduce it

---

## Finding 4 — Clarification Is a Core AI Capability

Some customer questions cannot be answered reliably without additional information.

The prototype successfully identified several situations where clarification was required, including:

- Country of legal residence
- Purpose of travel
- Family relationship
- Intended duration of stay

This suggests that AI performance should not be measured solely by its ability to provide immediate answers.

**Appropriate clarification should itself be considered a successful outcome.**

---

## Next Iteration

The next testing round will introduce more complex and ambiguous enquiries involving:

- EU family members
- Student visas
- Visa fees
- Jurisdiction
- Special territories

The evaluation will also examine whether tighter response instructions can reduce over-expansion without reducing accuracy.
