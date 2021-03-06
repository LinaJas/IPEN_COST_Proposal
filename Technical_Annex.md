#1.	S&T EXCELLENCE

##1.1.	Challenge 
##1.1.1.	Description of the Challenge (Main Aim)
Protecting fundamental rights online is made harder than it needs to be by the gap of understanding between technical, legal annd civil society communities.

Many people, from different areas such as data protection authorities, academia, open source and business development, and other individuals, are committed to finding engineering and political solutions to privacy challenges. Broadly, we can speak of the technical community (developers, researchers, those working in technical standardisation such as with the IETF, the W3C and the ISO) and the legal community (those working in regulation such as data protection authorities). While there are of course some who overlap, given the scale of the challenge, there are not enough such people and action is needed to provide an ongoing and rich point of contact between the communities.

Much of the technical development work for new internet based applications and services is now carried out by business enterprises, who are naturally mainly focussed on the potential for commercial return, and in many cases this conflicts with data protection and privacy rights. Because of the societal impact of these new services it is important that democratic institutions play a role in decision making about them, but often do not have the right level of technical expertise necessary. A forum where wider society representatives and the technical community inform each other and where concerns can be can be aired would generate a better outcome for business and individuals. 

##1.1.2.	Relevance and timeliness
The rising popularity of the internet for uses in entertainment, commerce, education, and dissemination of information and ideas brings important benefits for individuals and society but also creates dangers to both through the ease of collection and processing of personal data. Although there is a growing body of European and Member State law applicable to data protection, online security and privacy, personal data is increasingly collected on a massive scale and individuals do not have the ability to control or often even detect that it is happening. The protocols and standards underlying the internet have been built up over the years, and in the past perhaps not enough attention was paid to issues of security and privacy of individuals. There is now an urgent need to define new technologies and standards more suitable for the data protection and security requirements of networks used by billions of people.

The conception of, and level of interest in, privacy has also changed hugely within the Internet technical community over the last two years. That is partly as a result of the Snowden revelations, but is also a trend that has been increasingly obvious for the last five or so years. This can be seen in the significant increases in ciphertext in networks, for example with the proportion of email being protected with TLS as it is sent between servers having increased from an estimated 20% to above 90% when measured from a major email provider to most European and North American partners. There is a similarly increasing level of interest in the privacy aspects of many protocols, from HTTP/2.0 all the way down to MPLS. And within the IETF for example, RFC7258 has codified that trend so that privacy (in the sense of resisting pervasive monitoring) is an aspect that now needs to be considered in all protocol designs. The work however, has only really begun, as methods to mitigate traffic analysis are simply not well understood and much additional research and education (of protocol developers and implementers) is needed in that space. 



##1.2.	Objectives
##1.2.1.	Research Coordination Objectives

