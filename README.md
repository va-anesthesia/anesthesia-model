## VA Enterprise Anesthesia Model (VEAM)

**OBJECTIVE and MOTIVATION**

**The Open Anesthesia Model is a peer-reviewed, practice-driven, literature-backed freely licensed computable anesthesia information model that enables exchange of the anesthesia record easily with existing standards and technology.**  The Open Anesthesia Model is based on **JSON**, the same foundational data model adopted by the international healthcare interoperability standards organizations (HL7 and FHIR), thus allowing adoption and use by the broadest community of orgranizations providing anesthesia care.

The Open Anesthesia Model meets the mandates of the 2016 U.S. [CURES Act](https://en.wikipedia.org/wiki/21st_Century_Cures_Act) which requrires that the patients' health record - including all anesthesia record - must be accessible to all patients at no cost and with no special effort. Noncompliance - also known as "information blocking" - carries a fine of up to $1 million.


References:  
* [ASA Monitor:Open Anesthesia Records: Guidance for Anesthesia Providers on Implementing the Cures Act](https://pubs.asahq.org/monitor/article/85/2/e3/115119/Open-Anesthesia-Records-Guidance-for-Anesthesia)
* [FDA: guidance for anesthesia on implementing the Cures Act](https://www.opennotes.org/research/open-anesthesia-records-guidance-for-anesthesia-providers-on-implementing-the-cures-act)
* [Anesthesia & Analgesia: Sharing Anesthesia Records With Patients](https://journals.lww.com/anesthesia-analgesia/Fulltext/2022/10000/Keeping_an_Open_Mind_About_Open_Notes__Sharing.8.aspx)
* [ Anesthesia & Analgesia: Engaging Transparency and Being on the Right Side of History](https://journals.lww.com/anesthesia-analgesia/Citation/2022/10000/Engaging_Transparency_and_Being_on_the_Right_Side.7.aspx)
* [Why should anesthesiologists be concerned with infomration blocking?](https://www.anesthesiallc.com/publications/anesthesia-provider-news-ealerts/1219-why-should-anesthesia-providers-care-about-information-blocking-2)
* [Pediatric Anesthesiology: The Cures Act](https://ronlitman.substack.com/p/the-cures-act)
* [HealthIT.gov: Information Blocking](https://www.healthit.gov/topic/information-blocking)
* [Federal Register: 21st Century Cures Act: Interoperability, Information Blocking, and the ONC Health IT Certification Program](https://www.federalregister.gov/documents/2020/05/01/2020-07419/21st-century-cures-act-interoperability-information-blocking-and-the-onc-health-it-certification)







 **USE CASES**

**1. Semantic Interoperability of all structured data comprising a standard anesthesia record**.  This will allow exchange of the anesthesia record **directly from system-to-system** (such as AIMS--EHR or AIMS--Analytics platform) in machine processable form with without any cost, middleware, or middleman. This will support efficient, free, unlimited, and fully automated exchange of structured anesthesia information between all stakeholders to support aggregation, analytics, clinical research, compliance, and national quality initiatives.

**2. Review the entire digital anesthesia record on a single page view on any mobile or desktop web device.** This will provide anesthesiologists the most convenient, accessible, and rapid review of the digital anesthesia record - or a digitally exchanged one - from any device with a modern web browser at the bedside.  To accomodate viewing all data efficiently in smaller web browsers, the best practices in high density information display will be used, incorporating [sparklines](https://en.wikipedia.org/wiki/Sparkline) and motifs from [trading platforms](https://www.tdameritrade.com/tools-and-platforms/mobile-trading/td-ameritrade-mobile.page). This will allow anesthesiologists to review all past, present, or exchanged records rapidly and easily with a single ubiquitous viewer (including the one in their pocket) supporting  clinical decision support at the bedside,  enhancing patient safety and care. 

**3. Aggregation of all anesthesia records to provide population-based analytics for national quality improvement programs**.  Free and open licensing will allow the exchange and integration of the anesthesia record in structured machine processable form to support inter-institutional interoperabiity, secondary use, research, and national quality improvement initiatives. 



**MODEL CHARACTERISTICS**

The model will be constrained initially to a small set of **core concepts** required for a **baseline generalist model** and encourage **broadest adoption and feedback**.  Operational, administrative, financial, or specialist use cases are not accomodated in this core model. However, the model it will be structured with enumerations to allow local extension for all of the subspecialties.

The model will be a **self-contained**  and **fully functional**  with **no dependencies** on external proprietary technologies or terminologies. This will be licensed under Creative Commons for **universal and free use without any restriction** other than attribution.  There will be slots in the model with SameAs links  to  external controlled terminology (which is region and country-specific)  as desired. 

This model shall be **continuously published**  and made **universally accessible** at no cost in **machine processable form**  through direct URL dereferncing through a  **RESTful endpoint**  leveraging standard W3C web technologies such that web developers can incorporate this model directly in their web applications.

**PARTICPATION**

Participation is open to the public. No membership to any governing body, association, or orgainzation is required. 


**QUALITY ASSURANCE**

To keep this small and high quality the following approach will be taken:

* **Accountability**: Proposers of each term will be the "owner" of the term in order to field all questions regarding it. Proposers must include their email address (using non-machine readable form, such as myaddress AT domain dot com), and supporting information with their proposal (context, usage, frequency, impact, literature links) to initiate peer review.
* **Context**: Explanation of anticipated context and use of term in workflow (preop, intraop, postop, etc.)
* **Practice-driven**: Is the term rarely used, or used only by subspecialists, or is it used by most anesthesiologists in most cases and contexts?  Provide information on frequency of term usage as a % of cases or contexts covered (100%, >90%, >50%, <25%, <10%, or <1%). Provide URL to pubmed or other openly available literature to support its usage in practice.
* **Impact**: How will digitally recording this concept impact patient care or outcomes? Provide URL to pubmed or other openly available literature to support its impact factor.
* **Peer review**: The term, its location in the hierarchy, and all supporting information will have independent validation through peer review on Github.
* **Continuous review**: All terms will be continously reviewed.  If there are considerably more than 100 in the list (say over 150) then the less frequently used ones (<10% or <1%) will be deprecated to make space for other terms with more general applicability.


***
**SIGN UP** to the Open Anesthsia Model community

Contributors should sign up for a free account on:
* [WebProtege](http://webprotege.stanford.edu/#Edit:projectId=6e850880-fed9-4b75-bbb0-8c57119cca1a): Stanford's web-based collaborative model development platform.  Then you may review and contribute to the [Anesthesia Model](http://webprotege.stanford.edu/#Edit:projectId=6e850880-fed9-4b75-bbb0-8c57119cca1a) that is hosted there.
* [Github](https://github.com/): Our collaboration and communication platform.  To submit or review model recomendations, or to join our online conversations, use our [Anesthesia Model Forum](https://github.com/healthschema/anesthesia/issues)

***
**CONTRIBUTE**

1. Open the [Issues tab](https://github.com/healthschema/anesthesia/issues) 
2. Create a new issue ticket labelled with your new term ([see example: "Mallampati Score"](https://github.com/healthschema/anesthesia/issues/8))
3. Label issue as "proposed term"
4. In the body of the issue ticket include your name and email address (yourname AT domain DOT com), context of use, frequency of use, impact on patient care, and literature links.
5. Support reasons for your term inclusion with literature links to [Pubmed search](http://www.ncbi.nlm.nih.gov/pubmed) or other freely accessible literature source.
6. Peers will review this submission and provide feedback, comments, recommendations; and will further tag the proposal. In the example "Mallampati Score" it was flagged as "peer reviewed: incomplete" because it was lacking any literature citations.


Any questions?  Create a new Issue!

***
**FOUNDATION MODEL CLASSES:** for [Open Anesthesia Model](http://webprotege.stanford.edu/#Edit:projectId=6e850880-fed9-4b75-bbb0-8c57119cca1a)

*  **PATIENT** : patient preop history, assessments, and risk factors; **static data**
* **PROCEDURE**:  details about the surgeon and surgery; **static data**
* **CHARTING**: all observations, administrations, procedures; **flow data**

**static data** = enter once and leave alone; historical info; doesn't change; no timestamp required

**flow data** =  continously changing set of events, observations, administrations, procedures. These are all temporally changing and interdependent and therefore require continuous charting with timestamps.  (Example: observation BP is low -- 1min--> administer medication --2min--> observation BP is normal)

***
**INITIAL MODEL**

1. Google image search for "preop assessment form", "anesthesia record", "postop recovery forms" and contributed PDF copies of these forms.
2. Pubmed search on "most frequently used anesthesia data elements", "preop assessment", "risk stratification", "anesthesia chart", etc.
3. Pubmed search for papers on "anesthesia outcomes" to catalog risk factors that are of value
4. Review of papers from the Anesthesia Patient Safety Foundation (APSF) on quality and safety parameters.
5. Review structured data output of ASA AQI initiative of *actually collected data*  (not the model)
6. Review structured data generated by operational Periop, Surgery, or AIMS systems.


**Getting Started with Github**

1. Review [Github Guide](https://guides.github.com/)
2. Review [Intro to Issues](https://guides.github.com/features/issues/) 
3. Review [Intro to Wikis](https://guides.github.com/features/wikis/)

For the technically curious:

1. [Why Github?](http://healthschema.github.io/page2/)
2. [Github and Government: A perfect match](http://healthschema.github.io/page3/)
3. [Git: The Simple Guide](http://rogerdudler.github.io/git-guide/)


