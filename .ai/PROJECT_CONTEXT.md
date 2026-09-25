---
doc_id: ai-project-context
version: 1.1.1
canonical_path: .ai/PROJECT_CONTEXT.md
updated: 2026-09-25
---

# linjingzhu/bulk-image-collector-public Context

Static Be My Image support and policy site, consisting of index.html, privacy.html, terms.html and style.css.

## repository_mode

```text
repository_mode: protected
```

## Facts the checks read

```text
base_branch: main
merge_deploys: yes
runtime_gate: none
test_command: none
lint_command: none
build_command: none
generated: none
external_scripts: none
public_ids: none
owner_ledger: .ai/reports/OWNER_ACTIONS.md
```

`merge_deploys: yes` is a conservative assumption because external deployment integrations were not verified. It is not evidence that a merge deploys this repository. `none` for a command means no configured command was identified, not that verification passed. External scripts, public identifiers and generated assets are limited to the inspected evidence; complete runtime inventories remain unverified. The owner-action ledger is .ai/reports/OWNER_ACTIONS.md; no owner-only actions are currently recorded.

## Authoritative product constraints

Keep support, privacy and terms pages consistent. Existing public copy states local processing/storage, no server-side account/data, and no bypass of logins, paywalls, DRM or access controls. These statements are product commitments to preserve and verify against the extension when changing behavior.

GitHub Actions is disabled by the owner's standing direction for this adoption; keep all workflow files absent and perform future validation locally. Do not add or re-enable Actions without a new explicit owner instruction.

## Current architecture

HTML pages and one stylesheet are the tracked site content; no package/build/test manifest or backend was found.

## Current development slice

The 2026-09-25 change adopts ai-dev-rule 3.0.0 from `94e808cc78d8ca194a8e20272a395551be3066db` and removes tracked Actions workflows. It changes policy/capability files and repository context only; it does not implement a product feature. Product roadmap status must be established from current repository documentation before subsequent product work.

## Permanently excluded scope

Preserve the exclusions stated in Authoritative product constraints and existing product specifications. No additional product exclusions were inferred during adoption.

## Evidence and verification limits

Repository facts above were derived from: All tracked root file names and index.html content.

No external script src was found in the three HTML documents. The site claims were recorded from existing copy; extension behavior and live hosting were not independently verified.

The structural policy check answers whether policy metadata, references and required context fields are consistent. It does not validate product facts or runtime behavior. Application tests, builds and runtime checks were not run for this policy-only change.
