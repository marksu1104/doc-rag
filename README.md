# QA_Rag
- The goal is to eat yakiniku without spending my own money.

## Data and publication policy

This repository contains legacy retrieval code, not a redistributable competition
dataset. Non-public documents, questions, answers, generated results, serialized
databases, and legacy notebooks have been excluded from the published branch and
its rewritten history. The retained historical commit dates describe the original
development stages; the privacy cleanup was performed on 2026-09-28.

`reference/`, `dataset/`, and `database/` are local-only paths. Legacy scripts still
refer to those paths; a fresh clone does not include their inputs and is not a
self-contained demo. Use only data you are authorized to use. Do not upload private
inputs or derived artifacts, and do not bypass `.gitignore` with `git add -f`.

Legacy notebooks are excluded in full: clearing their outputs alone would not
remove examples embedded in source cells or metadata. New public examples and
notebooks require a separate data/license review before publication.

Do not merge or push old branches or repository backups into this rewritten history.
Other clones and GitHub pull-request references or cached views may still retain
old data; rewriting the main branch does not erase those copies.

This cleanup does not fix legacy dependency vulnerabilities or certify the old
code as production-ready. Application and dependency modernization remain pending.
