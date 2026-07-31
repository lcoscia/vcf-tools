# VCF Tools Hub

A collection of free, browser-only tools for planning, sizing, and documenting VMware Cloud Foundation 9 deployments — no login, no backend, nothing to install.

**Live site:** [vcftools.lcoscia.fr](https://vcftools.lcoscia.fr/)

## Tools

### [VCF Network Planner](https://vcfplanner.lcoscia.fr/)
Design a compliant VMware Cloud Foundation 9 network topology end to end, then export it straight into your build documentation.
- Guided workflow from overview through Management Domain, Platform Services, Workload Domains, VLAN design, appliances, and VIPs
- Supports both VCF 9.0 and VCF 9.1 architecture rules
- Auto-generates VLAN tables, IP/FQDN allocations, and VIP pools from your topology
- Built-in validation flags issues as Blocker, Warning, or Info
- Models Consolidated, Single-Site, and Stretched Cluster (vMSC) topologies independently for Management and Workload Domains
- Exports to a five-sheet Excel workbook or JSON, with JSON re-import for iterative planning

### [VCF Planning & Preparation Workbook](https://vcfplanning.lcoscia.fr/)
An interactive, browser-only replacement for Broadcom's 27-sheet VCF 9.1 Planning & Preparation Excel workbook.
- 19 guided pages covering 600+ fields across all 27 original workbook sheets
- Live sizing calculator for Management Domain host requirements (CPU, RAM, disk per host)
- Supports VCF and VVF deployment types, plus New Fleet, Additional Instance, Workload Domain, and Additional Cluster modes
- Validates VLAN conflicts, IP conflicts, CIDR overlaps, and FQDN formatting as you go
- Imports an existing Broadcom .xlsx workbook or a VCF Installer JSON to pre-fill the form
- Exports to JSON, a Markdown As-Built report, a CSV IPAM table, or a VCF Installer SddcSpec JSON ready to POST

### [VCF Design Decision Library](https://vcfdd.lcoscia.fr/)
Browse, filter, edit, and export nearly a thousand VMware Cloud Foundation design decisions, with the blueprint reference data to back each one.
- Close to 1,000 design decisions spanning VCF 9.0 and 9.1 across 28 components
- Switch between 5 VCF Fleet blueprint topologies (single site, minimal footprint, multi-site, multi-region) with their host, VLAN, and networking requirements
- Full-text search plus filters by component, type, category, status, and criticality
- Click-to-edit any decision's type, status, criticality, justification, implication, or notes
- Star decisions individually or in bulk, then export to Excel in the original format
- Import an updated Design Library .xlsx or add temporary session-only decisions

## About this repository

This repo hosts the **VCF Tools Hub** landing page (`index.html` / `styles.css`) — a static site served via GitHub Pages with a custom domain (see `CNAME`). It links out to the three tools above, which are built and hosted separately.

## License

MIT — see [LICENSE](LICENSE).

## Author

Built by [Leonardo Coscia](https://github.com/lcoscia), VMware Cloud Foundation specialist at ITQ.
