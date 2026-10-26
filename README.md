# Google Colab (google-colab)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Google Colab (Colaboratory) is a hosted Jupyter notebook environment that provides free access to computing resources including GPUs and TPUs, with APIs for managing notebooks, runtimes, and integration with Google Drive for collaborative data science and machine learning workflows.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/google-colab/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/google-colab/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Collaboration
- Data Science
- Google Cloud
- Jupyter
- Machine Learning
- Notebooks
- Python

## Timestamps

- **Created:** 2026-03-13
- **Modified:** 2026-05-19

## APIs

### Colab API via Google Drive API

Google Colab notebooks are stored as files in Google Drive with the MIME type application/vnd.google.colaboratory. The Google Drive API provides programmatic access to create, read, update, delete, share, and organize Colab notebooks. Developers can use the Drive API to list notebooks, manage permissions for collaboration, copy templates, and integrate Colab notebooks into automated workflows.

- **Human URL:** [https://developers.google.com/drive/api/guides/about-sdk](https://developers.google.com/drive/api/guides/about-sdk)
- **Base URL:** `https://www.googleapis.com/drive/v3`

#### Tags

- File Management
- Google Drive
- Notebooks

#### Properties

- [Documentation](https://developers.google.com/drive/api/reference/rest/v3)
- [OpenAPI](openapi/colab-drive-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/colab-drive.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/colab-drive.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/google-colab-notebook-schema.json) — [JSON Schema](https://json-schema.org/specification)

### Colab Runtime and Kernel Management

Google Colab provides internal APIs for managing notebook runtimes and kernels, including connecting to hosted runtimes, local runtimes, and custom GCE VM backends. The runtime API handles kernel lifecycle (connect, interrupt, restart), resource allocation (GPU/TPU), and execution of notebook cells. These capabilities are exposed through the Colab UI and the colab Python package.

- **Human URL:** [https://research.google.com/colaboratory/faq.html](https://research.google.com/colaboratory/faq.html)
- **Base URL:** `https://colab.research.google.com`

#### Tags

- GPU
- Kernels
- Runtime
- TPU

#### Properties

- [Documentation](https://research.google.com/colaboratory/faq.html)
- [Postman Collection](collections/colab-drive.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/colab-drive.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Colab Enterprise API

The Colab Enterprise API on Google Cloud provides managed notebook runtimes integrated with Vertex AI. It enables creating and managing notebook execution schedules, runtime templates, and managed runtimes within Google Cloud projects. The API supports enterprise governance features including VPC Service Controls, customer-managed encryption keys, and IAM-based access control.

- **Human URL:** [https://cloud.google.com/colab/docs](https://cloud.google.com/colab/docs)
- **Base URL:** `https://notebooks.googleapis.com`

#### Tags

- Enterprise
- Managed Notebooks
- Vertex AI

#### Properties

- [Documentation](https://cloud.google.com/colab/docs/reference/rest)
- [Postman Collection](collections/colab-drive.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/colab-drive.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/googlecolab)
- [LinkedIn](https://www.linkedin.com/company/google-colab)
- [Getting Started](https://colab.research.google.com/notebooks/welcome.ipynb)
- [Pricing](https://colab.research.google.com/signup)
- [Authentication](https://developers.google.com/drive/api/guides/about-auth)
- [Support](https://research.google.com/colaboratory/faq.html)
- [Status Page](https://status.cloud.google.com)
- [JSON-LD](json-ld/google-colab-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
