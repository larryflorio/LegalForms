# Contract Provision: Multisig Wallet Operational Security Standards

## Section \[X\]: Operational Security Requirements for Multisig Wallet Management

To ensure the security of \[Company Name\]’s digital assets held in multisig wallets on which \[Service Provider\] is a signer, \[Service Provider\] shall implement and maintain operational security ("OpSec") standards at least as stringent as those set forth herein.

### 1\. Dedicated Air-Gapped Signing Devices

\[Service Provider\] shall ensure that all authorized personnel (“Signers”) tasked with approving multisig wallet transactions utilize dedicated, air-gapped devices (e.g., hardware wallets or isolated computers) exclusively for signing activities. Such devices shall remain offline at all times except during transaction signing, and the use of general-purpose devices (e.g., personal laptops or phones) for signing is expressly prohibited. Devices shall be sourced directly from the manufacturer whenever possible and from reputable vendors in all cases. Devices shall be verified for integrity upon receipt. The \[Service Provider\] shall conduct quarterly audits of all signing devices, with records available for \[Company Name\]’s review upon request.

### 2\. Out-of-Band Transaction Verification

The \[Service Provider\] shall implement a mandatory process whereby each Signer independently verifies every transaction through a secondary, secure, offline channel prior to approval. Verification shall include confirmation of transaction details (e.g., hash, recipient address, amount) via methods such as direct phone calls among Signers or designated security personnel, encrypted messages on pre-approved applications (e.g., Signal) using separate dedicated devices, or physical checklists countersigned by a non-signing supervisor. Approval shall be withheld if verification fails or discrepancies arise. Transaction logs, including verification records, shall be maintained and subject to monthly review, with copies provided to \[Company Name\] upon request.

### 3\. Diversified Signer Environments

The \[Service Provider\] shall ensure Signers operate from distinct physical and digital environments to mitigate the risk of simultaneous compromise. Signers shall be geographically dispersed (e.g., no two Signers in the same office or city unless impracticable), and each shall utilize a unique combination of operating system (e.g., Linux, MacOS), wallet software version, and hardware type. Shared networks among Signers or use of Windows operating systems are prohibited. The \[Service Provider\] shall conduct biannual audits of Signer environments, documenting compliance and obtaining \[Company Name\]’s written approval for any exceptions.

### 4\. Key Management and Rotation

The \[Service Provider\] shall securely manage and periodically rotate private keys associated with multisig wallets. Keys shall be exclusively stored offline. Keys shall not be reused across wallets or retained after wallet decommissioning. Key rotation shall occur at least every six (6) months or immediately following any suspected security incident. The \[Service Provider\] shall provide annual training to Signers on phishing and social engineering prevention, with training logs and key rotation schedules available for \[Company Name\]’s inspection upon request.

### 5\. Governance for Smart Contract Modifications

The \[Service Provider\] shall enforce heightened governance for any modifications to multisig wallet smart contracts. Routine transfers and changes to the multisig contract shall be distinct operations, with multisig contract changes requiring approval from at least eighty percent (80%) of Signers (e.g., 4-of-5 in a 3-of-5 configuration) and a forty-eight (48)-hour time-lock period. The \[Service Provider\] shall log all contract change requests and outcomes for quarterly review by a designated governance body, with records accessible to \[Company Name\].

### 6\. Compliance and Enforcement

- **Minimum Standard:** The \[Service Provider\] warrants that its OpSec practices for multisig wallet management shall meet or exceed the standards herein. Any deviation requires prior written consent from \[Company Name\].  
- **Roles:** The \[Service Provider\] shall designate personnel responsible for device management, audits, key oversight, transaction verification, and governance, ensuring separation of duties.  
- **Breach:** Failure to comply with these standards shall constitute a material breach of this Agreement, entitling \[Company Name\] to terminate the Agreement immediately and seek damages for any resulting losses.  
- **Audit Rights:** \[Company Name\] reserves the right to audit the Service Provider’s compliance with these standards annually or following any security incident, with reasonable notice.

### 7\. Review and Updates

The \[Service Provider\] shall review its OpSec practices annually or following any major security incident affecting multisig wallet operations, proposing updates to align with evolving threats. Any amendments to these standards shall be mutually agreed upon in writing by both Parties.  
