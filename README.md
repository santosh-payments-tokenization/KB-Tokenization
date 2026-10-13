# 1. Welcome to My Personal Wiki

This knowledge hub documents my learning journey across payments, DLT, blockchain, digital assets and tokenization.  
It focuses on how emerging technologies are changing the way money and financial assets are issued, transferred, settled and recorded.  
The objective is to connect traditional financial infrastructure with new tokenized financial ecosystems.  
Topics are explained in simple terms with a focus on practical financial-services use cases.

# 2. Basics of DLT — Distributed Ledger Technology

DLT is a technology that allows multiple authorised participants to maintain and share the same transaction record.  
Instead of one central database controlling all records, copies of the ledger can exist across multiple network participants.  
Transactions are validated according to agreed rules before being added to the ledger.  
Blockchain is one form of DLT, but DLT can also use other architectures.

## 2.1 Different DLT Architectures

### 2.1.A Blockchain

Blockchain groups transactions into blocks that are cryptographically linked together in sequence.  
Each new block normally contains a reference to the previous block, helping protect the integrity of historical records.  
Bitcoin and Ethereum are well-known examples of blockchain-based networks.  
Blockchain can be public, private or permissioned depending on the use case.
Most useful domains: Banking and payments, capital markets, asset tokenization, digital assets, trade finance, supply chain, identity and healthcare records.

### 2.1.B Directed Acyclic Graph — DAG

DAG allows transactions to reference or validate other transactions without grouping everything into traditional blocks.  
Transactions can be processed in parallel rather than waiting for a single sequence of blocks.  
This can potentially improve scalability and transaction throughput.  
Different DAG-based networks use different approaches to consensus and validation.
Most useful domains: Internet of Things (IoT), machine-to-machine payments, micropayments, logistics, high-volume transaction networks and real-time data exchange.

### 2.1.C Hashgraph

Hashgraph uses a different distributed-consensus model rather than a conventional blockchain structure.  
Participants share information about transactions and the history of communication between nodes.  
The model aims to achieve fast consensus and high transaction throughput.  
Hedera is one well-known implementation associated with Hashgraph technology.
Most useful domains: Enterprise payments, financial services, supply chain, tokenized assets, sustainability/ESG tracking, identity and high-throughput business applications.

### 2.1.D Holochain

Holochain follows an agent-centric architecture rather than maintaining one identical global ledger for everyone.  
Each participant maintains their own chain of activity and shares relevant information with other participants.  
Validation rules determine whether information can be accepted by the wider network.  
It is structurally different from traditional blockchain systems.
Most useful domains: Peer-to-peer applications, decentralised social networks, digital identity, community platforms, collaborative data sharing and user-controlled data ecosystems.

## 2.2 Key Benefits of DLT

### 2.2.A Distributed / Shared Ledger

Multiple authorised participants can access a common transaction record.  
This can reduce the need for each institution to maintain and reconcile separate copies of the same information.  
Participants can work from a shared or synchronised source of transaction data.  
This may simplify some multi-party financial processes.

### 2.2.B Immutability

Once a transaction has been validated and recorded, it becomes difficult to alter without detection.  
Cryptographic techniques help protect the integrity of historical records.  
This can improve auditability and transaction traceability.  
Immutability does not necessarily mean that absolutely nothing can ever be changed; governance and technical design still matter.

### 2.2.C Transparency

DLT can provide authorised participants with greater visibility into transaction status and ownership records.  
This can reduce uncertainty between multiple parties involved in a financial transaction.  
Public blockchains may provide broad transparency, while permissioned networks can restrict visibility.  
The level of transparency depends on network design and privacy requirements.

### 2.2.D Speed

DLT can reduce delays caused by multiple intermediaries and reconciliation processes.  
Transactions may potentially be processed and settled closer to real time.  
This is particularly relevant to cross-border payments, securities settlement and collateral movement.  
Actual speed still depends on the network, controls and settlement model.

### 2.2.E Programmability

DLT platforms can support programmable rules through smart contracts.  
Smart contracts can automatically validate conditions and trigger financial actions.  
For example, payment can be released only when a tokenized asset is ready for transfer.  
Programmability can support automation, conditional payments and atomic settlement.

