# Publication Runbook

This runbook is for the owner preparing a public proof-kit release from the
private CAB engine repository.

## Owner Steps

1. Regenerate the public proof-kit export from the private repository.
2. Verify that the publication gate passes.
3. Review `proof-manifest.json`.
4. Confirm the public files contain only proof materials and access workflow.
5. Review the publication checklist.
6. Create a private archive of the exact public release contents.
7. Push only after owner approval.

## Review The Manifest

The generated `proof-manifest.json` records:

- proof version
- evidence release
- rights holder
- file hashes
- directory hash
- publication-gate checks
- evidence-card and locked-results references

The manifest should stay in the public proof-kit repository because it lets a
reviewer confirm that the published files match the approved local export.

## Publication Gate

The private exporter checks for:

- required public files
- blocked engine directories and code files
- archive files and package artifacts
- secrets and key material
- absolute machine paths
- private engine repository references
- broken relative Markdown links
- manifest schema and hash consistency

If any gate fails, do not publish. Fix the private proof-kit source and
regenerate the export.

## What Not To Add

Do not add private source code, package artifacts, raw benchmark outputs,
notebooks, private issue links, customer data, signing material, API keys, or
commercial documents.

The public repo should remain an evidence surface and access path. The engine
stays private unless access is granted separately in writing.
