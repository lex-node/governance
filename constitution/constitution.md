[DRAFTING NOTES:

    1. waiting for feedback from team, but I likely need to revise the new  code deference provisions re: Council smart contract since they are currently using Rinkelby smart contract with manual approval of vote minting, etc.; possibly will bifurcate between current and future arrangement and provide code-deference structure for the latter that kicks in if/when activated by council 

    2. fix clause / section numbering periodically
    3. should have section on nodes and providing that persons operating nodes consent to being slashed (can also later repurpose some of that language re: slashing for Constitutional violations if that eventually becomes a thing)
    4. discuss/research possibilities re: Council as unincorporated nonprofit association and best jurisdiction (some U.S. states provide limited liability for members of such an association)
    5. get feedback from team re: what happens with voting tokens when a governance stake that formerly satisfied criteria for minting voting tokens become un-satisfied (e.g., due to large aggregate council-wide governance stake increase after voting tokens minted on basis of lower aggregate governance stake)
    6. tighten up contract boilerplate, arbitration provisions (class action waiver), choice of law question, etc. 
    7. has the first member of the foundation resigned so that it is in fact ownerless?
    8. has the foundation board passed the resolution called for by 1.6(a) of the foundation articles (" a resolution of the board determining that the DAO is operational and is able to pass DAO resolutions"?)

# THE POCKET NETWORK CONSTITUTION

This Pocket Network Constitution (this **Constitution** ) is a legally binding agreement governing the Pocket DAO. The Pocket DAO governs the Pocket Network and Pocket Blockchain and the use of the Pocket Technologies in connection therewith. 

# Mission Statement

The members of the Pocket DAO are united together in the mission to build censorship-resistant technology that will lay the foundation for reorganizing the world’s institutions towards a more equitable, hyper-connected, interplanetary future.

# Principles

1. **Credible Neutrality:** No one User should be favored over any other within their demographic. For example, Protocol Upgrades which favor Nodes over Apps are neutral, but Protocol Upgrades which favor specific App types (e.g. exchanges) or specific Apps (e.g. Binance) are not neutral.
2. **Sustainable Decentralization:** The Pocket Network should optimize for as many unaffiliated and autonomous Nodes as possible, because this reinforces the resilience and censorship-resistance of the service, but this should not be rushed at the cost of the sustainable growth of Pocket Network.
3. **User-Centrism:** The Pocket Network is specialized to provide reliable decentralized infrastructure to Users. We must therefore continue to optimize for 1) User adoption and 2) the qualities that contribute to reliable infrastructure: network redundancy, robust data integrity, data sovereignty, minimal latency, minimal downtime, and minimalist engineering.
4. **Freedom of Movement:** The Pocket Network should be accessible to both Apps and Nodes. Equally, all Pocket Network stakeholders or participants should enjoy the right to exit.
5. **Optionality:** Operating a Node should incur no more costs than the cost of operation. All other responsibilities, e.g. participation in the Council, should be optional.
6. **Agnosticism:** The Pocket Protocol should maintain neutrality as a middleware protocol. While the governance of Pocket Network may be reliant from time to time on other networks or tools, the system itself should retain a level of modularity that facilitates switching out components with minimal friction.
7. **Cross-Chain Diplomacy:** The Pocket Protocol is a middleware protocol, which means the members of the Pocket DAO will come from a wide range of blockchain communities. Pocket DAO participants should leave tribalism at the door: i.e., they should refrain from engaging in political debates that are not directly relevant to improving the Pocket Technologies, Pocket Protocol or Pocket Network.
8. **Consensual Collaboration:** While the Pocket Network Council is relatively permissionless, this does not mean anyone is owed any duties by the Council or has any rights with respect to the Council. Proposals will be assessed on their merits alone, including Contributors’ fitness to fulfill the proposal. Likewise, Contributors are not required to let any other Contributor work with them, unless the Council has approved a proposal to that effect.

