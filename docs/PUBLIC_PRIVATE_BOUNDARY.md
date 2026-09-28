# LUCA Public / Private Boundary

## Public

The public LUCA repository may contain:

- architectural descriptions
- public interface contracts
- sanitized examples
- bounded public evidence
- reproducible demonstrations explicitly approved for publication
- public research results
- documentation describing validated capabilities

## Private

The following remain outside the public repository:

- production engine source unless explicitly released
- environment files and credentials
- private or production configuration
- signing authority material
- runtime state registries
- internal knowledge and memory stores
- customer and target datasets
- raw acquisition corpora
- operational logs
- internal security research
- production deployment artifacts
- historical backups containing internal state

## Vulnerability research boundary

Public vulnerability research must be sanitized and suitable for responsible
disclosure.

The public repository must not contain unresolved exploitable findings against
real targets, credentials, sensitive target data, exploit material tied to a
live target, or operational details that would expose a private security
boundary.

Authorized research may be documented publicly only at a level appropriate
for safe technical disclosure.

## Publication rule

Publication is an explicit projection operation.

The production LUCA tree is never treated as the source of a blind repository
synchronization operation.
