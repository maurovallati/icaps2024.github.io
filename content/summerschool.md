---
title: "Summer School"
draft: false
---


<!--  How to test webpage locally? Execute "hugo server" in the root folder -->


# The 12th ICAPS Summer School

The Summer School on Automated Planning and Scheduling in 2024 will be the first in-person summer school since 2018 – *after six long years!*

#### NEWS: Free remote participation !

We were able to make the Summer School available online as well. I.e., you are able to *freely* participate in both our talks, and even the labs! (ICKEPS will however remain an in-person competition for our on-site participants.)

Both the lectures and the labs will be managed via zoom, the URL is going to be shared in our [git repository](https://github.com/CLAIR-LAB-TECHNION/ICAPS-24). *Please check out the section below about our labs for requirements.*

**IMPORTANT:** We also rely on the the readme of our git repository to communicate any recent news -- i.e., they will be posted there, not here. So check this file carefully.


## When and Where?

The summer school will take place from *27 May 2024* to *31 May 2024* (5 full days), in Banff, the week before ICAPS. So if you plan to attend ICAPS, you could simply arrive one week earlier!


## What?

The summer school provides a comprehensive and incremental overview of frameworks for planning and sequential decision-making (classical planning, hierarchical planning, task and motion planning, planning under uncertainty, RL, etc.) while using integrated task and motion planning (TMP) as the underlying ‘running example’ in the hands-on lab sessions (designed and executed by Sarah Keren), which are designed to demonstrate ideas and theories discussed in the lectures. The program will include two lectures presented by researchers from the ICAPS community in the morning and early afternoon, followed by the lab session. 

***We will also help hosting ICKEPS 2024!*** You find a description and the organizers below.

**The following is our list of speakers (*ordered alphabetically by last name*) and topics:**

<!--
<div style="width: 100%; margin: 0; padding: 1%;">
<h3 style="color:orange;"><strong><a href="URL">NAME</a></strong>, AFFILIATION</h3>
<h4 style="color:black;"><strong>TITLE</strong></h4>
TALK SUMMARY<br><br>
<div style="display: inline-block; width: 30%; border: 2px solid orange; border-radius: 3%; padding: 1%; vertical-align:middle;">
<img style="width:100%; border-radius: 3%; vertical-align: middle;" src="https://icaps24.icaps-conference.org/summerschool/PICNAME.jpg" />
</div>
<div style="display: inline-block; width: 68%; padding: 1%; vertical-align: middle;">
<div style="margin:0; padding: 0; padding-left: 2%">
<p>
CV
</p>
</div>
</div>

</div>
-->

<div style="width: 100%; margin: 0; padding: 1%;">
<h3 style="color:orange;"><strong><a href="https://comp.anu.edu.au/people/pascal-bercher/">Pascal Bercher</a></strong>, the Australian National University (ANU)</h3>
<h4 style="color:black;"><strong>An Introduction to Hierarchical Task Network (HTN) Planning: Theoretical Foundations & Problem Solving</strong></h4>
In this introductory talk, we explore the basics of HTN planning, designed to enable anybody without prior knowledge of this field to easily follow current research papers in this field. Starting with a simplistic formalization of the problem -- as used in scientific papers -- we explore how this relates to non-hierarchical (STRIPS) planning both in terms of computational complexity and a more fine-grained measure of expressivity, before looking into extensions of the core formalism. We study the most commonly known solution technique -- progression search -- but also provide pointers to others such as compilation techniques.<br><br>
<div style="display: inline-block; width: 30%; border: 2px solid orange; border-radius: 3%; padding: 1%; vertical-align:middle;">
<img style="width:100%; border-radius: 3%; vertical-align: middle;" src="/summerschool/Pascal-Bercher.jpg" />
</div>
<div style="display: inline-block; width: 68%; padding: 1%; vertical-align: middle;">
<div style="margin:0; padding: 0; padding-left: 2%">
<p>
Pascal Bercher is a Senior Lecturer at the Australian National University. His research is mostly concerned with Hierarchical Task Network (HTN) Planning, but covers also non-hierarchical planning. He is interested in heuristic search (mostly heuristic design), plan verification, and extending the framework with language features that are crucial for real-world applications, such as uncertainty and time. He is especially interested in modeling support, i.e., in autonomously helping a domain modeler with creating a domain model. In all these research directions, complexity investigations are often done as a first step -- to ensure a solid problem formalization and to give an indication about the right tools to attempt a given problem, based on its complexity. On top of research, he is passionate for teaching (by putting lots of effort/time into slides and organization) and mentoring students and supporting colleagues. He reviews for most of the large AI and planning conferences (ICAPS, IJCAI, AAAI, ECAI), some other conferences, as well as several workshops each year. He founded the ICAPS workshop on hierarchical planning (HPlan) and co-organizes it since then annually. This year, he also co-organizes this summer school and hopes that it will be both enjoyable and a valuable learning experience for everybody.
</p>
</div>
</div>
</div>


<div style="width: 100%; margin: 0; padding: 1%;">
<h3 style="color:orange;"><strong><a href="https://www.linkedin.com/in/jeremy-frank-62141bb3">Jeremy Frank</a></strong>, NASA</h3>
<h4 style="color:black;"><strong>The Distributed Spacecraft Autonomy (DSA) Project</strong></h4>
Autonomous decision-making significantly increases mission effectiveness by mitigating the effects of communication constraints, like latency and bandwidth, and mission complexity on multi-spacecraft operations. To advance the state of the art in autonomous Distributed Space Systems (DSS), the Distributed Spacecraft Autonomy (DSA) team at NASA is maturing technology in the following technical areas: distributed resource and task management, reactive operations, human-swarm interaction, and ad hoc network communications. DSA is divided into two parts. DSA’s primary flight mission showcases collaborative resource allocation for multipoint science data collection with four small spacecraft as a payload on NASA’s Starling 1.0 satellites. A scalability demonstration of Lunar Position, Navigation and Timing services (PNT) services was performed in simulation, and on a 100-node heterogenous Processor-in-the-Loop (PiL) testbed. In this talk, I will describe the overarching goals of DSA, discuss progress in both areas, then sum up with lessons learned.<br><br>
<div style="display: inline-block; width: 30%; border: 2px solid orange; border-radius: 3%; padding: 1%; vertical-align:middle;">
<img style="width:100%; border-radius: 3%; vertical-align: middle;" src="https://icaps24.icaps-conference.org/summerschool/Jeremy-Frank.jpg" />
</div>
<div style="display: inline-block; width: 68%; padding: 1%; vertical-align: middle;">
<div style="margin:0; padding: 0; padding-left: 2%">
<p>
Dr. Jeremy Frank is the Group Lead of Planning and Scheduling Group, in the Intelligent Systems Division, at NASA Ames Research Center. He received his Ph. D. from the Department of Computer Science, at the University of California at Davis, in June 1997. He also has a B.A. in Mathematics from Pomona College.  Dr. Frank’s work involves the development of automated planning and scheduling systems for use in space mission operations, the integration of technologies for planning, plan execution, and fault detection for space applications, and the development of technology to enable astronauts to autonomously operate spacecraft.  Dr. Frank has published over 75 conference papers, 12 journal papers, and three book chapters, and received over 45 NASA awards, including the Exceptional Achievement Medal, the Silver Snoopy, and the NASA Engineering and Safety Center Award.
</p>
</div>
</div>
</div>


<div style="width: 100%; margin: 0; padding: 1%;">
<h3 style="color:orange;"><strong><a href="https://sarahk.cs.technion.ac.il">Sarah Keren</a></strong>, Technion</h3>
<h4 style="color:black;"><strong>Introduction to integrated task and motion planning</strong></h4>
Integrated Task and Motion Planning (ITMP) is the problem of planning for robots that operate in complex environments and need to combine low-level motion planning in a continuous space with a high-level search in a discrete space for a sequence of actions that is predicted to accomplish their assigned task. With the increasing complexity of the tasks autonomous agents and robots are required to achieve in applications such as packing, personal assistance, and cooking, this dichotomous view becomes inefficient. Instead, there is a need for new ways for integrating task-level considerations when planning the robot’s movement, and for propagating motion-planning considerations into the task-level process. This is even more important in settings in which agents are required to share their environment and collaborate with other autonomous agents. I will introduce the rich and active field of integrated task and motion planning, present the key technical challenges that TMP entails, and highlight some of the state-of-the-art approaches towards addressing them. I will end my talk by overviewing some of the major open problems in the field and potential ways of addressing them.<br><br>
<div style="display: inline-block; width: 30%; border: 2px solid orange; border-radius: 3%; padding: 1%; vertical-align:middle;">
<img style="width:100%; border-radius: 3%; vertical-align: middle;" src="https://icaps24.icaps-conference.org/summerschool/Sarah-Keren.jpg" />
</div>
<div style="display: inline-block; width: 68%; padding: 1%; vertical-align: middle;">
<div style="margin:0; padding: 0; padding-left: 2%">
<p>
Sarah Keren is a senior lecturer (assistant professor) at The Taub Faculty of Computer Science at the Technion - Israel Institute of Technology where she leads the [Collaborative AI and Robotics (CLAIR) lab](https://clair.cs.technion.ac.il). Before joining the Technion, Sarah was a postdoctoral fellow at Harvard University and Hebrew University of Jerusalem. She received her PhD from the Technion.

Sarah's research focuses on providing theoretical foundations for AI systems that are capable of effective collaboration with each other and with people. She has received several awards, including the ICAPS 2020 Best Dissertation Honorable Mention, the ICAPS 2014 Honorable Mention for Best Paper, the Eric and Wendy Schmidt Postdoctoral Award for Women in Mathematical and Computing Sciences, and the Weizmann Institute of Science National Postdoctoral Award for Advancing Women in Science. Sarah’s work has been published in leading conferences and journals for AI and robotics, including IJCAI, AAAI, ICAPS, NeurIPS, AAMAS, JAIR, KR and IROS. 
</p>
</div>
</div>
</div>


<br>
<div style="width: 100%; margin: 0; padding: 1%;">
  <h3 style="color:orange;"><strong><a href="https://www.unibw.de/home-en/appointment-of-professors/prof-jane-jean-kiam">Jane Jean Kiam</a></strong>, Universität der Bundeswehr München</h3>
  <h4 style="color:black;"><strong>Automated planning for airborne applications: feasibility and challenges</strong></h4>
  <p>
    In this talk, we will delve into some of the examples of how automated planning can be used in aviation. The talk will first focus on our efforts in using automated task and motion planning for coordinating Unmanned Aerial Vehicles (UAVs). Two different types of UAV-related applications will be illustrated, one being the coordination of High-Altitude Pseudo Satellites (HAPS), a completely solar-powered unmanned platform operating in the stratosphere, the other being the deployment of multiple unmanned drones in rescue missions. Besides showcasing the progresses we made, challenges faced in these works will be analysed, together with some insights on our more recent attempts.
  </p>
  <div style="float: left; width: 30%; margin: 0 3% 1% 0; border: 2px solid orange; border-radius: 3%;">
    <img style="width:100%; border-radius: 3%;" src="https://icaps24.icaps-conference.org/summerschool/Jane-Kiam.jpeg" />
  </div>
  <p>
    Jane Jean Kiam is an assistant professor of Applied AI for Dynamic Systems with the Institute of Flight Systems at the University of the Bundeswehr Munich in Germany. Her research work focuses on applying AI-methods in decision-making support for real-world applications. This includes the use of methods from automated planning and acting,  game theory, as well as machine learning (reinforcement learning) for decision-making support in missions ranging from airborne applications (e.g. high-altitude pseudo satellites, intelligent cockpit for general aviation, drone swarms deployed for search and rescue), to other organised missions such as patrolling in conservation areas, and serious games for disaster resilience among citizens etc. She currently leads the AI-Lab team of the Institute of Flight Systems and is actively involved in German national and Horizon EU projects.
  </p>
</div>


<div style="width: 100%; margin: 0; padding: 1%;">
<h3 style="color:orange;"><strong><a href="https://users.cecs.anu.edu.au/~hannakur/">Hanna Kurniawati</a></strong>, Australian National University</h3>
<h4 style="color:black;"><strong>Planning under Uncertainty, RL and Task and Motion Planning</strong></h4>
Uncertainty is ubiquitous. A robot or agent must decide what it should do now to accomplish its tasks, despite not knowing the exact effects of its actions, errors in sensors and sensing, and the lack of information and understanding about itself and its environment. However, the technology for making good decisions in the presence of uncertainty is still lacking. I will present a tutorial on decision-making under uncertainty. We’ll briefly cover decision-making when the effects of actions is uncertain framework, the Markov Decision Processes (MDPs). And, quickly progress to its expansion when the states are also only partially observable, namely the Partially Observable Markov Decision Processes (POMDPs). We will end with Reinforcement Learning. In these discussions, I will use motivating examples from decision-making problems in robotics.<br><br>
<div style="display: inline-block; width: 30%; border: 2px solid orange; border-radius: 3%; padding: 1%; vertical-align:middle;">
<img style="width:100%; border-radius: 3%; vertical-align: middle;" src="https://icaps24.icaps-conference.org/summerschool/Hanna-Kurniawati.png" />
</div>
<div style="display: inline-block; width: 68%; padding: 1%; vertical-align: middle;">
<div style="margin:0; padding: 0; padding-left: 2%">
<p>
Hanna Kurniawati is a Professor in the ANU School of Computing and holds the SmartSat CRC Professorial Chair for System Autonomy, Intelligence & Decision-Making. She leads the Robust Decision-making and Learning Lab at the ANU and is the ANU Node Lead and Planning & Control Theme Lead for the Australian Robotics Inspection and Asset Management (ARIAM) Hub. Hanna’s research spans robotics, decision-making under uncertainty, motion planning, computational geometry applications, integrated planning and learning, and reinforcement learning. She and her teams have developed algorithms that enable the principled decision-making under uncertainty framework to become practical. Hanna’s works have received multiple recognitions, including Best Paper at ICAPS 2015, finalist for Best Paper at ICRA 2015, keynote speaker at IROS 2018, and the Robotics: Science and Systems 2021 Test of Time Award. She is actively involved in the robotics community, including as a Senior Editor for IEEE RA-L, General Chair for SIMPAR’18, and Program Co-Chair for ICRA’22.
</p>
</div>
</div>
</div>


<div style="width: 100%; margin: 0; padding: 1%;">
<h3 style="color:orange;"><strong><a href="https://www.cs.unh.edu/~ruml/">Wheeler Ruml</a></strong>, University of New Hampshire</h3>
<h4 style="color:black;"><strong>Suboptimal heuristic search and motion planning</strong></h4>
Many interesting problems are too hard to solve optimally.  We'll talk about alternative problem settings in which optimality is sacrificed for lower search time, such as greedy search, bounded-suboptimal search, contract search, and real-time search.  When planning under time pressure, additional sources of heuristic information beyond cost-to-go become relevant, so there is lots of room for creativity here.  We'll also discuss motion planning, where we'll see how ideas from suboptimal graph search can be very useful in searching continuous spaces.<br><br>
<div style="display: inline-block; width: 30%; border: 2px solid orange; border-radius: 3%; padding: 1%; vertical-align:middle;">
<img style="width:100%; border-radius: 3%; vertical-align: middle;" src="https://icaps24.icaps-conference.org/summerschool/Wheeler-Ruml.jpg" />
</div>
<div style="display: inline-block; width: 68%; padding: 1%; vertical-align: middle;">
<div style="margin:0; padding: 0; padding-left: 2%">
<p>
Wheeler Ruml is a Professor of Computer Science at the University of New Hampshire. His interests include planning and heuristic search, with a special emphasis on planning under time pressure. Before becoming a professor, he led a team at Xerox's PARC lab that used AI planning techniques to build the world's fastest printer. He was co-chair of ICAPS-14 and a co-founder of SoCS. And yes, Wheeler is his real name!
</p>
</div>
</div>
</div>


<br>
<div style="width: 100%; margin: 0; padding: 1%;">
<h3 style="color:orange;"><strong><a href="https://apps.ualberta.ca/directory/person/nathanst">Nathan Sturtevant</a></strong>, University of Alberta</h3>
<h4 style="color:black;"><strong>The Foundation of Best-First Search</strong></h4>
This session will cover the foundations of best-first search algorithms, which are broadly used for planning, including A*, WA*, GBFS, and many others. We will cover the theoretical foundations of best-first search, and then use this foundation to introduce a variety of algorithms that tackle challenges that arise when solving practical problems. This includes things like the worst-case performance of A* and how it is fixed with BGS, suboptimal algorithms (focal search, WA* and variants such as XDP), as well as ideas like partial-expansion. The goal of this talk is to give a foundational knowledge of best-first search that can be used for designing new algorithms to handle novel applications with unique problem constraints.<br><br>
<div style="display: inline-block; width: 30%; border: 2px solid orange; border-radius: 3%; padding: 1%; vertical-align:middle;">
<img style="width:100%; border-radius: 3%; vertical-align: middle;" src="https://icaps24.icaps-conference.org/summerschool/Nathan-Sturtevant.jpeg" />
</div>
<div style="display: inline-block; width: 68%; padding: 1%; vertical-align: middle;">
<div style="margin:0; padding: 0; padding-left: 2%">
<p>
Nathan is a Fellow and Canada CIFAR AI Chair at Amii and a Professor in the Department of Computing Science at the University of Alberta. His research looks broadly at heuristic and combinatorial search problems, including both theoretical and applied approaches, with many applications in games. His work on pathfinding has been used in the games Dragon Age: Origins and Nightingale. Nathan’s work has won the best paper awards at the AAAI, and SoCS conferences, as well as the AI Journal Prominent Paper Award.
</p>
</div>
</div>
</div>


<br>
<div style="width: 100%; margin: 0; padding: 1%;">
<h3 style="color:orange;"><strong><a href="https://groups.csail.mit.edu/mers/">Brian C. Williams</a></strong>, MIT</h3>
<h4 style="color:black;"><strong>Risk-bounded Task and Motion Planning in the Real World</strong></h4>
Robots need to know their limits, lest they recklessly endanger themselves and others. In this tutorial we present paradigms for designing task and motion planners that bound risk of failure, while spending acceptable risk to its greatest effect. Applications range from an autonomous car that maneuvers around reckless drivers to robot assembly and exploration of a deep-sea volcano.<br><br>
<div style="display: inline-block; width: 30%; border: 2px solid orange; border-radius: 3%; padding: 1%; vertical-align:middle;">
<img style="width:100%; border-radius: 3%; vertical-align: middle;" src="https://icaps24.icaps-conference.org/summerschool/Brian-Williams.jpg" />
</div>
<div style="display: inline-block; width: 68%; padding: 1%; vertical-align: middle;">
<div style="margin:0; padding: 0; padding-left: 2%">
<p>
Brian Williams: Brian Williams is a Professor of Aeronautics and Astronautics at the Massachusetts Institute of Technology, a Principal Investigator in the MIT Computer Science and Artificial Intelligence Laboratory, and an adjunct researcher at the Woods Hole Oceanographic Institute. His research focuses on online task and motion planning with bounded risk and human robot collaboration, applied to autonomous vehicles and robotic teams.
</p>
</div>
</div>
</div>


<br><br>
### ICKEPS 2024

The International Competition on Knowledge Engineering for Planning and Scheduling (ICKEPS) has been running since 2005 as an event promoting the development and importance of the use of knowledge engineering (KE) methods and techniques within planning and scheduling (P&S).

This year's special edition will be the first one to be run as part of a Summer School, and will focus on the knowledge engineering of domain models showing high degrees of maintainability, extendability, and operationality. Competitors (competing teams) will be provided with the specifications of challenging P&S scenarios and problems, and they will have to produce knowledge models encoding the requirements, and to demonstrate how their KE process will support changes in requirements resulting in extensions and/or modifications of the models. The competitors will also have to show how the designed models allow state-of-the-art planning engines to generate solutions.

**ICKEPS is organized by (*ordered alphabetically by last name*):**

<div style="width: 100%; margin: 0; padding: 1%;">
<h3 style="color:orange;"><strong><a href="https://sites.google.com/view/lukaschrpa/home">Lukáš Chrpa</a></strong>, Czech Technical University in Prague and Filuta AI</h3>
<div style="display: inline-block; width: 25%; border: 2px solid orange; border-radius: 3%; padding: 1%; vertical-align:middle;">
<img style="width:100%; border-radius: 3%; vertical-align: middle;" src="https://icaps24.icaps-conference.org/summerschool/Lukas-Chrpa.jpg" />
</div>
<div style="display: inline-block; width: 68%; padding: 1%; vertical-align: middle;">
<div style="margin:0; padding: 0; padding-left: 2%">
<p>
Lukáš Chrpa is an associate professor at Czech Technical University in Prague and a research scientist at Filuta AI. His research expertise is in i) developing techniques for capturing Domain Control Knowledge (e.g. macro-operators, entanglements) and encoding it into domain models, so generic planning engines can exploit it, and ii) applying domain-independent planning in areas such as Urban Traffic control, or Mission planning for AUVs. He co-organised the International Planning Competition (IPC) in 2014, the International Competition on Knowledge Engineering for Planning (ICKEPS) in 2016, Symposium of Combinatorial Search in 2022, the IPC workshop in 2016, the PlanSIG workshop in 2016, the AI for Urban Mobility workshop in 2021, the KEPS workshop in 2017, 2018, 2019, 2020, 2021, 2022 and 2023.
</p>
</div>
</div>
</div>


