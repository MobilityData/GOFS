# GOFS JSON schema

This directory contains partial [JSON schema](https://json-schema.org/) definitions for GOFS.

## Disclaimer

These definitions are a work-in-progress and as such:

- They do not yet cover the entire GOFS specification
- They are not yet restrictive enough to guarantee the correctness of GOFS feeds which pass validation

## Usage

At present it is possible to validate a GOFS feed by pasting each file of the feed (as Document or Input JSON) and its corresponding schema definition (as Schema) into a tool such as [jsonschemalint.com](https://jsonschemalint.com/) or [jsonschemavalidator.net](https://www.jsonschemavalidator.net/).
