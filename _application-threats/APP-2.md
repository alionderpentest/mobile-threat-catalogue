---
    layout: threat
    ThreatCategory: Vulnerable Applications
    ID: APP-2
    Threat: "Storing files with insecure file permissions or in an unprotected location on the device"
    ThreatOrigin:
    ExploitExample:
        - "Vulnerability in Skype for Android [^67]"
        - "World Writable Code Is Bad, MMMMKAY [^68]"
        - "LOOK-11-001 something [^69]"
    CVEExample:
        - CVE-2011-1717
    PossibleCountermeasures:
        - "App vetting tools/services or pen testing to detect these vulnerabilities in apps."
        - "Android N has new behavior to improve the protections given to the internal storage directories of applications."
---