* The Principles are ranked in order of priority.
* Decisions [of???] must be made according to their furtherance of the Principles. 
* When deciding between alternatives, these alternatives shall be prioritized according to the ordering of the Principles listed above, with higher-ranking Principles to always take priority over lower-ranking Principles. 
* Lower-ranking Principles should only be sacrificed in favor of higher-ranking Principles if a Pareto optimal state has been achieved, i.e. it is not possible to improve one Principle without making another Principle worse off. Until then, the Council shall seek to make only Pareto improvements, where Principles are improved without making any other Principles worse off.3
* Once it is no longer possible to optimize any Principle without sacrificing another, this Constitution should be amended to introduce minimum satisfaction thresholds on each Principle.
* Stakeholder rights at any given moment, as defined by the values of On-Chain parameters, may justifiably be sacrificed in the furtherance of the Principles, because it is intended that the Principles, if achieved, will ensure maximum utility to maximum stakeholders.
* The Principles should be designed, in all future iterations of this Constitution, to optimally achieve the mission of the Pocket DAO stated under "Mission Statement" above.
# Covenants
## 4. Pocket DAO Governance
4.1. Governance of the Pocket DAO is an emergent phenomenon arising from the decision-making and activities of a variety of User demographics and other Persons, including: 
* the Pocket Network Foundation;
* the Pocket Network Council and Council Members; 
* the Pocket Development Company and other developers of Pocket Core and other Pocket Technologies; 
* POKT holders; and
* Node operators.
### Legislature / Council
#### Nature & Functions of Council
4.2. The legislative function of the Pocket DAO is performed by the Pocket Network Council, which is the unincorporated nonprofit association of Council Members [NOTE TO DRAFT: DISCUSS "UNINCORPORATED NONPROFIT ASSOCIATION" & JURISDICTIONAL ISSUES]. The Council: (a) monitors, supervises and governs the Foundation, as further set forth in Section [] hereof; (b) holds and governs the Council On-Chain Treasury, which is the aggregate of all unspent POKT DevFund Awards allocated from POKT Block Awards; and (c) considers, holds votes with respect to and approves or denies Pocket Improvement Proposals (PIPs), Pocket Ecosystem Proposals (PEPs) and Parameter Update Proposals (PUPs). 
#### Council Membership
4.4. A Person shall be deemed a **Council Member** if and only if: (a) such Person has deposited POKT to the Council Multisig to create a Governance Stake; (b) such Governance Stake is active; and (c) such Person has minted and continues to hold and control one or more Voting Tokens with respect to such Governance Stake. 
4.5. The Governance Stake of a Person shall be deemed active if and only if at least one of the following conditions precedent is satisfied with respect thereto:
        (a) Such Person is a **Trusted Account Holder** (i.e., such Person has achieved [(and at each relevant time, maintains)] an Elite level in the Pocket Community Game or has been vouched for by a Council Champion [(which voucher has not been revoked)]); or
        (b) such Governance Stake is a **Trust-Minimized Stake** (i.e., [at each relevant time,] such Governance Stake comprises a number of POKT at least equal to (A) the total aggregate number of POKT on deposit in the Council On-Chain Treasury (or the relevant temporary trust, if applicable) with respect to which Voting Tokens have been minted and remain outstanding at such time; divided by (B) the number of Council Members at such time). 
        [NOTE TO SELF/DRAFT: what happens if someone holds Voting Tokens and their Governance Stake subsequently becomes 'inactive' (e.g., due to staked POKT dipping below the variable trust-minimization threshold)?]

