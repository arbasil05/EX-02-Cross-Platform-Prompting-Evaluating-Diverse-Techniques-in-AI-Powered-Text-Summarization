# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

---

## Scenario:
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

- Accuracy  
- Coherence  
- Simplicity  
- Speed  
- User experience  

---

## Prompting Techniques Used

### 1. Zero-Shot Prompting
"Summarize the given blockchain article in ~200 words."

### 2. Few-Shot Prompting
"Here are 2 example summaries (simple + structured). Generate a similar summary for the blockchain article."

### 3. Chain-of-Thought Prompting
"Break the article into key concepts step-by-step, then produce a final summary."

### 4. Role-Based Prompting
"Act as a computer science professor and summarize blockchain for undergraduate students."

---

## LLM Outputs

---

# 🔹 ChatGPT

### Zero-Shot Output
Blockchain is a decentralized ledger that records transactions securely across a distributed network. It uses consensus mechanisms and cryptographic hashing to maintain data integrity. Applications include cryptocurrency, supply chains, and healthcare.

### Few-Shot Output
Blockchain is a distributed system where transactions are stored in blocks linked via hashes. It ensures transparency, immutability, and security. Consensus methods like PoW and PoS validate data. It is used in finance, identity systems, and smart contracts.

### Chain-of-Thought Output
Step 1: Blockchain is a decentralized ledger.  
Step 2: Data is stored in blocks linked with hashes.  
Step 3: Consensus mechanisms validate transactions.  
Step 4: Applications include crypto and supply chains.  

Final Summary:  
Blockchain securely stores transactions in a decentralized network using cryptography and consensus, enabling trustless systems.

### Role-Based Output
As a professor would explain, blockchain is a distributed ledger system ensuring secure and immutable transactions. It uses consensus algorithms and cryptography to eliminate intermediaries and supports applications like cryptocurrencies and smart contracts.

---

# 🔹 Gemini

### Zero-Shot Output
Blockchain is a peer-to-peer distributed ledger that records transactions in linked blocks. It ensures integrity through cryptographic hashing and consensus mechanisms.

### Few-Shot Output
Blockchain consists of blocks containing transactions and hashes of previous blocks. It maintains decentralization, transparency, and security. It is widely used beyond cryptocurrency.

### Chain-of-Thought Output
Step 1: Define blockchain as distributed ledger  
Step 2: Explain blocks and hashing  
Step 3: Describe consensus  
Step 4: Mention applications  

Final Summary:  
Blockchain is a decentralized system ensuring secure and transparent transactions using cryptography and distributed consensus.

### Role-Based Output
From a systems perspective, blockchain is a decentralized architecture that replaces centralized trust with cryptographic validation and consensus protocols.

---

# 🔹 Claude

### Zero-Shot Output
Blockchain is a distributed ledger where transactions are recorded in blocks linked via cryptographic hashes. It ensures transparency and security.

### Few-Shot Output
Blockchain stores transactions in linked blocks secured through hashing. Consensus mechanisms validate entries. It supports applications like cryptocurrencies and smart contracts.

### Chain-of-Thought Output
Step 1: Identify blockchain as ledger  
Step 2: Explain block structure  
Step 3: Add consensus concept  
Step 4: Mention applications  

Final Summary:  
Blockchain is a decentralized ledger system ensuring secure and immutable records through cryptographic linking and consensus.

### Role-Based Output
As an academic explanation, blockchain is a distributed ledger that ensures immutability and trust through decentralized validation and cryptographic techniques.

---

# 🔹 Copilot

### Zero-Shot Output
Blockchain is a decentralized digital ledger that stores transactions securely in linked blocks using cryptography.

### Few-Shot Output
Blockchain links data blocks using hashes, ensuring security and transparency. It uses consensus mechanisms and supports applications like cryptocurrencies.

### Chain-of-Thought Output
Step 1: Blockchain is distributed  
Step 2: Blocks store transactions  
Step 3: Hashing ensures integrity  
Step 4: Consensus validates  

Final Summary:  
Blockchain is a secure decentralized system for storing and validating transactions.

### Role-Based Output
As a technical instructor, blockchain is a distributed system that uses cryptographic methods and consensus algorithms to maintain secure and transparent records.

---

## Comparative Evaluation

### ChatGPT
- **Accuracy:** 9/10  
- **Coherence:** 9/10  
- **Simplicity:** 9.5/10  
- **Speed:** 9.5/10  
- **User Experience:** 9/10  

---

### Gemini
- **Accuracy:** 9/10  
- **Coherence:** 8.5/10  
- **Simplicity:** 8/10  
- **Speed:** 8.5/10  
- **User Experience:** 8/10  

---

### Claude
- **Accuracy:** 9.5/10  
- **Coherence:** 9.5/10  
- **Simplicity:** 8.5/10  
- **Speed:** 8/10  
- **User Experience:** 9/10  

---

### Copilot
- **Accuracy:** 8.5/10  
- **Coherence:** 8.5/10  
- **Simplicity:** 8.5/10  
- **Speed:** 8.5/10  
- **User Experience:** 8/10  

---

## Result

- **Best Overall Model:** Claude  
- **Best Prompting Technique:** Role-Based Prompting  
- **Best for Simplicity:** ChatGPT  
- **Best Structured Outputs:** Gemini  
- **Best Logical Breakdown:** Chain-of-Thought (across models)  

### Final Conclusion
Applying all prompting techniques across multiple AI platforms shows that output quality varies significantly based on both the model and prompting strategy. Role-based prompting consistently produced the most coherent and accurate summaries, while zero-shot prompting offered the fastest responses. Few-shot prompting improved structure, and chain-of-thought enhanced conceptual clarity.

Thus, combining the right prompting technique with the appropriate AI model is essential for achieving optimal summarization performance.
