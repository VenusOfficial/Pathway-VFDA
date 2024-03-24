# Pathway-VFDA

Contact: venus@ipfsforce.com or **@Joss-Venus** on Filecoin Slack.

The details of this Allocator pathway were initially described in an application to the Fil+ Governance Team in December 2023: [LINK](https://github.com/filecoin-project/notary-governance/issues/1035).

Below is an summary of the key client requirements and processes that the Venus team will follow to oversee proper due diligence while insuring compliance to Fil+ guidelines for DataCap allocations.

## Background

### What is Filecoin Plus?
[Filecoin Plus](https://github.com/filecoin-project/FIPs/blob/master/FIPS/fip-0003.md) aims to maximize the amount of useful storage on Filecoin by adding a layer of social trust to the Network. [Clients](https://github.com/filecoin-project/filecoin-plus-client-onboarding#client) can apply to Notaries to receive [DataCap](https://github.com/filecoin-project/filecoin-plus-client-onboarding#datacap), which can be used to incentivize Storage Providers (SPs) to take storage deals. SPs who take deals that are compensated with DataCap receive a 10x to their quality adjusted power - increasing their probability of winning block rewards. Filecoin Plus puts power in the hands of Clients and incentivizes SPs to support real use case on the Network.
For more detailed descriptions, please refer to [here](https://github.com/filecoin-project/FIPs/blob/master/FIPS/fip-0003.md).

### What is an Allocator?
As of March 2024, there are a total of 4 Pathways for Client to obtain Datacap, which are:
1. [Datacap faucet](https://verify.glif.io/) *(32 GiB/time/day)*
2. [Ordinary dataset application](https://github.com/filecoin-project/filecoin-plus-client-onboarding/issues)  *(0-500 TiB/time)*
3. [Large dataset application](https://github.com/filecoin-project/filecoin-plus-large-datasets/issues)  *(>500 TiB/time)*
4. [Fil-E dataset application](https://github.com/filecoin-project/filecoin-plus-large-datasets/issues)  *(private data)*

Now the community has stopped further maintenance of 2), 3), and 4), and has been replaced by a new channel called Allocator. The Allocator channel has several Pathways, each defined by an organization or individual for rules and maintenance, and all allocator information can be viewed [here](https://github.com/filecoin-project/notary-governance/issues?q=allocator).

### What is VFDA?
VFDA is a pathway maintained by Venus team as an Allocator, and clients can apply for Datacaps through VFDA.
![image](https://github.com/VenusOfficial/Pathway-VFDA/assets/155081686/a96ec32b-37a4-4c69-86ce-bb32455b8a39)


## Using DataCap
### How to Get DataCap
Client can get the DataCaps of VDFA on the [Registry](https://github.com/VenusOfficial/Pathway-VFDA/issues/new/choose), and they need to initialize their on chain address by sending a small amount of FIL to their address.

#### Current Scope:
Any client looking to onboard a Public/Private Dataset to Filecoin can apply to this allocator pathway.

#### Minimum client requirements:
- At least 2 sealed copies of a dataset, stored with 2 separate Storage Provider entities, each in different regional locations(city).
- The dataset is made readily retrievable on the network.
- Clients disclose their storage provider partners upfront.
- Clients are required to apply for DataCap using the following GitHub repo [LINK](https://github.com/VenusOfficial/Pathway-VFDA/issues/new/choose).

#### Once an application is submitted, diligence to be completed on clients includes:
##### New User Check
- Is this a completely new GitHub ID?
- Is this the first time this GitHub ID has applied for DataCap in this or other allocotor pathways?

##### Client ID Check (KYC)
- All applicants will be asked if they are willing to complete a free know your customer (KYC) check to confirm themself as a human user associated with a specific GitHub ID.
- Users are asked to validate their ID and livelihood via a link on [filplus.storage](filplus.storage).

##### Storage Provider (SP) Usage Check
- Clients of this pathway will have access to SP Marketplace.
- Clients are also free to select their own SPs.

##### Allocation Tranche Schedule to clients:
- As mentioned above, each application will have the GitHub ID assessed to confirm if they are a new GitHub ID or first time user to the allocator.

### The allocation schedule for trusted users is:
- 1st allocation 25%
- 2nd allocation 25%
- 3rd allocation 25%
- 4th allocation 25%

After successful on-boarding of a dataset as a trusted GitHub ID, users then become eligible to apply for 5PiB+ as needed to meet their demand.

#### Subsequent allocation schedule:
- When clients use up > 75% of the prior DataCap allocation, a request for additional DataCap in the form of the next tranche is automatically kicked off (via the subsequent allocation bot). The allocator team will set an SLA (Service Level Agreement) to keep up with allocation review and comment on bot messages within 3 days.

#### Compliance check mechanisms for the client applications:
- After each allocation we will manually review the on-chain deal making activity of the applicant to confirm compliance mostly relying on the AC Bot, which runs weekly, to identify non-compliance of deal making, distribution and retrievals and that information will be used to drive action on applications. The bot will be set up to automatically close applications after several allocations if thresholds are not met.
- At any point if clients are caught providing fake or misleading information about themselves or their SP partners, we will close any open applications and add the GitHub user IDs and miner IDs involved and block them from future participation in the allocator.

#### Disputes/Appeals:
- For any disputes between our allocator and a client, hereby termed appeal(s), we will source the appeals through the [VFDA Appeals Form](https://docs.google.com/forms/d/1ihy6HsxJlHmoThrMhVsvHFumoQ1BHIKYCNkEQIlM7UU/edit?pli=1) where all our clients can submit an appeal.
- We would like to respect the privacy of the client and do not plan to host a public resolution process.
- For disputes raised by community members/non-clients about our allocation approach and strategy, we will comply with the public dispute tracker that is being built by the Filecoin Foundation Governance team.