<div style="width: 100%; margin: 0; padding: 1%;">
<h3 style="color:orange;"><strong><a href="http://petrick.uk">Ron Petrick</a></strong>, Heriot Watt University</h3>
<div style="display: inline-block; width: 25%; border: 2px solid orange; border-radius: 3%; padding: 1%; vertical-align:middle;">
<img style="width:100%; border-radius: 3%; vertical-align: middle;" src="https://icaps24.icaps-conference.org/summerschool/Ron-Petrick.jpg" />
</div>
<div style="display: inline-block; width: 68%; padding: 1%; vertical-align: middle;">
<div style="margin:0; padding: 0; padding-left: 2%">
<p>
Ron Petrick is a Professor in the Department of Computer Science at Heriot-Watt University and the Edinburgh Centre for Robotics. He is Director of the UKRI AI Centre for Doctoral Training in Dependable and Deployable AI for Robotics, Co-Chair of the AAAI Symposium Series, and Coordinator of the UK Planning and Scheduling Special Interest Group. His research interests include epistemic planning, knowledge representation and reasoning, cognitive robotics, and explainable planning, with a particular interest in applications of planning to robot systems deployed in real-world environments with humans.
</p>
</div>
</div>
</div>



<div style="width: 100%; margin: 0; padding: 1%;">
<h3 style="color:orange;"><strong><a href="https://www.mvallati.net/">Mauro Vallati</a></strong>, University of Huddersfield</h3>
<div style="display: inline-block; width: 25%; border: 2px solid orange; border-radius: 3%; padding: 1%; vertical-align:middle;">
<img style="width:100%; border-radius: 3%; vertical-align: middle;" src="https://icaps24.icaps-conference.org/summerschool/Mauro-Vallati.png" />
</div>
<div style="display: inline-block; width: 68%; padding: 1%; vertical-align: middle;">
<div style="margin:0; padding: 0; padding-left: 2%">
<p>
Mauro Vallati Is a UKRI Future Leaders Fellow, ACM Senior Member, ACM Distinguished speaker on AI for the UK, Full Professor at the School of Computing and Engineering of the University of Huddersfield, and Director of the Research Centre on Autonomous and Intelligent Systems.
My main research interests are in Artificial Intelligence Planning and Argumentation. In particular I am interested in the application of AI Planning techniques to Urban Traffic and Mobility (this is also the topic of my Fellowship). I am also interested in the field of innovative applications of AI in Medicine.
</p>
</div>
</div>
</div>


