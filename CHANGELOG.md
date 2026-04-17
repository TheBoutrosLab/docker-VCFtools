# Changelog
All notable changes to the VCFtools Docker file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

This project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [Unreleased]

---
## [0.1.17] - 2026-04-17
### Changed
- Update VCFtools `v0.1.16` to `v0.1.17`
- Update Miniforge version to `v26.1.1-2`
- Update Ubuntu version to `v24.04`
- Replace `condaforge/mambaforge` with `condaforge/miniforge3`

---

## [0.1.16] - 2024-04-16
### Added
- Add PR template to repo
- Add `Docker-build-release.yaml` to repo
- Add `bldocker` as group and user to Dockerfile
- Set `bldocker` as default user

### Changed
- Update CICD-base docker registry to `ghcr.io/uclahs-cds`
- Standardize `README.md`
- Standardize `metadata.yaml`
- Standardize Dockerfile
- Use condaforge as builder

### Removed
- Remove `blcdsdockerregistry/bl-base` as builder

---

## [0.1.16] - 2021-05-07
### Added
- Migrated VCFtools dockerfile to its own repository
- Created CHANGELOG.md
