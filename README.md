# oss-audit-24BCE11220
Open Source Audit — MySQL
Overview

This repository contains a capstone project for the Open Source Software course. The project presents a structured audit of MySQL, focusing on its origin, licensing model, ecosystem, and comparison with proprietary database systems.

The repository also includes five Linux shell scripts demonstrating practical concepts related to system analysis, package management, and open-source philosophy.

Project Objectives:
      Analyse MySQL as an open-source software artifact
      Understand the GNU General Public License (GPL v2)
      Study MySQL’s role in the Linux ecosystem
      Explore dependencies and contributions to the FOSS ecosystem
      Compare open-source and proprietary database systems
      Demonstrate Linux scripting concepts through practical scripts

Repository Contents
1. Project Report

The report covers:

Origin and philosophy of MySQL
Licensing (GPL v2 and dual licensing model)
Linux installation, directories, and security
MySQL ecosystem and dependencies
Comparison with Oracle Database

2. Shell Scripts
Script 1 — System Identity Report

Displays system information including kernel, distribution, user details, uptime, and MySQL version.

Script 2 — FOSS Package Inspector

Checks if MySQL is installed and prints version details along with an open-source philosophy note.

Script 3 — Disk and Permission Auditor

Audits important system directories and checks MySQL data directory permissions and size.

Script 4 — Log File Analyzer

Analyzes a log file, counts keyword occurrences, and displays recent matching entries.

Script 5 — Open Source Manifesto Generator

Generates a personalized open-source manifesto based on user input and saves it to a file.

Requirements:
      Linux-based operating system (Ubuntu/Debian recommended)
      Bash shell
      MySQL (optional, for full script functionality)

How to Run

Make scripts executable:chmod +x script_name.sh

Run a script:./script_name.sh

Example:./log_analyzer.sh /var/log/mysql/error.log error

Key Concepts Covered:
      Open Source Philosophy
      GPL v2 Licensing
      Linux System Administration
      Shell Scripting (Bash)
      File Permissions and Process Management
      Log Analysis
Conclusion:
This project demonstrates how MySQL represents both the strengths and complexities of open-source software. It highlights the balance between community-driven development and corporate control, while also providing practical exposure to Linux and scripting.
