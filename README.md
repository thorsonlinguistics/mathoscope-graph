# Mathoscope Knowledge Graph

# Setup

This section provides step-by-step instructions on how to download, install, and
import the provided Neo4j database dump (`.dump`) file to explore the graph
dataset locally.

> ⚠️ **Status Notice:** Currently, there is no hosted, online read-only version
> of this database accessible. To query and visualize the data, you must set up
> a local instance using the instructions below. We are currently exploring
> options to have a hosted version for minimal setup.

---

## 1. Prerequisites & Installation

To easily manage and interact with the database dump, we recommend installing
**Neo4j Desktop**, a free local development environment that includes the Neo4j
Database, browser tools, and plugins.

1. **Download Neo4j Desktop:** Visit the official [Neo4j Download
   Center](https://neo4j.com/download/) and download the installer for Neo4j
   Desktop (available for Windows, macOS, and Linux).
2. **Install:** Follow the platform-specific installation wizard instructions.
3. **Activation:** When you launch Neo4j Desktop for the first time, it will
   request an activation key. Register your details on the Neo4j page to get a
   free personal/developer activation key.

---

## 2. Importing the Database Dump

Once Neo4j desktop is installed, follow the graphical method below.

1. **Open Neo4j Desktop** and select `Create instance`.
2. **Load the Dump File:** Expand the section at the bottom of the form and
   upload your `.dump` file.
3. **Configure Details:**
    - **DBMS Name:** Enter a name of your choice, such as `mathoscope`.
    - **Password:** Enter a secure password and make note of it, as it will not
      be recorded.
    - **Version:** The latest 2026 version is recommended for compatibility with
      this dump.
4. **Create Database:** Press the `Create` button and wait for the database to
   initialize.

## 3. Sample Queries


