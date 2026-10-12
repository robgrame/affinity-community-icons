# Affinity Community Icons

Original minimalist vector icons for device management, networking, cloud,
AI, security, and document sections. Created in Affinity Studio and shared
with the community under the [Apache License 2.0](LICENSE).

**Version 2.0.2** includes **60 SVG variants**, matching PNG exports where
available, **8 editable Affinity documents**, and preview sheets. The 48
infrastructure icons are different designs; security entries include color
and usage variants, not 60 distinct concepts.

> **Not official Azure icons:** Azure-related illustrations in this collection
> are independent, original conceptual symbols, not Microsoft's official Azure
> service icons or product logos. They do not imply Microsoft endorsement.

## Download and use

Download the repository ZIP from **Code > Download ZIP**, or clone it:

```powershell
git clone https://github.com/robgrame/affinity-community-icons.git
```

The small native `.af` documents are stored directly in Git: no Git LFS
client or separate binary download is required. Open them in a compatible
version of Affinity Studio (created with Affinity 3.3). Use SVG for scalable
UI, presentations and print; PNG is convenient for applications that do not
support SVG. Keep the original proportions and recolor both fills and strokes.

## Collections

| Collection | SVG variants | Native documents | Artwork and preview |
|---|---:|---:|---|
| [Infrastructure 01](sets/infrastructure-01) | 16 | 1 | Device management, inventory, compliance, deployment; topology, wireless, internet, firewall; services, upload, security, hybrid cloud; processor, neural network, assistant, automation |
| [Infrastructure 02](sets/infrastructure-02) | 16 | 1 | Remote support, updates, diagnostics, power; switch, VPN, Ethernet, load balancing; storage, backup, database, multi-region; model, data pipeline, prompt, insights |
| [Infrastructure 03](sets/infrastructure-03) | 16 | 1 | Policy, encryption, enrollment, lifecycle; DNS, latency, routing, gateway; containers, autoscaling, monitoring, recovery; agents, vision, knowledge, guardrails |
| [Section icons](sets/section-icons) | 4 | 2 | Challenge shield and lock, outcome trace, capability checklist, ascending-bar alternative |
| [Security: lock and magnifier](sets/security-lock-magnifier) | 4 | 1 | Navy outline, Azure outline, solid Azure and solid monochrome |
| [Security: solid Azure exports](sets/security-solid-azure) | 4 | 2 | Light, dark and white-lock variants, plus SVG/ICO favicon and multiple PNG sizes |

### Infrastructure 01

![Infrastructure set 01 preview](sets/infrastructure-01/infrastructure-icons-preview.png)

### Infrastructure 02

![Infrastructure set 02 preview](sets/infrastructure-02/infrastructure-icons-extended-preview.png)

### Infrastructure 03

![Infrastructure set 03 preview](sets/infrastructure-03/infrastructure-icons-set3-preview.png)

### Section icons

![Section icons preview](sets/section-icons/section-icons-preview.png)

SFIDA means "challenge"; the shield has an unfilled outline and a centered
padlock. OUTCOME includes an off-white vector grid. The checklist is the
preferred FEATURES icon; the original bar chart is retained as an alternative.
The v1.1.3 native document contains all four artboards; v1.0.2 preserves the
first three designs.

### Security: lock and magnifier

| Navy outline | Azure outline | Solid Azure | Solid monochrome |
|---|---|---|---|
| ![Navy outline](sets/security-lock-magnifier/security-lock-magnifier-01-outline-navy.svg) | ![Azure outline](sets/security-lock-magnifier/security-lock-magnifier-02-outline-azure.svg) | ![Solid Azure](sets/security-lock-magnifier/security-lock-magnifier-03-solid-azure.svg) | ![Solid monochrome](sets/security-lock-magnifier/security-lock-magnifier-04-solid-monochrome.svg) |

### Security: solid Azure exports

![Security usage preview](sets/security-solid-azure/solid-azure-usage-preview.png)

