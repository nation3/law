NATION
: Import definitions https://linked.md/api/github/nation3/law/main/shared/NATION.linked.md

Judges Multisig
: Import definitions https://linked.md/api/github/nation3/law/main/Constitution.linked.md

Conflict of Interest, Collusion
: Import definitions https://linked.md/api/github/nation3/law/main/shared/primitives/Basic.linked.md

Collateral Amount
: 10 NATION

Monthly Compensation
: 1 NATION

Severe Breach Slashing Percentage
: 100%

Minor Breach Slashing Percentage
: 30%

Finalization Notice Time
: 30 days

Dispute Resolution Clause
: Import https://linked.md/api/github/nation3/law/main/shared/DisputeResolutionClause.linked.md

---

# Nation3 Court Judge agreement

## Responsibilities

Judge agrees to provide dispute resolution services to Nation3 DAO by:
1. Reviewing evidence sent by the parties of a disputed agreement.
2. Requesting more evidence to the parties if needed, and engaging with them to understand the case.
3. Submitting reasonable outcomes to settle disputes to the Judges Multisig.
4. Voting on outcomes submitted by other judges by signing transactions in the Judges Multisig.

## Collateral

Judge enters this agreement by staking [%Collateral Amount].

## Compensation

Judge shall be compensated by Nation3 DAO with [%Monthly Compensation] per month, paid monthly.

## Severe breach of contract

The following clauses outline what constitutes a severe breach of this agreement. In case of severe breach Judge will be stripped of all their functions, removed from the Judges Multisig, and [%Severe Breach Slashing Percentage] of their collateral will be taken away. The following constitute a severe breach of contract:

### Leaking evidence

Judge shall commit to following the Evidence Submission process.

### Collusion

Judge shall not collude with other Judge(s) in an act of Collusion.

### Conflict of interest

Judge shall not participate on a case involving an agreement in which they are involved as one of the parties, or otherwise have a Conflict of Interest.

## Minor breach of contract

In case of minor breach Judge will be stripped of all their functions, removed from the Judges Multisig, and [%Minor Breach Slashing Percentage] of their collateral will be taken away. The following constitute a minor breach of contract:

### Inactivity

Judge shall make a Reasonable Effort to participate in resolving disputes, both by engaging in the Evidence Submission process and by signing transactions in the Judges Multisig. Not signing one transaction in the Judges Multisig for two months will be considered medium breach of agreement. 

### Outcome submission in appealed disputes

Judge shall not submit a new outcome for a dispute while a previous outcome is in the appeal period.

## Jurisdiction and dispute resolution

:include[Dispute Resolution Clause]{"Parties"="Nation3 DAO and Judge"}

## Finalization

Nation3 DAO and Judge agree to amicably finalizing this agreement by:
1. Sending a communication with the intent to finalize, giving notice of at least [%Finalization Notice Time].
2. Signing the finalization after such notice has passed.

Nation3 DAO shall present this notice to Judge by passing a Proclamation Governance Proposal with the text `Nation3 DAO agrees to give finalization notice to Nation3 Court judge with address {address}.`

Judge shall present notice to Nation DAO by posting a message to the Nation3 Forum, describing the intent to finalize the agreement and containing a valid signature produced by the Ethereum address they used in the Judges Multisig.

Upon finalizing this agreement, Nation3 DAO and Judge relieve each other of any responsibilities and liabilities relating to carrying out the activities described in this agreement.

