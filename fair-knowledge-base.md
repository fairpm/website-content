# FAIR Knowledge Base

## **Frequently Asked Questions**

We’re gathering focused answers to the most common questions about the FAIR project, its governance, security, and technical operations in the Technical Steering Committee repository on GitHub:

Go to the [FAIR project Frequently Asked Questions (GitHub)](https://github.com/fairpm/tsc/tree/main/faqs).

If you have a question not covered here, please open an issue or pull request, or post in [the ideas forum (GitHub)](https://github.com/orgs/fairpm/discussions/categories/ideas).

## **Glossary**

### **Aggregator**

Any server which aggregates or collects package data. This can be done from Repositories and/or other Aggregators.

### **API Replacement**

For specific features, FAIR provides replacement implementations of currently centralized vendor-specific services. Examples are update checks, browser version checks, event and news feeds.

### **AT Protocol**

ATProto is a standard for sharing social networking services. It is developed by Bluesky Social PBC, and is used by FAIR as the basis for the package distribution protocol. [Learn more about the AT Protocol](https://en.wikipedia.org/wiki/AT_Protocol).

### **DID**

Decentralized Identifier; a universally-unique identifier specified by the [W3C specification](https://www.w3.org/TR/did-1.0/). [Decentralized identifier article at Wikipedia](https://en.wikipedia.org/wiki/Decentralized_identifier).

Example of a DID in action: [Git Updater](https://github.com/afragen/git-updater)

DID registered via \[...\]

In the Git Updater plugin header:

/\*\*

 \* Plugin Name:       Git Updater

 \* Plugin ID:         did:plc:afjf7gsjzsqmgc7dlhb553mv

 \* ...

`https://plc.directory/did:plc:afjf7gsjzsqmgc7dlhb553mv` points to the full package information at `https://fair.git-updater.com/wp-json/minifair/v1/packages/did:plc:afjf7gsjzsqmgc7dlhb553mv`

### **FAIR**

FAIR is an acronym and stands for **F**ederated **A**nd **I**ndependent **R**epositories.

### **FAIR Core**

The core FAIR [protocol specification](https://github.com/fairpm/fair-protocol/blob/main/specification.md)

### **FAIR Distro**

A full WordPress distribution with FAIR preinstalled. Ideal for provisioning workflows. Available in the [release assets](https://github.com/fairpm/fair-plugin/releases) associated with FAIR Plugin releases.

### **FAIR Package Manager Project**

The overarching project creating a distributed system for software package releases.

### **FAIR Plugin**

[A plugin](https://github.com/fairpm/fair-plugin) that configures your site to use FAIR implementations of the key services that are currently centralized on WordPress.org. Installable on any individual WordPress site, no configuration needed.

FAIR can be installed manually by downloading the latest zip from releases and installing it via your WordPress admin dashboard.

* [FAIR Releases](https://github.com/fairpm/fair-plugin/releases)  
* [How To Manually Install a Plugin](https://wordpress.org/documentation/article/manage-plugins/#manual-plugin-installation-1)

### **FAIR Protocol**

The FAIR Package Management Protocol is a system for distributing installable software, the protocol outlines the core FAIR protocol specification ("FAIR Core").

* [Specification](https://github.com/fairpm/fair-protocol/blob/main/specification.md)  
* [Documentation](https://github.com/fairpm/fair-protocol/blob/main/specification.md)

### **The FAIR Web Foundation**

A Linux Foundation directed fund, intended to provide funding for the Fair Package Manager. Formation still in process.

### **Mini-FAIR Repo**

[A WordPress plugin](https://github.com/fairpm/mini-fair-repo) that transforms your site into a FAIR Repository, allowing you to serve packages directly from your own infrastructure into the FAIR system.

### **Node**

Sometimes used to refer to a Repository, a “node” is better understood as anything connected to the FAIR network, be it an Aggregator, a Repository, or a Client/Installer like the FAIR Plugin.

### **Package**

A package is an installable piece of software. Specifically in WordPress and in the current phase of the FAIR Package Manager Project, a package will most often be a plugin or a theme.

### **Package binary**

An asset such as a zip file containing the binary executable code of a package.

### **Planet**

The FAIR's Planet instance ([Venus](https://www.intertwingly.net/code/venus/)) which houses the \[News/Event\] feed displayed in the WordPress Dashboard to FAIR plugin users by default.

### **Repository**

A server that hosts one or more packages and their DIDs. You can set up a repository with the Mini-FAIR Repo plugin.

### **TSC (Technical Steering Committee)**

The *Technical Steering Committee* is the organization responsible for determining the technical requirements and implementation for the FAIR package manager.

