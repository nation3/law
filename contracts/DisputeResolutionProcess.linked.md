Supreme Court Multisig, Jurisdiction Agreement, Designated Smart Contracts
: Import definitions ipfs://bafybeicm4hbd5ozlvapns4ps4fwpx6ef6mwqfqogikpswjorkk45nor5uy/Constitution.linked.md

Parties
: Parties bound by a Nation3 Jurisdiction Agreement.

Judges
: Members of the Supreme Court Multisig.

Skiff
: skiff.com by Skiff World, Inc.

Skiff Ethereum alias
: A valid Ethereum address or ENS name followed by `@skiff.com` linked to an account created on Skiff.

Ethermail
: ethermail.io by EtherMail GmbH

Ethermail address
: A valid Ethereum address followed by `@ethermail.io` linked to an account created on Ethermail.

Tresorit Send
: send.tresorit.com by Tresorit AG

Evidence Submission Time Window
: 5 days

Outcome Proposal Time Window
: 4 days

Etherscan
: https://etherscan.io/verifiedSignatures

Time Windows
: Evidence Submission Time Window and Outcome Proposal Time Window
---

# Dispute resolution process

The process is as follows:

1. The claimant disputes the agreement on-chain, submitting claims and evidence to the judges and notifying all the counterparties.
2. The [%Evidence Submission Time Window] from the moment the judges confirm the reception of the dispute and proper notification to all parties involved/
3. After the Evidence Submission Time Window ends, the Supreme Court Multisig has [%Outcome Proposal Time Window] to put forward their desired settlement outcome.
4. Once a settlement proposal has been put forth by the Supreme Court Multisig, any of the Parties can appeal such proposal. The time window for the appeal process is encoded in the Designated Smart Contracts.
5. If the settlement proposal is not appealed within the specified time window, or it is endorsed after an appeal dismissal, it will be enforceable and final, as encoded in the Designated Smart Contracts.

## Extension for Time Windows
Parties may agree upon an extension of the Evidence Submission Time Window and Outcome Proposal Time Window in their agreements. However, the total combined duration of both time windows, as agreed upon by the parties, shall not exceed 21 days. If the parties fail to specify the duration of the extended time windows, the default durations of 5 days for the Evidence Submission Time Window and 4 days for the Outcome Proposal Time Window will apply. If the parties specify a combined duration that exceeds 21 days, a 14-day Evidence Submission Time Window and a 7-day Outcome Proposal Time Window will be applied instead.

## Evidence Submission Process

For Parties to open a dispute, respond to a claim or otherwise engage with a disputed agreement, they will have to either 1) specify which means they want to be contacted through on their agreement (email, discord, telegram, etc.) or 2) else generate an Skiff Ethereum alias created by [linking their Ethereum account within Skiff](https://skiff.com/blog/ethereum-wallet-email). 

### Communicating with Judges

#### Communication Mechanism

Parties may agree to alternative means for communication and evidence submissions in their agreements. However, if they fail to specify such alternatives, they must use Skiff for all communications and evidence submissions.

#### Evidence Submission

Any evidence to support claims or respond to them must be attached to emails within Skiff, unless parties have agreed to alternative means for evidence submissions in their agreement. Any evidence over 25MB will be sent using Tresorit Send. Only Parties can submit evidence related to a dispute or participate in the dispute process.


#### Privacy

All hearings and communications between Parties and Judges will be strictly private, unless parties have agreed to alternative means for communications in their agreement. No other parties shall be included in the hearings or communications between Parties and Judges. No private communications between Parties and Judges shall be released to the public or anyone else outside those groups.

Hearings or communications shall be public, and the above shall not apply, if the case involves the dismissal of a Judge from the Supreme Court Multisig.

In case of a Judge being dismissed, Parties and Judges shall, within the next 7 days, exclude such Judge from all future communications related to the dispute.

Failure to comply with these privacy rules will result in the infringing party being ruled entirely liable for the maximum possible amount of losses within the agreement.

The Supreme Court Multisig might decide to publish anonymized data about the case, if such action would be in the interest of morals, public order, the security of Nation3, or the interests of the parties and witnesses. No data shall be published that cannot be effectively anonymized.

#### Platform Malfunction

In case of a malfunction within Skiff, the Supreme Court Multisig will post a joint statement declaring the use of Ethermail instead of Skiff. All Parties and Judges shall continue adhering to the same procedures detailed for Skiff, but instead of using their Skiff Ethereum alias, they must use their Ethermail address, unless parties have agreed to alternative means for communications in their agreement.

#### Language
All communications, evidence submissions, appeals, and any other relevant documents or interactions within the dispute resolution process must be in English. Parties, Judges, and the DAO are required to use English as the medium of communication to ensure a clear understanding of the case and maintain consistency throughout the process.

## Appeal Process
Appeals are only allowed in cases involving procedural issues. The parties have the right to appeal the outcome, with the DAO deciding if the appeal proceeds.
1. Once a settlement proposal has been put forth by the Supreme Court Multisig, any of the Parties can appeal such proposal within a 4-day window, which is encoded in the Designated Smart Contracts, if they believe there is a procedural limited to:

a. Deadlines not being respected by the Judges.

b. Parties weren't notified properly.

c. If one of the Judges leaks confidential information.

d. If one of the Parties has evidence that one of the Judges was biased or bribed.

e. Parties didn't have the opportunity to present their case.

2. If the settlement is appealed by one of the parties, they have to submit their claims towards the DAO through a forum post, including all the relevant information, plus a signed message on Etherscan to prove they are the owners of the said wallet. The claims must focus on the procedural issues in question if anything related to the substance of the dispute is disclosed then the appeal won't proceed. The counterparty is allowed and encouraged to do the same in reply to the appellant's post.
3. Parties have a total of 4 days to present their evidence in the forum. Once this time window passes, the DAO has to vote on the outcome; they have 2 days to do so.
4. If the DAO votes in favor of the appellant, then the Judges have to emit a resolution with a different outcome, and Judges could be either slashed or replaced by the DAO depending on the severity of the issue. If one Judge was bribed or engaged in fraudulent behaviour, they will be removed and their agreement with the DAO terminated, resulting in the immediate slashing of their collateral.
5. If the DAO decides that there were no procedural issues and the settlement was fair, then the decision of the Judges is executed.

