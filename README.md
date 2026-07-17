<img width="1983" height="793" alt="blacknet" style="border-radius: 15px;" src="https://github.com/user-attachments/assets/d7f36b49-6f6e-44aa-a60f-7074b0eb8721" />


> **An experimental private network for temporary sharing of encrypted files.**

BlackNet is an early research and development project focused on controlled file sharing. Its purpose is to create a network dedicated exclusively to this use case — without an integrated browser, public proxy, social network, or attempt to replace the Internet.

## Status

**Early concept / private development.**

BlackNet is not ready for real-world use, production use, or storage of sensitive information. Protocols, limits, and components may change during testing.

## Initial Goal

BlackNet's initial goal is to allow authorized members to share files temporarily through a private network using cryptographic protection and distributed storage.

The first phase aims to provide:

- Network access only through a request, invitation, or approval process;
- A dedicated application for file sharing;
- Acceptance of password-protected ZIP or RAR archives only;
- Validation of file format and encryption indicators without receiving the user's password;
- Additional local encryption before distribution;
- File splitting into uniformly sized blocks;
- Temporary distribution of encrypted fragments among authorized nodes;
- Automatic share expiration;
- Download/recovery limits for each share;
- Integrity verification before file reconstruction;
- Reduced knowledge of the distributed file at each storage node.

The ZIP or RAR password belongs only to the sender and authorized recipients. It must never be sent to, stored by, or requested by the BlackNet network.

## Project Principles

BlackNet is guided by the following principles:

```text
Privacy by default
Encryption before distribution
Controlled access
Temporary storage
Minimum necessary metadata
Verifiable integrity
Technical transparency and responsible operation
```

## First-Phase Scope

BlackNet is not intended to be an alternative to Tor, I2P, VPNs, or privacy browsers.

The first phase does not include:

- Anonymous web browsing;
- A proxy for external websites;
- Public website hosting;
- Public chat, social networking, or messaging;
- Public file sharing without authorization;
- Any promise of absolute anonymity;
- Any promise that files already downloaded by a recipient can be remotely deleted.

The focus is exclusively on temporary and controlled sharing of protected files.

## Security and Realistic Expectations

No system can guarantee perfect anonymity, prevent a recipient from copying a file they have already downloaded, or replace basic security practices.

BlackNet aims to reduce unnecessary exposure through encryption, fragmentation, access control, expiration, and data-integrity verification. The project does not claim absolute protection.

Before any real-world use, the software should undergo testing, code review, and independent security assessment.

## Network Participation

The network will initially be closed. Both users and storage-node operators may require approval before participating.

Participating as a storage node does not grant access to stored file contents. Nodes must operate only within the rules, limits, and technical requirements defined by the project.

## Development Direction

Initial development will proceed gradually:

1. Define the threat model clearly;
2. Build a local prototype using test files only;
3. Implement member access control and credentials;
4. Implement verifiable fragmentation and reconstruction;
5. Test expiration, limits, availability, and failure handling;
6. Perform security review before expanding the network.

Internal architecture and implementation details may remain private during the early research phase.

## Responsible Use

BlackNet must be used only for lawful purposes and in compliance with applicable laws. The project does not support illegal activity, unauthorized distribution of content, privacy violations, or abuse of other participants' infrastructure.

## Author

Created and maintained by **Voided** — [@voidfd](https://github.com/voidfd)

## License

This project is licensed under the **GNU Affero General Public License v3.0 (AGPL-3.0)**. See [LICENSE](LICENSE) for details.
