MarFS provides a scalable near-POSIX file system by using one or more POSIX file systems as a scalable metadata component and one or more data stores (object, file, etc) as a scalable data component. Our default implementation uses GPFS file systems as the metadata component and Scality or EMC ECS ViPR object stores as the data component.  The MetaData Abstraction Layer and Data Abstraction Layer (MDAL/DAL) provide a modular way to introduce alternative implementations (metadata and data implementations, respectively).  We are developing a Multi-Component data implementation, which we are currently in the process of validating.
There is extensive documentation in the Documents directory, including theory and an install-guide.
