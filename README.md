# Docker Data Management Lab

A hands-on Docker data-management project completed during the CMIT AI Internship to understand named volumes, bind mounts, persistence, read-only mounts, and Docker storage best practices.

## Objective

The goal of this task was to learn how Docker manages persistent data and how data can be shared between the host and containers.

The practical work covered:

- Docker named volumes
- volume creation and listing
- volume inspection
- data persistence after container removal
- bind mounts
- host-to-container file sharing
- container-to-host file updates
- read-only bind mounts
- Docker storage best practices

---

## 1. Named Volume

A named volume is Docker-managed persistent storage.

The volume was created using:

```bash
docker volume create patient-data