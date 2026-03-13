# Google Colab (google-colab)
Google Colab (Colaboratory) is a hosted Jupyter notebook environment that provides free access to computing resources including GPUs and TPUs for data science and machine learning workflows. Colab notebooks are managed through the Google Drive API as files with a Colab-specific MIME type, and the Colab Enterprise API on Vertex AI provides managed runtime templates and execution scheduling for enterprise use cases.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/google-colab/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - Notebooks, Machine Learning, Data Science, Jupyter, Python, Google Cloud, Collaboration

## Timestamps

- **Created:** 2026-03-13
- **Modified:** 2026-03-13

## APIs

### Colab API via Google Drive API
Google Colab notebooks are stored as files in Google Drive with the MIME type application/vnd.google.colaboratory. The Google Drive API provides programmatic access to create, read, update, delete, share, and organize Colab notebooks. Developers can use the Drive API to list notebooks, manage permissions for collaboration, copy templates, and integrate Colab notebooks into automated workflows.

**Human URL:** [https://developers.google.com/drive/api/guides/about-sdk](https://developers.google.com/drive/api/guides/about-sdk)


#### Tags:

 - Notebooks, Google Drive, File Management

#### Properties

- [Documentation](https://developers.google.com/drive/api/reference/rest/v3)
- [OpenAPI](openapi/colab-drive-openapi.yml)
- [JSONSchema](json-schema/google-colab-notebook-schema.json)

### Colab Runtime and Kernel Management
Google Colab provides internal APIs for managing notebook runtimes and kernels, including connecting to hosted runtimes, local runtimes, and custom GCE VM backends. The runtime API handles kernel lifecycle (connect, interrupt, restart), resource allocation (GPU/TPU), and execution of notebook cells.

**Human URL:** [https://research.google.com/colaboratory/faq.html](https://research.google.com/colaboratory/faq.html)


#### Tags:

 - Runtime, Kernels, GPU, TPU

#### Properties

- [Documentation](https://research.google.com/colaboratory/faq.html)

### Colab Enterprise API
The Colab Enterprise API on Google Cloud provides managed notebook runtimes integrated with Vertex AI. It enables creating and managing notebook execution schedules, runtime templates, and managed runtimes within Google Cloud projects. The API supports enterprise governance features including VPC Service Controls, customer-managed encryption keys, and IAM-based access control.

**Human URL:** [https://cloud.google.com/colab/docs](https://cloud.google.com/colab/docs)


#### Tags:

 - Enterprise, Vertex AI, Managed Notebooks

#### Properties

- [Documentation](https://cloud.google.com/colab/docs/reference/rest)

## Common Properties

- [GettingStarted](https://colab.research.google.com/notebooks/welcome.ipynb)
- [Pricing](https://colab.research.google.com/signup)
- [Authentication](https://developers.google.com/drive/api/guides/about-auth)
- [Support](https://research.google.com/colaboratory/faq.html)
- [Status](https://status.cloud.google.com)
- [JSON-LD](json-ld/google-colab-context.jsonld)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
