# Docker 知识地图

## 00. 基础概念

- Container
- Image
- Docker Engine
- Docker CLI
- Docker Daemon
- Registry
- Repository
- Tag
- Docker vs VM

## 01. Docker CLI

- docker version
- docker info
- docker help
- docker run
- docker ps
- docker stop
- docker start
- docker restart
- docker rm
- docker exec
- docker logs
- docker inspect
- docker cp
- docker stats
- docker top

## 02. Image

- Image
- Repository
- Tag
- Digest
- Image ID
- Image Layer
- Image Config
- Image Manifest
- Image Pull
- Image Push
- Image Build
- Image Tag
- Image Remove
- Image History
- Image Save
- Image Load

## 03. Container

### Container 生命周期

- Created
- Running
- Paused
- Stopped
- Removed

### Container 创建

- docker create
- docker run

- Container 启动
- Container 停止
- Container 重启
- Container 删除

### Container 进入

- docker exec
- docker attach

- Container 日志
- Container 状态

### Container 资源

- CPU
- Memory
- PID
- IO

- Container 环境变量
- Container 工作目录
- Container 用户
- Container hostname
- Container restart policy
- Container healthcheck

## 04. Dockerfile

- Dockerfile
- Build Context
- FROM
- RUN
- COPY
- ADD
- CMD
- ENTRYPOINT
- ENV
- ARG
- WORKDIR
- USER
- EXPOSE
- VOLUME
- LABEL
- SHELL
- STOPSIGNAL
- HEALTHCHECK

## 05. Dockerfile 核心机制

- Instruction
- Layer
- Build Step
- Build Context
- Build Cache
- Cache Hit
- Cache Miss
- Cache Invalidation
- CMD vs ENTRYPOINT
- COPY vs ADD
- Shell Form
- Exec Form

## 06. Docker Build

- docker build
- BuildKit
- Buildx
- Build Cache
- Cache Mount
- Secret Mount
- SSH Mount
- Multi-stage Build
- Builder Stage
- Runtime Stage
- Multi-platform Build
- Build Arguments
- Build Output

## 07. .dockerignore

- .dockerignore
- Build Context Filtering
- Pattern
- Wildcard
- Exclusion

## 08. Storage

- Container Filesystem
- Writable Layer
- Read-only Layer
- Copy-on-Write
- Storage Driver
- overlay2

### Volume

- Named Volume
- Anonymous Volume
- Volume Create
- Volume Mount
- Volume Inspect
- Volume Remove

- Bind Mount
- tmpfs
- Read-only Mount

## 09. Network

- Docker Network

### Network Driver

- bridge
- host
- none
- overlay
- macvlan
- ipvlan

- Container IP
- Container DNS
- Container Name
- Service Discovery
- Port Mapping
- Port Publishing
- Network Connect
- Network Disconnect

## 10. Docker Compose

- Docker Compose
- compose.yaml
- Service
- Image
- Build
- Command
- Entrypoint
- Environment
- Ports
- Volumes
- Networks
- Depends On
- Healthcheck
- .env
- Profiles
- docker compose up
- docker compose down
- docker compose start
- docker compose stop
- docker compose restart
- docker compose ps
- docker compose logs
- docker compose exec
- docker compose build
- docker compose pull

## 11. Registry

- Registry
- Repository
- Tag
- Digest
- docker login
- docker logout
- docker pull
- docker push
- Image Naming
- Private Registry
- Registry Authentication

## 12. Docker 安全

- Root Container
- Non-root Container
- User Namespace
- Linux Capability
- --privileged
- Device Access
- Seccomp
- AppArmor
- SELinux
- Secret
- Image Vulnerability
- CVE
- SBOM
- Image Signing

## 13. Docker 架构

- Docker Client
- Docker CLI
- Docker API
- Docker Daemon
- Docker Engine
- containerd
- containerd-shim
- runc
- OCI

## 14. Docker 底层原理

### Namespace

- PID Namespace
- Network Namespace
- Mount Namespace
- UTS Namespace
- IPC Namespace
- User Namespace

### Cgroups

- CPU
- Memory
- PID
- IO

- Capability

### OverlayFS

- Lowerdir
- Upperdir
- Merged
- Workdir
- Copy-up

- veth
- Linux Bridge
- NAT
- iptables

## 15. OCI

- OCI
- OCI Image Specification
- OCI Runtime Specification
- OCI Distribution Specification
- Manifest
- Config
- Layer
- Digest

## 16. containerd

- containerd
- Client
- Daemon
- Content Store
- Metadata Store
- Snapshotter
- Snapshot
- Shim
- Runtime

## 17. runc

- OCI Runtime
- Container Process
- Rootfs
- Namespace Setup
- Cgroup Setup
- Capability Setup
- Process Exec

## 18. Container 启动链路

- docker run
- Docker CLI
- Docker API
- Docker Daemon
- containerd
- containerd-shim
- runc
- Linux Kernel
- Container Process

## 19. Image 构建链路

- Dockerfile
- BuildKit
- Build Graph
- Build Step
- Layer
- Image Config
- Manifest
- Registry

## 20. Docker 性能

- CPU Limit
- CPU Quota
- CPU Shares
- CPU Pinning
- Memory Limit
- Swap
- OOM
- IO
- Network Throughput
- Network Latency
- Image Size
- Layer 数量
- Build Cache
- Build Performance

## 21. Docker 镜像优化

- Base Image
- Minimal Image
- Image Size
- Layer Optimization
- Cache Optimization
- Multi-stage Build
- Build Context Optimization
- Runtime Image
- Non-root
- Read-only Filesystem

## 22. Docker 调试

- Container 启动失败
- Image 问题
- CMD 问题
- ENTRYPOINT 问题
- Permission 问题
- Environment 问题
- Network 问题
- DNS 问题
- Port 问题
- Mount 问题
- Volume 问题
- Storage 问题
- CPU 问题
- Memory 问题
- IO 问题
- docker logs
- docker inspect
- docker exec
- docker stats
- docker events
- docker diff

## 23. Docker 高级

- Multi-platform Image
- Buildx
- Build Cache Export
- Build Cache Import
- Remote Build
- Rootless Docker
- Docker Context
- Docker Plugin
- Volume Driver
- Network Plugin
- Custom Runtime
- Container Runtime
- Image Distribution
- Docker API
