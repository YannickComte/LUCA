# LUCA Architecture - Public View

LUCA maintains an evidence-driven intelligence state and projects bounded views
of that state into different interfaces.

## Logical flow

Evidence
  -> Acquisition / Observation
  -> Provenance + Identity Binding
  -> Authoritative Knowledge State
       -> Browser Intelligence
       -> Audit / KYB
       -> Defense
       -> Vulnerability Intelligence
       -> Public Web/API

## Authority

A projection does not become a second intelligence authority.

Public interfaces consume bounded representations of authoritative LUCA state.

## Temporal semantics

Historical evidence remains historical evidence.

A historical identity or observation must not silently become a claim about
current state.

## Exact-target semantics

Information associated with one target must not be used as evidence for a
different target without an explicit validated relationship.

## Unknown state

LUCA preserves an explicit unknown/not-assessed state rather than converting
missing evidence into a fabricated conclusion.

## Vulnerability evidence boundary

Vulnerability intelligence remains subject to the same evidence model as every
other LUCA projection.

A vulnerability identifier, technology match, or external advisory may provide
evidence, but does not independently establish that a specific target is
currently vulnerable, exploitable, or compromised.

Those states require their own admissible evidence and provenance.
