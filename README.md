# Onchain-Grant-Agreements
_Provides templates and guidance to apply Vellum on-chain agreements and signatures to the larger developer grants ecosystem._

Developer grants are a popular way to incentivise development of decentralised applications on various platforms. For maximum transparency and trust, it is preferable if such grants are signed and executed in public - as this provides accountability, and also allows the community to transparently observe the fair execution of the grants, and the disbursement process. Vellum provides effective infrastructure to bring these grant agreements fully on-chain, and also provides the capabilities to allow on-chain execution of contractual terms - for eg., when developers accomplish promised milestones.

Here we provide a template contract for issuing developer grants on Solana. This template can serve as an easy reference and Quickstart for all grants being issued in the Solana ecosystem and beyond, including grants from the Solana Foundation , and various other DAOs and crypto companies.


**Transparency & Accountability using Vellum:**
DAO grants are founded on the premise of fair and transparent disbursal of treasury funds. Token holders like to see where all the funds from the treasury are being spent, and what work output is being achieved via the expenditures. This allows for a rapid and effective feedback loop, allowing DAO treasuries to more efficiently allocate their funds.

Similarly, Developers are taking a big leap of faith when they decide to work for a DAO grant - in some cases in the past, DAOs have failed to pay their developers, despite full, high-quality work being delivered. They sometimes use excuses such as "market conditions" or "hacks", which catch the hard-working developers by surprise. If the whole grant agreement and payment track record of a DAO is visible on chain - that would do wonders for increasing the confidence of developers who are deciding to work full-time under a grant. Moreover, the accountability engendered by such radical transparency, would make a Company wary of ever reneging on their obligations, as the record will be visible for all future developers to see.

Public accountability, via sharing contract links on Twitter, and the permanence of the contract on-chain (they are immutable and un-deletable), further stregnthens the incentives of both parties to mutually co-operate. Such co-operation is essential for the long term growth of various decentralsied ecosystems.


**Post Execution Steps**
In addition to the benefits outlined above, bringing grant agreements on-chain via Vellum allows easy execution of next steps as envisioned in the contract. For example, a multisig can release the payment from the treasury, whenever a developer submits a milestone, and his work has been reviewed. Direct integration with smart contracts will allow the expansion of the effective deal terms between developers and DAOs in the future - for instance, if greater than a certain percentage of DAO members like a particular feature, the developer may be paid a bonus. Such features would be incredibly hard to implement and enforce with traditional agreements, but they become a breeze with on-chain contracts.

Furthermore, in the future, potential dispute resolution via smart contracts (such as Aragon or Kleros Courts) may also be an in-built feature, to further increase the confidence of the counterparties.

**How to use this template**

We provide a simple video demo on how to use Vellum to publish your grant contract on-chain. Note that since Vellum is still in prototype stage, we were unable to actually publish the contract due to some bugs in the website - as seen in the video. However we have no doubt that the team will fix them in no time - and the process would remain the same anyways.

You can find the demo video here: https://youtu.be/rES_0XHnvP4 

In this example we use a template Grant contract, which is also available in this repo. Below we highlight some key terms in the contract that you may want to modify, allowing you to bootstrap your own grant agreements and publish them on-chain with minimal effort.

**Legal Terms for Grants**
To demonstrate our example, we provide a simple example agreement for developing an open-source product in exchange for tokens  - the specific functionalities of such a product are excluded and left up to individual grant creators. We also include the dispute resolution clause, as found on the Solana Foundation website :  - as an example, this can be modified/replaced according to the needs of the grant provider.

"_2. Statements of Work._ " - This must be included with the contract, and should define the scope of work and the terms of the payments as specifically as possible. In particular, the timeline for the work, and the timeline for review and disbursement of tokens, should be clearly specified. In case of unexpected circumstances, these timelines may be adjusted in the future with mutual consent.

"_10. Ownership of Deliverables and Work Product._" - By default, the ownership in the work product is with the company providing the token grant. In case of open source work, public goods, or business partnerships, this provision should be changed accordingly.

"_14. Rights to Tokens._" - In case any portion of tokens are being given in a vested, staked, or otherwise illiquid status, this provision would need to be modified.

"_15. Agreement to Terms of Use._" - Link to your ToS here is advisable

"_16. Independent Contractor._" - In most cases this is preferable, however please consult with your advisors on the optimal legal and taxation strategy.

"_III. DISPUTE RESOLUTION_" - In the future, on-chain dispute resolution and arbitration courts may be included as the first line of dispute resolution, as they are often more convinient when the parties are distributed around the globe.

