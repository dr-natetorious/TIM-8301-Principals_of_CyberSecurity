# Week 3: Cyber Espionage and Global Influences

- [Required Readings](Readings/Citations.md)
- [Summary of Articles](Readings/README.md)
- [Essay: Understanding and Mitigating Global Risks](BachmeierNTIM8310-3.docx)

## What is the central idea

The Internet does not exist as a single homogeneous global communication tool, but as collection of islands where different nations express their sovereignty through trade-offs between govt oversight, societal freedoms, and international actors rights.  These decisions create a geography with varying degrees of transparency and confidentiality assurances.

According to Article 51 of the UN, state actors are free to perform cyber-espionage under the disguise of self-defense.  While capitalist countries believe this stops at govt spying on govt, socialist and authoritarian nations lack a clear division between public and private industries and do not honor the distinction.

Therefore,  when an organization seeks to do business in a foreign market, they need to understand the `security guarantees and assertions` of that new environment might differ from their `native locale` and assess the global risk that come from these interactions.

Some foreign markets more robust assertions that require upgrading our products to include encryption and related privacy features.  In contrast, others have weak guarantees, such as rampant cyber espionage, sabotage, and subversion, and are less desirable to share trade secrets.  

An assessment of these risks needs to find a cost-benefit balance for accessing that market without compromising the integrity, confidentiality, and availability of the organization.  That balance might come from reducing the available feature set, or declining the deal entirely. While it can be challenging to navigate these foreign policies, businesses that come with skepticism and security awareness of the different geographics trusts that exist across markets, and not treat the Internet as one homogeneous locale.

## Expressing this abstractly

If you step back and look at the problem its actually fairly simple; Organization `O` has product `P` with Features `Fi..n` that they want to sell to market `M`.

```policy
For I to N in count(F):
- M(Fi) expects security assertions 'Am' and provides guarantees 'Gm'
- O(Fi) expects security assertions 'Ao' and provides guarantees 'Go'
- If (Am contained-within Go) and (Ao contained-within Gm) then ship it
- Else not supported
```

Where assertions and guarantees center around ideas like _integrity, confidentiality, and availability_.  While the context of this material is `foreign states`, M could be any market (e.g., AWS services shipping to AWS outpost or proprietary code shipping in redistributable package).
