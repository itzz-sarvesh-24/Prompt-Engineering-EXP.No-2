# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM:
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## SCENARIO:
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

1.Accuracy

2.Coherence

3.Simplicity

4.Speed

5.User experience

## OUTPUT:

Prompt:
The Basics of Blockchain Technology
Blockchain technology is a decentralized digital ledger system used to record
transactions securely and transparently across a network of computers. Unlike
traditional databases that rely on a central authority, blockchain operates through a
distributed network where each participant maintains a copy of the ledger. This
structure reduces the need for intermediaries and increases trust among users. The
main idea behind blockchain is to create a system where data can be recorded in a
secure, tamper-resistant, and verifiable way.
A blockchain is composed of a sequence of blocks that store transaction data. Each
block contains three main components: the transaction data, a timestamp, and a
cryptographic hash of the previous block. The hash acts like a digital fingerprint,
uniquely identifying each block. Because every block contains the hash of the
previous block, the blocks are linked together in chronological order, forming a chain.
If someone attempts to alter the data in a block, the hash changes, breaking the
chain and making the tampering easily detectable.
One of the key features of blockchain technology is decentralization. In a
decentralized network, control is distributed among many nodes (computers) rather
than a single central authority. Each node participates in validating and storing
transactions. This structure improves system reliability because the network can
continue functioning even if some nodes fail or are attacked. It also increases
transparency since all participants can view and verify the transactions recorded on
the ledger.
To maintain accuracy and trust in the network, blockchain uses consensus
mechanisms. These are protocols that allow network participants to agree on the
validity of transactions before they are added to the blockchain. Two common
consensus mechanisms are Proof of Work (PoW) and Proof of Stake (PoS). In Proof
of Work, participants called miners solve complex mathematical puzzles to validate
transactions and create new blocks. In Proof of Stake, validators are chosen based
on the amount of cryptocurrency they hold and are willing to “stake” as collateral.
These mechanisms help prevent fraudulent activities such as double spending.
Blockchain technology is widely known for its role in supporting cryptocurrencies like
Bitcoin and Ethereum. In cryptocurrency systems, blockchain enables secure peerto-peer transactions without the need for banks or financial intermediaries. Every
transaction is recorded on the blockchain and can be verified by anyone on the
network, ensuring transparency and accountability.
Beyond cryptocurrencies, blockchain has many applications across different
industries. In supply chain management, blockchain can track products from their
origin to the final consumer, improving traceability and reducing fraud. In healthcare,
it can securely store patient records and allow authorized professionals to access
them when needed. In digital identity systems, blockchain can help individuals
control and verify their personal information without relying on centralized authorities.
Despite its advantages, blockchain technology also faces challenges such as high
energy consumption in some consensus mechanisms, scalability limitations, and
regulatory concerns. However, ongoing research and technological advancements
aim to address these issues and improve the efficiency of blockchain systems.
In conclusion, blockchain technology provides a secure, transparent, and
decentralized method of recording and verifying transactions. Its unique structure
and consensus mechanisms make it a powerful tool for building trust in digital
systems, and its potential applications continue to expand across various sectors.
summarize this paragraph.
OUTPUT:
ChatGPT:
Summary:
Blockchain technology is a decentralized digital ledger that securely records
transactions across a distributed network of computers. Transactions are stored in
blocks linked together using cryptographic hashes, making the data transparent
and difficult to alter. The network relies on consensus mechanisms such as Proof
of Work and Proof of Stake to validate transactions without a central authority.
While blockchain is widely used for cryptocurrencies like Bitcoin and Ethereum, it
also has applications in supply chain management, healthcare, and digital
identity systems. Although it offers benefits like security, transparency, and trust,
challenges such as energy consumption, scalability, and regulation still exist.
Gemini:
Blockchain technology is a decentralized digital ledger that records transactions
across a network of computers, eliminating the need for a central authority. Each
"block" in the chain contains data, a timestamp, and a unique cryptographic
hash of the previous block, making the system tamper-resistant and transparent.
Key points include:
 Security & Consensus: The network stays accurate through mechanisms
