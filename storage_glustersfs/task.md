* Set up a high-availability storage with two storage servers (CentOS 7.2) that use GlusterFS:
  * Each storage server will be a mirror of the other storage server, and files will be replicated automatically across both storage servers.
  * The client system (CentOS 7.2 as well) will be able to access the storage as if it was a local filesystem.

Note: GlusterFS is a clustered file-system capable of scaling to several peta-bytes. It aggregates various storage bricks over Infiniband RDMA or TCP/IP interconnect into one large parallel network file system. Storage bricks can be made of any commodity hardware such as x86_64 servers with SATA-II RAID and Infiniband HBA.
Suggestions:
  * You can use any type of software/hardware to build this lab.
  * you also can use any type tutorial found on Internet to build this lab.