## 2.3 Types of DLT Networks

### 2.3.A Permissionless Networks

A permissionless network allows almost anyone to participate and submit transactions.  
In some networks, users can also participate in transaction validation or consensus.  
Bitcoin and Ethereum are common examples.  
These networks prioritise openness and decentralisation.

### 2.3.B Permissioned Networks

A permissioned network restricts participation to approved organisations or users.  
Identity, access, governance and privacy can be controlled.  
Banks and financial institutions often prefer this model for regulated financial activity.  
Examples include many institutional blockchain and DLT platforms.

# 3. Basics of Assets

An asset is something that has economic value and can potentially be owned, transferred, invested in or used as collateral.  
Assets may be physical, financial or digital.  
Examples include property, gold, shares, bonds, cash and cryptocurrencies.  
Tokenization allows certain rights to assets to be represented digitally.

## 3.1 Asset Classes

### 3.1.A Equities

Equities represent ownership in a company.  
Examples include ordinary shares and preference shares.  
Investors may receive dividends and voting rights depending on the share type.  
Equities can potentially be issued or represented as security tokens.

### 3.1.B Fixed Income

Fixed-income assets include government bonds and corporate bonds.  
Investors typically lend money to an issuer in return for interest and repayment of principal.  
Government bonds, Treasury securities and corporate debt can potentially be tokenized.  
Tokenization may automate parts of issuance, settlement and servicing.

### 3.1.C Cash and Cash Equivalents

Cash includes traditional bank deposits and central-bank money.  
Cash equivalents include highly liquid short-term financial instruments.  
Emerging forms include tokenized deposits, CBDCs and regulated stablecoins.  
These instruments are important for the cash leg of financial settlement.

### 3.1.D Commodities

Commodities include gold, silver, oil and agricultural products.  
Ownership or claims on these assets can sometimes be represented digitally.  
Tokenized gold is a common example of commodity tokenization.  
The physical asset normally remains held by a custodian or vault provider.

### 3.1.E Real Estate

Real estate includes residential, commercial and industrial property.  
Tokenization can potentially represent ownership, fractional interests or investment rights.  
Legal ownership structures remain important even when blockchain is used.  
The token does not replace property law.

### 3.1.F Investment Funds

Investment funds pool money from multiple investors.  
Examples include mutual funds, money-market funds, private funds and ETFs.  
Fund units or shares can potentially be represented on blockchain.  
Several institutional tokenized-fund products already exist globally.

### 3.1.G Alternative Assets

Alternative assets include private credit, infrastructure, artwork and collectibles.  
These assets often have lower liquidity than publicly traded securities.  
Tokenization may provide new ways to record ownership and improve transferability.  
Legal, custody and valuation arrangements remain essential.

# 4. Basics of Tokens

A token is a digital representation of value, ownership, rights or access recorded on a digital ledger.  
A token may represent something digitally native or an existing financial or physical asset.  
Smart contracts can define how tokens are created, transferred, restricted and redeemed.  
The legal rights associated with a token depend on its underlying contractual structure.

# 5. Types of Tokens

Tokens can be classified according to their **technical structure** and their **economic purpose or utility**.

## 5.1 Classification by Technological Structure

### 5.1.A Fungible Tokens

Fungible tokens are interchangeable with other units of the same token.  
One unit generally has the same characteristics and value as another unit.  
Currencies and many tokenized deposits or stablecoins are examples.  
ERC-20 is a common Ethereum standard for fungible tokens.

### 5.1.B Non-Fungible Tokens — NFTs

NFTs represent unique digital items or ownership records.  
Each token can have its own identity and metadata.  
They can represent artwork, certificates, luxury goods or unique assets.  
ERC-721 is a widely used Ethereum NFT standard.

### 5.1.C Semi-Fungible Tokens

Semi-fungible tokens can behave like fungible tokens during part of their lifecycle and unique tokens later.  
For example, multiple identical event tickets may initially be interchangeable.  
After use, each ticket may become a unique historical record.  
ERC-1155 can support this type of token model.

### 5.1.D Soulbound Tokens

