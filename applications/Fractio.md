# Polymesh Association Grant Proposal

> This document will be part of the terms and conditions of your agreement and therefore needs to contain all the required information about the project. Don't remove any of the mandatory parts presented in bold letters or as headlines! Lines starting with a `>` (such as this one) can be removed.
>

- **Project Name:** Fractio
- **Team Name:** Fractio
- **Payment Address:** Polymesh (POLYX) payment address. Please also specify the currency.  
- **Level:** 1, 2 or 3

> ⚠️ *The combination of your GitHub account submitting the application and the payment address above will be your unique identifier during the program. Please keep them safe.*

## Project Overview :page_facing_up:

If this application is in response to an [RFPs](https://github.com/PolymeshAssociation/Grants-Program/tree/main/rfp-proposal), please indicate this on the first line of this section.

If this is an application for a follow-up grant (the continuation of an earlier, successful Polymesh grant), please provide name and/or pull request of said grant on the first line of this section.

### Overview

Please provide the following:

- Project Name: Fractio
- Fractio aims to create a democratized, fractionalized real estate investment platform. By leveraging the ERC1400 standard on blockchain, Fractio facilitates fractional ownership of real estate, enabling retail investors to access previously unreachable assets with a fraction of the cost, while maintaining compliance with global regulatory frameworks.

- Fractio integrates with Polymesh by utilizing its security token standards to ensure transparency, compliance, and efficiency in real estate transactions.
- The team is passionate about bridging the gap between retail investors and high-barrier real estate markets, using blockchain technology to revolutionize access to property investment globally.

### Project Details

We expect the teams to already have a solid idea about your project's expected final state. Therefore, we ask the teams to submit (where relevant):

Fractio is a platform that uses blockchain technology to tokenize real-world assets, specifically real estate, providing opportunities for fractional ownership. By offering these assets to retail investors, Fractio lowers the barrier to entry in property investments.

- Mockups/designs of any UI components: https://fractio.live/
- Data models / API specifications of the core functionality: https://fractioapi.netlify.app/
- An overview of the technology stack to be used
-  Blockchain: ERC1400-compliant tokens
- Smart Contracts: Built for fractional ownership, ensuring real-time regulatory compliance
- Frontend: Web3 integrated interface for retail and institutional investors
- Backend: Blockchain-based real estate tokenization and management
- Security: KYC/AML compliance mechanisms
- Documentation of core components, protocols, architecture, etc. to be deployed:
- Integration of jurisdictional laws in smart contracts (via polymesh capital platform)
- Fractionalized property ownership models: revenue-sharing and equity-sharing
- PoC/MVP or other relevant prior work or research on the topic: https://fractio.live/
- What your project is **_not_** or will **_not_** provide or implement
  - This is a place for you to manage expectations and to clarify any limitations that might not be obvious.
  - Fractio will NOT initially have or launch a token. Our tokens will be issued per property, or property / asset collection. We are not a meme coin, nor will we attempt to position ourselves as such.

### Ecosystem Fit

Help us locate your project in the Polymesh ecosystem / landscape and what problems it tries to solve by answering each of these questions:

- Fractio fits into the Polymesh ecosystem by providing a new avenue for individuals, to invest in real estate.
- Target audiences include real estate agents and developers, family offices, institutional investors, retail investors.
- There are similar projects in the blockchain real estate space, such as:
- RealT, HoneyBricks, RedSwan CRE, and a few other noteable players.
- Fractio differentiates itself by offering both fractionalized revenue-sharing and equity models, while also providing financial education for retail investors, via a learn-to-earn mechanism.

## Team :busts_in_silhouette:

### Team members

- Name of team leader: Rich-Allee A John
- Names of team members: In-progress

### Contact

- **Contact Name:** Rich-Allee A John
- **Contact Email:** fractio.team@gmail.com
- **Website:** https://fractio.live/

### Legal Structure

- **Registered Address:** 20-22 Wenlock Road, London, UK, N1 7GU
- **Registered Legal Entity:** Fractio-UK LTD

### Team's experience

Rich-Allee John, Founder and CEO, has a background in blockchain development, and tokenization of personal assets. Fractio was born out of his vision to lower the barrier to entry for everyday individuals in real estate investments. With a foundation in blockchain development and tokenizing personal assets, Rich-Allee is now applying that experience to real estate, aiming to tokenize and fractionalize properties for a broader investor base.

### Team Code Repos

Provide the address of the github org and repos where the completed project will be hosted
- https://github.com/Fractio-UK

Please also provide the GitHub accounts of all team members. If they contain no activity, references to projects hosted elsewhere or live are also fine.

- (https://github.com/blockchainscorpion) Rich-Allee A John


### Team LinkedIn Profiles (if available)

- https://www.linkedin.com/in/rich-allee-antonio-j-7724a394/

## Development Status :open_book:

Fractio will leverage the Polymesh Capital platform as the core infrastructure for tokenization services, offering a streamlined approach to fractional ownership of real estate assets. The Fractio team will focus on developing external APIs and additional platform features, working closely with Polymesh to ensure seamless integration.

The main service will focus on tokenizing real estate assets and facilitating a private marketplace for verified and accredited investors. Investors can purchase tokens to either fund property developments or receive a share of the revenue generated by the properties.

While Fractio has not yet tokenized real estate assets, our founder has experience in tokenizing personal assets. And has been bootsrtapping a Proof of concept platform for the past 9 months.

The most recent update can be seet here: https://fractio.live/

The next steps include launching the MVP using the Polymesh platform, followed by the development of features to enhance investor experience, such as real-time property valuation and dynamic receipt Dnft's.

## Development Roadmap :nut_and_bolt:

This section should break the development roadmap down into milestones and deliverables. To assist you in defining it, we have created a document with examples for some grant categories [here](../docs/grant_guidelines_per_category.md). Since these will be part of the agreement, it helps to describe _the functionality we should expect in as much detail as possible_, plus how we can verify and test that functionality. Whenever milestones are delivered, we refer to this document to ensure that everything has been delivered as expected.

Below we provide an **example roadmap**. In the descriptions, it should be clear how your project is related to Polymesh. We _recommend_ that teams structure their roadmap as 1 milestone ≈ 1 month. We also _recommend_ that you build up the scope of the project in a way that it can be completed in max 3 months. If the entirety of your project is going to take more than 3 months, please submit it's parts that can be completed in 3 months as one grant project. This helps us move forward quickly and deliver features quickly.

For each milestone,

- make sure to include a specification of your software. _Treat it as a contract_; the level of detail must be enough to later verify that the software meets the specification.
- include the amount of funding requested _per milestone_.
- include documentation (tutorials, API specifications, architecture diagrams, whatever is appropriate) in each milestone. This ensures that the code can be widely used by the community.
- provide a test suite, comprising unit and integration tests, along with a guide on how to set up and run them.
- commit to providing Dockerfiles for the delivery of your project.
- indicate milestone duration as well as number of full-time employees working on each milestone.
- **Deliverables 0a-0d are mandatory for all milestones**, and deliverable 0e at least for the last one. If you do not intend to deliver one of these, please state a reason in its specification (e.g. Milestone X is research oriented and as such there is no code to test).

> :zap: If any of your deliverables is based on somebody else's work, make sure you work and publish _under the terms of the license_ of the respective project and that you **highlight this fact in your milestone documentation** and in the source code if applicable! **Teams that submit others' work without attributing it will be immediately terminated.**

### Milestone 1 - Legal & Regulatory Compliance
### | Aspect | Details |
|--------|---------|
| **Estimated Duration** | 6 months |
| **FTE** | 1 |
| **Costs** | $45000 |

| Number | Deliverable | Specification |
|--------|-------------|----------------|
| 0a. | License | Unlicenced / FCA |
| 0b. | Documentation | Complete legal framework documentation and compliance reports |
| 0c. | Testing Guide | Provide regulatory testing guide to ensure FCA compliance and alignment with global regulations |
| 1. | Legal Framework | Secure the necessary legal and regulatory compliance, ensuring adherence to FCA regulations for tokenized real estate assets in the UK |
| 2. | Platform Compliance | Establish the platform's legal structure to operate as a compliant real estate tokenization service in the UK and Europe |


### ## Milestone 2 — Platform Setup and Integration with Polymesh Capital

| Item | Details |
|------|---------|
| **Estimated Duration:** | 6 months |
| **FTE:** | 4 |
| **Costs:** | $555,000 USD (funded by Pree-seed round) |

| Number | Deliverable | Specification |
|--------|-------------|---------------|
| 0a. | License | Polymath Capital |
| 0b. | Documentation | Publish API integration documentation with Polymesh Capital |
| 0c. | Testing Guide | Provide unit and integration testing documentation for platform setup |
| 0d. | Docker | Dockerfiles for Polymesh integration and initial property tokenization testing |
| 1. | Platform Setup | Configure the white-label Polymesh Capital platform for Fractio's tokenization services, including wallet and smart contract execution integration |
| 2. | Initial Property Listings | Tokenize and list the first five properties on the platform to kickstart fractional investment offerings


## Future Plans

Please include here

- Fractio will continue expanding its tokenized real estate offerings globally and nurturing private marketplaces that serve investors of different classes, while exploring new asset classes such as art and luxury goods.
- As the platform grows, community-driven governance features will allow token holders to shape the platform’s future. The focus will be on maintaining legal compliance while scaling platform capabilities, and ensuring investor confidence and regulatory alignment.
- We will leverage in-person networking events to market our service to the relevant audiences, while cultivating an interconnected online and in-person community of investors.
- Personal branding through audience specific story telling and narratives.


## Additional Information :heavy_plus_sign:

**How did you hear about the Grants Program?** Recommendation by previous course I attended (Gritnova Global Campus).

Here you can also add any additional information that you think is relevant to this application but isn't part of it already, such as:

- As the founder, I have already experimented with tokenizing real world assets, utilizing the concept to tokenize my own personal assets to garner greater clarity around the requirements for the process.
- Founder: I have also continued to improve my knowledge and experience in the blockchain space by primarily focusing on blockchain development, while establishing partnerships with relevant and key individuals in both the real-estate and blockchain space. This is an ongoing effort.
