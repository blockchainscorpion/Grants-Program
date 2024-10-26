# Polymesh Association Grant Proposal

> This document will be part of the terms and conditions of your agreement and therefore needs to contain all the required information about the project. Don't remove any of the mandatory parts presented in bold letters or as headlines! Lines starting with a `>` (such as this one) can be removed.
>

- **Project Name:** Fractio
- **Team Name:** Fractio
- **Payment Address:** Polymesh (POLYX) payment address. Please also specify the currency.  
- **Level:** 1

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

- Mockups/designs of any UI components: https://fractiodao.netlify.app/

- Data models / API specifications of the core functionality:
- API Architecture: https://claude.site/artifacts/44f1189a-f34a-44e6-b90d-4df6f70de425
- Core APIs:
- Property Management API
  - Property listing and management
  - Documentation and verification
  - Valuation updates
- Investment API
  - Token creation and management
  - Transaction processing
  - Portfolio management
- Analytics API
  - Market data analysis
  - Performance metrics
  - Custom reporting
- Compliance API
  - KYC/AML verification
  - Regulatory reporting
  - Compliance monitoring

 Data Models (example):

Property Asset:
```json
{
  "propertyId": "string",
  "title": "string",
  "location": {
    "address": "string",
    "coordinates": {
      "latitude": "number",
      "longitude": "number"
    }
  },
  "valuation": {
    "currentValue": "number",
    "lastUpdated": "timestamp",
    "historicalValues": ["array"]
  },
  "tokenization": {
    "totalTokens": "number",
    "tokenPrice": "number",
    "remainingTokens": "number"
  },
  "compliance": {
    "regulatoryStatus": "string",
    "requiredDocuments": ["array"],
    "lastAuditDate": "timestamp"
  }
}
```

Token Structure (V1 example):
```
{
  "tokenId": "string",
  "propertyId": "string",
  "tokenType": "enum(EQUITY, REVENUE_SHARE)",
  "ownershipDetails": {
    "percentageOwned": "number",
    "acquisitionDate": "timestamp",
    "acquisitionPrice": "number"
  },
  "restrictions": {
    "lockupPeriod": "number",
    "transferRestrictions": ["array"]
  }
}
```
 An overview of the technology stack to be used:

- Blockchain: ERC1400-compliant tokens
- Smart Contracts: Built for fractional ownership, ensuring real-time regulatory compliance
- Frontend: React.js with Web3 integration
- Backend: Node.js/Express.js
- Blockchain: Polymesh infrastructure with ERC1400 implementation
- Database: PostgreSQL for off-chain data
- Caching: Redis for performance optimization
- Security: KYC/AML compliance mechanisms
- Documentation of core components, protocols, architecture, etc. to be deployed:

- Whitepaper: https://docs.google.com/document/d/1dG5WAeeRjb3BhUbmJShArP4_HsigFIxEluEISZItr3U/edit?usp=drive_link

- Integration of jurisdictional laws in smart contracts (where possible).
- Fractionalized property ownership models: revenue-sharing and equity-sharing


Security Implementation:

- Multi-factor authentication
- Role-based access control
- Real-time transaction monitoring
- Automated compliance checks
- Secure key management
- Regular security audits

PoC/MVP or other relevant prior work or research on the topic:

- DAO - https://fractiodao.netlify.app/, 
- General Demo - https://fractio.live/, 
- CRM Demo - https://fractiocrm.netlify.app/tokenization (you can test it out with a mock property),
- https://github.com/blockchainscorpion/Silver1.git,
- https://www.linkedin.com/posts/activity-7237731304924999680-dcNa?utm_source=share&utm_medium=member_desktop
- What your project is **_not_** or will **_not_** provide or implement
  
  This is a place for you to manage expectations and to clarify any limitations that might not be obvious.
  - Fractio **IS NOT** a meme coin.

### Ecosystem Fit

Help us locate your project in the Polymesh ecosystem / landscape and what problems it tries to solve by answering each of these questions:

- Fractio fits into the Polymesh ecosystem by providing a new avenue for individuals, to invest in real estate.
- Target audiences include real estate agents and developers, family offices, institutional investors, retail investors.
- There are similar projects in the blockchain real estate space, such as:
- RealT, HoneyBricks, RedSwan CRE, and a few other noteable players.
- Fractio differentiates itself by offering both fractionalized revenue-sharing and equity models, while also providing financial education for retail investors, via a learn-to-earn mechanism. And, with a focus on regulatory compliance.