<!--
[Lukáš Chrpa](https://sites.google.com/view/lukaschrpa/home), Czech Technical University in Prague and Filuta AI; [Ron Petrick](http://petrick.uk), Heriot Watt University; and [Mauro Vallati](https://www.mvallati.net/), University of Huddersfield (ordered alphabetically).
-->


<br><br>
## Program

For the entire program, we are always in room KC 201.

<b>On Monday, the program starts at 9 am with a 30 minute opening session before the first talk.</b>

Also, in the schedule below, all labs are organized and executed by Sarah Keren and our two Teaching Assistants (TAs) Guy Azran and Yuval Goshen.

<!--Is there an easy way to make all cells centered without adding arguments to all the cells?-->
<table>
<!--
    <tr>
        <th></th>
        <th>Monday</th>
        <th>Tuesday</th>
        <th>Wednesday</th>
        <th>Thursday</th>
        <th>Friday</th>
    </tr>
-->
    <tr>
        <td style="min-width: 150px;"></th>
        <td style="min-width: 150px;"><b>Monday</b></th>
        <td style="min-width: 150px;"><b>Tuesday</b></th>
        <td style="min-width: 150px;"><b>Wednesday</b></th>
        <td style="min-width: 150px;"><b>Thursday</b></th>
        <td style="min-width: 150px;"><b>Friday</b></th>
    </tr>
    <tr>
        <td><b>speaker</b></td>
        <td style="background-color: #ffa500;">Nathan Sturtevant</td>
        <td style="background-color: #ffa500;">Wheeler Ruml</td>
        <td style="background-color: #ffa500;">Jane Jean Kiam</td>
        <td style="background-color: #ffa500;">Brian C. Williams</td>
        <td style="background-color: #ffa500;">Hanna Kurniawati</td>
    </tr>
    <tr>
        <td><b>topic & time</b></td>
        <td style="background-color: #ffa500;">The Foundation of<br>Best-First Search<br>(09:30-11:00)</td>
        <td style="background-color: #ffa500;">Suboptimal Search and Motion Planning<br>(08:30-10:30)</td>
        <td style="background-color: #ffa500;">Automated planning for airborne applications: feasibility and challenges<br>(09:00-10:30)</td>
        <td style="background-color: #ffa500;">Risk-bounded Task and Motion Planning in the Real World<br>(08:30-10:30)</td>
        <td style="background-color: #ffa500;">Planning under Uncertainty, RL and Task and Motion Planning<br>(09:00-10:30)</td>
    </tr>
    <tr style="background-color: #f2f2f2;">
        <td><b>Coffee Break (time)</b></td>
        <td>(11:00-11:30)</td>
        <td>(10:30-11:00)</td>
        <td>(10:30-11:00)</td>
        <td>(10:30-11:00)</td>
        <td>(10:30-11:00)</td>
    </tr>
    <tr>
        <td><b>speaker</b></td>
        <td style="background-color: #ffa500;">Sarah Keren</td>
        <td style="background-color: #ffa500;">Pascal Bercher</td>
        <td style="background-color: #add8e6">Lukáš Chrpa, Ron Petrick, Mauro Vallati (organizers)</td>
        <td style="background-color: #ffa500;">Jeremy Frank</td>
        <td style="background-color: #ff0">Sarah Keren and TAs</td>
    </tr>
    <tr>
        <td><b>topic & time</b></td>
        <td style="background-color: #ffa500;">Introduction to Integrated Task and Motion Planning<br>(11:30-12:30)</td>
        <td style="background-color: #ffa500;">An Introduction to Hierarchical Task Network (HTN) Planning: Theoretical Foundations & Problem Solving<br>(11:00-12:30)</td>
        <td style="background-color: #add8e6">ICKEPS<br>(11:00-12:30)</td>
        <td style="background-color: #ffa500;">The Distributed Spacecraft Autonomy (DSA) Project<br>(11:00-12:30)</td>
        <td style="background-color: #ff0">Lab: Final session<br>(11:00-12:30)</td>
    </tr>
    <tr style="background-color: #f2f2f2;">
        <td><b>Lunch (time)</b></td>
        <td>(12:30-13:30)</td>
        <td>(12:30-13:30)</td>
        <td>(12:30-13:30)</td>
        <td>(12:30-13:30)</td>
        <td>(12:30-13:30)</td>
    </tr>
    <tr style="background-color: #f2f2f2;">
        <td><b>Break (time)</b></td>
        <td>(13:30-14:00)</td>
        <td>(13:30-14:00)</td>
        <td>(13:30-14:00)</td>
        <td>(13:30-14:00)</td>
        <td>(13:30-14:00)</td>
    </tr>
    <tr>
        <td><b>Topic & time</b></td>
        <td style="background-color: #ff0">Lab: Task Planning<br>(14:00-15:30)</td>
        <td style="background-color: #ff0">Lab: Motion Planning<br>(14:00-15:30)</td>
        <td style="background-color: #add8e6">ICKEPS<br>(14:00-15:30)</td>
        <td style="background-color: #ff0">Lab: Task and motion planning<br>(14:00-15:30)</td>
        <td>Panel - All speakers<br>(14:00-16:00)</td>
    </tr>
    <tr style="background-color: #f2f2f2;">
        <td><b>Coffee Break (time)</b></td>
        <td>(15:30-16:00)</td>
        <td>(15:30-16:00)</td>
        <td>(15:30-16:00)</td>
        <td>(15:30-16:00)</td>
        <td>(15:30-16:00)</td>
    </tr>
    <tr>
        <td><b>Topic & time</b></td>
        <td style="background-color: #ff0">Lab: continue...<br>(16:00-17:30)</td>
        <td style="background-color: #ff0">Lab: continue...<br>(16:00-17:30)</td>
        <td style="background-color: #add8e6">ICKEPS<br>(16:00-17:30)</td>
        <td style="background-color: #ff0">Lab: continue...<br>(16:00-17:30)</td>
        <td>Summer school wrap-up and Quiz<br>(16:00-17:30)</td>
    </tr>
    <tr>
        <td><b>Evening (time)</b></td>
        <td>"Speed Dating" at TCPL<br>(20:00-21:30)</td>
        <td></td>
        <td></td>
        <td>Dinner<br>(18:00-19:30)<br>Hang-out & Jam Session at TCPL (20:00-21:30)</td>
        <td></td>
    </tr>
</table>
<br>

**Further Information:**
- Our social evening program is voluntary. Parts of it will be announced on-site.
- In the "Speed Dating" we mix up pairs of two randomly who can ask random questions so that we all get to know each other! "Rules" will be shared in time.
- The venue TCPL of some of our social events are stands for TransCanada Pipelines Pavilion and it's on campus.
- Keep in mind that we don't update this page anymore close to the event. We use the readme in our [github](https://github.com/CLAIR-LAB-TECHNION/ICAPS-24) for recent news.


**Caption:**
- <span style="background-color: #ff0; color: black;">Labs:</span> All our lab sessions are depicted in <span style="background-color: #ff0; color: black;">Yellow</span>. These are our hands-on sessions on Task and Motion Planning.
- <span style="background-color: #ffa500; color: black;">Lectures:</span> All talks (sometimes called lectures) are depicted in <span style="background-color: #ffa500; color: black;">Orange</span>.
- <span style="background-color: #add8e6; color: black;">ICKEPS:</span> Our program for the International Competition on Knowledge Engineering for Planning and Scheduling is depicted in <span style="background-color: #add8e6; color: black;">Blue</span>.



### Lab Sessions

To participate in the lab sessions (online or on-site), you will require:

- A laptop. Software runs in a browser, so no special software or operating system is required. If you use Google Colab (which is what we use), you will need a google account. The URL of the notebooks is [https://github.com/CLAIR-LAB-TECHNION/ICAPS-24](https://github.com/CLAIR-LAB-TECHNION/ICAPS-24). That repository contains a readme, which explains how to run the notebooks. (At least the readme *will* contain that explanation before the labs start.)
- Basic knowledge of PDDL. If you can't read PDDL yet, you could check out this [hands-on lecture](https://www.youtube.com/watch?v=pfNb0IAkbcQ&t=3s) (you can start at 40:00 in case you are already familiar with classical planning). The required hands-on material can be downloaded [here](https://bercher.net/data/teaching/2022/2022-S1--CCSE--PlanningIntroHandsOn.zip). Slides are available [here](https://bercher.net/data/teaching/2022/2022-S1--CCSE-PlanningIntro.pdf).
- Basic knowledge of the programming language Python.
- Live participation will be enabled via zoom. The zoom link is made available in the readme that's part of our git (see above). (As mentioned at the very top, our readme will also serve as our central hub for any news and other info we want to share in a timely manner, so check it frequently!)
- Please note that in case remote participation in the labs exceeds our capacities, priority will be given to our in-person participants.


## Who can join? 

The summer school is primarily intended for PhD students, but post-docs in their early post-doctoral career are also eligible. We also do not exclude students who did not start their PhD yet, so encourage them to apply as well.

As of now, we have 40 (in-person) spots for participants. We would have loved to make the event bigger, but given the circumstances, it doesn't look possible. But well, it is not all about numbers! It will be a small and tight-knit group! 


## Costs and Financial Aid

The registration fees are 950 CAD. They include board and lodging, see below. Note that travel costs (for flights or any transport means to travel to the Banff Centre) are *not* part of the registration fees, so you will have to finance this on your own.

We will provide a small number of financial aids, which cover parts or all of the registration fees for a few selected participants (the application form allows you to apply for this). 


## Board and Lodging

The registration fees include:
- Six nights in the Banff Centre (from Sunday, 26 May to Saturday, 1 June), where also ICAPS takes place. If you stay for ICAPS, you will have to book the remaining nights yourself. Note that we *only* booked double-rooms, so you will have to share a room. We plan to write to all accepted applicants once selection is completed, so you can coordinate in case you prefer staying with somebody you know already.
- Breakfast, lunch and coffee breaks from Monday (27 May) to Friday (31 May).
- Dinner on Thursday (30 May).


## Important Dates & Application

- Applications open:   <s>12 February</s>
- Applications close:  <s>26 February</s>
- Notifications sent:  <s>4 March</s>
- Summer school:       Monday, 27 May to Friday, 31 May 2024.

Application data required:
- Basic information to be provided in the [google document](https://docs.google.com/forms/d/e/1FAIpQLSetvlhWIMTFmrIYhpjSv53Nu6lE1xk4WD3WJT2-jNysQVlHcw/viewform?usp=sf_link).
- A *light-weight* motivation letter describing the relevance of the Summer School and how you would benefit from it. It is perfectly fine if the topics covered are a bit further away from what you do in your research -- after all, it's about learning something new!
- A CV.
- Our [consent form by your supervisor](https://icaps24.icaps-conference.org/files/AdvisorForm.pdf), confirming the applicant's identity and consent to attend the summer school.
- If you request financial aid, provide a letter of recommendation by your supervisor, which should also lay out the necessity for this aid.

Please merge the documents in the order provided into one single PDF. You will then have to upload it via [google forms](https://docs.google.com/forms/d/e/1FAIpQLSetvlhWIMTFmrIYhpjSv53Nu6lE1xk4WD3WJT2-jNysQVlHcw/viewform?usp=sf_link). Note that google forms strictly requires a google account because of the file upload. We apologize for this.

Applications will be reviewed for admission after submission is closed. Note that admissions will *not* be assessed based on a first-come-first-serve basis, so every application that arrives before the closing date will be evaluated fairly, no matter when they were submitted. 


## Organizing Team

The organizing team, sorted alphabetically by last name, consists of:

- Pascal Bercher from the Australian National University, Australia -- pascal.bercher at anu.edu.au, [webpage](https://comp.anu.edu.au/people/pascal-bercher/)
- Sarah Keren from Technion, Israel -- sarahk at technion.ac.il, [webpage](https://sarahk.cs.technion.ac.il)
- Jane Jean Kiam from University of the Bundeswehr Munich, Germany -- jane.kiam at unibw.de [webpage](https://www.unibw.de/home-en/appointment-of-professors/prof-jane-jean-kiam)

In putting together the program, Sarah has been supported by our two teaching assistants:

- Guy Azran from Technion, Israel
- Yuval Goshen from Technion, Israel



## Sponsors

We greatly appreciate our **Platinum** sponsors:  

<a href="https://www.birs.ca/">
    <img src="/summerschool/BIRS_Logo2.png"/>
</a>
<br><br>

<a href="https://aij.ijcai.org/">
    <img src="/img/partners/aij.jpeg" alt="AIJ" width="250"/>
</a>
<br><br>


| Platinum sponsorship (5000 CAD and above)&nbsp;&nbsp;&nbsp;&nbsp; | Gold sponsorship (2500 to 4999 CAD)&nbsp;&nbsp;&nbsp;&nbsp; | Silver sponsorship (1000 to 2499 CAD) |
| ------------------------------------------ | ---------------------------------- | ------------------------------------- |
|                                            |                                    |                                       |
| *30 mins* presentation                     | *15 mins presentation*             |  --                                   |
| *2* poster                                 | *1 poster*                         | --                                    |
| flyer and goodies                          | flyer and goodies                  | *flyer and goodies*                   |
| email-forward                              | *email-forward*                    | --                                    |
| networking package                         | networking package                 | *networking package*                  |
| *large logo* (and link) posted             | *mid-sized logo* (and link) posted | *small logo (and link) posted*        |
| *additional requests, e.g., participation* | --                                 | --                                    |

<br>


**Benefits explained:**

- All Silver benefits are included in the Gold benefits, all Gold benefits are included in the Platinum benefits (or slightly improved according to the table).
- poster: You may send us 2 or 1 (Platinum vs Gold) poster up to size A0 directly to the venue. We will prominently display them during all 5 days of the summer school.
- presentation: You may give a 30 or 15 minute (Platinum vs Gold) *online* presentation that our participants will attend (e.g. a pitch on the sponsor's activities). This time does include a Q&A exchange with our participants.
- flyer and goodies: You may send us an A5 PDF, two-sided, which we will print out and distribute to the participants. You may also send us (directly to the venue) some merchandise (pens, etc.) that we will distribute as well. (Consider that everybody will be traveling by plane, so space is restricted.)
- email-forward: You may send us a single email (e.g., in style of a newsletter, announcement, etc.) which we will forward to our participants. (This way you can reach our participants even if they do not consent to make their contact details available.)
- networking package: We will create a LinkedIn group and ask our participants to join (although this is voluntary). Our sponsors will join it too and can hence write an announcement or connect directly with our participants. We furthermore ask our participants for consent to make their contact data available to our sponsors (again this is voluntary). This data will contain their name, status (Master Student, PhD student, Post-Doc etc.), and email address.
- logo: We will make your logo available in large, medium, or small size according to the sponsorship model. This logo will also contain a link to the sponsoring organization. These will be made available both on this (summer school) webpage, as well as on a dedicated summer school page in the ICAPS proceedings (not where the ICAPS sponsors are listed). In case we create some booklet of this summer school (which is not clear yet; but if we do, it will only be a PDF but not printed/formally published), sponsors will be added there as well.
- additional requests: In the Platinum model, you may contact us organizers for any specific proposals (e.g., if you want to send a PhD student to participate), and we can see what we can do.




<!--  Additional information that we might want to add in the future:

- Links to past summer schools, including the info whether tutorial recordings exist.
- ???

-->
