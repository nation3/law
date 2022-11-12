NATION
: Import definitions https://linked.md/api/github/nation3/law/main/shared/NATION.linked.md

Guardian Guild, DAO as Nation3 DAO
: Import definitions https://linked.md/api/github/nation3/law/main/Constitution.linked.md

Conflict of Interest, Collusion, Person
: Import definitions https://linked.md/api/github/nation3/law/main/shared/primitives/Basic.linked.md

Dispute Resolution Clause
: Import https://linked.md/api/github/nation3/law/main/shared/DisputeResolutionClause.linked.md

Finalization Clause
: Import https://linked.md/api/github/nation3/law/main/contracts/FinalizationWithDAO.linked.md

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

Contributors
: Any Person or entity providing services to the Nation3 DAO.

---

# Nation3 Guardian Guild agreement

## Duties
Guardian agrees to provide the following services to Nation3 DAO:
1. Assessing the work performed by Contributors.
2. Releasing payments if the assessment is that Contributors are delivering the work as proposed to the DAO. 
3. Disputing agreements between the Contributors and the DAO in case of breach.
4. If required, curate Governance Proposals sent by Citizens, and publish adequate Governance Proposals on the DAO's preferred Voting Platform.
5. Other services, as agreed by the Guardian Guild and the DAO.

## Collateral
Guardian enters this agreement by staking [%Collateral Amount].

## Compensation
Guardian shall be compensated by Nation3 DAO with [%Monthly Compensation] per month, paid monthly.

## Severe breach of contract
The following clauses outline what constitutes a severe breach of this agreement. In case of severe breach Guardian will be stripped of all their functions, removed from the Guardian Guild, and [%Severe Breach Slashing Percentage] of their collateral will be taken away. The following constitute a severe breach of contract:

### Leaking evidence
Guardian shall not leak private evidence obtained in disputes between the Guardian Guild, the Contributors and the DAO.

### Collusion
Guardian shall not collude with other Guardian(s) in an act of Collusion.

### Conflict of interest
Guardian shall not participate on a case involving an agreement in which they are involved as one of the parties, or otherwise have a Conflict of Interest.

### Control of private key
Guardian shall exercise sole control of the private key uniquely related to the Ethereum Account used by the Guardian in the Guardian Guild. Judge shall not publish, sell or otherwise share or lose control over such private key.

## Minor breach of contract
In case of minor breach Guardian will be stripped of all their functions, removed from the Guardian Guild, and [%Minor Breach Slashing Percentage] of their collateral will be taken away. The following constitute a minor breach of contract:

### Inactivity
Guardian shall make a Reasonable Effort to participate in the activities of the Guardian Guild. Inactivity for two months will be considered a minor breach of contract. 

## Jurisdiction and dispute resolution
:include[Dispute Resolution Clause]{"Parties"="Nation3 DAO and Guardian"}

## Finalization
:include[Finalization Clause]{"Party1"="Nation3 DAO" "Party2"="Guardian" "Guild"="Guardian Guild" "Finalization Notice Time"="[%Finalization Notice Time]"}