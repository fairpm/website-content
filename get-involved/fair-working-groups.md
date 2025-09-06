# FAIR Working Groups

The FAIR Technical Steering Committee (TSC) organizes much of its efforts into Working Groups, often abbreviated WG in general communication. Each group has a specific mandate for its area of responsibility, and may hold separate meetings to plan and coordinate work. Some WGs are temporary, while others are permanent to address an ongoing need.

See also: [GitHub \- fairpm/tsc: Technical Steering Committee information and documentation](https://github.com/fairpm/tsc) 

## **Active Working Groups**

### **AspireCloud Working Group**

**Special Note:** This working group was formed in collaboration with [AspirePress](https://aspirepress.org), who began work in October 2024 before the formation of FAIR. Future development of certain AspirePress projects will continue under the FAIR project, with names retained in recognition of the early work of the AspirePress team, most of whom continue to work on these projects under FAIR.

* **Type:** Permanent  
* **Began:** July 2025 (October 2024\)  
* **Chat:** \#wg-aspirecloud  
* **Mandate**:  
  * (1) Develop server-side software to index packages and respond to API calls in the [WordPress.org](http://wordpress.org) format to serve download urls from a mirror of the [WordPress.org](http://wordpress.org) software repository.  
  * (2) Support queries using the FAIR Protocol to provide DID-based package management and to present a unified set of search results for packages from the [WordPress.org](http://wordpress.org) mirror and any other FAIR Repository it indexes. (e.g., using the Mini-FAIR Repo Plugin)  
  * (3) Coordinate with other FAIR software projects to support requirements as needed between projects.

#### **AspireCloud WG Projects**

##### **AspireCloud**

* **Description:** The primary index for the AspirePress mirror of the [WordPress.org](http://wordpress.org) repository and initial FAIR Aggregator.  
* **Repository:** [/AspireCloud](https://github.com/aspirepress/AspireCloud)  
* **Documents:** [/aspirecloud](https://github.com/fairpm/aspirecloud)

**Related AspirePress Projects**

* **Description:** The AspirePress group works with and within FAIR on several related projects which do not have their own WG. For example, these include:  
* AspireSync, which works in a network- and server-friendly fashion to build an initial mirror of packages and keep it updated with packages available from [WordPress.org](http://wordpress.org) as changes occur.  
* AspireExplorer, a browseable listing of plugins and themes for download from AspirePress mirror  
* AspireHub, a proof-of-concept WordPress plugin which can act as an Aggregator for selectively indexing a manually-curated list of packages.  
* **Repositories:** [/aspirepress](https://github.com/aspirepress)

### **Community Working Group**

* **Type:** Permanent  
* **Began:** June 2025  
* **Chat:** \#wg-community  
* **Mandate:** Suggest and oversee community-driven or community-focused initiatives

### **Community WG Projects**

**Admin News Feed**

* **Repository:** [/planet](https://github.com/fairpm/planet)

### **FAIR Working Group**

* **Type:** Permanent  
* **Created:** June 2025  
* **Chat:** \#wg-fair  
* **Mandate:** General matters pertaining to the FAIR Protocol and other TSC matters.

#### **FAIR WG Projects**

##### **FAIR Protocol**

* **Repository:** [/fair-protocol](https://github.com/fairpm/fair-protocol)

##### **FAIR Plugin**

* **Description:** (Inherited) Client/Installer plugin created under the Technical Independence WG.  
* **Chat:** \#fair-plugin  
* **Repository:** [/fair-plugin](https://github.com/fairpm/fair-plugin)

##### **Mini-FAIR Repository Plugin**

**Description:** A WordPress plugin with a sample implementation of a package repository supporting the FAIR Protocol. The plugin facilitates DID creation and canonical hosting of its code, which can be installed using its DID.

* **Repository:** [/mini-fair-repo](https://github.com/fairpm/mini-fair-repo)

### **Infrastructure Working Group**

* **Type:** Permanent  
* **Began:** August 2025  
* **Mandate:** Maintenance and development of the technical infrastructure  
* **Chat:** \#wg-infrastructure

#### **Infrastructure WG Projects**

##### **FAIR Infrastructure**

* **Repository:** (currently this is a private repo for security reasons)

**FAIR Server**

* **Repository:** [/server](https://github.com/fairpm/server)

### **Website Working Group**

* **Type:** Permanent  
* **Began:** July 2025  
* **Mandate:** Management of the code and architecture of public-facing websites  
* **Chat:** \#wg-website

#### **Website WG Projects**

**FAIR Theme**

* **Repository:** [/fair-parent-theme](https://github.com/fairpm/fair-parent-theme)

## **Archived Working Groups**

### **Technical Independence**

* **Type:** Temporary  
* **Term:** Spring 2025 to June 5, 2025  
* **Mandate:** Create a WordPress plugin capable of replacing services supplied by [WordPress.org](http://wordpress.org), or redirect to alternate sources via API or RSS as appropriate.  
* **Status:** Closed, Successful.

**Result:** A proof-of-concept plugin was developed to redirect software installations to AspireCloud, replacing other functions which relied on [WordPress.org](http://wordpress.org)’s API with ones run locally within the plugin or from independent third-party sources. The FAIR Plugin was shipped and [announced publicly at the Alt-Ctrl event in Basel, Switzerland](https://www.youtube.com/watch?v=owH0xMGsuCw) with the announcement of the formation of FAIR and collaboration with AspirePress.

To support the news feed in the WordPress Admin dashboard, a Planet instance was also created. The FAIR Plugin and Planet instance were handed to other Working Groups to maintain once the goals of the Technical Independence WG were achieved.

