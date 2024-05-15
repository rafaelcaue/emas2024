---
layout: home
limit: 10
show_excerpts: true
entries_layout: list
---

# Programme
Short papers are up to 20 minutes (up to 15 minutes of presentation and at least 5 minutes of questions).   
Full papers are up to 30 minutes (up to 25 minutes of presentation and at least 5 minutes of questions).   
Invited talks are up to 60 minutes (up to 50 minutes of presentation and at least 10 minutes of questions).   

|                 | **Monday (May 6)**                                 | **Tuesday (May 7)**                                           |
|-----------------|----------------------------------------------------|---------------------------------------------------------------|
| **8:00-8:30**   | Registration Opens                                 | Registration Opens                                            |
| **8:30-9:20**   | Arrival & Welcome                                  | Arrival & Welcome                                             |
| **9:20-10:00**  | [Session 1 (short): Agent Design I](#s1)           | [Session 6 (short): Explainability and Trust](#s6)            |
| **10:00-10:30** | Coffee Break                                       | Coffee Break                                                  |
| **10:30-11:30** | [Session 2: Planning and Learning](#s2)            | [Session 7: Correctness and Testing](#s7)                     |
| **11:30-12:30** | [Session 3: Agent Development](#s3)                | [Session 8 (short): Cognitive Agents](#s8)                    |
| **12:30-14:00** | Lunch Break                                        | Lunch Break                                                   |
| **14:00-15:00** | [Invited Talk: Stephen Cranefield](#talk1)         | [Invited Talk: Sebastian Rodriguez](#talk2)                   |
| **15:00-16:00** | [Session 4: BDI Agents](#s4)                       | [Community Discussion](https://forms.office.com/e/4MC4XtzVcb) |
| **16:00-16:30** | Coffee Break                                       | Coffee Break                                                  |
| **16:30-16:50** | [Session 5 (short): Agent Design II](#s5)          | Community Discussion Overview                                 |
| **16:50-17:10** | IIPC Discussion                                    | Awards and Closing                                            |


# Invited Talks

### <a id="talk1"></a> **Stephen Cranefield: Engineering Social Order in Multi-Agent Systems**

(<a target="_blank" href="{{ '/assets/slides/Cranefield EMAS 2024.pdf' | relative_url }}"> Slides </a>)

(Chair: Rafael C. Cardoso)

<img src="{{ '/assets/images/stephen.jpg' | relative_url }}" alt="Stephen Cranefield" style="max-width: 150px; float: left; margin-left: 10px; margin-right: 10px;">

<p style="margin-top: -10px;"> <b>Abstract:</b> One of my long-standing research interests is to develop practical techniques for agents to understand the social constraints they and other agents are operating under, so they can coordinate more effectively without relying on centralised infrastructure. I will begin this talk with a brief overview of my prior work on monitoring social expectations, learning norms from observation, following social practices and proposing and executing group plans.
  
I will then discuss recent work on a practical technique for recognising common belief, which is an important enabler of efficient coordination within groups. Our approach is based on philosopher David Lewis's account of common knowledge (which is really about warranted common belief). It considers the common case where (i) a publicly observable “state of affairs” A (which we view as a set of percepts) indicates to an agent that some proposition P holds, and (ii) through reasoning about shared background knowledge and standards of reasoning, the agent can infer that other agents should also believe P. Prior work does not provide a precise and satisfactory definition of the nature of indication, nor does it explain how agents reason about shared knowledge and reasoning standards. We propose specific mechanisms based on theory-of-mind (ToM) rules in a forward-chaining rule engine. We prove that only two levels of ToM modelling is required to recognise the existence of common belief. The approach is implemented using the Prolog Forward Chaining (Pfc) library and can be used in conjunction with the Jason agent platform. We illustrate the approach in a scenario from classical Athens of decision-making requiring common belief of the information on a public monument.

  </p>

**Bio:** Stephen is a full professor in the School of Computing at the University of Otago, in Dunedin, New Zealand. Ater an undergraduate degree in Mathematics and Computer Science from Otago, he received a PhD from the (former) Department of Artificial Intelligence at the University of Edinburgh. His main research interest is on techniques for engineering social order in open communities of autonomous agents by adapting social concepts and mechanisms observed in human society, with a focus on normative multi-agent systems.

### <a id="talk2"></a> **Sebastian Rodriguez: Agile Approach for Agent Oriented Software Engineering**

(<a target="_blank" href="{{ '/assets/slides/Sebastian-EMAS.pdf' | relative_url }}"> Slides </a>)

(Chair: Brian Logan)

<img src="{{ '/assets/images/sebastian.jpg' | relative_url }}" alt="Sebastian Rodriguez" style="max-width: 150px; float: left; margin-left: 10px; margin-right: 10px;">

<p style="margin-top: -10px;"> <b>Abstract:</b> The agile software development life cycle is widely used in industry today due to its highly flexible and iterative processes that facilitate rapid prototyping. In this talk, we advocate to close the gap between mainstream software engineering and agent technology by adopting and adapting well-known and accepted techniques. We introduce an agile approach to capturing requirements in agent systems via user and system stories and how to translate these requirements into goal-oriented agent models. We cover how to define test cases to verify the expected system behaviour following a Behaviour-Driven Development (BDD) approach. We leverage a range of state-of-the-art development tools, inheriting the rich set of features they provide. Finally, we discuss future directions and opportunities. </p>

**Bio:** Sebastian specialises in software engineering for artificial intelligence systems. He has been involved in a wide range of projects applying AI and SE solutions to industry applications such as transportation, logistics and business processes. He also founded start-ups applying AI techniques to energy management; 3D simulations; and new business models for media companies. Additionally, he is an active contributor to open-source software for AI systems and a core member of the SARL programming language.

# Sessions

### <a id="s1"></a> **Agent Design I (Chair: Ömer Ibrahim Erduran)**

<table>
  <tr>
    <td NOWRAP><b>9:20-9:40</b></td>
    <td>Henning Gösling, Dennis Maecker, Tom Pieper, Timon Sachweh and Christoph Heinbach. <em>A Procedure for Conceptualizing and Implementing Spade Agents</em> (<a target="_blank" href="{{ '/assets/papers/EMAS_2024_paper_4 (1).pdf' | relative_url }}"> PDF </a>) (<a target="_blank" href="{{ '/assets/slides/Sesssion 1 - Paper 1.pptx' | relative_url }}"> Slides </a>)</td>
  </tr>
  <tr>
    <td NOWRAP><b>9:40-10:00</b></td>
    <td>Dennis Maecker, Henning Gösling and Timon Sachweh. <em>Setting up a ROS2-based Multi-Agent System implementing the Contract Net Protocol and IDS Connectors</em> (<a target="_blank" href="{{ '/assets/papers/EMAS_2024_paper_15.pdf' | relative_url }}"> PDF </a>) (<a target="_blank" href="{{ '/assets/slides/Sesssion 1 - Paper 2.pptx' | relative_url }}"> Slides </a>)</td>
  </tr>
</table>

### <a id="s2"></a> **Planning and Learning (Chair: Felipe Meneguzzi)**

<table>
  <tr>
    <td NOWRAP><b>10:30-11:00</b></td>
    <td>Sanjay Chandlekar and Easwar Subramanian. <em>A Novel Bidding Strategy for PDAs using MCTS in Continuous Action Spaces</em> (<a target="_blank" href="{{ '/assets/papers/EMAS_2024_paper_3.pdf' | relative_url }}"> PDF </a>) (<a target="_blank" href="{{ '/assets/slides/Sesssion 2 - Paper 1.pdf' | relative_url }}"> Slides </a>)</td>
  </tr>
  <tr>
    <td NOWRAP><b>11:00-11:30</b></td>
    <td>Sizhe Wang, Long Qian, Cairun Yi, Fan Wu, Qian Kou, Mingyang Li, Xingyu Chen and Xuguang Lan. <em>SADMA: Scalable Asynchronous Distributed Multi-Agent Reinforcement Learning Training Framework</em> (<a target="_blank" href="{{ '/assets/papers/EMAS_2024_paper_5.pdf' | relative_url }}"> PDF </a>) (<a target="_blank" href="{{ '/assets/slides/Sesssion 2 - Paper 2.pptx' | relative_url }}"> Slides </a>)</td>
  </tr>
</table>

### <a id="s3"></a> **Agent Development (Chair: Louise Dennis)**

<table>
  <tr>
    <td NOWRAP><b>11:30-12:00</b></td>
    <td>Marcel Mauri, Ömer Ibrahim Erduran and Mirjam Minor. <em>Jadex BDI Agents Integrated with MATSim for Autonomous Mobility on Demand</em> (<a target="_blank" href="{{ '/assets/papers/EMAS_2024_paper_9.pdf' | relative_url }}"> PDF </a>) (<a target="_blank" href="{{ '/assets/slides/Sesssion 3 - Paper 1.pptx' | relative_url }}"> Slides </a>)</td>
  </tr>
  <tr>
    <td NOWRAP><b>12:00-12:30</b></td>
    <td>Masaki Ishizaka, Akihito Taya and Yoshito Tobe. <em>SPARKIT: A Mind Map-Based MAS for Idea Generation Support</em> (<a target="_blank" href="{{ '/assets/papers/EMAS_2024_paper_11.pdf' | relative_url }}"> PDF </a>) (<a target="_blank" href="{{ '/assets/slides/Sesssion 3 - Paper 2.pptx' | relative_url }}"> Slides </a>)</td>
  </tr>
</table>

### <a id="s4"></a> **BDI Agents (Chair: Brian Logan)**

<table>
  <tr>
    <td NOWRAP><b>15:00-15:30</b></td>
    <td>Martina Baiardi, Samuele Burattini, Giovanni Ciatto, Danilo Pianini, Alessandro Ricci and Andrea Omicini. <em>On the external concurrency of current BDI frameworks for MAS</em> (<a target="_blank" href="{{ '/assets/papers/EMAS_2024_paper_14.pdf' | relative_url }}"> PDF </a>) (<a target="_blank" href="{{ '/assets/slides/Sesssion 4 - Paper 1.pdf' | relative_url }}"> Slides </a>)</td>
  </tr>
  <tr>
    <td NOWRAP><b>15:30-16:00</b></td>
    <td>Alexandre Yukio Ichida, Felipe Meneguzzi and Rafael C. Cardoso. <em>BDI Agents in Natural Language Environments</em> (<a target="_blank" href="{{ '/assets/papers/EMAS_2024_paper_13.pdf' | relative_url }}"> PDF </a>) (<a target="_blank" href="{{ '/assets/slides/Sesssion 4 - Paper 2.pdf' | relative_url }}"> Slides </a>)</td>
  </tr>
</table>

### <a id="s5"></a> **Agent Design II (Chair: Yi Yang)**

<table>
  <tr>
    <td NOWRAP><b>16:30-16:50</b></td>
    <td>Alessandro Ricci, Samuele Burattini, Matteo Castellucci and Andrei Ciortea. <em>Agents for DDD – Back and Forth</em> (<a target="_blank" href="{{ '/assets/papers/EMAS_2024_paper_7.pdf' | relative_url }}"> PDF </a>) (<a target="_blank" href="{{ '/assets/slides/Sesssion 5 - Paper 1.pdf' | relative_url }}"> Slides </a>)</td>
  </tr>
</table>

### <a id="s6"></a> **Explainability and Trust (Chair: Alessandro Ricci)**

<table>
  <tr>
    <td NOWRAP><b>9:20-9:40</b></td>
    <td>Michael Winikoff. <em>Towards Engineering Explainable Autonomous Systems</em> (<a target="_blank" href="{{ '/assets/papers/EMAS_2024_paper_1.pdf' | relative_url }}"> PDF </a>) (Slides)</td>
  </tr>
  <tr>
    <td NOWRAP><b>9:40-10:00</b></td>
    <td>Dennis Maecker, Felix Harenbrock, Henning Gösling, Timon Sachweh and Oliver Thomas. <em>Synergizing Trust and Autonomy: Gaia-X Enabled Multi-Agent Ecosystems for Advanced Freight Fleet Management</em> (<a target="_blank" href="{{ '/assets/papers/EMAS_2024_paper_10.pdf' | relative_url }}"> PDF </a>) (Slides)</td>
  </tr>
</table>

### <a id="s7"></a> **Correctness and Testing (Chair: Emiliano Lorini)**

<table>
  <tr>
    <td NOWRAP><b>10:30-11:00</b></td>
    <td>Yi Yang and Tom Holvoet. <em>Enhancing Confidence of the vGOAL Interpreter Using SAT Solving</em> (<a target="_blank" href="{{ '/assets/papers/EMAS_2024_paper_2.pdf' | relative_url }}"> PDF </a>) (Slides)</td>
  </tr>
  <tr>
    <td NOWRAP><b>11:00-11:30</b></td>
    <td>Samira Shirzadehhajimahmood, Wishnu Prasetya, Mehdi Dastani and Frank Dignum. <em>Cooperative Multi-agent Approach for Automated Computer Game Testing</em> (<a target="_blank" href="{{ '/assets/papers/EMAS_2024_paper_17.pdf' | relative_url }}"> PDF </a>) (Slides)</td>
  </tr>
</table>

### <a id="s8"></a> **Cognitive Agents (Chair: Michael Winikoff)**

<table>
  <tr>
    <td NOWRAP><b>11:30-11:50</b></td>
    <td>Alessandro Ricci, Stefano Mariani, Franco Zambonelli, Samuele Burattini and Cristiano Castelfranchi. <em>The Cognitive Hourglass: Agent Abstractions in the Large Models Era</em> (<a target="_blank" href="{{ '/assets/papers/EMAS_2024_paper_6.pdf' | relative_url }}"> PDF </a>) (<a target="_blank" href="{{ '/assets/slides/Sesssion 8 - Paper 1.pdf' | relative_url }}"> Slides </a>)</td>
  </tr>
  <tr>
    <td NOWRAP><b>11:50-12:10</b></td>
    <td>Emiliano Lorini, Magalie Ochs and Nicolas Sabouret. <em>Cognitive Planning for Persuasive Multimodal Interaction</em> (<a target="_blank" href="{{ '/assets/papers/EMAS_2024_paper_18.pdf' | relative_url }}"> PDF </a>) (Slides)</td>
  </tr>
</table>
