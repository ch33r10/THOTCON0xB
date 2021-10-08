# [![THOTCON0xB header](https://github.com/ch33r10/THOTCON0xB/blob/main/Nirvana/Thotcon2021.png)](https://sites.google.com/view/ch33r10)
<p align='center'>
<a href="https://twitter.com/Ch33r10"><img height="30" src="https://github.com/ch33r10/BlackHatAsia2020/blob/master/img/twitter%20blue%20logo.png"></a>&nbsp;&nbsp;
 <a href="https://www.linkedin.com/in/xena-olsen/"><img height="30" src="https://github.com/ch33r10/BlackHatAsia2020/blob/master/img/linkedin%20logo.png"></a>&nbsp;&nbsp;
</p>
<h3 align="center">ADVERSARY DETECTION PIPELINES: FINALLY MAKING YOUR THREAT INTEL USEFUL🎚️</h3>
<h5 align="center">🎙️<a href="https://open.spotify.com/album/1To7kv722A8SpZF789MZy7?si=Ui7PEKP7Tf-M49WS0_Y25A&dl_branch=1">NIRVANA MTV Unplugged New York Spotify Playlist</a>🎙️</h5>
<h5 align="center">"It's better to burn out than to fade away" - Kurt Cobain</h5>
<p align="center">I plan on discussing the pain points to threat intel and sharing that this presentation is not for the Microsofts and Targets of the world but instead for the orgs that want to get more value out of their small CTI team. I'll discuss why true attribution is a bad idea for most organizations with real world examples. Then, I will provide real world examples of how TTPs can help an organization better by knowing the What and How (TTPs) versus the Who and Why (true attribution). I'll show examples of how an org can build out an adversary detection pipeline starting with the attack data in their mail and expanding out to the WAF attack data and tickets with the SOC/DFIR. A discussion of mapping MITRE ATT&CK ttps and how to find the specific procedures. Next, there will be real world examples of adversary detection pipelines and how purple team exercises can be run from threat intel specific to the org's attack data. Finally, a discussion of reporting for management/department that is possible as a result of the adversary detection pipelines. Main takeaways: Squeeze more value out of the data you are already collecting, Showing how any organization can leverage threat intel through adversary detection pipelines, regardless of internal skill sets or experience, Heatmaps for threat actor campaign volume, multiple year tracking, delivery rate, click rate, and more used to prioritize Hunt, Red Team, and Blue Team actions with respect to Threat Actor Activity, Intelligence driven hypothesis creation for threat hunting, How to operationalize adversary detection pipelines to enhance red team & purple team activities, particularly to improve adversary emulation/simulation, RELEVANT red team ops, Higher fidelity alerts for the SOC with less false positives.</p>
<p></p>
<p><h1 align="left">🚬<b>"I'M SO HAPPY 'CAUSE TODAY I FOUND MY FRIENDS, THEY'RE IN MY HEAD" - Kurt Cobain</b></h1></p>
<h3 align="center">😎Ch33r10's CTI Capability Model Self-Assessment Spreadsheet - <a href="https://docs.google.com/spreadsheets/d/1MLFXE7lDrkkqYblIIXz6Vx8OtKCt49wp0U29P0p1kEE/edit?usp=sharing">Link</a></h3>
<p>Citation: Shin, B., & Lowry, P. B. (2020). A review and theoretical explanation of the ‘Cyberthreat-Intelligence (CTI) capability’ that needs to be fostered in information security practitioners and how this can be accomplished. Computers & Security 92(101761), pages 1-16. <a href="https://doi.org/10.1016/j.cose.2020.101761">https://doi.org/10.1016/j.cose.2020.101761</a>
<p align="center"><img src="https://github.com/ch33r10/THOTCON0xB/blob/main/Nirvana/ctiselfassessment.png"></p>
<p></p>
<h3 align="left">🕯️<b>ADVERSARY DETECTION PIPELINES</b></h3>

