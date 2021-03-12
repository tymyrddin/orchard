# Public keyring identities leakage

Identities present in a public keyring hold the information of who an E2EE user has communicated with. Some information leaks are inevitable, as this information can be obtained from other sources. For example, if an E2EE messaging or email application does not remove the Key IDs from outgoing messages, they will be accessible to a relevant server, web application and MitM adversaries.
Mitigation

In the context of surveillance capitalism exposed, a journalist or privacy analyst might manually import a whistle blower public key into his or her keyring and use E2EE only for encryption and decryption of messages exchanged with the whistle blower over a non-web-based external channel to not disclose the presence of the key to a keyserver or web application. 