Portal PNG sizes: 32, 40, 48, 64, 256 and 512 px for each light/dark/white
variant. Favicon PNGs: 16, 32, 48, 64, 128 and 256 px, plus a multi-image ICO.
The native v1.1.4 document includes the white-lock artboard; v1.1.3 is retained
as an earlier version.

## Design

The infrastructure sets use 256 x 256 px transparent artboards, arranged in
a 4 x 4 grid per native document. The shared palette is navy **#0F2741** and
Azure blue **#0078D4**, with rounded 8 px strokes. Recommended display size:
32 px or larger; use 48 px for detail-heavy icons. Light-colored security
variants are intended for dark backgrounds.

All icon SVGs contain vector geometry rather than embedded raster artwork
or font-dependent labels. Preview sheets are raster images with labels.
The [catalog](catalog.json) records every distributed asset's SHA-256 hash,
size and relative path for integrity checks.

## Azure service illustrations

Generic cloud concepts are already available; dedicated service-specific
illustrations are proposed below and **are not included in this release**.
Any future Azure service illustrations will be original, non-official designs,
not copies or recolorings of Microsoft's official icons. "Azure blue" in the
palette describes a color, not official branding or certification.

If an architecture diagram requires the official Microsoft symbols, obtain
them separately from the
[official Azure architecture icon collection](https://learn.microsoft.com/en-us/azure/architecture/icons/),
under Microsoft's applicable terms. They are not distributed in this repository.

## Useful additions: coverage assessment

The existing collections cover broad operational concepts. Additional icons
would be useful where a diagram needs a specific service, physical device,
network boundary, or AI workflow rather than another generic cloud symbol.
The following **40 candidates are proposals, not downloadable assets**.

| Area | Priority | Proposed icons | Gap addressed |
|---|---|---|---|
| Azure Services | High | Azure Functions, App Service, AKS, Key Vault, Service Bus, Event Grid, Cosmos DB, Azure SQL | Original, clearly non-official service-specific illustrations for architecture diagrams |
| Devices | High | Laptop, smartphone, tablet, printer, IoT sensor, edge appliance, docking station, GPU workstation | Distinguish physical device types; current device icons describe management operations |
| Networking | High | Subnet, private endpoint, VNet peering, network security group, NAT gateway, reverse proxy, packet inspection, SD-WAN | Show boundaries, private connectivity and traffic paths beyond existing routing and firewall concepts |
| AI | High | Embeddings, vector search, RAG, model evaluation, fine-tuning, dataset curation, content moderation, tool calling | Represent retrieval, quality and model-development stages beyond existing agents and guardrails |
| Cloud Services | Medium | Compute instance, serverless execution, message queue, event stream, identity provider, secrets service, API gateway, cost management | Provider-neutral compute, integration, identity and governance concepts beyond storage and backup |

Prioritize Devices and Networking for immediate cross-provider usefulness,
then Azure Services and AI. Add provider-neutral Cloud Services where they
can be visually distinguished from existing icons. Each future collection
should use one editable document with one artboard per icon, matching SVG/PNG
exports and a labeled preview.

## Contributing

Issues and pull requests are welcome. Include a descriptive icon name, an
SVG export and a preview, and keep editable Affinity source when available.
Follow the existing palette and proportions, or clearly identify intentional
alternatives. Contribute only original artwork or work you have permission to
redistribute. Do not include credentials, private documents or personal data.

Versions use **Major.Minor.Build**. Increment Build for each change, Minor for
a new collection or significant capability, and Major for breaking changes.

## License

The artwork is distributed under the [Apache License 2.0](LICENSE). Follow
its notice and attribution requirements when redistributing the artwork.
Copyright and license notices remain applicable independently of asset names.

Asset filenames and native document titles are generic. This release changes
the filenames; update existing links to the paths in the current catalog.
The icon geometry is unchanged.

Service and company names are descriptive only. No official Microsoft Azure,
Affinity or Canva badges are reproduced, and no endorsement or trademark
rights are granted.