Soulbound tokens are designed to remain associated with a particular wallet or identity.  
They are normally non-transferable.  
Potential use cases include qualifications, memberships, identity credentials and reputation records.  
They are conceptually different from normal tradeable tokens.

## 5.2 Classification by Purpose and Utility

### 5.2.A Utility Tokens

Utility tokens provide access to a platform, service or functionality.  
They are often used within a particular digital ecosystem.  
They may provide usage rights rather than ownership of an underlying financial asset.  
Their regulatory treatment depends on how the token is structured.

### 5.2.B Security Tokens

Security tokens represent financial or investment rights.  
They may represent shares, bonds, fund units or other regulated securities.  
They are generally subject to relevant securities regulation.  
Tokenization changes the technology used to represent the security, not necessarily its legal status.

### 5.2.C Payment / Currency Tokens

Payment tokens are intended primarily to transfer or store value.  
Cryptocurrencies such as Bitcoin are examples of payment-oriented digital assets.  
Stablecoins can also function as payment tokens.  
Some tokenized commercial-bank money may also support payment and settlement use cases.

### 5.2.D Governance Tokens

Governance tokens allow holders to participate in decisions relating to a digital protocol or ecosystem.  
Voting may include decisions about software changes, fees or treasury allocation.  
Governance arrangements vary widely between platforms.  
Holding a governance token does not automatically mean ownership of a company.

# 6. Asset Tokenization

Asset tokenization is the process of creating a digital token representing ownership or rights relating to an asset.  
Examples include tokenized bonds, shares, investment funds, property and gold.  
Smart contracts can help automate issuance, transfers, restrictions, servicing and redemption.  
Tokenization can potentially improve settlement efficiency, transparency, programmability and asset accessibility.

## 6.1 Typical Asset-Tokenization Lifecycle

### 6.1.A Asset Identification  
Identify the asset that will be tokenized.

### 6.1.B Legal Structuring  
Define what legal rights the token represents.

### 6.1.C Custody  
Arrange safekeeping of the underlying asset where applicable.

### 6.1.D Token Creation  
Create the digital representation using a token or smart-contract framework.

### 6.1.E Issuance  
Issue or mint tokens to approved investors.

### 6.1.F Transfer  
Allow tokens to move between eligible participants.

### 6.1.G Servicing  
Manage dividends, coupons, reporting or other asset lifecycle events.

### 6.1.H Redemption  
Redeem or cancel tokens when ownership is converted back, repaid or terminated.

# 7. Tokenized Deposits

A tokenized deposit is a digital representation of a commercial-bank deposit on programmable or DLT-based infrastructure.  
It remains a liability of the issuing commercial bank.  
Tokenized deposits can potentially support 24/7 payments, programmable transactions and settlement of tokenized assets.  
They can combine traditional commercial-bank money with modern digital-ledger functionality.

## 7.1 Key Characteristics

### 7.1.A Issuer  
Commercial bank.

### 7.1.B Liability  
Liability of the issuing bank.

### 7.1.C Value  
Usually denominated in an existing fiat currency such as GBP, EUR or USD.

### 7.1.D Use Cases  
Payments, treasury, cross-border transfers and tokenized-asset settlement.

# 8. Tokenized Reserves

Tokenized reserves represent central-bank money or reserve balances on programmable/DLT infrastructure.  
They are primarily designed for regulated financial institutions rather than ordinary consumers.  
They may allow banks to settle tokenized transactions using central-bank money.  
This can support wholesale payments, securities settlement and cross-border transactions.

## 8.1 Key Characteristics

### 8.1.A Issuer  
Central bank.

### 8.1.B Holders  
Normally eligible commercial banks or financial institutions.

### 8.1.C Purpose  
Wholesale settlement.

### 8.1.D Key Benefit  
Combines central-bank settlement safety with programmable infrastructure.

# 9. Settlement Architectural Model Using Tokenized Deposits and Tokenized Reserves

Consider Bank A sending £1 million in tokenized deposits to a beneficiary at Bank B.  
The customer-facing liability can move as commercial-bank tokenized deposits.  
The obligation between Bank A and Bank B can be settled using tokenized central-bank reserves.  
A shared programmable platform can coordinate these settlement legs.

## 9.1 Simplified Settlement Flow

