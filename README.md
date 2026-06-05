# Google Colab (google-colab)

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
