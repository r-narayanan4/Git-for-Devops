# Version Control Systems (VCS)

Version Control Systems (VCS), also known as Source Code Management (SCM) systems or Revision Control Systems, are software tools that keep track of changes made to files over time. They enable collaboration among multiple people on a project by tracking who made changes, what changes were made, and when they were made. This facilitates efficient teamwork, conflict management, and maintains a history of changes for reference.

Popular VCS tools include Git, Mercurial, and Subversion.

## Types of Version Control Systems (VCS)

### 1. Centralized Version Control Systems (CVCS)

Centralized Version Control Systems (CVCS) utilize a single, centralized server to store the repository. Developers check out files from this central location, make changes locally, and then commit them back to the central server. Examples of CVCS include Subversion (SVN) and CVS (Concurrent Versions System).

![Centralized VCS](images/cvcs-image.png)

### 2. Distributed Version Control Systems (DVCS)

Distributed Version Control Systems (DVCS) do not necessarily rely on a central server. Instead, each user has a complete copy of the repository on their local system. This allows for more flexibility, offline work, and easier branching and merging. Examples of DVCS include Git, Mercurial, and Bazaar.

![Distributed VCS](images/dvcs-image.png)

## Difference Between CVCS and DVCS

| Feature                        | Centralized VCS (CVCS)                                       | Distributed VCS (DVCS)                                      |
|--------------------------------|--------------------------------------------------------------|-------------------------------------------------------------|
| **Repository Location**        | Repository is stored on a central server.                   | Each user has a complete copy of the repository locally.    |
| **Network Dependency**         | Requires constant network connection for most operations.    | Most operations can be performed offline.                   |
| **Collaboration**              | Collaboration relies heavily on the central server.         | Easier collaboration without strict reliance on a server.   |
| **Branching and Merging**      | Branching and merging are typically more challenging.        | Branching and merging are often easier and more flexible.   |
| **Backup**                     | Central server acts as a single point of failure.            | Each user's local repository serves as a backup.           |
| **Examples**                   | SVN (Subversion), CVS (Concurrent Versions System)           | Git, Mercurial, Bazaar                                     |


## Standalone VCS Software Tools:

- **Git**: Distributed
- **Subversion (SVN)**: Centralized
- **Mercurial**: Distributed

## Hosting Platforms for Git Repositories:

- **GitHub**: Distributed (hosting platform for Git repositories)
- **Bitbucket**: Distributed (hosting platform for Git repositories)
- **GitLab**: Distributed (hosting platform for Git repositories)
