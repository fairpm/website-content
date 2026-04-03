# Trust in a Federated System

Text Required:
Challenges with a decentralized trust model
Differences between centralized & decentralized trust

One of the issues FAIR solves is removing the single-point of failure for package hosting, deployment, and distribution. With that federated distribution comes new challenges, such as trust. When you only have one server pushing out packages, you can do a lot to ensure that one site is trustworthy, but when you open the door to anyone, you introduce a new risk point.

In order to mitigate those risks, FAIR is introducing a Moderation Labeling Service. Moderation does not mean evaluating the code for security, but properly labeling and tagging packages for what they are. FAIR makes use of existing technology, such as DID protocol, DNS TXT entries, and BlueSky’s moderation (labeling) system to help establish provenance (proving that a package is managed by the rightful owners) and also to allow for further integration down the line.

Through the Moderation service, other noted and trusted entities (e.g. a security firm) could make their own add-on service to automatically flag an insecure or abandoned package.

## Trust Signals: The Primary FAIR Labeler

Text Required:
Lift & edit description from Github
Link to Moderation/labelling spec on Github

The roadmap for FAIR includes the establishment of a required labelling service available at multiple levels in the network, or supply chain. The requirements for trust are being drafted carefully to ensure supply chain security to the greatest reasonable extent. Upon completion, trust labels will be visible to end users to assist in their software selections. Sample trust labels could include “Verified Source”, “Trusted Author”, “Unverified Publisher”, “Untrusted Repository”, “Suspended Package”, or some other variety of signals. These are yet to be determined based on our review and drafting of specific business requirements to support assignment of such labels.

To bridge the gap to the availability of fully-implemented trust labels throughout the network, FAIR envisions a phased approach to facilitate establishing trust as the federated network is opened up to additional participants. Bearing in mind that many users are already installing and updating software using the FAIR Plugin and network, we begin with a near-closed system where all recognized connections can be trusted. At this stage, federation begins by invitation.

Once we have established the level of verification which is achievable through automated methods and human review, federation can be opened up through an application process. This application process can be refined in steps toward making it as open as possible to join the federated network, with assignment of trust labels, perhaps beginning with something along the lines of “New: Trust Not Yet Assigned”.

Trust is tracked in the network by DID. Since packages in the WordPress mirror repository do not have DIDs assigned to them, AspireCloud attaches a Web:DID to make them available and indexable using the FAIR Protocol. These are presented as a true copy of the package from the official (canonical) WordPress repository. All such packages inherit a level of trust from the process of submitting, verifying, and publishing the software to the WordPress repository, which is extended to the AspirePress mirror as a verified true copy of the software. Package authors or publishers who wish to transition to DID-based installers through FAIR will have a path to verify their package and inherit the existing trust level it carries from the WordPress repository to a new canonical home in the federated network.