**INTERNAL ATTACK DATA**|**MANAGEMENT**|**INTELLIGENCE**|**EMERGING THREATS**
---|---|---|---
Email, Incident Tickets, Red/Purple Ops|Their concerns/agenda etc.|Industry vertical, previous/current targeting, open source, paid, etc.|Org Relevant trending/new threats
<p></p>
<h3 align="left">🔗<b>ADVERSARY DETECTION PIPELINE CYCLE</b></h3>
<ol>
  <li><b>CTI</b> - Prioritized Collection and Research for Relevant Threats</li>
  <li><b>CTI ANALYSIS</b> - Analysis and Preparation of Deliverable</li>
 <li><b>OTHER TEAMS</b> - Red, Hunt, Purple, SOC, Detection Engineering <b><i>ACT</b></i> on CTI provided context</li>
  <li><b>FEEDBACK/INPUT</b> - Communication and Collaboration</li>
  <li><b>RINSE & REPEAT</b></li>
</ol>
 <p></p> 
<p></p>
<p><h1 align="left">⚡🎸<b>"HERE WE ARE NOW, ENTERTAIN US" - Kurt Cobain</b></h1></p>
<p>The resources below are pointers...all you gotta do is pull that string and keep pulling.</p>

<p>📻<b>ATTRIBUTION</b></p>
<ul>
 <li>Brian Bartholomew & Juan Andres Guerrero-Saade. Wave Your False Flags! Deception Tactics Muddying Attribution in Targeted Attacks - <a href="https://media.kasperskycontenthub.com/wp-content/uploads/sites/43/2017/10/20114955/Bartholomew-GuerreroSaade-VB2016.pdf">Link</a></li>
 <li>Jake Williams. Conducting a Successful False Flag Operation. BlackHat Europe 2019 - <a href="https://youtu.be/W2vBu_Jui9A">Link</a></li>
 <li>Jason D. Jolley. Attribution, State Responsibility, and the Duty to Prevent Malicious Cyber-Attacks in International Law - <a href="https://www.amazon.com/ATTRIBUTION-RESPONSIBILITY-MALICIOUS-CYBER-ATTACKS-INTERNATIONAL-ebook/dp/B07TYJYFYM/ref=sr_1_1?dchild=1&keywords=jason+jolley+attribution&qid=1599458954&sr=8-1">Link</a></li>
 <li>Katie Nickels. The Attribution Game: When Knowing Your Adversary Matters - <a href="https://redcanary.com/blog/apt-attribution-rsa/">Link</a></li>
 <li>Robert M. Lee. The Problems with Seeking and Avoiding True Attribution to Cyber Attacks - <a href="https://www.sans.org/blog/the-problems-with-seeking-and-avoiding-true-attribution-to-cyber-attacks/">Link</a></li>
 <li>Thomas Rid & Ben Buchanan. Attributing Cyber Attacks - <a href="https://ridt.co/d/rid-buchanan-attributing-cyber-attacks.pdf">Link</a></li>
 <li>Tim Maurer. Cyber Mercenaries: The State, Hackers, and Power - <a href="https://www.amazon.com/Cyber-Mercenaries-State-Hackers-Power/dp/110756686X/ref=sr_1_1?dchild=1&keywords=tim+cyber+mercenaries&qid=1599459104&sr=8-1">Link</a></li>
</ul> 
<p>🦾<b>TTPs</b></p>
<ul>
  <li>Adam Pennington. Emulating an Adversary with Imperfect Intelligence. DEF CON 28 Red Team Village - <a href="https://youtu.be/cXlWY3OnjO0">Link</a></li>
 <li>MITRE ATT&CK TTP Training - <a href="https://attack.mitre.org/resources/training/cti/">Link</a></li>
 <li>MITRE ENGENUITY - ATT&CK Evaluations - <a href="https://attackevals.mitre-engenuity.org/">Link</a></li>
