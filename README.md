PP-SPEC-025: Funding tier disclosure oxymoron

## Funding Tier Oxymoron
**Status:** Draft — held pending release
**Author:** Craig Ellrod
**Date:** September 18, 2026
**License:** CC BY-ND 4.0
**Related:** PP-SPEC-023 (Structural Independence and the Fidelity-at-Capture Requirement), PP-SPEC-024 (The Self-Attestation Oxymoron)
 
## Summary
 
Structural independence, as defined in PP-SPEC-023 and PP-SPEC-024, rules out certain relationships entirely, outcome-contingent fees, ceded operational control, return-engagement incentives disguised as consulting. It does not, on its own, distinguish between the different funding relationships that remain valid once those are excluded. Not all valid funding relationships carry the same strength. This spec requires that difference be disclosed on the mark itself, not buried in methodology documentation.
 
## The Problem This Closes
 
A certification mark that states only a score, without stating who paid for the assessment and under what structure, invites the reader to assume a uniform level of independence across all marks bearing the same score. That assumption is false. A vendor-funded assessment and a buyer-funded assessment can produce the identical PES number under identical technical methodology and still carry different residual incentive risk, because the direction of the payer's interest differs. Presenting both without distinction misrepresents the strength of the claim, even when every individual safeguard in PP-SPEC-023 and PP-SPEC-024 is honestly applied.
 
## The Three Tiers
 
**Tier 1 — Vendor-Funded.** The assessed party funds the assessment directly, as a one-time fee or ongoing subscription. Valid only when all of the following hold without exception: the fee is flat and published, with no component contingent on outcome; the pass/fail threshold is mechanical and public, with no discretionary step a payment could influence; every assessment run, regardless of result, is written permanently to ProofRegister at the moment of generation, independent of whether the vendor's engagement continues. Absence of any one of these three disqualifies the assessment from issuing a mark at all, not merely from claiming Tier 1.
 
**Tier 2 — Buyer-Funded.** A party other than the assessed vendor, a customer, a procurement body, or a buyer-side coalition, funds the assessment because it wants an accurate reading rather than a favorable one. Structurally stronger than Tier 1 because the payer's financial interest runs in the same direction as the accuracy of the result rather than in tension with it. Still a financial relationship and still disclosed as such; Tier 2 is a materially different claim from no financial relationship at all, not an equivalent one.
 
**Tier 3 — PESA-Governed.** The assessment is funded through the pooled PESA structure rather than a traceable transaction between the assessor and either the assessed vendor or a specific buyer. No individual payer's satisfaction can be tied to a specific result, because no individual payer funded that specific result. This is the tier that removes the incentive-alignment risk present in Tiers 1 and 2, rather than only mitigating it through safeguards.
 
## Disclosure Requirement
 
Every mark issued under Proof Protocol displays its funding tier as a permanent, equally prominent field alongside the PES score, on both the human-readable certificate and the ProofRegister metadata record. A score without a tier is an incomplete claim. "PES 94%, Tier 1, Vendor-Funded" and "PES 94%, Tier 3, PESA-Governed" are different statements about the same number, and the reader is entitled to know which one they are looking at before drawing a conclusion from the score alone.
 
## Relation to PP-SPEC-024
 
PP-SPEC-024 establishes that self-attestation cannot be fixed by rigor applied inside the same structure. This spec extends that principle to funding: rigor applied inside a Tier 1 relationship, however well safeguarded, does not become a Tier 3 relationship. The safeguards in PP-SPEC-023 make Tier 1 valid. They do not make it equivalent to Tier 3. Conflating validity with equivalence is a smaller version of the same category error PP-SPEC-024 identifies in self-attestation generally.
 
This spec's tier structure is also the direct descendant of PP-SPEC-024's Funding Oxymoron: a certification framework whose top-tier funders hold governance seats over the body stewarding it reproduces, at the institutional level, the same disclosure gap Tier 1 creates at the individual-mark level. Requiring a tier to be disclosed on every mark is this specification's answer at the mark level. Requiring a framework's own funding-to-governance structure to be disclosable in the same terms is the open question PP-SPEC-024 raises and does not yet resolve. A future revision of this specification may extend the same three-tier taxonomy to framework-level governance disclosure, not only mark-level assessment disclosure.
 
## Provenance
 
This document is timestamped and anchored via Zenodo, DOI [10.5281/zenodo.22832992](https://doi.org/10.5281/zenodo.22832992), as of the publication date above.
 