4.7. POKT comprising: (a) an active Governance Stake that has not been promptly utilized to mint Voting Tokens; or (b) a Governance Stake that has not promptly been activated may, in the sole and absolute discretion of the Council, be deemed abandoned. In the sole and absolute discretion of the Council, POKT deemed to be abandoned may be: (i) returned to the depositing address (less applicable transaction fees and setoffs, if any); (ii) treated in accordance with any applicable laws of property escheatment; (iii) left indefinitely in the Council Multisig; or (iv) treated in any other manner that does not violate this Constitution or applicable law. 
4.8. Each Council Member shall vote his, her or its Voting Shares and otherwise exercise the rights, powers and perquisites of a Council Member on a reasonably informed basis and in good faith, taking into account the Pocket Principles. Each Council Member shall not sell his, her or its Voting Shares or any of the other rights, powers and perquisites of being a Council Member or accept any compensation, reward, reimbursement or incentive for voting such Council Member's Voting Shares or using such rights, powers and perquisites. 
#### Council Proposals
4.10. Proposals to be voted upon by the Council must be submitted solely by Council Members. The immediately preceding sentence shall not be deemed to limit the right, power or discretion of a Council Member to submit such a proposal on behalf of or in cooperation with another User or User demographic, provided that such Council Member independently supports such proposal on its own merits without regard to any personal or business-related affiliation or pecuniary gain with respect to such other User(s) or such proposal and has not breached Section 4.8. 
4.11. Proposals are of three main types: Pocket Improvement Proposals (PIPs), Pocket Ecosystem Proposals (PEPs) and Parameter Update Proposals (PUPs), each as defined hereinafter.
4.12 Each proposal shall be made by any Council Member initiating a Signaling Vote or an Executive Vote with respect to such proposal, properly identified as a PIP, PEP or PUP. 
4.13. Moderators may edit proposal forum posts only for the purpose of assigning numbers, categorizing, and updating the phases/statuses of proposals. Contractors of the Pocket Development Company will be the first Moderators, but anyone can apply to become a Moderator, or propose the removal of existing Moderators, by submitting a PIP.
#### Council Member Representations
Each Person who creates a Governance Stake or otherwise becomes a Council Member hereby represents and warrants, to and for the benefit of the Council, the Council Members and the Users, as follows, as of the date on which such Person becomes a Council Member and as of each date on which such Person remains a Council Member: 
4.14 Status. If I am an individual, I am of legal age in the jurisdiction in which I reside and a, of sound mind and body. If I am another type of Person (such as a business entity), I am duly organized, validly existing and in good standing under the laws of the jurisdiction in which I am organized, and I have all requisite power and authority for a to carry on my business and operations.
4.15 Power and Authority. I have all requisite capacity, power and authority to accept the terms and conditions of this Constitution and to carry out and perform my obligations under this Constitution. This Constitution constitutes a legal, valid and binding obligation, enforceable against me in accordance with its terms.
4.16 No Conflict; Compliance with Law. My entering into this Constitution and creating my Governance Stake becoming a Council Member does not constitute, and would not reasonably be expected to result in (with or without notice, lapse of time, or both) a breach, default, contravention or violation of any Law applicable to me, or any contract or agreement to which I am a party or by which I am bound.
4.17. Not Subject to Sanctions. I am not, and am not owned or controlled by, or acting on behalf of, any other Person who is, identified on any list of prohibited parties under any Law or by any Governmental Authorities, such as, for example, the lists maintained by the United Nations Security Council, the U.S. government (including the U.S. Treasury Department's Specially Designated Nationals list and Foreign Sanctions Evaders list), the European Union (EU) or its member states, and the government of my home country. I am not, and am not owned or controlled by, or acting on behalf of, any other Person who is, located, ordinarily resident, organized, established, or domiciled in Cuba, Iran, North Korea, Sudan, Syria, the Crimea region (including Sevastopol) or any other country or jurisdiction against which the U.S. maintains economic sanctions or an arms embargo. The POKT provided for my Governance Stake are not derived from, and do not otherwise represent the proceeds of, any activities done in violation or contravention of any Law.
4.18. No Claim, Loan, Ownership Interest or Investment Purpose. I understand and agree that the deposit of my POKT, the creation of my Governance Stake and my becoming a Council Member do not: (a) represent or constitute a loan or a contribution of capital to, or other investment in, the Pocket Foundation, the Pocket Development Company or any other Person; (b) provide me with any ownership interest, equity, security, or right to or interest in the assets, rights, properties, revenues or profits of, or voting rights whatsoever in, the foregoing Persons or any other Person; or (c) creates or implies any fiduciary or other agency relationship between me and any of the foregoing Persons or any of their respective directors, officers, employees, agents, equity hodlers or Affiliates. I am not entering into this Constitution, depositing POKT, creating my Governance Stake or becoming a Council Member for the purpose of making an investment, but solely wish to participate in the Council as a free and voluntary contribution of my time and attention to the Pocket DAO.
4.19. Non-Reliance. I am knowledgeable, experienced and sophisticated in using and evaluating the Pocket Network, Pocket Technologies and similar networks and technologies. I have conducted my own thorough independent investigation and analysis of the Pocket Network and Pocket Technologies and Pocket DAO in determining to deposit POKT, create a Governance Stake and become a Council Member, and I have not relied upon any information, statement, omission, representation or warranty, express or implied, written or oral, made by or on behalf of the Pocket DAO, the Council, any Council Members or any other person in making such decision or any other decision relating to the Pocket DAO or the other matters contemplated by this Constitution. 
### PIPs
**Pocket Improvement Proposals (PIPs)** are proposals to improve Pocket Core or the other Pocket Technologies or the Pocket Network or Pocket Blockchain or Council governance procedures. Without limiting the generality of the foregoing, PIPs include Protocol Upgrades and Governance Upgrades. 
4.14. PIPs should not contain multiple new specifications that could feasibly be divided into separate proposals without losing their meaning. This policy is intended  to prevent omnibus proposals whereby unpopular proposals are pushed through by bundling them with popular proposals.
4.15. PIP votes will last 7 days and pass with Majority Approval, unless otherwise specified in this Constitution (e.g. see Supermajority Approval requirement in ‘Constitutional Amendments’).
4.16. The execution of successful PIPs should be delayed by a period equal to the Unbonding Period plus one day, to give Bonded Users time to unbond and exit the network before the upgrade is executed.
### PEPs
4.17. **Pocket Ecosystem Proposals (PEPs)** are proposals to provide funding out of the Council On-Chain Treasury to or form agreements with other Pocket DAO participants. 
4.18. Because the Pocket DAO is a non-profit multi-stakeholder organization, the Council shall only approve PEPs in the form of grants.
### PUPs
4.20.**Parameter Update Proposals (PUPs)**  are proposals to change the value of a given parameter of the Pocket Blockchain, including proposals to change: 
    (a) the monetary policy of the Pocket Blockchain (i.e., economic parameters such as BaseRelaysPerPOKT and StabilityAdjustment);
    (b) the whitelist of blockchain networks supported by the Pocket Blockchain (i.e., the SupportedBlockchains parameter); and
    (c) the consensus mechanisms of the Pocket Blockchain (i.e., consensus parameters such as UnstakingTime, MaximumChains and FraudulentRelayBatchPenalty).
A full list of parameters is maintained at : https://governance.docs.pokt.network/docs/submit-a-pup
4.21. Each PUP should specify: 
    (a) Current Value: What is the current value of the parameter? For whitelists, just leave this field blank
    (b) New Value: What is the proposed value of the parameter? For whitelists, just list the addresses/IDs you wish to add or remove
    (c) Abstract: a ~200 word description of the parameter value being proposed and why.
    (d) Motivation: Explain in detail why the new parameter value is better than the current parameter value. What is the intended effect of changing the parameter value?
    (e) Rationale: Provide detailed justification behind why the specific value was selected
    (f) Dissenting Opinions: Acknowledge all opinions which disagree with the rationale of this proposal.
    (g) Analyst(s): Where relevant, provide details of the analyst(s) whose work leads to the recommended value. How are they qualified?
4.22. Off-chain parameters signaling the pricing preferences of the Council (the USDRelayTargetRange and the ReturnOnInvestmentTarget) will be governed using Conviction Signaling, whereby the Conviction-weighted average of all values will be submitted.
4.23. The following discretionary On-Chain parameters will be governed by the Foundation in order to fulfil the targets set by the Council: BaseRelaysPerPOKT and StabilityAdjustment. 
The Foundation will anchor around the Council’s targets according to a 14-day average; if the actual relay price exceeds this target range temporarily, the Foundation may ignore it, but if the range is exceeded on average for 14 days, the Foundation must respond.
4.24. The SupportedBlockchains parameter will not be governed through voting, but instead according to the Network ID configuration choices of [Council Members] [SHOULD THIS INSTEAD REFER TO VALIDATOR NODES?]. The Foundation will add Network IDs to the whitelist if 5% of [Council Members] have configured their App or Node to include the Network ID. [HOW DO WE KNOW ALL COUNCIL MEMBERS HAVE AN ‘APP OR NODE’? SEEMS LIKE THIS SHOULD JUST BE DECIDED BY VALIDATOR NODES, NOT NECESSARILY ONES THAT ALSO ARE COUNCIL MEMBERS] PUPs can still be submitted for this parameter to draw attention to new eligible Network IDs.
4.25. All other On-Chain parameters not specified above will be governed using Majority Approval, in votes lasting 7 days.
#### Removing Council Members
4.26. Council Members can be removed by the Council for [5 violations of this Constitution] [WHY MAKE IT SO CONSTRAINED? I THINK THE COUNCIL SHOULD BE ALLOWED TO REMOVE A COUNCIL MEMBER BY MAJORITY VOTE OR SUPERMAJORITY VOTE (PICK YOUR POISON—I GUESS IT SHOULD MATCH THE RE-ADMITTANCE STANDARD IN THE NEXT SECTION (SO, SUPERMAJORITY VOTE)).]. 
4.27. Council Members who were removed pursuant to the preceding Article 4.11 will not be permitted to re-join unless they first successfully achieve Supermajority Approval in a Signaling Vote. 

#### Right to Exit

4.28. While the barrier to entering the Council is intended to provide a robust defense against time-based attack vectors such as vote renting, the barrier to exit is intentionally minimal. Any Council Member can exit the Council at any time by burning their Voting Token, unless a proposal to burn their token is already pending.

#### Redeeming/Burning Governance Stakes
4.29. If a Council Member burns such a Voting Token, the corresponding Governance Stake will be redeemed and returned to such Council Member. If a Council Member has a Voting Token burned by the Council in compliance with this Constitution, the corresponding Governance Stake will be forfeited (burned).
4.30. Whichever account has the Council On-Chain Treasury permissions will be responsible for executing redemptions/burning.

### Executive / Foundation
#### Nature & Functions of Foundation
4.31. The executive function of the Pocket DAO is performed by the Pocket Network Foundation, which is a Cayman Islands foundation company limited by guarantee. The Foundation is governed by its Articles of Association, a copy of which is available at https://github.com/pokt-network/governance/blob/master/foundation/Pocket-Network-Foundation-Articles-of-Association-Highlighted.pdf (the **Foundation Articles**). Without limiting the generality of the immediately following Article [4.x], the Foundation's objectives include:
  * serving as a fiduciary agent of the Council
  * stewarding the Pocket Technologies and Pocket Network, including Pocket Core
  * requesting funds from the Council for specific projects that have strategic value to the Pocket Technologies or Pocket DAO, by submitting PEPs.

#### Foundation Articles; Responsibility to Council

4.32.  The following is only a summary of certain provisions of the Articles and is subordinated in its entirety to the full text of the Articles; in the event of any conflict or inconsistency between this Constitution and the Articles, the actual text of the Articles shall prevail: 
* The Articles refer to the Council as the "DAO" and require the Council's approval of substantially all actions of the Foundation, including the appointment and removal of Foundation directors and supervisor
* The Articles require the Foundation directors not to hold any administrative or other position in the Council (other than the position of general Council Member by virtue of being a Council Member) and to observe, implement, carry out and execute with best efforts any and all resolutions of the Council, except as otherwise required by their fiduciary duties and applicable law. 
* The Articles require the Foundation directors to provide the Council with notices and other information concerning the Foundation's business and affairs, the appointment/remove of alternate directors or secretaries, any resignations of directors or supervisors, the directors' discharge of their duties and exercise of their powers and such other information as may be required by the Council.
##### Signaling Era; Future Governance Designs
4.30. The Foundation multi-sig will hold all ACL permissions at launch, but the Council may work to automate (and thus disintermediate) the Executive function by building a cross-chain integration between the Pocket Network and the Council Smart Contract, with appropriate amendments to this Constitution. The period before automatic cross-chain execution is achieved will be referred to as the Signaling Era. During the Signaling Era, the Council Smart Protocol is not a comprehensive method of governance, but the Council may utilize the Council Smart Contract as a convenient method for holding votes or granting Voting Tokens, but the operation and results of operation of the Council remain subject to the good faith interpretation and discretion of the ACL and thus the Foundation. At the end of the Signaling Era, the Foundation shall pass a resolution pursuant to Section 1.6(a) of the Foundation Articles determining that the Council is operational and able to pass resolutions. 
##### Transaction Batching
4.33. By default, the Foundation will batch Governance Transactions on a weekly basis, unless an alternative schedule is specified in this Constitution.
### Judiciary
4.33. The judiciary functions of the Pocket DAO are performed by Aragon Court. 
4.34. Any Council Member may challenge actions, if they think the action violates this Constitution. The outcome of disputes under this Judiciary function will be determined per ‘3. Arbitration’.


### Diplomatic & Regulatory / Nodes
4.35. The diplomatic and regulatory functions of the Pocket DAO are performed by the Nodes. Nodes receive, transmit and propagate transactions and data through the Pocket Network, between the Pocket Network and other blockchain networks and between applications and the Pocket Network and other blockchain networks. Validator Nodes enforce the Pocket Protocol and ensure the Pocket Blockchain conforms to its rules by proposing blocks and validating the blocks proposed by other Validator Nodes. 
4.36. Each Node, solely by connecting to the Pocket Network, shall be deemed to consent in all respects to the Pocket Protocol, the results of operations of which shall be final and binding upon each Node. Without limiting the foregoing, each Validator Node shall be deemed to consent in all respects to the slashing of such Validator Node's staked POKT in accordance with the Pocket Protocol and hereby waives, relinquishes and releases any and all claim against any Person arising from the loss of staked POKT in accordance with the Pocket Protocol. 

### Citizenry / Users

4.37. The citizenry of the Pocket DAO are End-Users in their capacities as such. End-Users utilize, rely upon and enjoy the benefits of the Pocket Network, and pay transaction fees and taxes (dilution through Block Rewards) where applicable. **End-Users** may be POKT holders, Persons who relay transactions to POKT Nodes for transmission to other blockchain networks or applications that rely on the Pocket Network or its Nodes.   [NOTE: consider just making it *Users*. I think the only delta is that Users would include persons who run Nodes, which seems okay].
## 5. Liability
5.1. The Foundation is a distinct legal entity representing the Pocket DAO in various matters, under supervision of the Council. This means the Pocket DAO accepts no liability and all disputes, including claims of tort, must be directed to the Foundation.
5.2. Users shall be liable for losses caused by false or misleading attestations, such as fraudulent relay proofs, and shall forfeit any stake thereby according to the consensus rules of Pocket Core.
5.3. Software developers (such as the Pocket Development Company) are contracted by the Foundation on behalf of the Pocket DAO to develop Pocket Core. Because the Foundation defer to the Council, the Council is ultimately responsible for reviewing new software and approving Protocol Upgrades. Further, the Validator Nodes are responsible for accepting Protocol Upgrade Governance Transactions approved by the Council, and Users consent to the Validator Nodes' decisions through their use of the blockchain in accordance with Article 2.1. Therefore, the Users agree to hold software developers harmless for unintentional mistakes made in the expression of contractual intent, whether or not said mistakes were due to actual or perceived negligence.

## 7. Finances

7.1. Contributors agree to pay taxes on all Pocket DAO-related income in whichever jurisdiction they reside. The Pocket DAO will not be held liable for any neglect in this matter.

7.2. The Pocket DAO will only accept incoming payments to its treasury in the form of Governance Stakes and the Pocket Network Block Reward.
For outgoing payments to recipients who may have not consented to this Constitution, the DAO will send funds piecemeal from the Council On-Chain Treasury to the Foundation's On-Chain multi-signature wallet for specific PEPs.

7.3. It is forbidden to propose or approve unconditional general distributions of the Council On-Chain Treasury to token holders, which may be misconstrued as dividends.

7.4. The Foundation may on the Council's behalf exchange POKT for another cryptocurrency or token for the purpose of using external blockchains.

## 8. Amendments

### Constitutional Amendments

8.1. This Constitution may be amended according to Majority Approval in the PIP process, unless otherwise specified in ‘Immutability’ and ‘Undo’ below.

#### Executing Constitutional Amendments

8.7. All relevant permission holders must act to execute new versions of the Constitution by updating Pocket Core and/or relevant off-chain tools, platforms, or mechanisms, within 7 days, or else they will be removed from the permissions they hold.

#### Crediting Constitutional Amendments

8.8. Authors of constitutional amendments will be listed chronologically as authors of the Constitution.

#### Tracking Constitutional Amendments

8.9. Amendments which modify existing clauses will add a 0.01 increment to the Constitution version for every modification. Amendments which introduce/remove clauses will add a 0.1 increment to the Constitution version for every modification.

#### Upgrading the Council

8.10. The Foundation will hold these permissions and will therefore be responsible for any Council upgrades that have been approved in the PIP process.

8.11. If an upgrade involves introducing a new platform, which may use different addresses, the Foundation will be responsible for configuring the new platform, which Council Members will join by re-staking their Governance Stake with their new addresses in the transaction memo.

### Pocket Core Amendments

8.12. Protocol Upgrades (including changes to the ACL) will be approved by the Council according to the PIP process.

8.13. Upgrades are pushed to Nodes in a dormant state then, once the Council has signaled approval, the Foundation will activate the upgrade retroactively by submitting a Governance Transaction.

8.14. Pocket Core's upgrade process is permissive. Node operators can keep pocket-runner on their Pocket Core installation if they consent to automatically updating their Nodes according to the Council's decisions. If they decide they want to refuse the Council's decisions, they can replace pocket-runner with their own versioning software and ignore Governance Transactions. This power is subject to a Tendermint consensus test, whereby 66%+ of the nodes must refuse the Council's decision in order for the blockchain to continue to operate normally without forking.

### Foundation Amendments

8.15. Because Supervisor decisions are not valid unless ratified by the Council, no upgrade can be made to the Foundation's Articles without the Council first signaling approval.

## 9. Initialization

9.1. No decision by the Council shall be legitimate until the founding Council Members have unanimously approved this Constitution. [NOTE: HAS THIS OCCURRED?]

9.4. The App and Node UnstakingTime parameters will be changed from 21 days to 1 hour once Decentralization Day has been achieved, subject to Majority Approval.

9.5. The option to become a Council Champion through committing a Trust-Minimized Stake will be in place at least until the Pocket Community Game has been in operation for one full season, after which the Council will hold a majority vote on whether to keep it.

## Interpretation, Dispute Resolution, Etc. 

### Interpretation
1.1. The Mission Statement and Principles are non-binding recitals provided for informational purposes only; provided, however, that in the event of any ambiguity in the interpretation of the plain language of the Articles, the resolution of such ambiguity shall take into account the Mission Statement and Principles.
1.2. Any rule of construction to the effect that ambiguities are to be resolved against the drafting party shall not be applied in the construction or interpretation of this Constitution. 

### Binding Nature of Constitution
2.1. Each Person who directly or indirectly uses, operates, executes, installs, sends transactions to or receives transactions from or accesses: (a) the Pocket Network (whether through Pocket Core or any other software); (b) the Pocket Blockchain; or (c) any of the other Pocket Technologies in connection with the Pocket Network or Pocket Blockchain (each such Person, a ***User**) is, without any further any action or agreement, automatically deemed to have consented to and agreed to be bound by and become a party to this Constitution.
2.2. Without limiting the generality of Section 2.1, entry into the Council, and the signing of this Constitution required to mint oneself a Voting Token, or to submit any other action to the Council, shall constitute consent to the terms of this Constitution.
2.3. All service providers who stake or sign transactions on behalf of Users, or develop tools to facilitate staking or signing by Users, shall make every effort to inform said Users of this Constitution's terms. Service providers shall be liable for losses resulting from failure to do this.

### Entire Agreement

2.4. This Constitution constitutes the entire agreement between the Parties with respect to the subject matter hereof and supersedes all prior agreements and understandings, both written and oral, among the Parties (or any of them) with respect to the subject matter hereof.

### Severability

2.5. In the event any one or more of the provisions of this Constitution is for any reason held to be invalid, illegal or unenforceable, in whole or in part or in any respect, or in the event that any one or more of the provisions of this Constitution operate or would prospectively operate to invalidate this Constitution, then and in any such event, such provisions only will be deemed null and void and will not affect any other provision of this Constitution and the remaining provisions of this Constitution will remain operative and in full force and effect and will not be affected, prejudiced, or disturbed thereby.

### Notices

2.6. Any notice required or permitted by this Constitution will be deemed sufficient when published on the Pocket Blockchain or through other electronic means reasonably sufficient to notify each and all of the Parties hereto concurrently.

### Arbitration

3.1. Unless otherwise stated in this Constitution, any controversy between members of the Council arising out of or in connection with this Constitution shall be submitted to Aragon Court for resolution under its public arbitration rules, as amended from time to time.

3.2. Controversies arising out of or in connection with actions that are bound programmatically to this Constitution, must be submitted before the action executes; if not, the controversy shall be deemed resolved in favor of the action. [?]

3.3. In the event that Aragon Court is not accessible, the Foundation shall refer the dispute to the International Chamber of Commerce for arbitration according to their rules. 

3.4. By consenting to this Constitution, all Parties waive their right to resolve any controversy in any manner other than defined in this Constitution. EACH PARTY HEREBY IRREVOCABLY WAIVES ALL RIGHT TO TRIAL BY JURY IN ANY ACTION, PROCEEDING OR COUNTERCLAIM WHETHER BASED ON CONTRACT, TORT OR OTHERWISE ARISING OUT OF OR RELATING TO THIS CONSTITUTION, THE DAO, OR THE MATTERS CONTEMPLATED HEREBY OR THE ACTIONS OF SUCH PARTIES IN THE NEGOTIATION, ADMINISTRATION, PERFORMANCE AND ENFORCEMENT HEREOF.

[NOTE TO SELF: CHOICE OF LAW?]
[NOTE TO SELF: BEEF UP ARBITRATION PROVISIONS ('final, binding and determinative resolution' etc.)]


# Definitions
* **Access Control List (ACL):** a permission framework used by Pocket Core to control which accounts can submit Governance Transactions, such as transferring funds from the Council On-Chain Treasury, burning funds in the Council On-Chain Treasury, updating On-Chain parameters, and activating Protocol Upgrades.
* **Aragon Court:** a decentralized court system that incentivizes internet jurors to rule fairly on subjective disputes and will perform the Judiciary function of the Pocket DAO
* **Apps:** Pocket Network accounts that stake POKT to submit API requests (relays) to the Pocket Network
* **Bonded:** the state of an App or Node that has staked POKT
* **Burning Tokens:** the permanent removal of POKT from circulation
* **Constitution:** has the meaning set forth in the Preamble
* **Contributors:** anyone who is doing work in service of the Pocket DAO and/or the Pocket Network ecosystem or Pocket Technologies, such as proposal recipients, bounty recipients, and protocol developers
* **Council:** the unincorporated nonprofit association of Council Members, also known as "The Pocket Network Council"
* **Council Blockchain:** the blockchain designated by the Council for deployment of the Council Smart Contract. The initial Council Blockchain is the Ethereum “Rinkelby” testnet--i.e., the blockchain with "chainID:4" on "networkID:4" as recognized by a majority of nodes running Go Ethereum, the Official Golang implementation of the Ethereum protocol at https://github.com/ethereum/go-ethereum. There shall be only one Council Blockchain at any given time.
* **Council Champion:** a person who has been voted to become eligible to become a Council Member by a [current] Trusted Account Holder [NOTE: DO THEY HAVE TO CHAMPIONS OR CAN THEY BE ANY COUNCIL MEMBERS?] via Supermajority Approval. The Council Champion designation is intended to enable trusted community members to access a cheaper Governance Stake without having to play the Pocket Community Game. 
* **Council Member:** has the definition set forth in Section 4.4.
* **Council Multisig:** the address designated by the Council to hold Governance Stakes during the Signaling Era, which is currently 6386713deb27b609daad5e2e32ee6591753e5f4e on the Pocket Network. The Council Multisig is controlled by the ACL. 
* **Council On-Chain Treasury:** the account designated by the Council to hold POKT DevFund Awards. The initial Council On-Chain Treasury is address 6386713deb27b609daad5e2e32ee6591753e5f4e on the Pocket Network. 
* **Council Protocol:** the voting, accounting and other rules and procedures embodied in the Council Smart Contract
* **Council Smart Contract:** : (a) shall initially be the source code at https://rinkeby.etherscan.io/address/0x954Ef520DD4B969C5fd3709Bbf8b258A871639dd#code as deployed to 0x6581bFd757FF2a3333F9DD2c49C6A5CBb31C5633 as deployed on the Council Blockchain; and (b) shall subsequently be any other source code that (i) is designated by the Council to serve as the 'Council Smart Contract’ under this Constitution and (ii) is deployed to a specified public key address on a specified public blockchain and specified blockchain network, each as designated by the Council. There shall be only one Council Smart Contract at any given time
* **Decentralization Day:** a legal milestone for the decentralization of the Pocket Network, marked by the existence of 100 independently operated Nodes and the passing of the Council’s first vote (9.1)
* **Executive:** the functions of the Pocket DAO that are responsible for executing the decisions made by the Legislature
* **Executive Vote:** any vote made by the Council with the intent of executing an action, both On-Chain and within the Council’s platforms
* **Governance Stake:** POKT deposited with the Council On-Chain Treasury (or a temporary trust, if the funds have been transferred to the trust by the Foundation), for so long as such POKT remains so deposited.  
* **Governance Upgrades:** any amendment to the government apparatus of the Pocket DAO, including the appointment or removal of directors or supervisors. 
* **Governance Transactions:** transactions executing the Council’s decisions in Pocket Core, by activating Protocol Upgrades, transferring Council On-Chain Treasury funds, and/or changing parameters
* **Legal Order:** any restraining order, preliminary or permanent injunction, stay or other order, writ, injunction, judgment or decree that either: (i) is issued by a court of competent jurisdiction, or (ii) arises by operation of applicable law as if issued by a court of competent jurisdiction, including, in the case of clause “(ii)” an automatic stay imposed by applicable law upon the filing of a petition for bankruptcy
* **Legal Proceeding:** means any private or governmental action, suit, litigation, arbitration, claim, proceeding (including any civil, criminal, administrative, investigative or appellate proceeding), hearing, inquiry, audit, examination or investigation commenced, brought, conducted or heard by or before, or otherwise involving, any court or other governmental entity or any arbitrator or arbitration panel.
* **Legislature:** the functions of the Pocket DAO responsible for decision-making
* **Majority Approval:** 50% Approval and 50% Quorum from Council Members on a proposal. 
* **Node:** an instance of Pocket Core (or another software client embodying the Pocket Protocol) that is online and operating on the Pocket Network, synced on a reasonably current basis with the Pocket Blockchain and receiving and propagating transactions from other Nodes on the Pocket Network
* **On-Chain:** any activity that is directly or indirectly reflected in information included in the Pocket Blockchain
* **Ownerless Foundation:** a foundation which has no members, shareholders or other equity holders 
* **Parameter Update Proposal (PUP):** proposals to change the value of a given parameter, On-Chain or in the Council’s tools or platforms
* **Parties:** any Person who consents to, is deemed to have consented to or is otherwise a party to or bound by this Constitution.
* **Permission Holders:** Pocket DAO participants who possess permissions as defined by the ACL of Pocket Core or an external Council platform designated for such purpose.
* **Person:** any (i) individual, corporation, company, general partnership, unincorporated association, group, organization, joint venture, limited partnership, limited liability partnership, estate, trust  or entity or legal person or (ii) (A) nation or international or multinational sovereignty, (B) government or instrumentality, subdivision, department, ministry, board, court or agency of any government or (C) quasi-governmental or private body exercising any executive, legislative, judicial, regulatory, taxing, importing or other governmental functions.
* **Pocket Blockchain:** at each time, the blockchain with "id:0001" that has been most recently validated by the Validator Nodes on the Pocket Network in accordance with the Pocket Protocol.
* **Pocket Community Game:** a series of gamified Pocket DAO community quests with levels that can be achieved by completing a set of tasks
 **Pocket Core:** at each relevant time, the most up-to-date official release of the Official Golang Implementation of the Pocket Network Protocol available at  https://github.com/pokt-network/pocket-core, without any modification thereto 
* **Pocket DAO:** means the unincorporated association of the Pocket Network’s Council, Users, Contributors, and Stakeholders. The Pocket DAO governs the public goods that are Pocket Core, the Council On-Chain Treasury, and all associated ecosystem resources, according to the structures, rules and procedures outlined in this Constitution. 
* **Pocket Development Company:** Pocket Network Inc., a Delaware corporation
* **Pocket Ecosystem Proposal (PEP):** has the definition set forth in Section ____. :
  * **Imbursements:** paying Contributors to fund future work
  * **Reimbursements:** paying Contributors for previous work
  * **Bounties:** funding work that has yet to be claimed by Contributors
  * **Transfers:** transferring funds to addresses that facilitate the above
  * **Agreements:** formal understandings of Contributor relationships, including non-financial in nature
* **Pocket Improvement Proposal (PIP):** proposals to upgrade any facet of the Pocket Network, including Protocol Upgrades and Governance Upgrades
* **Pocket Network:** the network recognized as having "netid: mainnet" by [any of][at least a majority of][NOTE TO TEAM: ANY PREFERENCE?] the following seed nodes:     
    * b3d86cd8ab4aa0cb9861cb795d8d154e685a94cf@seed1.testnet.pokt.network:26656 
    * 17ca63e4ff7535a40512c550dd0267e519cafc1a@seed2.testnet.pokt.network:26656
    * f99386c6d7cd42a486c63ccd80f5fbea68759cd7@seed3.testnet.pokt.network:26656
* **Pocket Network Foundation** or **Foundation**: the Pocket Network Foundation, a Cayman Islands foundation company limited by guarantee
* **Pocket Protocol:** the validity, consensus and coordination rules and procedures embodied in Pocket Core.
* **Pocket Technologies:** Pocket Core and the other software and technologies integral to the Pocket Network or Pocket Blockchain, including all software at https://github.com/pokt-network. 
* **POKT:** the unit of account recognized as "POKT" by Pocket Core on the Pocket Network and Pocket Blockchain. Balances of POKT are tracked in denominations of "pokt" or "upockt" in the "coins" or "balance" field for each unique address / public key on the Pocket Blockchain. POKT is the native cryptocurrency of the Pocket Network and Pocket Blockchain 
* **POKT Block Reward:** the POKT that is automatically minted in accordance with the Pocket Protocol every time a proposed block is validated by Validator Nodes on the Pocket Network for inclusion in the Pocket Blockchain
* **POKT DevFund Award:** the portion of each POKT Block Reward that is allocated to the Council On-Chain Treasury in accordance with the Pocket Protocol. 
* **Protocol Upgrades:** software updates to Pocket Core, approved according to PIPs
* **Quorum:** the minimum percentage of Voting Tokens held by Council Members that must have been voted to approve, reject or abstain on a proposal in order for such proposal to be eligible for approval or rejection.
* **ReturnOnInvestmentTarget:** an off-chain pricing parameter, enabling the Council to signal how many days they believe it should take an App to achieve the USD/Relay Target Range, accounting for the opportunity cost of using the Pocket Network versus competing services
* **Seed Node:** a Node (other than a Validator Node) that: (a) maintains a copy of the 'Node Address Book' for the Pocket Network and engages in the related peer ID discovery and peer ID propagation activities; and (b) dispatches relay requests to Validator Nodes. 
* **Signaling Era:** the period before automatic cross-chain execution of the Council’s decisions is achieved
* **Signaling Vote:** a vote that does not have the intent of executing an action upon completion, but is instead used to assess the sentiment of the Council
* **Stakeholder:** any Party who has a valid Governance Stake.
* **Supermajority Approval:** 80% Support and 50% Quorum from Council Members. 
* **Support:** the minimum percentage of Voting Tokens held by Council Members comprising a Quorum that must have been voted to approve a proposal in order for such proposal to be considered approved.
* **SupportedBlockchains:** a whitelist parameter defining which blockchains are permitted to generate Block Rewards, to limit revenue generation capabilities to blockchains with enough traction that they would not facilitate self-dealing by Nodes (wherein they stake as an App and, due to low traction, are matched with their own Node and can thereby process fake relays)
* **Unbonding Period:** the period of time that an App or Node must wait after revoking their Bonded status to receive their staked POKT
* **User:** has the definition set forth in Article 2.1.
* **USDRelayTargetRange:** an off-chain pricing parameter, enabling the Council to signal what they believe the rough long-term price range (in USD) should be for relays, to ensure Pocket Network’s service is competitive enough to attract new Apps
* **Validator Node:** a Node that: (a) validates, services and dispatches relay requests, relays and other transactions on the Pocket Network, is eligible to be randomly selected as a "block proposer" for the Pocket Blockchain and validates the blocks proposed by other such Nodes; and (b) maintains staked at least the current minimum amount of POKT required by the Pocket Protocol to perform such functions on the Pocket Network. 
* **Vote:** a transaction within the Council by a Council Member to approve a proposed action
* **Voting Token:** a blockchain token representing the owner’s right to submit Vote transactions [NOTE TO TEAM: do outstanding Voting Tokens cease to function within the Council if one of the conditions precedent re: the underlying Governance Stake ceases to be satisfied (e.g., the relevant Governance Stake dips below the required minimum amount of POKT based on # deposited POKT / number of Council Members?]



# Acknowledgements

## v1.1

**Authors:** Jack Laing

**Acknowledgements:**
* The comments of Michael O’Rourke, Dermot O’Riordan, Nelson Ryan, Stéphane Gosselin, Adam Liposky, Gabriel Shapiro, Lawrence Lundy-Bryan, Philippe Honigman, Louis Giraux, Felix Machart, Xule Lin, and John Light.
* The legal advice of Ryan Williams and Ashok Ayyar of Ashbury Legal, and Michael Robinson and Bradley Kruger of Ogier, in designing the Pocket Network Foundation (Foundation).
* Parts of the Statutes have leveraged a Qualified Code Deference template by Gabriel Shapiro, but this does not constitute an attorney-client relationship.