</ul>
<p>🔥<b>CYBER THREAT INTELLIGENCE</b></p>
<ul>
 <li>Amy Bejtlich. Analytic Tradecraft in the Real World - <a href="https://youtu.be/MWJZsW9HooY">Link</a></li>
 <li>Bongsik Shin and Paul Benjamin Lowry. A review and theoretical explanation of the ‘Cyberthreat-Intelligence (CTI) capability’ that needs to be fostered in information security practitioners and how this can be accomplished - <a href="https://doi.org/10.1016/j.cose.2020.101761">Link</a></li>
 <li>Brian P. Kime. Threat Intelligence: Planning and Direction - <a href="https://www.sans.org/reading-room/whitepapers/threatintelligence/threat-intelligence-planning-direction-36857">Link</a></li>
  <li>MITRE ATT&CK - <a href="https://attack.mitre.org/">Link</a></li>
 <li>Rebekah Brown & Robert M. Lee. The Evolution of CTI: 2019 SANS CTI Survey - <a href="https://www.sans.org/reading-room/whitepapers/threats/paper/38790#:~:text=SANS%20has%20been%20tracking%20the,its%20applications%20in%20information%20security.&text=While%20the%20use%20of%20CTI,size%2Dfits%2Dall%20approach">Link</a></li>
 <li>Scott J. Roberts. CTI Squad Goals-Setting Requirements - <a href="https://medium.com/@sroberts/cti-squadgoals-setting-requirements-41bcb63db918">Link</a></li>
 <li>Sergio Caltagirone. Building Threat Hunting Strategies with the Diamond Model - <a href="http://www.activeresponse.org/building-threat-hunting-strategy-with-the-diamond-model/">Link</a></li>
 <li>Sergio Caltagirone, Andrew Pendergast, & Christopher Betz. The Diamond Model of Intrusion Analysis - <a href="https://apps.dtic.mil/dtic/tr/fulltext/u2/a586960.pdf">Link</a></li>   
</ul>
<p>👑<b>DETECTION ENGINEERING</b></p>
<ul>
 <li>Detection Ideas Repo by Vadim Khrykov @BlackMatter23 - <a href="https://github.com/vadim-hunter/Detection-Ideas-Rules/">Link</a></li>
<li>Sigma Rules Repository - <a href="https://github.com/SigmaHQ/sigma">Link</a></li>
 <li>YARA Rules Resource - <a href="https://github.com/InQuest/awesome-yara">Link</a></li>
 </ul>
<p>🕶<b>DFIR</b></p>
 <ul>
  <li>Ali Hadi's DFIR Resources - <a href="https://www.youtube.com/channel/UCnGqqX9vefQV0d68ktNblrQ/featured">Link</a></li>
 <li>The DFIR Report - <a href="https://thedfirreport.com/">Link</a></li>
  </ul>
<p>🌎<b>HUNT</b></p>
<ul>
 <li>Ch33r10's Twitter Threat Hunting List - <a href="https://twitter.com/i/lists/1445402146434867206">Link</a></li>
 <li>David J. Bianco and Cat Self. SANS Threat Hunting & IR Europe Summit 2020 - <a href="https://youtu.be/HInxsRyYCK4">Link</a></li>
  <li>David J. Bianco. The ThreatHunting Project - <a href="https://www.threathunting.net/">Link</a></li>
 <li>Joshua Stevens. Hunting for the Undefined Threat: Advanced Analytics & Visualization. RSA Conference 2015 - <a href="https://docs.huihoo.com/rsaconference/usa-2015/anf-w04-hunting-the-undefined-threat-advanced-analytics-visualization.pdf">Link</a></li>
 <li>Matt Bromiley. Thinking like a Hunter: Implementing a Threat Hunting Program. SANS Analyst Paper - <a href="https://www.sans.org/reading-room/whitepapers/analyst/thinking-hunter-implementing-threat-hunting-program-38923">Link</a></li>
 <li>Robert M. Lee and David J. Bianco. Generating Hypotheses for Successful Threat Hunting. SANS Analyst White Paper - <a href="https://www.sans.org/reading-room/whitepapers/threats/generating-hypotheses-successful-threat-hunting-37172">Link</a></li>
   <li>Roberto Rodriguez. How Hot is your Hunt Team? - <a href="https://cyberwardog.blogspot.com/2017/07/how-hot-is-your-hunt-team.html">Link</a></li>
 <li>Roberto Rodriquez. ThreatHunter Playbook - <a href="https://github.com/OTRF/ThreatHunter-Playbook">Link</a></li>
  <li>Valentina Costa-Gazcon. Practical Threat Intelligence and Data-Driven Threat Hunting - <a href="https://www.amazon.com/Practical-Threat-Hunting/dp/1838556370">Link</a></li>
  </ul>
 <p>👾<b>MALWARE ANALYSIS</b></p>
 <ul>
 <li>Coleman Kane. Malware Analysis - <a href="https://class.malware.re/">Link</a></li>
 <li>Monnappa K A. Learning Malware Analysis - <a href="https://www.amazon.com/Learning-Malware-Analysis-techniques-investigate-ebook/dp/B073D49Q6W">Link</a></li>
