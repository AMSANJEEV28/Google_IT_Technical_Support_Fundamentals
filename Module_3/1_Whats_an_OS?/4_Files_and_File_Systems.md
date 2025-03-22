# Module 3: Files and File Systems

### Introduction
- Computers can store hundreds of thousands of files, which requires efficient tracking.
- The **kernel** manages file storage and file systems on an operating system (OS).
- Key components in file management:
  - **File Data**
  - **Metadata**
  - **File System**

### File Systems
- When a new hard disk is used, it must be erased and configured to allow the OS to read and write data.
- **File systems** keep track of files and vary based on:
  - Storage capacity support
  - Speed of operation
  - Resiliency against file corruption
- Major operating systems use different file systems:
  - **Windows**: NTFS (New Technology File System)
    - Features: encryption, faster access speeds, and security.
    - An upcoming file system: ReFS (Resilient File System).
  - **Mac OS**: HFS+ (Hierarchical File System Plus)
    - Journaled for better recovery in case of failures.
  - **Linux**: ext4 (Fourth Extended File System)
    - Compatible with older ext file systems.

- **File system compatibility**: Different file systems don't easily interact with each other. It's best to use the recommended file system for each OS.

### File Data Storage
- Data is stored in **blocks** on hard drives, not in one long piece.
- **Block storage** enables faster data access and better storage utilization.
  
### File Metadata
- **Metadata** provides information about the file:
  - Creator, last modified date, access permissions, etc.
  - File type is often determined by the **file extension** (e.g., `.jpeg` for image files).

### Importance of File Systems Knowledge
- Understanding file systems is crucial for:
  - **Data recovery** from damaged disks.
  - Managing systems with **dual-boot** configurations (e.g., Windows and Linux on the same machine).
