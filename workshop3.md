# 3rd ACCSS Security & AI Workshop

Organised by the <a href="https://secai-accss.github.io" target="_blank" rel="noopener">ACCSS Working Group on AI & Security</a>, this event brings together researchers at the intersection of security/privacy and artificial intelligence to foster innovation and share cutting-edge ideas, experiences, and collaboration opportunities.

A key feature of this year’s edition will be breakout sessions on topics collected from the community, enabling focused discussions and collaborative exchange on emerging challenges. Participants are also invited to submit abstracts for short talks/posters to present their work and engage with peers in an open and interactive setting.

When registering, you will have the opportunity to suggest topics for the breakout sessions, helping shape the conversation.

## Details
- Date: 24th September 2026
- Location: CVD Apeldoorn (Wapenrustlaan 11, 7321 DL Apeldoorn)
- Registration: [Register here](https://forms.cloud.microsoft/Pages/DesignPageV2.aspx?subpage=design&token=96b2a2ce538c47b08e310a618ed7a5c6&id=oUYycvXDxUOs3EOttASsTYMOvQu-34dGnACrN6AGnhBUM1owQTk4VVdUT01JSE1CRE9HTldDRUhHRC4u)
- Program: See the tentative programme below


<h2>Keynote Speakers</h2>

<div class="speaker">
  <img src="{{ '/assets/img/marten.jpg' | relative_url }}" alt="Marten van Dijk" loading="lazy">
  <div class="speaker-body">
    <h3><a href="https://www.cwi.nl/en/people/marten-van-dijk/" target="_blank" rel="noopener">Marten van Dijk</a> <span>— CWI and VU Amsterdam</span></h3>
    <p><strong>Talk Title:</strong> <em>PACZero is the answer where DP-SGD fails to give significant privacy guarantees</em></p>
    <p><strong>Abstract:</strong> The Differential Privacy (DP) framework has been extensively used by industry to market adherence to data privacy regulations of services and applications. The reported classical (eps,delta)-DP guarantees for services/applications based on complex learning tasks trained on (potentially) private data turn out to only prove that a successful interference attack is at least as hard as solving a simplified hypothesis testing problem which has a significant advantage over random guessing (the latter is equivalent to ideal privacy). This advantage turns out to be very large for complex learning tasks. In fact no significant privacy guarantee is given by the reported DP guarantees. Even though these reported DP guarantees are vacuous, non-vacuous (or stronger) DP guarantees are not chosen since these require considerably more noise and therefore will severely degrade the model’s utility. This translates the reported DP guarantees into a psychological sales trick, which even some researchers use in their research papers (likely benign due to their lack of understanding of what the DP framework actually stands for). We note that the added DP mechanism may actually provide a form of privacy, however, this can only be heuristically demonstrated by evaluating a benchmark suite of Membership Inference Attacks (MIAs).

We will explain recent theoretical results on the impossibility and possibility of using DP-SGD for training a neural network with significant DP guarantees. This leads to the question whether we may want to redefine the privacy framework so that it still captures the class of MIA attacks that we want to protect against in our practical setting as well as providing a proof technique that leads to strong privacy guarantees. The PAC Privacy framework provides such an alternative and we show a new ZO-SGD approach (for training neural networks), coined PACZero, that offers strong privacy guarantees.</p>
    <p><strong>About:</strong>Marten van Dijk founded and leads the Computer Security research group at CWI and is an IEEE Fellow for his expertise in secure processor design and encrypted calculations. Notable achievements include the creation of Aegis, a groundbreaking secure processor, and the development of influential protocols like ‘Path ORAM’ and ‘Fully Homomorphic Encryption over the Integers.’ Van Dijk is the recipient of the IEEE CS (Computer Society) Edward J. McCluskey Technical Achievement Award 2023 and the IEEE & ACM A. Richard Newton Technical Impact Award in Electronic Design Automation 2015. He has won several test-of-time awards (HPCA 2025, CCS 2023 and Intel 2022; as well as a most frequently cited paper award 2000-2009 Symposium on VLSI Circuits 2017, and an inclusion in the “25 years of International Conference on Supercomputing” 2014).</p>
  </div>
</div>

<hr>

<div class="speaker">
  <img src="{{ '/assets/img/fatih.jpg' | relative_url }}" alt="Fatih Turkmen headshot" loading="lazy">
  <div class="speaker-body">
    <h3><a href="https://www.rug.nl/staff/f.turkmen/?lang=en" target="_blank" rel="noopener">Fatih Turkmen</a> <span>— University of Groningen</span></h3>
    <p><strong>Talk Title:</strong> <em>To be announced</em></p>
    <p><strong>Abstract:</strong> To be announced.</p>
    <p><strong>About:</strong> Fatih Turkmen is an Associate Professor at the University of Groningen, where he has been affiliated since 2019. His research focuses on the security and privacy of/with AI systems, privacy-enhancing technologies, as well as formal and empirical approaches to security analysis of software and hardware. He has extensive experience in designing and developing decentralized security solutions, particularly in contexts involving processing of sensitive data (e.g., genomic data) or access to services. More recently, his work has expanded into the security and privacy challenges of neuromorphic systems (often associated with in-memory computing). His research explores key questions such as: What are the security and privacy vulnerabilities in software and hardware implementations of neuromorphic systems and how do ML attacks transfer to such systems? In this context, he investigates vulnerabilities across both software and hardware, drawing on techniques from machine learning security, side-channel analysis, and fuzz testing. He has contributed to several national and international research initiatives in these domains, including the Dutch LESSEN project. He serves as an editor for the International Journal of Information Security (IJIS), was General Chair of the 26th Information Security Conference (ISC), and regularly serves in program committees of leading security and privacy conferences such as CCS, PETs, and SACMAT.</p>
  </div>
</div>

<style>
.speaker{
  display:flex; gap:1rem; align-items:flex-start;
  background:#fff; border:1px solid #eee; border-radius:12px;
  padding:16px; box-shadow:0 1px 3px rgba(0,0,0,.04); margin:1rem 0;
}
.speaker img{
  width:110px; height:110px; border-radius:50%;
  object-fit:cover; border:1px solid #eee; flex:0 0 110px;
}
.speaker-body{min-width:0}
.speaker-body h3{margin:.2rem 0}
.speaker-body h3 span{font-weight:400; color:#666}
.speaker-body p{margin:.35rem 0}
@media (max-width: 540px){
  .speaker{flex-direction:column; align-items:center; text-align:center}
  .speaker img{width:96px; height:96px}
}
</style>


## Programme

*Tentative programme—times and sessions are subject to change.*

| Time | Activity |
| --- | --- |
| 9:30–10:00 | Walk-in |
| 10:00–10:10 | Welcome |
| 10:10–11:10 | Keynote by Marten van Dijk|
| 11:10–11:30 | Coffee + posters |
| 11:30–12:15 | Talks |
| 12:15–13:15 | Lunch |
| 13:15–14:15 | Keynote by Fatih Turkmen|
| 14:15–14:35 | Coffee + posters |
| 14:35–15:45 | Breakout sessions + Panel discussion |
| 15:45– | Drinks & Bitterballen + posters |

## Organizers

<div style="display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:16px;align-items:start;max-width:1000px;margin:0 auto 1rem;">
  <figure style="text-align:center;margin:0;">
    <img src="{{ '/assets/img/katja-tuma.jpeg' | relative_url }}" alt="Katja Tuma" style="width:160px;height:160px;object-fit:cover;border-radius:50%;display:block;margin:0 auto 8px;">
    <figcaption><strong>Katja Tuma</strong><br><span style="opacity:.8">TU Eindhoven</span><br><a href="mailto:k.tuma@tue.nl">k.tuma@tue.nl</a></figcaption>
  </figure>
  <figure style="text-align:center;margin:0;">
    <img src="{{ '/assets/img/megha-khosla.jpg' | relative_url }}" alt="Megha Khosla" style="width:160px;height:160px;object-fit:cover;border-radius:50%;display:block;margin:0 auto 8px;">
    <figcaption><strong>Megha Khosla</strong><br><span style="opacity:.8">TU Delft</span><br><a href="mailto:m.khosla@tudelft.nl">m.khosla@tudelft.nl</a></figcaption>
  </figure>
  <figure style="text-align:center;margin:0;">
    <img src="{{ '/assets/img/thijs-van-ede.jpg' | relative_url }}" alt="Thijs van Ede" style="width:160px;height:160px;object-fit:cover;border-radius:50%;display:block;margin:0 auto 8px;">
    <figcaption><strong>Thijs van Ede</strong><br><span style="opacity:.8">University of Twente</span><br><a href="mailto:t.s.vanede@utwente.nl">t.s.vanede@utwente.nl</a></figcaption>
  </figure>
</div>
