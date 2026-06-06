
# Soldrift / devbeast5775 — Solana Tool Vendor Security Warning

# Security Notice: Solana Tool Vendor Risk Report

This repository is a public safety notice for Solana builders, traders, and project owners.

This notice is **not** a call for harassment, threats, doxxing, retaliation, or mass reporting.
Do not contact, threaten, harass, or target any individual mentioned here.

The purpose of this page is limited to documenting a security/payment incident and warning others to use strong precautions before sharing funds, private keys, API keys, server access, or production credentials with unknown third-party developers.

---

## Identifiers Referenced

The following public identifiers were involved in the incident report:

* GitHub profile: `https://github.com/soldrift`
* GitHub username observed: `soldrift`
* Display name observed: `Soldrift`
* Telegram handle observed: `@devbeast5775`

These identifiers are listed only to help other users recognize the same vendor/contact.
No private personal information is published here.

---

## Summary

A third-party Solana/web tooling developer relationship was initiated through Telegram.

The vendor presented themselves as a Solana tool developer and was given payment and server access for a Solana-related dashboard/bundler project.

After the incident, multiple security concerns were identified, including:

* wallet/private-key handling risk,
* server root-access risk,
* API-key/RPC-key exposure risk,
* unsafe operational setup risk,
* and payment-delivery concerns.

Because Solana tools may involve private keys, seed phrases, wallet funding, RPC keys, transaction signing, and server access, even a partially unsafe setup can create serious financial risk.

This notice is published to help other builders avoid sharing sensitive credentials or production access without independent code review, isolated testing, and strict wallet separation.

---

## Incident Timeline

1. A Solana/web tool development arrangement was discussed through Telegram.
2. Payment was sent for development work.
3. Server access was provided for setup/modification.
4. A Solana-related tool/project was delivered or modified.
5. After review, security and wallet-safety concerns were identified.
6. Server access was removed and credentials were rotated.
7. Wallets, API keys, and server configuration were reviewed.
8. Evidence was preserved for platform reports, exchange reports, and potential legal follow-up.

This report does not publish the full private conversation because it may contain unrelated or sensitive private information.

---

## Public Safety Warning

Do not share the following with unknown or unverified third-party developers:

* private keys,
* seed phrases,
* wallet export files,
* API keys,
* RPC keys,
* dashboard passwords,
* server root access,
* production source-code access,
* funded wallets,
* or production credentials.

If you already shared any of the above, rotate them immediately and move funds to new wallets.

Recommended precautions:

* use disposable wallets only,
* test with very small amounts first,
* run tools only on isolated servers,
* remove developer access after setup,
* review `.env` values manually,
* verify safe-withdraw addresses,
* check for unexpected external URLs or webhooks,
* and confirm that API ports are not publicly exposed.

---

## Evidence Preserved

The following evidence has been preserved privately for reports and review:

* Telegram export,
* payment transaction records,
* wallet address records,
* TXID records,
* GitHub profile/repository screenshots,
* server logs,
* file snapshots,
* delivered project files,
* access timeline,
* payment timeline,
* and post-incident security review notes.

Only limited relevant screenshots or transaction identifiers may be shown publicly.

---

## Related Evidence

Add screenshots below.

### GitHub Profile / Availability Evidence

<img width="1905" height="910" alt="GitHub evidence screenshot" src="https://github.com/user-attachments/assets/257d96aa-3ae4-40e2-9ce3-2faf27e77bdb" />

### Telegram Profile Evidence

<img width="396" height="697" alt="Telegram evidence screenshot" src="https://github.com/user-attachments/assets/c9284b8e-a981-4805-908b-bc12b0b29aa3" />

### Payment / TXID Evidence

<img width="1371" height="622" alt="Payment evidence screenshot" src="https://github.com/user-attachments/assets/4b9a0f1d-20f5-4666-b6b9-adf05a57552a" />

---

## Wallet / Transaction Identifiers

Primary wallet observed:

`E8RcJDs3SaBP2udWy6bD7576zJ3WitfbVh16vgeqoAgi`

Related wallet observed:

`5cZWa1KZQnMPeXTHPRF8JSEPMhzRaHPehAoG1rPtiHGc`

Transaction reference:

`33Jc35XrQwhFAZN93Gcsyi2a3Zb9ujgxNeSPcD2xUMzcQ3b18kqCUHHhUdzzAY5dNDgQHSfqFM7RshX7A4KvCnKW`

Solscan reference:

`https://solscan.io/tx/33Jc35XrQwhFAZN93Gcsyi2a3Zb9ujgxNeSPcD2xUMzcQ3b18kqCUHHhUdzzAY5dNDgQHSfqFM7RshX7A4KvCnKW`

---

## Remediation Taken

After the incident, the following actions were taken:

* developer access removed,
* server password rotated,
* SSH keys reviewed and removed,
* firewall rules reviewed,
* IPv6 SSH access restricted,
* API/RPC keys reviewed or rotated,
* exposed wallets abandoned or rotated,
* `.env` and wallet data permissions restricted,
* server ports reviewed,
* project files reviewed for unsafe behavior,
* and evidence archived.

---

## Final Note

This is a documented security and payment-risk notice.

It is not an instruction to harass, threaten, doxx, or retaliate against anyone.

Builders should independently verify developers, isolate test environments, avoid sharing private keys, and never fund third-party tools with production wallets until the code, server access, wallet flow, and withdrawal paths have been reviewed.

