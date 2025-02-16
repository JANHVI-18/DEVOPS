# DEVOPS
# README: Subversion (SVN) & Mercurial (HG)

This document provides an overview and instructions on using **Subversion (SVN)** and **Mercurial (HG)**, two version control systems commonly used in software development. The guide covers the basics of both systems, how to install them, and commonly used commands for managing project files and repositories.

---

## **1. Subversion (SVN)**

### Overview:
**Subversion (SVN)** is an open-source version control system (VCS) used for managing changes to files over time. It allows developers to track changes, collaborate, and maintain different versions of a project.

### Types of Version Control Systems:
- **Centralized Version Control System (CVCS)**:
  - A central server stores all versions.
  - Users check out the latest version, make changes, and commit them back to the central server (e.g., SVN).
  
- **Distributed Version Control System (DVCS)**:
  - Each user has a full copy of the repository, enabling offline work and branching (e.g., Git).

### Why Use Version Control?
- **Track Changes**: Maintain a historical record of all changes.
- **Revert Versions**: Easily roll back to previous versions.
- **Collaboration**: Allows multiple users to work on the same project simultaneously.
- **Branching & Merging**: Enables independent feature development and seamless merging without disrupting the main project.

### Installing SVN on Windows:
1. **Download and Install TortoiseSVN**:  
   Visit [TortoiseSVN](https://tortoisesvn.net/downloads.html) to download and install the version suitable for your system.
   
2. **Restart the System**:  
   Restart your computer to integrate TortoiseSVN with Windows Explorer.
   
3. **Verify Installation**:  
   Open Command Prompt and type the following to confirm installation:
   ```bash
   svn --version
