<div align="center">

# Gagandeep

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=6C63FF&center=true&vCenter=true&width=650&lines=B.Tech+Computer+Engineering+%40+Thapar;ML+Research+%2B+Cloud+%2B+Systems+Engineering;I+build+the+unabstracted+version+of+the+problem" alt="Typing SVG" />

<br>

<img src="https://img.shields.io/badge/CGPA-8.55%2F10-6C63FF?style=for-the-badge" />
<img src="https://komarev.com/ghpvc/?username=Gagan2435&label=PROFILE+VIEWS&color=6C63FF&style=for-the-badge" alt="profile views" />
<img src="https://img.shields.io/github/followers/Gagan2435?label=FOLLOWERS&style=for-the-badge&color=6C63FF" alt="followers" />

*I don't stop at calling a library. Hand-written CUDA kernels instead of cuDNN. Self-collected datasets instead of a Kaggle download. Serverless architecture that costs nothing until someone actually uses it.*

</div>

<br>

## Experience

**ML Research Intern** — *Emotion-Aware Multilingual Speech AI* · ELC Internship, Thapar Institute of Engineering & Technology, under Dr. Aditi · Summer 2025

Joined a research team building a multilingual voice assistant that reads emotion from speech across six Indian languages — Hindi, Punjabi, Malayalam, Telugu, Gujarati, and Bengali. Within a six-person effort spanning all six languages, I was individually responsible for the Punjabi language track, run as an independent sub-project under the same supervision and publication goal.

Day to day, this meant coordinating and supervising live recording sessions inside the university (not just running a script against existing audio), making protocol decisions about sentence selection and emotion balance across the dataset, and iterating on the acoustic feature set once the first model runs came back weaker than expected on certain emotion classes. The work is now part of a conference publication currently in preparation, with the Punjabi results attributed to this track.

→ Full technical writeup and code: [Emotion-Voice-AI](https://github.com/Gagan2435/Punjabi-Speech-Emotion-Recognition)

<br>

## Projects

<table>
<tr>
<td width="100%">

### [ExamCloud — Serverless Online Examination System](https://github.com/Gagan2435/aws-serverless-online-examination-system)
No servers. No downtime. Just exams, scored the moment they're submitted. Every layer here — question delivery, answer submission, grading — runs on demand, in the cloud, and costs nothing when idle. Built entirely on managed AWS services, with no EC2 instance in sight.

**Result:** a complete Lambda → API Gateway → DynamoDB → S3/CloudFront pipeline that scales from one student to thousands with zero configuration change.

`AWS Lambda` `API Gateway` `DynamoDB` `S3` `CloudFront`

</td>
</tr>
<tr>
<td width="100%">

### [Cyber LexiBot](https://github.com/Gagan2435/Cyber-LexiBot)
Most people who've been scammed or harassed online don't know which law covers it, let alone what to do next. This bot reads a plain-language complaint the way a person would tell a friend what happened, and turns it into a classified incident, the relevant section of Indian cyber law, and a concrete next step. Fine-tuned DistilBERT for intent classification across six incident types, paired with Sentence-BERT + FAISS for legal-section retrieval and spaCy for entity extraction.

**Result:** roughly 84% classification accuracy under realistic, noise-injected evaluation on a 2,000-record test set.

`DistilBERT` `Sentence-BERT` `FAISS` `spaCy`

</td>
</tr>
<tr>
<td width="100%">

### [SoulChain — AI Blockchain Mood Journal](https://github.com/Gagan2435/AI-Blockchain-Mood-Journal)
A safe space for your feelings — analyzed by AI, sealed with Web3. Every entry gets read for emotion by TextBlob, then hashed with SHA-256 and published to the BlockDAG blockchain — proof that the entry existed, with the content itself never exposed. Built solo for the BlockDAG Hackathon 2025.

**Result:** a working live demo with full entry history and emotion-trend visualization, shipped within the hackathon window.

`Python` `Flask` `TextBlob` `BlockDAG` `SHA-256`

</td>
</tr>
<tr>
<td width="100%">

### [GPU-Accelerated Image Super-Resolution](https://github.com/Gagan2435/UCS645/tree/main/Project)
Most papers report a GPU speedup number without ever showing the CPU side of the comparison. This one builds both — the same four-layer CNN, trained under identical conditions, once with PyTorch on CPU and once with CUDA C++ written from scratch — so the speedup isn't a claim, it's a measurement. Every stage of the training loop, from forward convolution to the Adam optimizer update, runs as its own hand-written CUDA kernel.

**Result:** 2.31× faster training (1,447.88s → 626.26s), with the GPU run also converging to a lower final loss.

`CUDA C++` `PyTorch` `CNN` `VGG16 Perceptual Loss`

</td>
</tr>
</table>

<br>

## Technical Skills

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" />
  <img src="https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white" />
  <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
</p>

**ML / NLP:** DistilBERT · Sentence-BERT · FAISS · spaCy · librosa · scikit-learn
**Languages:** English, Hindi, Punjabi

<br>

## Reach Me

<p align="left">
  <a href="mailto:bsonu5147@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://github.com/Gagan2435"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
</p>

<div align="center">
<sub>Problem-solving · Quick learning · Teamwork · Time management · Adaptability</sub>
</div>
