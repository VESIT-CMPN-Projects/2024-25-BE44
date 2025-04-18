# 🏥 IMOBS: Blockchain-based Medicine Ordering System via IVR

**IMOBS (Interactive Voice Response-based Medicine Ordering System using Blockchain)** is a secure, accessible, and innovative healthcare solution tailored for populations with limited access to smartphones or the internet. Designed with simplicity and transparency in mind, the system empowers users to order medicines through basic voice calls, leveraging the power of blockchain for trust and traceability.

---

## 📜 Abstract

A large segment of the population, especially the elderly and rural communities, face barriers when accessing digital healthcare platforms due to low digital literacy and limited internet access. IMOBS addresses this gap by allowing users to order medicines using IVR calls—without needing a smartphone or technical know-how.

Blockchain, specifically **Hyperledger Fabric**, is employed to ensure transparency, integrity, and traceability in the pharmaceutical supply chain. Every transaction, from prescription validation to medicine delivery, is securely recorded on a tamper-proof distributed ledger.

---

## 🏢 Participating Organizations & Contributors

### 🏫 Vivekanand Education Society’s Institute of Technology (VESIT), Mumbai  
The research and implementation were carried out at the Department of Computer Engineering, VESIT, a reputed institution known for innovation in technology-driven solutions.

**Contributors:**
- Mr. Richard Joseph (Assistant Professor) – [richard.joseph@ves.ac.in](mailto:richard.joseph@ves.ac.in)
- Chinmay Phapale – [2021.chinmay.phapale@ves.ac.in](mailto:2021.chinmay.phapale@ves.ac.in)
- Aditya Kushwaha – [2021.aditya.kushwaha@ves.ac.in](mailto:2021.aditya.kushwaha@ves.ac.in)
- Lintomon Chirakkara – [2021.lintomon.chirrakara@ves.ac.in](mailto:2021.lintomon.chirrakara@ves.ac.in)
- Vedant Talwalkar – [2021.vedant.talwalkar@ves.ac.in](mailto:2021.vedant.talwalkar@ves.ac.in)

---

## 🔧 Tech Stack

| Component                | Description                                                                 |
|-------------------------|-----------------------------------------------------------------------------|
| **IVR System**          | Captures voice inputs from users, offering a user-friendly interface for medicine ordering. |
| **Fabric Client**       | Central controller that communicates between the IVR system and blockchain network. |
| **Hyperledger Fabric**  | Blockchain framework ensuring decentralized, tamper-proof transaction records. |
| **Smart Contracts**     | Implement business logic for order validation, prescription authenticity, and delivery tracking. |
| **OCR (Optical Character Recognition)** | Used by doctors/hospitals and delivery partners to digitize and validate prescriptions. |
| **CouchDB**             | State database for maintaining current world state in the blockchain ledger. |

---

## ⚙️ System Architecture Overview

1. **User:** Orders medicines through IVR; can upload prescriptions or use a pre-generated code.
2. **Doctor/Hospital:** Validates prescriptions using OCR and digital signatures.
3. **Pharmacist:** Verifies and prepares medicines once prescriptions are approved.
4. **Delivery Partner:** Ensures proper delivery and on-spot OCR validation if needed.
5. **Blockchain Network:** Records each transaction immutably—from order to delivery confirmation.

---

## 🔐 Why Blockchain?

- **Tamper-Proof Ledger:** Ensures all transactions are immutable and transparent.
- **Prescription Validation:** Prevents misuse by validating each order with verified prescriptions.
- **Counterfeit Prevention:** Every medicine’s source is traceable.
- **Trust & Compliance:** All participants are accountable within a decentralized ecosystem.

---

## 📈 Future Enhancements

- Integration with AI to provide **automated medical advice**.
- Natural Language Processing (NLP) for **smarter voice command understanding**.
- Expansion of services to include **consultation, emergency support, and real-time medicine tracking**.

---

## 🧠 References

The project builds upon literature in IVR systems, blockchain healthcare applications, and pharmaceutical traceability. A comprehensive list of academic references is included in the original paper.
