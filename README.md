# Prerequisites
  1. Clone https://stash.dss.husqvarnagroup.com/projects/SG/repos/smart-garden-gateway-seluxit-kernel and update to branch sg_gw_changes (as of 16.01.20)
  2. Build the kernel as described in the README of that repo

# Building the driver
  1. Replace `/path/to/kernel/repo` in Makefile with the full path of where the kernel has been cloned
  2. Run `make`