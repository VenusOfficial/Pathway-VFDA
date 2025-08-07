# Pathway-VFDA

Contact: venus@ipfsforce.com or **@Venus_Official** on Filecoin Slack.

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
Any client looking to onboard a Public Dataset to Filecoin can apply to this allocator pathway.

#### Minimum client requirements:
- At least 4 sealed copies of a dataset, stored with 4 separate Storage Provider entities, at least in 2 different regional locations(city).
- The dataset is made readily retrievable on the network. And the retrieval rate should not be less than 75%.
- Clients disclose their storage provider partners upfront. VPN for storage provider is not allowed.
- Clients are required to apply for DataCap using the following GitHub repo [LINK](https://github.com/VenusOfficial/Pathway-VFDA/issues/new/choose).

#### Once an application is submitted, diligence to be completed on clients includes:
We uphold a strict, multi-step verification process to guarantee that only eligible entities join our program. The onboarding procedure involves submitting legal formation documents, independently verifying all submitted information, and conducting detailed client interviews to confirm authenticity. Clients are required to maintain strong data retrieval performance, ensure fair distribution of deals across storage providers in multiple regions, and work exclusively with us. All procedures and related documentation will be made publicly available on GitHub for FIL+ and community scrutiny.


### The allocation schedule for trusted users is:
First allocation max 5%, but no more than 256TiB; 
Second max 10%; 
Third max 15%; 
Fourth max 20%; 
Fifth and there after max 25%;
AND No allocation can be bigger than 2x of the previous one. 



#### Subsequent allocation schedule:
- When clients use up > 75% of the prior DataCap allocation, a request for additional DataCap in the form of the next tranche is automatically kicked off (via the subsequent allocation bot). The allocator team will set an SLA (Service Level Agreement) to keep up with allocation review and comment on bot messages within 3 days.

#### Compliance check mechanisms for the client applications:
We safeguard program integrity through a thorough due diligence process that ensures all data and clients comply with program guidelines as well as applicable local and regional regulations. Clients are required to submit detailed documentation covering their data preparation methods and dataset attributes, including type and volume. Our ongoing verification includes random audits of data ownership via content sampling, deal validation through mapping file analysis, and Payload CID cross-checks utilizing Filecoin tools. We maintain complete audit records to guarantee transparency and accountability, which include client-submitted documents, verified compliance agreements, representative mapping file samples, detailed verification logs, and monitoring results.

#### Disputes/Appeals:
- For any disputes between our allocator and a client, hereby termed appeal(s), we will source the appeals through the [VFDA Appeals Form](https://docs.google.com/forms/d/1ihy6HsxJlHmoThrMhVsvHFumoQ1BHIKYCNkEQIlM7UU/edit?pli=1) where all our clients can submit an appeal.
- We would like to respect the privacy of the client and do not plan to host a public resolution process.
- For disputes raised by community members/non-clients about our allocation approach and strategy, we will comply with the public dispute tracker that is being built by the Filecoin Foundation Governance team.
