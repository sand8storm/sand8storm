Claude




























Readme · MD
# Michel Aljed
 
**Offensive Security Engineer · Penetration Tester** · Damascus, Syria
 
I test web applications for security flaws before someone else finds them, and build the tooling that makes each finding verifiable. Cybersecurity Engineer at Syber X Fortress (Damascus). Final-year Informatics Engineering (Cybersecurity) student at Antioch Private Syrian University, with research experience in algorithms, AI, and combinatorial optimization.
 
[cyborgt.me](https://cyborgt.me) · [العربية](https://cyborgt.me/ar) · [LinkedIn](https://www.linkedin.com/in/michel-aljed-566240334) · [CV](https://cyborgt.me/Michel_Aljed_CV.pdf) · michel.aljad@gmail.com
 
## Security tooling
 
**[Beast403](https://github.com/sand8storm/Beast403)**: accuracy-first 403/401 bypass scanner. Validates every candidate bypass against live per-target oracles using SimHash structural classification, with a raw-socket engine to defeat client-side path normalization. Independent four-server benchmark: 100% precision, zero false positives across 28 negative targets, 67% recall. [Case study](https://cyborgt.me/beast403).
 
```
pip install beast403
```
 
**SSTIeye** (in progress): server-side template injection scanner. Uses randomized arithmetic probes confirmed against a baseline response, so real template evaluation is separated from plain reflection.
 
**Pentest RAG assistant** (in progress): a locally-run LLM (Qwen via Ollama) with a retrieval layer over pentest and bug-bounty references, to automate the routine parts of reconnaissance and reporting while keeping data on-device.
 
## Security work
 
- Authorized black-box penetration tests of Syrian university and commercial web portals, and an OSINT-driven assessment of a public-sector portal. University portal: 21 findings, 8 critical, 24 matched CVEs. Public-sector portal: 19 subdomains mapped, 20 findings, 9 critical or high. Client details withheld under confidentiality.
- Responsible disclosure to a global device manufacturer's Security Response Center: an Apache APISIX admin dashboard exposed to the internet, ownership verified via its TLS certificate.
- Bug bounty and responsible disclosure as **sand666wind** on [HackerOne](https://hackerone.com/sand666wind), [Intigriti](https://app.intigriti.com/profile/sand666wind), and [Bugcrowd](https://bugcrowd.com/sand666wind).
## Writing
 
- [Why hasn't Syria been fully breached, yet?](https://cyborgt.me/writeups/why-syria) (Arabic): OSINT and passive-scan study of Syria's digital exposure.
## Research
 
- **TSP heuristics:** systematic empirical study of 20+ construction, local-search, and metaheuristic methods under a significance-tested protocol.
- **LKH candidate generation:** a topological candidate set (MST ∪ Delaunay ∪ k-NN) matched α-nearness quality at roughly 20× the speed, framed as independent verification.
- **Riemann zeta zeros:** autoencoder-based unsupervised analysis of Odlyzko's dataset.
## Stack
 
Python · C++ · Bash · SQL · raw-socket HTTP · NumPy · Pandas · scikit-learn · MATLAB · Linux / Kali
 
## Also
 
Arabic-language technical content on cybersecurity and programming at [@cyborg.div](https://instagram.com/cyborg.div).
 
Claude finished the response
