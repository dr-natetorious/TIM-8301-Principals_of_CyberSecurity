# Presentation Outline

1. What is CyberSecurity and Why Do I Care
    - To ensure the availability, reliability, performance, and continuity of a `business process`
    - Threats exist from multiple sources
        - Negligence
        - Maliciousness
        - Insiders
        - Nation-States
        - Karma/Luck
2. Evolution of attacker leverage
    - No longer one person manually poking
    - No longer only people with botnets trying lots of attacks
    - Now networking is fast and compute is cheap
3. What threats exists to these `processes`
    - STRIDE enumerates categories of attacks
        - Spoofing
        - Tampering
        - Repudiation
        - Information Disclosure
        - Denial of Service
        - Elevation of Priviledges
4. Getting a cup of coffee
    - Spoofing: Print a fake receipt
    - Tampering: Edit the receipt to include additional items
    - Repudiation: Tell them you ordered and didnt get receipt
    - Information Disclosure: Hear Alice order, then claim to be her
    - Denial of Service: Bring 100 friends and order at same time
    - Elevation of Priviledges: Walk behind the counter
5. Using threat modeling
    - Identify assets, risks, trust boundaries
    - Focuses the conversation to specific attack vectors
    - Produces test plan for efficient investigation
6. Threat: Spoofing
    - Examples
        - Cold calling
        - Name squating
    - Mitigations
        - Identification
7. Threat: Tampering
    - Examples
        - Weak authorization
        - No checksums
        - Lossy communication channels
    - Mitigations
        - Consistency
8. Threat: Repudiation
    - Examples
        - Weak auditing
        - Replay attacks
    - Mitigations
        - Cryptographic signatures
        - Contracts and recordings
9. Threat: Information Disclosure
    - Examples
        - Verbose error messages
        - Discussing trade secrets outside of work
    - Mitigations
        - Training
10. Threat: Denial of Service
    - Examples
        - Unthrottled traffic
        - Computational asymetry
    - Mitigations
        - Queuing
        - Horizontal scaling
11. Threat: Elevation of Priviledges
    - Examples
        - Alice asks Bob to do something for her
        - Shared passwords
        - Weak office locks
    - Mitigations
        - Least priviledges
12. What is the attack surface of these issues
    - 50% technology
    - 50% human error
13. Addressing the technology
    - Firewalls
    - IDS/IPS
    - Anti-Malware
14. Addressing the human factor
    - Security Awareness
    - Password Policies
    - Training
    - Building trust into the process
15. Addressing insider risks
    - Negligence: Lose an unencrypted device
    - Malicious: Steals corporate data for revenge or profit
16. Protecting corporate assets
    - Backups
    - Fail-over
    - Quotas
17. Conclusion
