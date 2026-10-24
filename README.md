<p align="center">
  <img src="assets/cat-banner.png" alt="a pixel-art white cat in a pink raincoat hood in the rain, next to the text hi, im ish" width="100%">
</p>

im a student and data is my thing. not just queries, but whole data
platforms and the infrastructure underneath, from ingestion and change data
capture to streaming, storage and the kubernetes clusters it all runs on.
im curious about how systems work, how they scale, and how to build them so
they solve real problems.

im also a big open source fan. most of what i use is open source, and this
is where i document, share and build what i learn. hopefully my journey is
useful for others too ^^

### ⋆ what im into

- **data platforms** and end-to-end data infrastructure, from ingestion and change data capture to streaming and storage
- **kubernetes**, running data workloads on clusters and all the plumbing around them
- **backend** stuff, mostly in go. small clis, services and the occasional mcp server
- **cloud and security**, so containers, registries, terraform on gcp and vulnerability scanning
- **open source**, building on it every day and sharing what i make

### ⋆ things i made

- [**puddle**](https://github.com/Dem1241/puddle) · watch kafka and redpanda topics in the terminal, with debezium changes shown field by field `go`
- [**slotwatch**](https://github.com/Dem1241/slotwatch) · watch postgres replication slots and catch the one quietly filling your disk with WAL `go`
- [**connectwatch**](https://github.com/Dem1241/connectwatch) · watch kafka connect connectors, see why a task failed and restart it `go`
- [**difftest**](https://github.com/Dem1241/difftest) · send the same random sql to dolt's engine and to mysql and report every answer that differs `go`
- [**go-cdc-lab**](https://github.com/Dem1241/go-cdc-lab) · change data capture playground with postgres, debezium and redpanda `go`
- [**pg-mcp-live**](https://github.com/Dem1241/pg-mcp-live) · read-only mcp server for postgres with schemas, safe selects and query plans `typescript`
- [**harbor-scanner**](https://github.com/Dem1241/harbor-scanner) · push images to harbor, trigger vulnerability scans and export the reports `go`
- [**mariadbmanagement**](https://github.com/Dem1241/mariadbmanagement) · run and manage several mariadb instances in docker `python`
- [**weight**](https://github.com/Dem1241/weight) · track your body weight in the terminal and watch the weekly average, not the daily noise `go`

### ⋆ open source contributions

mostly bug fixes in sql engines and database tools, each with a test and checked against the real database

- [**dolthub/go-mysql-server#4059**](https://github.com/dolthub/go-mysql-server/pull/4059) · `sql_select_limit` was ignored for simple selects and `DISTINCT`
- [**dolthub/go-mysql-server#4062**](https://github.com/dolthub/go-mysql-server/pull/4062) · `LEFT JOIN LATERAL` with a filter on the outer row failed to plan

<sub>more on the way for dolt, doltgresql, pgroll, redpanda connect, dbmate, goose and others, see [all my prs](https://github.com/search?q=author%3ADem1241+is%3Apr&type=pullrequests)</sub>

### ⋆ toolbox

![kubernetes](https://img.shields.io/badge/kubernetes-313244?style=flat-square&logo=kubernetes&logoColor=89b4fa) ![postgresql](https://img.shields.io/badge/postgresql-313244?style=flat-square&logo=postgresql&logoColor=89b4fa) ![go](https://img.shields.io/badge/go-313244?style=flat-square&logo=go&logoColor=74c7ec) ![python](https://img.shields.io/badge/python-313244?style=flat-square&logo=python&logoColor=f9e2af) ![typescript](https://img.shields.io/badge/typescript-313244?style=flat-square&logo=typescript&logoColor=89b4fa) ![docker](https://img.shields.io/badge/docker-313244?style=flat-square&logo=docker&logoColor=74c7ec) ![terraform](https://img.shields.io/badge/terraform-313244?style=flat-square&logo=terraform&logoColor=cba6f7) ![google cloud](https://img.shields.io/badge/google%20cloud-313244?style=flat-square&logo=googlecloud&logoColor=f5c2e7) ![nixos](https://img.shields.io/badge/nixos-313244?style=flat-square&logo=nixos&logoColor=89b4fa)

<sub>daily driver is nixos + hyprland, coding in zed, everything in catppuccin pink and a little rain</sub>

<p align="center"><sub>thanks for stopping by ⋆ have a nice day ^^</sub></p>