like Proof of Work (mining) or Proof of Stake (staking), which validate
transactions and prevent fraud.
 Decentralization: Data is stored across many nodes, ensuring the system
remains functional and verifiable even if parts of it fail.
 Versatile Applications: While famous for cryptocurrencies like Bitcoin, it is
also used to secure medical records, track supply chains, and manage digital
identities.
 Current Hurdles: The technology still faces challenges regarding high
energy use, scalability, and regulation.
Claude:
Blockchain is a decentralized digital ledger that records transactions across
networked computers in tamper-proof blocks linked by cryptographic hashes,
ensuring security and transparency without central authorities. Key features include
decentralization for reliability, consensus mechanisms like Proof-of-Work (miners
solve puzzles) or Proof-of-Stake (validators stake crypto) to validate transactions and
prevent fraud. Famous for powering cryptocurrencies like Bitcoin and Ethereum, it
also applies to supply chains (traceability), healthcare (secure records), and digital
identities. Challenges include energy use and scalability, but advancements continue
to expand its potential.
Copilot:
Here’s a clear, condensed summary of the passage:
Blockchain technology is a decentralized, tamper-resistant digital ledger that
records transactions across a network of computers. It stores data in linked blocks
containing transaction details, timestamps, and cryptographic hashes, making
alterations easily detectable. Decentralization distributes control among nodes,
enhancing reliability and transparency. Accuracy is maintained through consensus
mechanisms like Proof of Work and Proof of Stake, which prevent fraud. While
best known for powering cryptocurrencies such as Bitcoin and Ethereum, blockchain
also supports applications in supply chains, healthcare, and digital identity
systems. Despite challenges like energy use, scalability, and regulation, ongoing
innovation continues to expand its potential.
Prompting Techniques:
Prompt:
The Basics of Blockchain Technology
Blockchain technology is a decentralized digital ledger system used to record
transactions securely and transparently across a network of computers. Unlike
traditional databases that rely on a central authority, blockchain operates through a
distributed network where each participant maintains a copy of the ledger. This
structure reduces the need for intermediaries and increases trust among users. The
main idea behind blockchain is to create a system where data can be recorded in a
secure, tamper-resistant, and verifiable way.
A blockchain is composed of a sequence of blocks that store transaction data. Each
block contains three main components: the transaction data, a timestamp, and a
cryptographic hash of the previous block. The hash acts like a digital fingerprint,
uniquely identifying each block. Because every block contains the hash of the
previous block, the blocks are linked together in chronological order, forming a chain.
If someone attempts to alter the data in a block, the hash changes, breaking the
chain and making the tampering easily detectable.
One of the key features of blockchain technology is decentralization. In a
decentralized network, control is distributed among many nodes (computers) rather
than a single central authority. Each node participates in validating and storing
transactions. This structure improves system reliability because the network can
continue functioning even if some nodes fail or are attacked. It also increases
transparency since all participants can view and verify the transactions recorded on
the ledger.
To maintain accuracy and trust in the network, blockchain uses consensus
mechanisms. These are protocols that allow network participants to agree on the
validity of transactions before they are added to the blockchain. Two common
consensus mechanisms are Proof of Work (PoW) and Proof of Stake (PoS). In Proof
of Work, participants called miners solve complex mathematical puzzles to validate
transactions and create new blocks. In Proof of Stake, validators are chosen based
on the amount of cryptocurrency they hold and are willing to “stake” as collateral.
These mechanisms help prevent fraudulent activities such as double spending.
Blockchain technology is widely known for its role in supporting cryptocurrencies like
Bitcoin and Ethereum. In cryptocurrency systems, blockchain enables secure peer-
to-peer transactions without the need for banks or financial intermediaries. Every
transaction is recorded on the blockchain and can be verified by anyone on the
network, ensuring transparency and accountability.
Beyond cryptocurrencies, blockchain has many applications across different
industries. In supply chain management, blockchain can track products from their
origin to the final consumer, improving traceability and reducing fraud. In healthcare,
it can securely store patient records and allow authorized professionals to access
them when needed. In digital identity systems, blockchain can help individuals
control and verify their personal information without relying on centralized authorities.
Despite its advantages, blockchain technology also faces challenges such as high
energy consumption in some consensus mechanisms, scalability limitations, and
regulatory concerns. However, ongoing research and technological advancements
aim to address these issues and improve the efficiency of blockchain systems.
In conclusion, blockchain technology provides a secure, transparent, and
decentralized method of recording and verifying transactions. Its unique structure
and consensus mechanisms make it a powerful tool for building trust in digital
systems, and its potential applications continue to expand across various sectors.
summarize this paragraph in Zero-Shot ,Few-Shot ,Chain-of-Thought ,Role-Based
Prompt Technique
ChatGPT:
1. Zero-Shot Prompting
Summary:
Blockchain is a decentralized digital ledger that records transactions
across a network of computers without a central authority. Transactions
are stored in blocks linked by cryptographic hashes, making the data
secure and tamper-resistant. The network verifies transactions using
consensus mechanisms like Proof of Work (PoW) and Proof of Stake
(PoS). Blockchain is widely used in cryptocurrencies such as Bitcoin
and Ethereum and has applications in supply chains, healthcare, and
digital identity systems. Despite advantages like transparency and
security, it faces challenges such as scalability, energy consumption,
and regulatory issues.
2. Few-Shot Prompting
Summary:
Blockchain technology is a distributed and decentralized system that
securely records transactions across multiple computers. Data is stored
in blocks connected through cryptographic hashes, forming a tamperresistant chain. Transactions are verified through consensus methods
such as PoW and PoS, ensuring trust without a central authority. While
blockchain powers cryptocurrencies like Bitcoin and Ethereum, it is also
used in sectors like healthcare, supply chain management, and digital
identity. The technology improves transparency and security but still
faces challenges related to scalability and energy usage.
3. Chain-of-Thought Prompting
Step-by-Step Reasoning Summary:
1. Definition: Blockchain is a decentralized ledger used to record and
verify transactions across a distributed network.
2. Structure: Transactions are grouped into blocks containing data,
timestamps, and cryptographic hashes linking them together.
3. Security: The linking of blocks ensures that any data modification
is easily detected.
4. Validation: Consensus mechanisms such as Proof of Work and
Proof of Stake verify transactions before adding them to the chain.
5. Applications: Blockchain powers cryptocurrencies like Bitcoin and
Ethereum and is also used in industries like healthcare and supply
chains.
6. Conclusion: While blockchain offers transparency, security, and
decentralization, it still faces challenges like scalability, energy
consumption, and regulatory concerns.
4. Role-Based Prompting
Role: Technology Analyst
As a technology analyst, the article explains that blockchain technology
is a decentralized system for securely recording transactions across
multiple computers. It uses cryptographic hashing and distributed
consensus mechanisms to ensure data integrity and transparency
without relying on a central authority. The technology is most
recognized for enabling cryptocurrencies such as Bitcoin and Ethereum.
Beyond digital currencies, blockchain supports applications in supply
chain tracking, healthcare data management, and digital identity
verification. Although it provides strong security and trust, ongoing
improvements are needed to address issues like scalability, energy
usage, and regulatory frameworks.
Gemini:
1. Zero-Shot
Directly summarizing the content without prior examples.
Summary: Blockchain is a decentralized digital ledger that records transactions
across a network of computers using linked "blocks" secured by cryptographic
hashes. By utilizing consensus mechanisms like Proof of Work and Proof of Stake, it
ensures security and transparency without a central authority. While it famously
powers cryptocurrencies, its applications extend to supply chains and healthcare,
though it still faces hurdles like scalability and energy use.
2. Few-Shot
Simulating a pattern based on examples (e.g., Topic: One-sentence summary).
Input Example 1: [Article about AI] -> AI mimics human intelligence to solve
complex tasks.
Input Example 2: [Article about Solar Power] -> Solar power converts sunlight into
electricity for sustainable energy.
Summary: Blockchain technology provides a secure, decentralized way to verify and
store data across a global network.
3. Chain-of-Thought
Breaking down the logic step-by-step before reaching a conclusion.
 Step 1 (Core Identity): It is a decentralized, distributed ledger system.
 Step 2 (Mechanism): Blocks are linked by hashes, making them tamperresistant.
 Step 3 (Validation): Consensus protocols (PoW/PoS) verify data without