IPEN will launch projects for the development of infrastructure, tools and building-blocks which enable and enhance privacy. 
These projects are envisioned to be both initiatives within Standards Development Organisations (such as the ISO, W3C and IETF) to help build consensus for procedures and interfaces that enhance privacy, and projects to develop and assemble open source building blocks made available to the wider technical community, and help develop and enhance the internet infrastrucure as a space where fundemental rights are intrinsically supported. Potential projects include:
  - Describing and publishing the technical procedures that organisations, when subject to European Data Protection regulation and who control public facing web servers, should operate with respect to the collection of "tracking data" i.e. personal data pertaining to web activity. This should give specific guidance on the use static persistant identifiers and fingerprinting, in the context of the Privicy and Electronic Communications Directive, the Data Protection Directive and the forthcoming General Data Protection Regulation.  It should also describe what difference in behaviour and presentation data subjects should expect from servers responding to HTTP requests in which the DNT (Do Not Track) browser signal is present. 
    
  - Develop a draft standard for cryptographically signed mark-up declaring the identity of data controllers and processors responsible for a web origin, with the aim of enabling user-agents to inform users of the legal identity and privacy policy of controllers who may collect personal data while they browse the web. Introduce this draft to the relevant W3C or IETF working group, and support the standards work necessary to complete it. 

  - Develop a draft standard for web session establishment and management by user agents, with the aim to give individuals visibility of and control over authenticated and anonymous sessions. This should be synchronised with existing IETF work on preventing security token export and replay attacks. Introduce this draft to the relevant standards body working group, and support the work necessary to complete it.
        
  - Foster the development of protocols and standards for anonymous unlinkable and virtualised network identity. The aim is to give web users control of how much identifiable information is shared. It should, for example, be possible for users to manage and convey an audience categorisation to a publishers website without being tracked, and for    individuals to browse the web anonymously if they wish. 

  - Identify ['usecases'](http://www.techopedia.com/definition/25813/use-case) - where tech engineers identify a series of steps that will enable them to solve a specific problem - for which privacy can be implemented at the design level.
    





##1.2.2.	Capacity-building Objectives
IPEN will provide a forum allowing the technical Internet community to interact with data protection authorities, internet engineers and interested privacy researchers, so as to identify potential areas for conflict and potential areas for collaboration. The former may occur if one community embraces a change that is problematic for other communities. The latter could involve identification of areas where all communities recognise the potential for aiming to meet commensurate requirements. Note - the objective here is to identify and discuss such potential conflicts and areas for collaboration - the actual work to resolve conflicts or action collaborations is not intended to be done under the auspices of this COST action.

It will also encourage IT specialists to develop privacy friendly solutions and to recognise the impact of their technical choices on users' privacy. Its aim is to integrate data protection and privacy into all phases of the development process, from the requirements phase to production, as it is most appropriate for the development model and the application environment.

##1.3.	Progress beyond the state-of-the-art and Innovation Potential 
##1.3.1.	Description of the state-of-the-art
The internet has grown from its roots in academic and Government sponsored research to become a major factor in the lives of billions of people around the world. The frenetic pace of this development has unfortunately left major components insecure against threats such as mass unwarranted surveillance and predatory commercial profiling. The lack of basic privacy protection components has led to a atmosphere where many business and technical developers do not have the necessary awareness of the need, and training in techniques, for public facing computer systems to protect personal data and the fundamental human right to privacy. 

##1.3.2.	Progress beyond the state-of-the-art
We aim to create and disseminate a body of best practices, procedures and working open source code, and push for the design and widespread implementation, of APIs and protocols that can help solve current challenges to privacy and security. Through this activity we aim to improve the understanding in the wider technical community of the reasons for protecting privacy and of the techniques and infrastructure designed to do that, and educate the other communities of the potentials and constraints of technological processes.  

##1.3.3.	Innovation in tackling the challenge
There is an increasing number of client-side (in browsers) protocols and APIs, which could be used as a basis to enhance online privacy. Much of the work innovating around these new technologies has often been at the behest of Online Advertising and other commercial interests aiming to exploit so-called “Big Data”, (the massive low cost collection of personal data), but many engineers and businesses wish to explore the data protection possibilities of these mechanisms. Similarly the standards making process could be improved through the involvement of experts who are committed to improving privacy, but who up to now have often had to operate in an ad-hoc or uncoordinated way. Creating a focus for how enhanced technologies could be used to support fundamental rights will create a more diverse business environment which is more aligned with the interests of people and provide a stage for new business models.

##1.4.	Added value of networking 

##1.4.1.	In relation to the Challenge

The main added value here is to provide a rich and ongoing point of contact between the technical and legal communities, who have, to date, not had such a venue for collaboration.


##1.4.2.	In relation to existing efforts at European and/or international level

Many disparate activities have been endeavoured to design and develop Privacy Enhancing Technologies. Recognizing a need for coordination among these activities, several initiatives have started working on standardizing a catalogue of such technologies; however, they have fell short of achieving that. ISO and IEC through the group ISO/IEC JTC 1/SC 27/WG 5 focus on privacy frameworks and management (ISO 29100, 29134, 29151), but they have not yet gone down to the level of specific techniques. Other initiatives by e.g. OASIS (PbD-SE Privacy by Design for Software Engineering, PMRM Privacy Management Reference Model), W3C (Privacy Interest Group - PING), IETF (RFC 6973 and a discussion list) and the privacypatterns.eu portal have not yet provided mature enough results. In a specifically European context, we must remark as well the current works to develop a privacy engineering methodology carried out by FP7 CSA PRIPARE and the soon-to-be issued EC mandate to establish European Standards on PbD, which will be developed by CEN/CENELEC Joint Working Group 8 on ‘Privacy management in products and services’.

All these initiatives have in common a geographic and organizational dispersion of their members, which we consider that has prevented them from achieving further and faster results. The community is in need of an action such as IPEN that will help grease the network of individuals so that they foster a common vision and eventually achieve the above mentioned objectives. Needless to say that IPEN needs to be aligned with those other initiatives, so as to avoid the risk of fragmentation. However, this risk will not materialize; furthermore, IPEN results are guaranteed to be integrated within those initiatives, because all of them count with IPEN proposers among their members.


#2.	IMPACT

##2.1.	Expected Impact 
##2.1.1.	Short-term and long-term scientific, technological, and/or socioeconomic impacts

###Short Term Impact
A single document describing a common European wide approach to the collection and use of tracking data would give millions of companies with public facing websites legal surety. The considerable body of European privacy and data protection law would begin to be seen by individuals as a valuable aid to protecting them from non-consensual profiling and not, as it is often portrayed, as bureaucracy acting as an impenetrable smokescreen. 

###Long Term Impact
In the longer term the availability and standardisation of privacy and security supporting APIs and procedures will create an environment in Europe for technical and business innovation around new business models, which no longer need  conflict with the fundamental rights of individuals. The internet can take on its promised character to enhance democracy, build civilised values and foster a healthy and widely trusted business economy.

##2.2.	Measures to Maximise Impact
##2.2.1.	Plan for involving the most relevant stakeholders 
Text

##2.2.2.	Dissemination and/or Exploitation Plan 
Text

##2.3.	Potential for Innovation versus Risk Level 
##2.3.1.	Potential for scientific, technological and/or socioeconomic innovation breakthroughs
Text


#3.	IMPLEMENTATION

##3.1.	Description of the Work Plan
##3.1.1.	Description of Working Groups – Provide for each WG the Objectives, Tasks, Milestones and Deliverables.
##3.1.1.1  Standards Body Coordination and Support Working Group.
###3.1.1.1.1  Objectives.
The main job of this Working Group is to coordinate and support privacy and security enabling activities in the Standards Development Organisations.
###3.1.1.1.2  Tasks.
Organise regular web conferencing and face-to-face meetings for anyone committed to building support for online privacy in international standards.

###3.1.1.1.3  Milestones
- Agree the “Tracking  Data and User Consent Signal Compliance” document within the Working Group.
- Achieve consensus support for it from European DPAs, the Article 29 Working Party and the office of the European Data   Protection Supervisor.

###3.1.1.1.1.4  Deliverables
The “Tracking  Data and User Consent Signal Compliance” document hosted and maintained on the public web.

##3.1.1.2  Innovation and Research Working Group.
###3.1.1.2.1  Objectives.
This Working Group will co-ordinate the work in academia and private business developing new tools, protocols, open source code, guidelines and infrastructure to support data protection and online privacy.

###3.1.1.2.2  Tasks.
Organise regular web conferencing and face-to-face meetings to encourage communications between technical developers in academia and business, and other communities in civil society and the public sector also committed to data protection principles.

###3.1.1.2.3  Milestones
###3.1.1.2.4  Deliverables
##3.1.1.3  Education and Outreach Working Group
###3.1.1.3.1  Objectives.
The group will ensure that IPEN activities and Privacy-By-Design principals are communicated to the wider public and business communities. It will approach any business committed to data protection and privacy principals to encourage their involvement with IPEN. It will coordinate the supply of technical advice relevant to online privacy, data protection and security to institutions such as the European Commission and Parliament.

###3.1.1.3.2  Tasks.
###3.1.1.3.3  Milestones
###3.1.1.3.4  Deliverables
##3.1.1.4 Governance and Transparency Working Group
###3.1.1.4.1  Objectives.
The main task of this group is to ensure that IPEN operates in line with ethical principles, operational efficiency and European law. It will consist of representatives from each Participant and Working Group as well as non-voting representatives from the European Data Protection Supervisor’s office and the Article29 Working Party. Observers from the European Parliament and Commission will also be invited. The Group will also operate as the COST Management Committee. As far as is feasible enough members will be appointed to attain a 1:1 gender balance, with a target of least 40% of the under-represented sex, in line with the European Commission’s [“Strategy for equality between women and men 2010-2015”](http://ec.europa.eu/social/BlobServlet?docId=6568&langId=en)

###3.1.1.4.2  Tasks.
###3.1.1.4.3  Milestones
###3.1.1.4.4  Deliverables

##3.1.2.	GANTT Diagram 

##3.1.3.	PERT (optional)

##3.1.4.	Risk and Contingency Plans
Text

##3.2.	Management structures and procedures
Text

##3.3.	Network as a whole
Text