### Polymesh Integration & Cross-Chain Architecture

1. Polymesh Integration:
- Primary tokenization layer utilizing Polymesh's security token infrastructure
- Implementation of Polymesh's compliance framework for KYC/AML
- Integration with Polymesh Capital Platform or Self-developed, including:
  - Asset tokenization
  - Identity verification
  - Regulatory reporting
  - Transfer restrictions
  - Corporate actions

2. Cross-Chain Architecture (via Chainlink CCIP):

  Visual Artifact: https://claude.site/artifacts/7195bf1c-d458-476c-919b-1fd9e0b89549

3. Cross-Chain Implementation Details:

Primary Network (Polymesh):
- Asset origination and primary compliance
- KYC/AML verification
- Initial token issuance
- Regulatory reporting

Chainlink CCIP Integration:
- Message routing between networks
- Cross-chain token transfers
- State synchronization
- Security monitoring

Secondary Networks:

Algorand:
- ASA token representation
- High-performance trading
- Lower transaction costs
- Smart contract execution

Polygon:
- ERC token representation
- DeFi integration capabilities
- Secondary market trading
- Smart contract functionality

## Team :busts_in_silhouette:

### Team members

- Name of team leader: Rich-Allee A John
- Names of team members: In-progress

### Contact

- **Contact Name:** Rich-Allee A John
- **Contact Email:** fractio.team@gmail.com
- **Website:** https://fractio.info/

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

The most recent update can be seet here: # https://fractiodao.netlify.app/

The next steps include launching the MVP using the Polymesh platform, followed by the development of features to enhance investor experience, such as real-time property valuation and dynamic receipt Dnft's.

 ASA token representation
- High-performance trading
- Lower transaction costs
- Smart contract execution

Polygon:
- ERC token representation
- DeFi integration capabilities
- Secondary market trading
- Smart contract functionality

4. Updated Development Roadmap with Technical Deliverables:

### Milestone 1 — Core Infrastructure & Compliance (3 months)
* **FTE:** 3
* **Costs:** 10,000 USD

| Number | Deliverable | Technical Specification |
|--------|-------------|------------------------|
| 1a. | Polymesh Integration | - Setup Polymesh node integration<br/>- Implement ERC1400 token standard<br/>- Deploy compliance smart contracts<br/>- Integrate KYC/AML verification |
| 1b. | CCIP Configuration | - Configure Chainlink CCIP routers<br/>- Set up cross-chain messaging<br/>- Implement token bridge contracts<br/>- Deploy security monitoring |
| 1c. | Network Setup | - Deploy Algorand ASA contracts<br/>- Deploy Polygon ERC contracts<br/>- Implement state synchronization<br/>- Setup monitoring systems |

### Milestone 2 — Token Management & Trading (3 months)
* **FTE:** 3
* **Costs:** 10,000 USD

| Number | Deliverable | Technical Specification |
|--------|-------------|------------------------|
| 2a. | Token Lifecycle | - Implement token minting/burning<br/>- Deploy transfer restrictions<br/>- Setup corporate actions<br/>- Configure distribution rules |
| 2b. | Trading Engine | - Build order matching engine<br/>- Implement price discovery<br/>- Setup liquidity pools<br/>- Deploy trading controls |
| 2c. | Portfolio Management | - Create portfolio tracking<br/>- Implement performance analytics<br/>- Setup reporting engine<br/>- Deploy tax reporting tools |

### Milestone 3 — Advanced Features & Platform Launch (3 months)
* **FTE:** 4
* **Costs:** 10,000 USD

| Number | Deliverable | Technical Specification |
|--------|-------------|------------------------|
| 3a. | Analytics Engine | - Deploy real-time analytics<br/>- Implement ML price prediction<br/>- Setup market analysis tools<br/>- Create custom reports |
| 3b. | DAO Governance | - Deploy voting contracts<br/>- Implement proposal system<br/>- Setup treasury management<br/>- Create governance dashboard |
| 3c. | Platform Launch | - Security audit completion<br/>- Performance optimization<br/>- User acceptance testing<br/>- Production deployment |


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
- Founder: I have also continued to improve my knowledge and experience in the blockchain space by primarily focusing on blockchain development, while establishing partnerships with relevant and key partners in both the real-estate and blockchain space. This is an ongoing initiative.
