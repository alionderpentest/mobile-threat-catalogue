---
    layout: threat
    ThreatCategory: "Malicious or privacy-invasive application"
    ID: APP-32
    Threat: "Malicious app taking advantage of the device''s access to an internal enterprise network (e.g. via device-wide VPN connection or connection to corporate Wi-Fi) to access enterprise resources."
    ThreatOrigin:
    ExploitExample:
        - "Juniper Networks Third Annual Mobile Threats Report [^236]"
    CVEExample:
    PossibleCountermeasures:
        - "Prohibit sideloading of apps and prohibit use of unauthorized app stores"
        - "Use Android Verify Apps feature to identify harmful apps"
        - "Perform application vetting to identify inappropriate behaviors by apps including permission requests made by the apps"
        - "Use application threat intelligence data about potential risks associated with apps installed on devices"
        - "Use features such as Apple iOS Managed Apps, Android for Work, or Samsung KNOX Workspace that provide some level of separation between personal apps and enterprise apps to mitigate the impact of malicious behaviors, including use of per-app/per-user VPN features so that only enterprise-approved apps can traverse the VPN and access enterprise resources, not personal use apps"
---