### 9.1.A Customer Initiation  
Customer at Bank A initiates payment.

### 9.1.B Tokenized Deposit Transfer  
Bank A transfers or redeems the customer's tokenized deposit.

### 9.1.C Interbank Settlement  
Bank A transfers tokenized reserves to Bank B.

### 9.1.D Beneficiary Credit  
Bank B issues or credits the corresponding tokenized deposit to the beneficiary.

### 9.1.E Final Position

**Customer → Tokenized Deposit → Bank A → Tokenized Reserves → Bank B → Tokenized Deposit → Beneficiary**

# 10. Programmable Platforms and Smart Contracts

A programmable platform allows financial transactions to follow predefined software-based business rules.  
A smart contract is software that automatically performs actions when defined conditions are satisfied.  
Smart contracts can validate eligibility, transfer assets, release payments and enforce restrictions.  
They can support payments, settlement, custody and asset servicing.

## 10.1 Examples of Smart-Contract Rules

### 10.1.A Balance Validation  
Check whether sufficient funds or tokens exist.

### 10.1.B Investor Eligibility  
Confirm that the receiving investor is approved.

### 10.1.C Asset Locking  
Temporarily lock assets before settlement.

### 10.1.D Payment Release  
Release funds once settlement conditions are satisfied.

### 10.1.E Redemption  
Burn or cancel a token following redemption.

# 11. Atomicity

Atomicity means that multiple connected transaction steps are executed as one indivisible transaction.  
Either all actions complete successfully or none of them complete.  
This reduces the risk that one party delivers an asset while the other party fails to pay.  
Atomicity is particularly important for tokenized securities settlement.

## 11.1 Common Atomic Settlement Models

### 11.1.A Delivery versus Payment — DvP

A financial asset and payment are exchanged together.  
Example: a tokenized bond is transferred only if payment is simultaneously transferred.

### 11.1.B Payment versus Payment — PvP

Two different currencies are exchanged together.  
Example: GBP is transferred only if EUR is simultaneously received.

# 12. Stablecoins

Stablecoins are digital tokens designed to maintain a relatively stable value.  
They are commonly referenced to fiat currencies such as USD, EUR or GBP.  
Depending on their design, they may be backed by cash, bank deposits, government securities or other reserve assets.  
Stablecoins can support blockchain payments, trading and tokenized-asset settlement.

## 12.1 Main Types of Stablecoins

### 12.1.A Fiat-Backed Stablecoins

Backed by traditional financial assets such as cash or government securities.

### 12.1.B Crypto-Collateralised Stablecoins

Backed by other crypto assets held as collateral.

### 12.1.C Algorithmic Stablecoins

Attempt to maintain stable value through software-based mechanisms rather than full traditional reserve backing.

### 12.1.D Regulated Bank / E-Money Stablecoins

Issued within regulated financial or electronic-money frameworks.

# 13. Regulation of Stablecoins

Stablecoin regulation aims to ensure that digital money is issued, backed and operated safely.  
Regulation can cover reserve assets, redemption rights, governance, consumer protection and operational resilience.  
Issuers and service providers may also need to meet KYC, AML, sanctions and financial-crime requirements.  
Regulatory frameworks differ across jurisdictions and continue to evolve.

## 13.1 Main Regulatory Areas

### 13.1.A Issuer Authorisation  
Defines who is legally allowed to issue stablecoins.

### 13.1.B Reserve Requirements  
Defines the assets that must support the stablecoin.

### 13.1.C Safeguarding  
Protects customer and reserve assets.

### 13.1.D Redemption Rights  
Defines whether holders can exchange tokens for fiat money at par.

### 13.1.E AML / KYC  
Requires customer identification and financial-crime controls.

### 13.1.F Operational Resilience  
Requires secure, reliable and recoverable technology infrastructure.

### 13.1.G Disclosure and Transparency  
Requires issuers to explain reserves, risks and token-holder rights.

---

This hierarchy is much easier to navigate in GitHub Pages because you can now reference specific concepts such as **Section 5.1.A – Fungible Tokens**, **Section 9.1.C – Interbank Settlement**, or **Section 11.1.A – Delivery versus Payment** rather than referring only to general headings.