</ul>
 <p>🌠<b>PURPLE</b></p>
<ul>
  <li>Ch33r10's Purple Team Exercise Idea Queue - <a href="https://docs.google.com/spreadsheets/d/1wHRrqwb1chTWP8kQqJjA2Chl7bUtCxRlobiyT3V2thE/edit#gid=267180436">Link</a></li>
 <li>Ch33r10's Purple Team Resources - <a href="https://github.com/ch33r10/EnterprisePurpleTeaming">Link</a></li>
  <li>Jorge Orchilles. Purple Team Exercise Framework Workshop - <a href="https://www.scythe.io/library/ptef-workshop">Link</a></li>
 <li>SCYTHE’s Purple Team Exercise Framework - <a href="https://www.scythe.io/ptef">Link</a></li>
  <li>SCYTHE's Community Threats - <a href="https://github.com/scythe-io/community-threats">Link</a></li>
 </ul>
<p>👹<b>RED</b></p>
<ul>
<li>Atomic Red Team by Red Canary - <a href="https://github.com/redcanaryco/atomic-red-team">Link</a></li>
 <li>C2 Matrix - <a href="https://www.thec2matrix.com">Link</a></li>
 <li>Joe Vest & James Tubberville's Red Team Development and Operations - <a href="https://www.amazon.com/Red-Team-Development-Operations-practical/dp/B083XVG633/ref=sr_1_1?dchild=1&keywords=joe+vest+red+team+book&qid=1633667294&sr=8-1">Link</a>
 <li>Red Teaming Techniques & Experiments - <a href="https://www.ired.team/">Link</a>
<li>SpecterOps Blog - <a href="https://posts.specterops.io/">Link</a></li>
 <li>Vincent Yiu's Red Team Tips - <a href="https://www.vincentyiu.com/red-team-tips">Link</a>
 </ul>
<p>🎵<b>RESOURCES</b></p>
<ul>
<li>Attack2Jira by Mauricio Velazco and Olindo Verrillo - <a href="https://github.com/mvelazc0/attack2jira">Link</a></li>
<li>Ch33r10's Field Classifications Contribution for Attack2Jira by Mauricio Velazco and Olindo Verrillo - <a href="https://github.com/mvelazc0/attack2jira/pull/16">Link</a></li>
 <li>MITRE CAR - Cyber Analytics Repository - <a href="https://car.mitre.org/">Link</a></li>
 <li>MITRE D3FEND - <a href="https://d3fend.mitre.org/">Link</a></li>
 <li>MITRE SHIELD - <a href="https://shield.mitre.org/matrix/">Link</a></li>
 <li>MITRE ATT&CK Navigator - <a href="https://mitre-attack.github.io/attack-navigator/">Link</a></li>
<li>NIST Cybersecurity Framework, MITRE ATT&CK v8.2, & CIS Controls v8 CSV (Mappings Compliments of <a href="https://www.cisecurity.org/controls/cis-controls-navigator/">CIS</a> - Center for Internet Security) - <a href="https://github.com/ch33r10/EnterprisePurpleTeaming/blob/main/PractitionerResources/NISTCSF_MITRE.csv">Link</a></li> 
</ul>
<b></b>
<hr></hr>
<h6 align="center"><small>FOR THE LAWYERS</small></h6>
<h6 align="center"><sub>"The opinions expressed in this Github repo are those of the individual account, in their individual capacity, and not necessarily those of the employers. Mention of any vendors, services, products, or otherwise does not endorse them as a vendor. This content and any related discussions are solely the views, opinions, and experiences of the participants and should not be presumed to reflect the opinion or the official position of any employers of the participants. Examples and views provided herein, including strategies, goals, targets, and indicators are for illustrative purposes only and should not be regarded as representative of the participants' employers or respective portfolios. To the extent that this participation, discussion, and interview outlines a general technology direction, the participants' employers have no obligation to pursue any such approach or to develop or use any functionality mentioned herein. Any suggested technology strategy or possible future developments are subject to change at the employers' sole discretion without notice. Content in this presentation is the intellectual property of the applicable creators and may be protected under the copyright laws of the United States and/or other countries. All trademarks are the property of their respective owners and are used for informational purposes only."</sub></h6>
