# Welcome to My Personal Wiki

This knowledge hub documents my learning journey across payments, DLT, blockchain, digital assets and tokenization.  
It focuses on how emerging technologies are changing the way money and financial assets are issued, transferred, settled and recorded.  
The objective is to connect traditional financial infrastructure with new tokenized financial ecosystems.  
Topics are explained in simple terms with a focus on practical financial-services use cases.

# Basics of DLT — Distributed Ledger Technology

DLT is a technology that allows multiple authorised participants to maintain and share the same transaction record.  
Instead of one central database controlling all records, copies of the ledger can exist across multiple network participants.  
Transactions are validated according to agreed rules before being added to the ledger.  
Blockchain is one form of DLT, but DLT can also use other architectures.

#### Different DLT Architectures: Blockchain, DAG, Hashgraph & Holochain

**Blockchain** groups transactions into blocks that are cryptographically linked together in sequence.  
**DAG — Directed Acyclic Graph** allows transactions to reference other transactions without organising them into traditional blocks.  
**Hashgraph** uses a different consensus approach where network participants share information about transactions with each other.  
**Holochain** takes a more agent-centric approach where participants maintain their own records rather than relying on one global ledger.

#### Key Benefits of DLT: Shared Ledger, Immutability, Transparency, Speed and Programmability

A **shared ledger** allows multiple organisations to work from a common version of transaction data.  
**Immutability** makes confirmed records difficult to alter without detection, while transparency improves traceability and auditability.  
DLT can reduce reconciliation and potentially improve transaction and settlement speed.  
**Programmability** enables smart contracts to automate business rules and can support atomic transactions where linked actions succeed or fail together.

#### Types of Networks: Permissioned and Permissionless Networks

A **permissionless network** allows almost anyone to participate, submit transactions and potentially validate activity; Bitcoin and Ethereum are examples.  
A **permissioned network** restricts participation to approved organisations or users.  
Financial institutions often prefer permissioned networks because identity, access, privacy and governance can be controlled.  
Some modern financial infrastructures also combine public blockchain technology with permissioned access to financial products.

# Basics of Assets

An asset is something that has economic value and can potentially be owned, transferred, invested in or used as collateral.  
Assets may be physical, such as property and gold, or financial, such as shares and bonds.  
They may also be digital, such as cryptocurrencies or digitally issued securities.  
Tokenization provides a way of representing rights to certain assets digitally on DLT infrastructure.

#### Asset Classes

Asset classes group investments with similar financial characteristics.  
Common asset classes include **equities, government and corporate bonds, cash, commodities, property and investment funds**.  
Alternative assets can include private credit, infrastructure, artwork and other collectibles.  
Many of these assets are now being explored for tokenization.

# Basics of Tokens

A token is a digital representation of value, ownership, rights or access recorded on a digital ledger.  
A token can represent something digitally native, such as cryptocurrency, or an existing real-world/financial asset.  
Smart contracts can define how tokens are created, transferred, restricted and redeemed.  
The rights represented by a token depend on its legal and contractual structure, not simply on the technology.

## Types of Tokens

Tokens can be classified in different ways depending on their **technical structure** and **economic purpose**.  
For example, one classification considers whether tokens are interchangeable or unique.  
Another classification considers whether the token provides access, represents an investment, functions as money or gives voting rights.  
The same token can sometimes have characteristics belonging to more than one category.

#### Classification by Technological Structure: Fungible, Non-Fungible, Semi-Fungible and Soulbound Tokens

**Fungible tokens** are interchangeable—for example, one unit is equivalent to another unit of the same token.  
**Non-fungible tokens (NFTs)** represent unique items or records, where each token can have its own identity.  
**Semi-fungible tokens** may initially be interchangeable but later become unique depending on their lifecycle or use.  
**Soulbound tokens** are designed to remain linked to a particular wallet or identity and are normally non-transferable.

