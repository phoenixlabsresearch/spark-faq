# Address Screening & Geoblocking

## Address Screening

We receive blockchain intelligence provided by [TRM Labs](https://www.trmlabs.com/). TRM combines on-chain data and real-world investigations to identify financial crime and other prohibited activities.&#x20;

We intend to only block wallets that are owned or associated with clearly illegal behavior like: sanctions, terrorism financing, hacked or stolen funds, ransomware, human trafficking, and child sexual abuse material (CSAM).

If you believe your address has been incorrectly flagged, please contact [contact@marsfoundation.xyz](mailto:contact@marsfoundation.xyz).

Your address is shared with TRM, but no metadata is tracked or shared. The request from the UI is routed to the Spark hosted API, which is used as a proxy endpoint, and the address is passed directly through to the TRM service. Users' IP addresses are not shared with TRM.

Please note that we do not control TRM Labs or their independent determinations about risk categories and wallet addresses.\
\
Please also note that these determinations are not being reported to law enforcement.\


## Geoblocking

In accordance with [MIP108 Accessibility Scope Bounded Mutable Alignment Artifact](https://github.com/makerdao/mips/blob/master/MIP108/MIP108.md), MKR holders have made the decision to restrict access for individuals in specific jurisdictions.&#x20;

To uphold these restrictions, we are obligated to implement measures to prevent any circumvention of our access controls, which includes the blocking of known VPNs.&#x20;

There are alternative front-ends accessible in various jurisdictions outside of Spark that offer Spark protocol and MakerDAO features. However, it is essential to note that Maker has no control over these external platforms and lacks awareness of their regulatory positions. As a consequence, we cannot guarantee compliance with the laws in your jurisdiction when using such front-ends.
