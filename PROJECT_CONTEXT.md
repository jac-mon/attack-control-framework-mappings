## Data Source & References

The ATT&CK to NIST 800-53 mappings in this project are derived from the official dataset maintained by the [Center for Threat-Informed Defense (CTID)](https://ctid.mitre.org/).

| Resource | Description |
|----------|-------------|
| [CTID Mappings Explorer](https://center-for-threat-informed-defense.github.io/mappings-explorer/external/nist/) | Live, searchable interface for all ATT&CK → 800-53 mappings |
| [attack-control-framework-mappings (fork)](https://github.com/jac-mon/attack-control-framework-mappings) | Forked reference dataset this project builds on top of |
| [NIST SP 800-53 Rev 5](https://csrc.nist.gov/pubs/sp/800/53/r5/upd1/final) | Source control framework |
| [MITRE ATT&CK v14](https://attack.mitre.org/) | Source threat framework |
| [Sigma Rule Specification](https://github.com/SigmaHQ/sigma/wiki/Specification) | Detection rule format used as tool input |

> The `mappings/attck_to_80053.yaml` file in this repo is a curated, tool-optimized subset of the CTID dataset — structured for programmatic parsing and gap analysis automation rather than human reference.
