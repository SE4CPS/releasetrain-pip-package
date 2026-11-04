# Security Policy

## Reporting a vulnerability

Report suspected vulnerabilities through GitHub private vulnerability
reporting on this repository, or by email to the project owner. Please do not
open a public issue for security reports.

Include steps to reproduce and the impact you observed. Expect an
acknowledgement within a few business days.

## Scope

This repository is a Python CLI package (`PackageUpdateSearch`) that queries
the ReleaseTrain HTTP API and, optionally, drives a local Ollama agent. It
ships no server code and stores no credentials. The ReleaseTrain API and its
data store live in a separate `releasetrain-server` repository.

The optional `agent-update` command requires a locally running Ollama
instance; it does not send data to any third-party service beyond the
ReleaseTrain API and the local Ollama process.
