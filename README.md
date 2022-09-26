# Secure-and-efficient-remote-data-auditing
1.1 Problem definition
Cloud computing is a distributed computing architecture that uses a vast pool of virtualized computing resources to do computations. Users of cloud services have complete control over how resources are allocated and released. This concept provides a number of advantages to its consumers without requiring a lot of hardware or software.
Long-term storage services are provided over the Internet by a cloud storage system, which consists of a collection of storage servers. Data confidentiality is seriously harmed when data
is stored in a third-party cloud system.
General encryption algorithms ensure data security but limit the storage system’s usefulness because only a few activities can be performed on encrypted data.
Allowing either the user or the cloud server to conduct the auditing procedure will be unsuitable because the data is outsourced and under the control of the cloud service provider.
Second, due to transmission costs or processing limitations, the user may not always be able to handle the overhead of such an activity. Furthermore, service users should be able to store
and access data without having to constantly worry about data integrity. The use of a third party auditing firm is justified for these reasons. As a result, we must provide a data auditing
system that allows an auditing authority to examine data without impacting its confidentiality.

1.2 Limitations of existing system
Delegated verifiability: The user should be able to delegate data auditing to a third party
without affecting the data confidentiality. Without retrieving all of the data from the cloud
server, the TPA should be able to perform the auditing process swiftly.

Storage authenticity: the user should be able to verify (either directly or through the TPA) that
his data is correctly saved on cloud servers.

Privacy Preserving: The TPA should not be able to recover the audited data blocks during the
auditing process to ensure privacy.


Batch verification: The auditor should be able to do several data checks at once.
In the existing system, a cloud server is in charge of computing the evidence for data integrity
checks, as well as storing a large amount of user data. As a result, the weight of storage as
well as the duty of creating verification proof on the cloud server is increased. There is a
need to present a solution that does not place additional strain on the cloud server during the
auditing process. All of the following characteristics are vital and must be met in order for the
plan to be trustworthy. As a result, an efficient and secure auditing method that can efficiently
perform public auditing while retaining both the integrity and confidentiality of stored data is
required.

1.3 Proposed system
To overcome the limitations of the present auditing systems, a robust public auditing protocol
must be developed. Using TPA, the suggested system verifies the correctness of cloud data. It
audits either on a regular or on-demand basis. It ensures that no data content is leaked to TPA
during the auditing process. It ensures the integrity and secrecy of the stored data.
