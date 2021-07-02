# Ionburst Cloud Changelog Examples & Logic

The Ionburst Cloud Changelog gives us a mechanism to maintain a centralised list of changes, releases and fixes across the IBC ecosystem. This is otherwise difficult to do as we're a platform rather than a single OSS repo.

The Ionburst Cloud Changelog uses a layout similar to one defined by [semantic versioning](https://semver.org/), with some key changes:

- Instead of versions (v1.0.0), we will create entries for each month - e.g. June 2021
- The Changlog will be broken down by the type or "area" of change:
  - Ionburst Cloud Platform
  - Ionburst Cloud Website and Docs
  - Ionburst Cloud Clients - SDKs, integrations
- We will split changes out into:
  - New Releases - analogous to `MAJOR` in semver 
  - New Features - analogous to `MINOR` in semver
  - Fixes - analogous to `PATCH` in semver
- If no changes for a given type exist, it is ignored for that month
