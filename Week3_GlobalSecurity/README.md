# Week 3: Cyber Espionage and Global Influences

- [Required Readings](Readings/Citations.md)
- [Summary of Articles](Readings/README.md)
- [Essay: Understanding and Mitigating Global Risks](BachmeierNTIM8310-3.docx)

When an organization seeks to do business in a foreign market, they need to understand the `security guarantees and assertions` of that new environment might differ from their `native locale`.  Some foreign markets more robust assertions that require upgrading our products to include encryption and related privacy features.  In contrast, others have weak guarantees, such as rampant cyber espionage, sabotage, and subversion, and are less desirable to share trade secrets.  An assessment of these risks needs to find a cost-benefit balance for accessing that market without compromising the integrity, confidentiality, and availability of the organization.  That balance might come from reducing the available feature set, or declining the deal entirely. While it can be challenging to navigate these foreign policies, businesses that come with skepticism and security awareness are more likely to be successful.  That awareness needs to be cognizant of the different geographics of trust that exist across markets, and not treat the Internet as one homogeneous locale.

If you step back and look at the problem its actually fairly simple; Organization `O` has product `P` with Features `Fi` to `Fn` that they want to sell to market `M`.

```policy
For I to N in count(F):
- M(Fi) expects security assertions 'Am' and provides guarantees 'Gm'
- O(Fi) expects security assertions 'Ao' and provides guarantees 'Go'
- If (Am contained-within Go) and (Ao contained-within Gm) then ship it
- Else not supported
```

Where assertions and guarantees center around ideas like _integrity, confidentiality, and availability_.  While the context of this material is `foreign states`, M could be any market (e.g., AWS services shipping to AWS outpost or proprietary code shipping in redistributable package).
