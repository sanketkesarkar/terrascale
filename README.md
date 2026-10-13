# TerraScale

**Live site:** https://sanketkesarkar.github.io/terrascale/

TerraScale is a cloud web application on Google Cloud Platform, built across three repositories: a Node.js REST API, Terraform infrastructure, and serverless functions. This repository holds only its public showcase website. The application code lives in private repositories.

## What the site shows
- **Deployment simulation:** an interactive walkthrough from `git push` to running cloud services, with a terminal and an architecture diagram.
- **Infrastructure overview:** networking, compute, database, storage, messaging and serverless components, and how they connect.
- **Tech stack:** the tools and GCP services used across the project.

The simulation runs entirely in the browser. No git, Packer, Terraform or cloud commands execute, no cloud resources are created, and terminal output and timings are illustrative.

## Project structure
| Repository | Purpose |
| --- | --- |
| `webapp` | Node.js REST API |
| `tf-gcp-infra` | Terraform configuration for the GCP infrastructure |
| `serverless` | Cloud Functions for event-driven background work |

These repositories are private. Their code is available on request.

## Stack
Google Cloud Platform · Terraform · Node.js · Cloud SQL (MySQL) · Cloud Pub/Sub · Cloud Functions · Compute Engine · Cloud Storage

## Run the site locally
The site is a single self-contained `index.html` with no build step. Open it in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Credits
Built by [Sanket Kesarkar](https://github.com/sanketkesarkar).
