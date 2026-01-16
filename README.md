# [Hyades](https://hyades.mit.edu/), take three

## Directory Structure
- `packages`
  - `worker`: worker daemon
  - `control`: control plane API
  - `web_client`: web client (including public user management)
  - `cli_client`: terminal client for administrative purposes
- `schemas`: [gRPC](https://grpc.io/) proto-buffer files for inter-service communication
- `docs`: read 'em
- `just`: [just](https://just.systems/) build files

## Building
The project makes extensive use of [just](https://just.systems/) for building