intermediaries.
 Step 4 (Utility & Challenges): It is used in crypto and industry but faces
energy and scaling issues.
Summary: Consequently, blockchain is a secure framework that uses
cryptographic linking and collective validation to create a transparent, multiindustry tool for trustless data management.
4. Role-Based
Writing from the perspective of a specific persona.
Role: Tech Consultant for Beginners
"Think of blockchain as a shared digital record book that nobody can cheat. Instead
of one bank keeping the books, everyone in the network has a copy. It uses clever
math (hashes) to lock information in a chain, making it nearly impossible to hack.
While it’s the engine behind Bitcoin, it’s also revolutionizing how we track products
and protect medical data, despite some current 'growing pains' regarding speed and
power usage."
Claude:
Zero-Shot Prompt
Prompt: "Summarize the article 'The Basics of Blockchain Technology' in 100 words
or less, covering definition, structure, features, and applications."
Summary: Blockchain is a decentralized ledger recording transactions in linked
blocks via cryptographic hashes for tamper-resistance. Key features:
decentralization across nodes, consensus like PoW (mining puzzles) or PoS
(staking). Powers crypto (Bitcoin, Ethereum); applies to supply chains, healthcare,
identities. Challenges: energy use, scalability.
Few-Shot Prompt
Prompt:
"Example 1:
Input: Brief on AI.
Output: AI mimics human intelligence via machines learning from data.
Example 2:
Input: What is cloud computing?
Output: Cloud computing delivers on-demand resources over internet, scalable
without owning hardware.
Now summarize: [full text]."
Summary: Blockchain is a decentralized ledger of transaction blocks linked by
hashes, ensuring security without central control. Nodes validate via PoW or PoS
consensus; enables crypto like Bitcoin, plus supply chain tracking, health records,
identities. Faces energy and scale issues.
Chain-of-Thought Prompt
Prompt: "Summarize the article step-by-step: 1. Identify main topic. 2. List key
components (structure, features). 3. Note mechanisms and apps. 4. Mention
challenges. 5. Combine into 1 paragraph."
Summary:
1. Main topic: Basics of blockchain as decentralized ledger.
2. Structure: Blocks with data, timestamp, prior hash; chain links them. Features:
Decentralized nodes for reliability/transparency.
3. Mechanisms: PoW (puzzles), PoS (staking); apps: Crypto (Bitcoin/Ethereum),
supply chain, healthcare, IDs.
4. Challenges: Energy, scalability, regs.
Combined: Blockchain chains secure transaction blocks across decentralized
nodes using PoW/PoS consensus, powering crypto and industries like supply
chains despite energy hurdles.
Role-Based Prompt
Prompt: "You are a tech educator. Explain 'The Basics of Blockchain Technology'
article to a beginner in a 150-word summary, using simple analogies."
Summary: Imagine blockchain as a shared notebook where everyone writes
transactions in pages (blocks) locked with unique codes (hashes) linking to the
previous page—no single boss in charge. Computers (nodes) copy the notebook for
backup and vote on additions via puzzles (PoW) or bets (PoS) to keep it honest.
Famous for Bitcoin cash swaps without banks; also tracks food from farm to table,
secures health files, and manages IDs. It's super secure and open, but guzzles
energy and grows slowly—fixes are coming!
Copilot:
🔹 Zero-Shot
A direct summary without examples or prior guidance.
Summary:
Blockchain is a decentralized digital ledger that records transactions securely and
transparently across a network of computers. It links blocks of data using
cryptographic hashes, making tampering detectable. Consensus mechanisms like
Proof of Work and Proof of Stake ensure trust and prevent fraud. While best known
for cryptocurrencies, blockchain also supports applications in supply chains,
healthcare, and digital identity. Challenges include energy use, scalability, and
regulation, but ongoing research seeks solutions.
🔹 Few-Shot
Summarization after being shown examples of how summaries should look
(simulated here).
Example Summaries (few-shot style):
 Example 1: "AI is reshaping industries by automating tasks and improving