#### Classification by Purpose and Utility: Utility, Security, Payment and Governance Tokens

**Utility tokens** provide access to a service, platform or functionality.  
**Security tokens** represent financial or investment rights and may represent shares, bonds, funds or other regulated securities.  
**Payment tokens** are designed primarily to transfer or store value, while **governance tokens** may allow holders to participate in decisions about a digital protocol.  
The regulatory treatment depends on the token's characteristics, rights and jurisdiction.

# Asset Tokenization

Asset tokenization is the process of creating a digital token that represents ownership or rights relating to an asset.  
For example, a government bond, investment fund, property or gold holding could have a corresponding digital representation on a ledger.  
Smart contracts can help manage issuance, transfers, investor restrictions, corporate actions and redemption.  
Tokenization can potentially improve settlement efficiency, transparency, programmability and access to financial assets.

# Tokenized Deposit

A tokenized deposit is a digital representation of a **commercial-bank deposit** on programmable or DLT-based infrastructure.  
It remains a liability of the issuing commercial bank, similar in economic concept to money held in a normal bank account.  
It can potentially support 24/7 transfers, programmable payments and settlement of tokenized financial assets.  
Unlike many stablecoins, the customer has a direct deposit claim against the issuing bank.

# Tokenized Reserves

Tokenized reserves represent **central-bank money or reserve balances** on programmable/DLT infrastructure.  
They are primarily relevant to regulated financial institutions rather than ordinary retail customers.  
They could allow banks to settle tokenized transactions using central-bank money while operating on modern digital infrastructure.  
This is particularly important for wholesale payments, securities settlement and cross-border transactions.

# Settlement Architectural Model: Tokenized Deposits and Tokenized Reserves

Consider **Bank A** sending £1 million in tokenized deposits to a customer of **Bank B**.  
The customer-facing value can move as tokenized commercial-bank deposits, while the obligation between Bank A and Bank B can be settled using tokenized central-bank reserves.  
A shared programmable platform can coordinate the commercial-bank-money and central-bank-money legs.  
This model aims to preserve the traditional two-tier monetary system while making settlement more programmable and potentially more efficient.

**Simple model:** `Customer → Tokenized Deposit → Bank A → Tokenized Reserves → Bank B → Tokenized Deposit → Beneficiary`

# Programmable Platform and Smart Contract

A programmable platform allows financial transactions to follow predefined software-based business rules.  
A **smart contract** is code that automatically executes actions when specified conditions are satisfied.  
For example, it might release payment only after confirming that an investor is eligible and the corresponding security is ready for transfer.  
This can automate parts of payment, settlement, compliance, servicing and asset-transfer processes.

# Atomicity

Atomicity means that several related transaction steps are treated as **one indivisible transaction**.  
Either all required actions complete successfully, or none of them complete.  
For example, when buying a tokenized bond, the bond token and payment can potentially move simultaneously.  
This is known as **Delivery versus Payment (DvP)** and helps reduce the risk that one party delivers while the other does not pay.

# Stablecoins

Stablecoins are digital tokens designed to maintain a relatively stable value, commonly by referencing a fiat currency such as the **US dollar, euro or pound sterling**.  
For example, an issuer may design one token to maintain a value of approximately USD 1.  
Depending on their design, stability may be supported by cash, bank deposits, government securities or other collateral.  
Stablecoins can be used for blockchain-based payments, trading, settlement and movement of value between digital-asset platforms.

# Regulation of Stablecoins

Stablecoin regulation generally aims to ensure that digital money is issued, backed and operated safely.  
Rules can cover **issuer authorisation, reserve assets, safeguarding, redemption rights, governance, disclosures and operational resilience**.  
Issuers and service providers may also need to comply with AML, sanctions, KYC and financial-crime requirements.  
Regulatory approaches differ across jurisdictions, including the UK, EU and US, and continue to evolve as stablecoins become more integrated with mainstream finance.
