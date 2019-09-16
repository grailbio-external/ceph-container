GRAIL Readme
================

This is a frozen version of the [ceph-container](https://github.com/ceph/ceph-container) repo hosted at github. It was last sync'd to the commit f4faf64493a66b9d339e781780b9e316a99e9f76.

The repo is for building the Ceph container image that is used to bring up MON, MGR and OSD daemons on Ceph hosts. The Dockerfile has been modified to eliminate Ceph packages related to various filesystem layers like NFS, RBD etc to reduce both the size of the image and dependencies on other external packages.