efficiency."
 Example 2: "Climate change is driven by human activity and requires urgent
global action."
Summary (following the examples):
Blockchain is a secure, decentralized ledger system that links blocks of data with
cryptographic hashes. It uses consensus mechanisms to validate transactions,
supports cryptocurrencies, and has broader applications in supply chains,
healthcare, and identity management. Despite challenges like energy consumption
and scalability, it remains a transformative technology.
🔹 Chain-of-Thought
Step-by-step reasoning before producing the summary.
Reasoning:
1. Blockchain is defined as decentralized and secure.
2. Its structure: blocks + hashes + timestamps.
3. Consensus mechanisms ensure trust (PoW, PoS).
4. Applications: cryptocurrencies, supply chain, healthcare, identity.
5. Challenges: energy, scalability, regulation.
6. Conclusion: powerful but evolving technology.
Summary:
Blockchain is a decentralized, tamper-resistant ledger that uses cryptographic links
and consensus mechanisms to ensure trust. It underpins cryptocurrencies and offers
applications in industries like supply chain and healthcare, though it faces energy
and scalability challenges.
🔹 Role-Based Prompt Technique
Summarization from different perspectives or roles.
 Teacher:
"Blockchain is like a digital notebook shared across many computers. Each
page (block) is linked to the previous one with a special code (hash), making it
hard to cheat. People agree on what gets written using rules called consensus
mechanisms. It’s used in Bitcoin but also in healthcare and supply chains."
 Business Analyst:
"Blockchain provides decentralized trust by eliminating intermediaries. Its
applications extend beyond cryptocurrency into supply chain transparency,
secure health records, and digital identity. Key challenges include scalability
and regulatory frameworks."
 Technologist:
"Blockchain is a distributed ledger secured by cryptographic hashes and
consensus protocols such as PoW and PoS. It ensures immutability and
transparency, enabling peer-to-peer transactions and industry applications,
though energy efficiency and scalability remain pressing issues."
Would you like me to also compare these techniques side-by-side in a table so
you can quickly see how the style shifts?
 Platform Comparison:
Platform Accuracy Coherence Simplicity Speed User Experience
ChatGPT High Very High Very High Fast Excellent
Gemini High High High Very Fast Good
Claude Very High Very High High Moderate Excellent
Platform Accuracy Coherence Simplicity Speed User Experience
Copilot Medium Medium Medium Fast Good
Prompting Technique Comparison:
Prompt Technique Strengths Weaknesses
Zero-Shot Fast, simple May miss details
Few-Shot Consistent structure Requires examples
Chain-of-Thought High accuracy and reasoning Slightly slower
Role-Based Most student-friendly summaries Depends on role clarity
Conclusion:
The study shows that prompt design significantly impacts AI output quality. For
educational content summarization:
 Best Prompting Technique: Chain-of-Thought + Role-Based
 Best Platform: ChatGPT or Claude
Combining structured reasoning with a clear educational role produces summaries
that are accurate, coherent, and easy for students to understand.


## RESULT:
The experiment provided a clear understanding of Generative AI, its models, modern AI tools, and the construction of LLMs. The evolution timeline highlights how AI has progressed from rule-based systems to advanced generative and multimodal intelligence.
