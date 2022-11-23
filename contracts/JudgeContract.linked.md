NATION
: Import definitions https://linked.md/api/github/nation3/law/main/shared/NATION.linked.md

Supreme Court Judges Multisig as Judges Multisig, DAO as Nation3 DAO
: Import definitions https://linked.md/api/github/nation3/law/main/Constitution.linked.md

Conflict of Interest, Collusion
: Import definitions https://linked.md/api/github/nation3/law/main/shared/primitives/Basic.linked.md

Multisignature Wallet as Multisig, Account as Ethereum Account
: Import definitions https://linked.md/api/github/nation3/law/main/shared/primitives/Ethereum.linked.md

Dispute Resolution Clause
: Import https://linked.md/api/github/nation3/law/main/shared/DisputeResolutionClause.linked.md

Finalization Clause
: Import https://linked.md/api/github/nation3/law/main/shared/FinalizationWithDAO.linked.md

Dispute Resolution Process
: https://linked.md/v?u=https://linked.md/api/github/nation3/law/main/contracts/DisputeResolutionProcess.linked.md

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

---

# Nation3 Supreme Court Judge agreement

## Duties
Judge agrees to provide dispute resolution services to Nation3 DAO by:
1. Reviewing evidence sent by the parties of a disputed agreement.
2. Requesting more evidence to the parties if needed, and engaging with them to understand the case.
3. Submitting reasonable outcomes to settle disputes to the Judges Multisig.
4. Voting on outcomes submitted by other Judges by signing transactions in the Judges Multisig.

## Collateral
Judge enters this agreement by staking [%Collateral Amount].

## Compensation
Judge shall be compensated by Nation3 DAO with [%Monthly Compensation] per month, paid monthly.

## Severe breach of contract
The following clauses outline what constitutes a severe breach of this agreement. In case of severe breach Judge will be stripped of all their functions, removed from the Judges Multisig, and [%Severe Breach Slashing Percentage] of their collateral will be taken away. The following constitute a severe breach of contract:

### Leaking evidence
Judge shall commit to following the Dispute Resolution Process.

### Collusion
Judge shall not collude with other Judge(s) in an act of Collusion.

### Conflict of interest
Judge shall not participate on a case involving an agreement in which they are involved as one of the parties, or otherwise have a Conflict of Interest.

### Control of private key
Judge shall exercise sole control of the private key uniquely related to the Ethereum Account used by the Judge in the Judges Multisig. Judge shall not publish, sell or otherwise share or lose control over such private key.

## Minor breach of contract
In case of minor breach Judge will be stripped of all their functions, removed from the Judges Multisig, and [%Minor Breach Slashing Percentage] of their collateral will be taken away. The following constitute a minor breach of contract:

### Inactivity
Judge shall make a Reasonable Effort to participate in resolving disputes, both by engaging in the Dispute Resolution Process and by signing transactions in the Judges Multisig. Not signing one transaction in the Judges Multisig for two months will be considered minor breach of contract. 

### Outcome submission in appealed disputes
Judge shall not submit a new outcome for a dispute while a previous outcome is in the appeal period.

### Failure to give notice or enter a new version of this agreement
Nation3 DAO can, from time to time, create a new version of this agreement between the DAO and the Judges.

Judges shall not be bound by a new version of this agreement unless they have explicitly entered it.

In case of disagreement with such new version, Judge shall give notice and finalize their current agreement with Nation3 DAO.
In case of agreement, Judge shall have [%Finalization Notice Time] to finalize this current agreement and enter the new one, as communicated to the Judges by electronic means.

## Jurisdiction and dispute resolution
:include[Dispute Resolution Clause]{"Parties"="Nation3 DAO and Judge"}

## Finalization
:include[Finalization Clause]{"Party1"="Nation3 DAO" "Party2"="Judge" "Guild"="Judges Multisig" "Finalization Notice Time"="[%Finalization Notice Time]"}