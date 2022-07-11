# Patient Controlled Health DID, Aggregation, Sharing, and Monetization


:sunglasses: Project Idea: **Simple API for a Decentralized Health Data Sharing Protocol ** :sunglasses:

There are 350k health apps containing various types of symptom and factor data.  However, the isolated data's relatively useless in all these silos. In order to make clinical discoveries, all the factor data needs to be combined with the outcome data.  The web2 solution to combining all this data is a nightmare of
1. creating thousands of OAuth2 data connectors 
2. running a bunch of importer cron jobs on AWS.

**Web3 Solution**: User auth/databases/key management/access control/3rd party OAuth tokens abstracted away by a single, easy-to-use API

i.e. 
Pain Tracking App A:
 `db.collections.create('Arthritis Severity', timeSeriesData);`

Diet-Tracking App B:  
`let timeSeriesData = db.collections.get('Arthritis Severity');`

⇒ Making it possible for Diet-Tracking App B (and/or Pain Tracking App A) to easily analyze the relationship between dietary factors and Arthritis Severity using causal inference predictive model control recurrent neural networks.

**Libraries**: Lit and Ceramic?

**Nice to have**: Zero-knowledge proof of know-your-customer identity verification as a soul-bound token (EIP-5114)
