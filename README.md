# Autoware Release SOP

## Documentation moved

As of 2026-09-17, maintained documentation lives in
[the TensorRT Reliability Lab release-governance directory](https://github.com/77zmf/autonomous-driving-tensorrt-reliability-lab/tree/main/docs/release-governance).

The consolidation retains all 8 source commits and the original MIT license.
This repository is kept as a historical reference so existing URLs and tags
continue to resolve. Its older pages include incomplete drafts; use the new
location for updates and contributions. No code, issue, tag, or repository
history has been deleted, and no runtime or vehicle release is implied.

See the [import record](https://github.com/77zmf/autonomous-driving-tensorrt-reliability-lab/blob/main/docs/release-governance/PROVENANCE.md)
and the [main project entry point](https://github.com/77zmf/autonomous-driving-tensorrt-reliability-lab/blob/main/docs/start-here.md).

## Historical scope

This repository documents a **practical release and version management workflow**
for Autoware-based autonomous driving projects.

## Scope

- Release governance
- Test and validation workflow
- Test-to-tag traceability
- Dependency version locking
- Production-ready release process

> This repository contains **process documentation only**.  
> No proprietary or company-specific source code is included.

## Repository Structure

- `docs/sop/`  
  Core release and testing SOP documents

- `docs/diagrams/`  
  Visualized release workflows (Mermaid)

- `docs/templates/`  
  Templates for release test reports

## Documents

- [Autoware Release SOP](docs/sop/autoware-release-sop.md)
- [Release Flow Diagram](docs/diagrams/release-flow.md)
- [Test Record & Tag Binding Rules](docs/sop/test-and-tag-binding.md)
- [Release Test Report Template](docs/templates/release-test-report-template.md)

## Motivation

This SOP is derived from real-world autonomous driving projects,
where reproducibility, traceability, and release stability are critical.

It is designed for:
- Test Owners
- Release Owners
- System Integration Engineers
