## Welcome to ARIEL project

ARIEL is an ARINC-615A based DataLoader application and here you'll find everything you need to build and run the project.

[ARIEL](https://github.com/TCC-PES-2022/ARIEL) repository is the main repository and you'll find instructions there. If you're interested in something more specific, here's a sumary of everything else:

* [AuthenticationManager](https://github.com/TCC-PES-2022/AuthenticationManager) is the library responsible for the authentication system.
* [CommunicationManager](https://github.com/TCC-PES-2022/CommunicationManager) is the library responsible for communication between two endpoints using ARINC-615A protocol. It's subdivided in:
  * [ARINC615AManager](https://github.com/TCC-PES-2022/ARINC615AManager): Library responsible for transferring data between two endpoints using ARINC 615A protocol.
  * [BLSecurityManager](https://github.com/TCC-PES-2022/BLSecurityManager): Library responsible for the transfer mechanism for the authentication between DataLoader and the TargetHardware.
  * [TransferManager](https://github.com/TCC-PES-2022/TransferManager): A generic library for transferring data between two endpoints
  * [ATFTP](https://github.com/TCC-PES-2022/atftp/tree/libatftp): This is a simplified library version based on ATFTP project, which provides an implementation for the TFTP protocol. Please check the [original](https://salsa.debian.org/debian/atftp) project.
* [ImageManager](https://github.com/TCC-PES-2022/ImageManager) is the library responsible for managing images and compatibility files.
* [LogManager](https://github.com/TCC-PES-2022/LogManager) is the log library.
* [UI_API](https://github.com/TCC-PES-2022/UI_API) is a library intended to detach the user interface from the rest of the project.
  
There's also the [BLModule](https://github.com/TCC-PES-2022/BLModule) repository. This is a stub to receive data and act as a TargetHardware for the DataLoader. Following instructions from [ARIEL](https://github.com/TCC-PES-2022/ARIEL) repository will point you to the right direction on how to use this.
