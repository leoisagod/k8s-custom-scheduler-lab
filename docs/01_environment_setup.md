# 01. Environment Setup

This guide demonstrates how to build a Kubernetes cluster from scratch on Ubuntu using VMware.

## Requirements

- VMware Workstation 17
- Ubuntu 24.04 ISO
- At least 2 VMs (1 master, 1 worker)
- 4GB RAM per VM (recommended 8GB for master)

---

## Step 1: Install VMware

Download VMware Workstation from:
https://www.vmware.com/products/desktop-hypervisor/workstation-and-fusion

Install with default settings.

---

## Step 2: Create Ubuntu Virtual Machine

1. Create new VM
2. Select Ubuntu ISO
3. Assign hostname:
   - master (for control plane)
   - worker (for compute node)
4. Allocate disk space (recommend 40GB+ for master)
