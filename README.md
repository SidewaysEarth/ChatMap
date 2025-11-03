# ChatMap
ChatMap Knowledge for Regeneration
<!-- Copy and paste the converted output. -->

<!-----

You have some errors, warnings, or alerts. If you are using reckless mode, turn it off to see useful information and inline alerts.
* ERRORs: 1
* WARNINGs: 0
* ALERTS: 13

Conversion time: 5.579 seconds.


Using this Markdown file:

1. Paste this output into your source file.
2. See the notes and action items below regarding this conversion run.
3. Check the rendered output (headings, lists, code blocks, tables) for proper
   formatting and use a linkchecker before you publish this page.

Conversion notes:

* Docs to Markdown version 1.0β44
* Mon Nov 03 2025 06:06:03 GMT-0800 (PST)
* Source doc: ChatMap for Regeneration Specifications

ERROR:
undefined internal link to this URL: "#heading=h.e0detrm0gye1".link text: Regenerative Knowledge Systems
?Did you generate a TOC with blue links?

* Tables are currently converted to HTML tables.
* This document has images: check for >>>>>  gd2md-html alert:  inline image link in generated source and store images to your server. NOTE: Images in exported zip file from Google Docs may not appear in  the same order as they do in your doc. Please check the images!


WARNING:
You have 8 H1 headings. You may want to use the "H1 -> H2" option to demote all headings by one level.

----->


# ChatMap: Community Knowledge for Regeneration


## Specifications version 1.0


# Inspiration for the ChatMap specifications

Sideways.earth is releasing the body of work developed over the past two years since the collaboration was established. ChatMap was an idea that emerged based on a series of conversations about the “Knowledge Commons” for the regenerative movement. Sharing information and knowledge has been a focus of these movements, and there’s been an assumption that “if only” we could get information into the right hands at the right time, the movement would operate more effectively.

However, the approach towards knowledge commons has been based on pre-LLM thinking. The [Regenerative Knowledge Systems](#heading=h.e0detrm0gye1) table indicates some of the organizations that are collecting information in database or Wiki structures. The directionality of this effort is high-touch, manual, and requires centralized databases. ChatMap approaches the problem based on technology available in 2025, not in the outdated idea of collecting everything into a database. We believe those approaches have limited use based on their past history. There is potential of AI to serve the regenerative movement.

The specification of ChatMap is an early iteration of how we envision an LLM for community knowledge sharing on local, regional, and planetary levels. It is not the primary focus of Sideways, and we are open to partnership or to those who simply want to take this specification under the Copyleft license, and use it for their own non-commercial purposes. If you are using the concepts for commercial purposes, please get in touch with [grace@sideways.earth](mailto:grace@sideways.earth) to discuss licensing.


# Introduction: ChatMap in a nutshell

Chat Map for Regeneration is a proposed platform to serve the bioregional and regenerative community ecosystem. It aims to create a resource-sharing economy outside of the existing economic system by enabling trusted connections between individuals, organizations, and resources. 

ChatMap for Regeneration is a LLM-powered knowledge management system for regenerative projects within the Bioregional movement, as well as associated pro-social projects addressing the polycrisis. ChatMap is trained specifically on information from within the movement and will be able to answer questions such as “What other organizations are involved in cleaning this specific river?”, “Where is the best place to volunteer if I’m interested in food security for my town?”, “What organizations have authoritative certification that their funding actually results in biodiversity increase?” This ChatMap will be trained on data that has already been collected by the movement, which has accumulated dozens of “databases” and lists of “aligned organizations”, but has yet to create a “map”, because a map is the wrong framing for the questions they are asking.



* Phase 1 of ChatMap will rely on open and freely available knowledge. Phase 1 will have limited ability to customize responses based on people’s preferences.
* Phase 2 of ChatMap is designed to be able to understand people’s preferences and privileges through the use of Verifiable Credentials. Gated and private content can be included in this iteration, with the ability to customize outputs based on people’s associations.
* Phase 3 of ChatMap integrates “networks of networks” and provides ways for different communities and networks to develop their own ChatMap versions or to plug in different formulas for calculating the trustworthiness of data. We recognize our own biases and are planning to build in the ability for different groups to designate their own authorities when it comes to information reliability.


# Version History


<table>
  <tr>
   <td>Version
   </td>
   <td>Description
   </td>
   <td>Date
   </td>
   <td>Authors
   </td>
  </tr>
  <tr>
   <td>1.0
   </td>
   <td>First draft and request for input
   </td>
   <td>August 10, 2025
   </td>
   <td>Grace Rachmany
   </td>
  </tr>
  <tr>
   <td>1.1
   </td>
   <td>Second draft with input from Oli Sylvester-Bradley
   </td>
   <td>October 30, 2055
   </td>
   <td>Grace Rachmany
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>


# 


# Use cases

ChatMap has three categories of participants: Knowledge contributors, knowledge consumers, and knowledge curators. Most organizations will participate in more than one way, but for the purposes of this document, we are simplifying the use cases into those categories. As with all Sideways development projects, we believe that detailed use cases are essential to the development of tools that can actually be utilized by the community. In the Background section, we outline some of the failures of past knowledge management projects, and we believe the lack of specific use cases is one of the key contributors to the failure of these projects. 

**(This describes a future scenario. ChatMap has not been developed yet.) **


## Knowledge curators 

Initially, ChatMap is trained on information contributed by the Knowledge Curators, starting with the Sideways.Earth team members. Curators help ChatMap understand the difference between reliable information and greenwashing. Through curation, ChatMap maintains a bias towards organizations and data that have some level of validation from trusted organizations. 

We envision the development of a [Trust score](#trust-score-20) system that can be used by different communities and plugged into the LLM based on different groups of curators who represent different perspectives on what is reliable.


#### ChatMap team curators

When ChatMap is developed, Sideways.earth will use a range of prioritized content, including known Bioregional coordinated movements, lists of organizations working in the regenerative movement, participants in the Murmurations.network, and a variety of other initial groups. Within the movement, there are people who are able to curate whether content is trusted and interesting. Some people are just the kind of folks who love browsing the web and picking out content. Others are master networkers who actually know the people who they recommend to the curation engine. Some even travel physically to locations where regenerative action is happening to create curation based on facts on the ground. While ChatMap can use all information it finds on the regenerative, sustainability, and bioregional movements, ChatMap team curators maintain an ongoing process of marking more trustworthy content. 

The [Trust Score](#trust-score-20) is described below, and it provides a very basic ranking (trusted, unknown, sketchy) so that it doesn’t fall into the trap of becoming overly authoritative. In Phase 3, different communities of belonging will be able to create their own trust scores. Different networks can defer to different sources of authority.


### Cascadia bioregion

The Cascadia bioregion is an unknowing curator. Cascadia maintains a Wiki of organizations that are “recognized” by the Cascadia bioregioning team. Whether or not those organizations keep their wiki entry updated, ChatMap is able to access all public information on the web about these organizations. ChatMap uses the wiki as a signal that these organizations are trusted to offer reliable information. Unlike the Wiki, ChatMap requires ZERO additional work by the members of the Cascadia bioregional alliance. Just knowing the name of the organizations is enough for ChatMap to acquire all publicly available information on the organizations and include it as part of its training model.


#### Izzie the Info Junkie

Izzie spends a lot of time online, subscribing to all the metacrisis and regen economy newsletters, reading through reams of information. Izzie’s feeds on the social network are completely attuned to what Izzie cares about, which is how to regenerate the earth and solve the world’s problems. Izzie attends Zoom meetings and has developed a fairly astute Bullshit detector, with the ability to understand who is really doing work on the ground and who is just talking. Izzie is pretty full of BS herself, she has to admit, because she just spends all her time online. Finally, with ChatMap, she can do something productive, and mark the best projects and websites as trustworthy, and mark the sketchy ones as sketchy. Izzie and other info junkies can use the ChatMap Curator Tool to give their own sense of websites. 

With dozens of info junkies like Izzie, ChatMap attains a good consensus of who is full of it and who is real. When ChatMap detects anomalous behavior from a ChatMap curator, ChatMap reports it to the core team and the team is able to discern if there is a malicious or malaligned curator in the batch. 

The identification of divergent opinions can be identified with game-theoretical calculations. For example, if one curator consistently rates sources in the opposite way of 80% of the peers, this means that they are not values-aligned with what the core curation group feels is appropriate. They may be malicious or simply adhere to a different set of values. The [Trust Score](#trust-score-20) will allow for divergent training data over time, so that different “tribes” may have their own trust engines. The initial iteration will be aligned with the people that the ChatMap initial development team is biased towards. If there were such a thing as “unbiased”, this would be the best way to develop the system. Unfortunately, no such thing exists. 


## Knowledge contributors


### Open Future Coalition

The OFC Open Impact Platform interface provides both knowledge and curation information. The platform highlights hundreds of ecological projects worldwide, allowing drill-down into more detailed resources. ChatMap can use the open information as data to ingest, and also indicate that the projects listed are trusted, because they have been vetted by a trusted organization. 


### R3.0

r3.0 is a global common good not-for-profit platform that r3.0 crowdsources open recommendations for transformations across diverse fields and sectors, in response to the ecological and social collapses. The platform regularly holds gatherings, publishes news and reports, and posts recordings of the gatherings it holds. Because the curators have included r3.0 in the list of contributors, all publicly available information is included in ChatMap. r3.0 is developing its own knowledge commons and working with a variety of organizations on their own knowledge commons platforms. Any open platform under the r3.0 umbrella can be used by ChatMap and noted as trusted by r3.0.


### Random Regenerators

The Random Regenerators club is an international activist group for rogue riverbank cleanups worldwide. They host events and publish blogs by their participants at random intervals. To be included in ChatMap, they simply go to the ChatMap contributor’s interface and enter their website URLs. ChatMap includes their information as part of its resources, and gives it a “neutral” trust score until other trusted sources vouch for or against the randos.

Rather than listing more sources of potential knowledge (which could become a long list), perhaps it would be more interesting to start to define a policy for what constitutes ‘worthwhile’ sources of knowledge for ChatMap, how this policy would be governed and how decisions on what is eventually fed into chatmap are made. 


## Knowledge consumers


### Get all relevant events for Petra the Planner

Petra is overwhelmed by the different organizations she belongs to, and wants to choose the best events to attend for her particular interests. She can talk to ChatMap about her preferences in terms of online versus in-person events, what types of travel plans and limitations she has, and her areas of interest. ChatMap asks about what events she’s attended in the past, which ones she enjoyed most, and whether she’d like to apply for speaking opportunities in her area of expertise. Based on Petra’s responses, ChatMap also adds to the trust scores of events. ChatMap provides output in her preferred format, a chronological list, a Google-formatted calendar for integration with her calendar, a map of locations for events, or a shortlist of just those events she should prioritize. If Petra has expertise in a particular topic, ChatMap can suggest upcoming events where she should apply as a speaker. 

ChatMap allows Petra to discover events she doesn’t know about, because it has access to all of the calendars of all associated organizations, public lists such as EventBrite, Meetup, and [Lu.ma](Lu.ma). All of this happens WITHOUT any extra effort on the part of the hosts to post in a particular format or register their organization with ChatMap. ChatMap can also anticipate events that aren’t yet announced but that are regular annual or bi-annual events, allowing her to sign up for notifications if there are particular ones that she wants to know about early. Petra no longer has to find out about an event when it’s too late to sign up, and she is much more likely to get early bird pricing! 


### Local regeneration problem-solving: Bogdan the Balsam Basher

Bogdan participates in a cross-European citizen ranger group working to protect, maintain and restore the Boreal forests across the continent. On a June day, walking through a familiar area, he noticed a few plants with red-veined leaves he’d never seen before. Sure enough, it was Himalayan balsam, an invasive species that has been causing damage to waterways and biodiversity in Norway. 

Bogdan quickly called up ChatMap to inform him of the best way to uproot the patch he found, and also gave ChatMap the exact location. ChatMap emphasized the importance of uprooting the plants immediately, before they flower, and gave him specific instructions on how to do so. 

ChatMap added that there had been a few saplings sighted and removed the previous year from a mountain range nearby, and told Bogdan that it would be wise for him to arrange a weekend volunteer seek-and-destroy action before the second week in June, otherwise the flowers would open and bees would begin to pollinate and spread the invasive species. When he got back home, ChatMap gave Bogdan detailed information about successful efforts to prevent the spread of Himalayan Balsam, emphasizing areas that were similar in landscape and culture to his area. 


### Zack and the backpack

Zack is a cinematographer promoting solutions addressing the metacrisis. He travels throughout the world with almost no budget whatsoever, visiting projects, interviewing people, videocasting, and weaving a storytelling infrastructure within the movement. The transcripts from his videos serve as material for ChatMap to learn more about the project, but primarily Zack is the kind of ChatMap consumer that gives ChatMap its name. 

Zack uses ChatMap as a research tool to find out about areas with multiple projects of interest. ChatMap has learned Zack’s preferences and understands which projects fall into the “radical experimentation” category that excites Zack the most. ChatMap also makes suggestions of where Zack can stay during his travels. It has collected information about participating villages and ecologically aligned people who will give Zack a bed or campsite and a meal as he travels around. ChatMap does not integrate any information about transport networks for hitchhiking rides, but Zack has two thumbs.


### Vani the volunteer: finding the right vibe

Vani wants to get involved by volunteering in her bioregion in her spare time, but she doesn’t know where to start! She has an office job during the week and is pretty good at organizing people, but the last thing she wants to do on the weekend is spend more time indoors. Vani would be happy to give a full day twice a month on a Saturday or Sunday and one afternoon a week, especially if she gets to hang out with people with the right vibe. 

ChatMap asks Vani about her interests, whether she’d rather work in nature restoration, preservation, urban farming, etc. It also asks about the social aspects: what makes a good vibe? Because ChatMap is able to resource people’s public social media profiles, it can give Vani an idea of the types of people who volunteer in the local organizations, if they have indicated their affiliations or posted about their participation. It also has an idea of how organizations work with volunteers, on an ongoing basis or per-project. 

ChatMap doesn’t provide final recommendations to Vani, but rather a list of the top 10 organizations for her to contact about volunteer opportunities. If she wants to, Vani can go back to ChatMap after participating and let ChatMap know how accurate it was, or give it other information about the organization. 


### Freddie the funder 

Freddie is a private donor who regularly tithes several thousand dollars to projects he likes, but it’s hard to validate which organizations are doing good work. Every few months, Freddie asks ChatMap for its recommendations. They have a discussion about the global tipping points, what’s going on in Freddie’s bioregion, and where his money will be well spent. Freddie cares about funding organizations run by young people, particularly in establishing their connection with nature and skills for dealing with change. He’s always excited to hear about new initiatives in his area. ChatMap doesn’t do the funds distribution for Freddie. Rather, it directs him to a number of options that best fit his criteria, and he makes his own final decisions. Future versions of ChatMap might have additional features for larger funders, if that ever becomes 


# Background


## Failures of knowledge management

Existing approaches fall into two main categories: Database and Network Map. One novel and superior approach is Murmurations.network, which has agreed to partner with MapChat for the data input. (Many of the databases and network maps are also partners, but we have budgeted for additional outreach and integration, because there are so many potential partners.

Database approaches create lists, wikis, or databases (usually Airtable) of projects and individuals in the movement. For example, the Regenerate Cascadia team has a wiki of more than 200 projects in the region. 

The second approach is the mapping approach. Geographical maps, such as those of the Ecovillage Network and ic.org show associated organizations on a physical map. While these are more useful as a reference for people looking for a place to live or volunteer, they are still quickly outdated as each node needs to update the information in the database. They also require a tremendous amount of work on the part of the user. 

Some of the network and database approaches integrate a “network mapping” capability with a visual network showing the connections among participants. Data such as social networking “following” can show who is connected to whom. However, just because someone has met another person or follows them on social media is meaningless in terms of the quality of that connection. These networks are fun but they don’t provide quality information about the nature of these connections. 

In all of these approaches, the output is nearly useless. Users need to spend a lot of time going through lists or zooming in on 


### Knowledge commons

The regenerative movement is peppered with knowledge commons efforts. The table below shows a comparison of the different efforts.


### **Regenerative Knowledge Initiatives: System Design Comparison**


<table>
  <tr>
   <td><strong>Initiative</strong>
   </td>
   <td><strong>Accessibility</strong>
   </td>
   <td><strong>Usability</strong>
<p style="text-align: center">
<strong>(1–5)</strong>
   </td>
   <td><strong>Traffic</strong>
   </td>
   <td><strong>Maint. Model</strong>
   </td>
   <td><strong>Breadth / Depth</strong>
   </td>
   <td><strong>Format</strong>
   </td>
   <td><strong>Interop</strong>
   </td>
   <td><strong>Incentives</strong>
   </td>
  </tr>
  <tr>
   <td><strong>Bloom Network</strong>
   </td>
   <td>Open
   </td>
   <td>3
   </td>
   <td>Medium
   </td>
   <td>Crowdsourced
   </td>
   <td>Breadth
   </td>
   <td>Director, Events
   </td>
   <td>Low
   </td>
   <td>Community reciprocity
   </td>
  </tr>
  <tr>
   <td><strong>r3.0</strong>
   </td>
   <td>Open
   </td>
   <td>4
   </td>
   <td>Low
   </td>
   <td>Curated
   </td>
   <td>Depth
   </td>
   <td>PDFs, White Papers
   </td>
   <td>Medium
   </td>
   <td>Thought leadership
   </td>
  </tr>
  <tr>
   <td><strong>BioFi</strong>
   </td>
   <td>Open
   </td>
   <td>4
   </td>
   <td>Medium
   </td>
   <td>Curated + Automated
   </td>
   <td>Depth
   </td>
   <td>Web tools, APIs
   </td>
   <td><strong>High</strong>
   </td>
   <td>Funding access
   </td>
  </tr>
  <tr>
   <td><strong>COBALT</strong>
   </td>
   <td>Open
   </td>
   <td>4
   </td>
   <td>Low
   </td>
   <td>Curated
   </td>
   <td>Depth (regional)
   </td>
   <td>GIS maps
   </td>
   <td>Medium
   </td>
   <td>Grant mandates
   </td>
  </tr>
  <tr>
   <td><strong>Bioregional Weaving Labs</strong>
   </td>
   <td>Closed 
   </td>
   <td>2
   </td>
   <td>Low
   </td>
   <td>Crowdsourced (offline)
   </td>
   <td>Depth (hyperlocal)
   </td>
   <td>Oral/Workshops
   </td>
   <td>Low
   </td>
   <td>Trust/relationships
   </td>
  </tr>
  <tr>
   <td><strong>Design School for Regenerating Earth</strong>
   </td>
   <td>Closed (paywall)
   </td>
   <td>3
   </td>
   <td>Medium
   </td>
   <td>Static
   </td>
   <td>Depth
   </td>
   <td>Courses, video, PDFs
   </td>
   <td>Low
   </td>
   <td>Education impact
   </td>
  </tr>
  <tr>
   <td><strong>OFC Open Impact Platform</strong>
   </td>
   <td>Open
   </td>
   <td>5
   </td>
   <td>Medium
   </td>
   <td>Automated
   </td>
   <td>Breadth
   </td>
   <td>Directory, API, Data standards
   </td>
   <td><strong>High</strong>
   </td>
   <td>Industry adoption
   </td>
  </tr>
  <tr>
   <td><strong>Dark Matter Labs</strong>
   </td>
   <td>Open
   </td>
   <td>4
   </td>
   <td>Medium
   </td>
   <td>Curated
   </td>
   <td>Depth
   </td>
   <td>Interactive reports
   </td>
   <td>Medium
   </td>
   <td>Research grants
   </td>
  </tr>
  <tr>
   <td><strong>Open Civics</strong>
   </td>
   <td>Open
   </td>
   <td>3
   </td>
   <td>Low
   </td>
   <td>Crowdsourced
   </td>
   <td>Breadth
   </td>
   <td>Wiki, Toolkits
   </td>
   <td>Medium
   </td>
   <td>Civic participation
   </td>
  </tr>
  <tr>
   <td><strong>Buckminster Fuller Institute</strong>
   </td>
   <td>Open
   </td>
   <td>3
   </td>
   <td>Medium
   </td>
   <td>Static
   </td>
   <td>Hybrid
   </td>
   <td>Challenges, Database
   </td>
   <td>Low
   </td>
   <td>Prestige/network
   </td>
  </tr>
  <tr>
   <td><strong>Common Earth</strong>
   </td>
   <td>Gated (network)
   </td>
   <td>2
   </td>
   <td>Low
   </td>
   <td>Curated
   </td>
   <td>Breadth
   </td>
   <td>Alliance portal
   </td>
   <td>Low
   </td>
   <td>UN partnerships
   </td>
  </tr>
  <tr>
   <td><strong>Global Ecovillage Network</strong>
   </td>
   <td>Open
   </td>
   <td>3
   </td>
   <td>Medium
   </td>
   <td>Crowdsourced
   </td>
   <td>Breadth
   </td>
   <td>Directory, map
   </td>
   <td>Low
   </td>
   <td>Community pride
   </td>
  </tr>
  <tr>
   <td><strong>Restor.eco</strong>
   </td>
   <td>Open
   </td>
   <td><strong>5</strong>
   </td>
   <td><strong>High</strong>
   </td>
   <td>Automated + Crowd
   </td>
   <td>Breadth
   </td>
   <td><strong>Interactive map, directory, API</strong>
   </td>
   <td><strong>High</strong>
   </td>
   <td>Scientific impact
   </td>
  </tr>
  <tr>
   <td><strong>Transition Network</strong>
   </td>
   <td>Mixed (hubs)
   </td>
   <td>2
   </td>
   <td>Medium
   </td>
   <td>Crowdsourced
   </td>
   <td>Hybrid
   </td>
   <td>Wiki
   </td>
   <td>Low
   </td>
   <td>Local resilience
   </td>
  </tr>
  <tr>
   <td><strong>Precious Plastic Universe</strong>
   </td>
   <td>Open
   </td>
   <td>4
   </td>
   <td>Medium
   </td>
   <td>Crowdsourced + Automated
   </td>
   <td>Depth
   </td>
   <td>Map, Forums
   </td>
   <td>Medium
   </td>
   <td>Equipment sharing
   </td>
  </tr>
</table>


**Rating Keys**

**Traffic**



* **Low**: Minimal repeat use; little evidence of value to users (e.g., stale data, no community).
* **Medium**: Regular niche engagement; core users return but broader adoption limited (e.g., 1k–10k monthly visits, 30% retention).
* **High**: Thriving use; users consistently find value and return (e.g., 50k+ visits, 50%+ retention, vibrant community).

**Interoperability**



* *How easily can data be exported or integrated with other tools?*
    * **Low**: Siloed (no APIs/downloads).
    * **Medium**: Partial sharing (e.g., CSV exports, limited APIs).
    * **High**: Built for integration (open APIs, standardized schemas, webhooks).

**Usability (1–5)**



* 1: Confusing/clunky
* 3: Functional but unpolished
* 5: Intuitive, fast, delightful

🔹 **Maintenance Model**



* **Static**: Rarely updated.
* **Crowdsourced**: Relies on volunteers (unreliable).
* **Curated**: Dedicated team updates.
* **Automated**: Data pipelines/APIs


### Outliers

A few knowledge collection and mapping attempts have taken different approaches, though the adoption is low because they tend to be niche projects without much funding to expand their reach.

[Murmurations](https://docs.murmurations.network/about/introduction#how-does-it-work) represents a novel approach, using a distributed data sharing protocol that describes a method for coordinating the storage, indexing and retrieval of data over a distributed network. The ultimate goal of Murmurations is to facilitate collaboration at scale by enabling interoperable data sharing across platforms and between networks, all while providing Associated websites simply use tags in the HTML hidden text format, and the Murmurations can output either a database or a geographical map based on these tags. While this approach eliminates the heavy cost of regular updates, it requires adoption by the creator of the website to insert the appropriate HTML tags, create profiles and submit them to the Murmurations index. Furthermore, the interface is still limited and it’s designed as a kind of backend for developers, not as an end-user utility. WordPress plugins make it user-friendly for WP users, and the API allows the development of other user-friendly interfaces. The team behind Murmurations is actively a part of Sideways.earth and working together on Verifiable Community. We envision collaboration with them on ChatMap as well.

The Catalist project has collated an airtable of people and projects associated with a variety of values-based aligned individuals and projects. The vision of Catalist is similar to ChatMap, designed to target the problems of an individual looking to join organizations that address problems they are interested in, and that fit their skill sets. While Catalist is still in its early days, they have had some success in helping networks of changemakers organize their members and knowledge bases. 

The **ISE (Water Innovation & Solutions Engine)** is an AI chatbot focused on water sustainability, developed by the World Wildlife Fund partnering with Google. The Water Innovation & Solutions Engine (ISE)—a partnership between WWF, Google.org, and Cervest—uses an AI chat interface to connect water-focused stakeholders (governments, solution providers, and funders) with verified ecological projects, datasets, and funding opportunities. Users like Mexico City’s water department and startups such as EcoSwell leverage ISE to rapidly identify high-impact solutions (e.g., cutting flood risk by 25% or securing $500k in funding), with adoption driven primarily through WWF’s grassroots networks, Google’s tech outreach, and funder-mandated usage. Its success demonstrates the viability of conversational AI for ecological matchmaking, particularly through dynamic data integration and third-party impact verification (e.g., Cervest’s climate resilience scoring). Despite its strengths, ISE remains siloed within water sustainability, lacks cross-sector interoperability (e.g., bridging water, food, and biodiversity), and struggles to engage grassroots actors due to tech/literacy barriers.	


## Opportunity: UI is sooo last decade

User interfaces have been transforming through a plethora of chatbots that accompany web and mobile apps. Slowly, interfaces are being replaced by text inputs that simply instruct users to ask their question. At first, it’s disarming. Where is the drop-down with my destination and date of travel? Ultimately, it just makes sense. Why force users to choose from 4 dropdowns when they could just type in a natural language sentence (in French or English)? 


![SNCF](images/Images/1CM-sncf.png)


Most people don’t know how to write a database query, and most searches provide only a small sampling of the information that people want. LLMs provide a completely different approach to development of user interfaces that makes them intuitive. Not only can people type into these interfaces, voice-to-text and text-to-voice allow LLMs to be as simple as a normal conversation. 

Furthermore, LLMs eliminate the need to gather all the information together in one big database. As a result, an LLM-based solution eliminates maintenance problems and the need for organizations to store all of their data. 


## ChatMap differentiation

ChatMap leverages LLMs to bring together all of the efforts noted above. Any public information can be brought into one, easy-to-use chat application. ChatMap addresses the weaknesses of other knowledge commons solutions by by aggregating *multi-sectoral* regenerative initiatives (not just water) and prioritizing low-tech access and local partnerships (e.g., bioregional hubs). Crucially, ChatMap moves beyond discovery to activate *collaboration*—enabling complex queries like “Find food security projects amplified by river restoration” and automating systemic synergies (e.g., identifying 4x-impact project combinations). This positions ChatMap not as another directory, but as a nervous system for the regenerative movement—turning fragmentation into collective action

ChatMap’s competitive advantages include:



1. Ingesting the results of many different knowledge mapping exercises to create creating a meta-map.
2. Eliminating the need for manual work and database updates: All public information (websites, documents,  knowledge bases, individual public social media profiles, repositories) is included automatically and updated as the organizations make updates.
3. Designing for usability: The front end (ChatMap) is an easy-to-use chat interface, designed for the end user rather than a technical integrator.
4. Providing the integration of multiple aligned networks and making it easy to “join” the movement. Rather than a fragmented environmental movement, ChatMap represents the ability to create significant coherence among the people working for shared goals.
5. A future trajectory that can integrate objective measurement information such as land and water quality, population information, and other types of quantitative information that would better inform and develop capabilities needed for environmental restoration and integrative cultural and social solutions.
6. Abilities to output any of the formats provided by the prior solutions (geographical overlay, network mapping) based on data.
7. Future integration with verifiable credentials for validation and certification of projects by third parties.


## AI, Molloch and Golem

Many in the regenerative and ecological movements have an understandable aversion to technology. One leader said to us “AI is destroying the world.” Although they are involved in helping create a knowledge base, as far as they are concerned, AI is beyond the pale. We write this specification with the full knowledge of the truth in that statement.

AI already has caused and continues to cause untold damage to society at large. From the social media that causes misery and self-harm to the LLMs that encourage people to commit suicide, to online gambling that causes people to go bankrupt, it is almost impossible to see any positive impact of AI. If you look, even at those who are leveraging AI in their careers, you’ll see no significant improvement in their lives. Sure, we used some AI to create this document. It saved us some time. But have our lives changed in any significant way? No. We are still sitting in front of a computer doing work. We aren’t getting paid more than before (We’re making less, come to think of it.). Even worse, data centers are causing both ecocide and human health problems. The more we think about it, the more we realize that society has, in fact, produced the paper clip maximizer. 

Yes, we are in the age of Molloch, Frankenstein, and Golem. Technology has created monsters that can no longer be controlled. 

And yet, we write this ChatMap specification. 

It seems to us that we cannot organize a planetary regenerative shift without technology. For the first time in human history, we have powerful coordination mechanisms that can allow planetary action. Ignoring the fact that AI now exists simply puts us at a disadvantage vis-a-vis the forces we are trying to combat. 

Is this the right thing to do? We don’t know. We are not blind to the costs of this approach. 


# Chatmap specifications

Chat Map will be an LLM-powered conversational interface that:



* Ingests multiple data sources: Databases, Airtables, maps, websites from regenerative/bioregional organizations
* Enables context-aware discovery: Users can have natural conversations about their needs/interests rather than using rigid search parameters
* Incorporates reputation and trust: Connected with a group-based identity system for verification
* Preserves data sovereignty: Ideally architected so data stays with original sources rather than creating a centralized database

**Note from Oli:** Data sovereignty is a huge topic and needs expanding. So far in this Doc there has been no mention of where this LLM lives, how it is provisioned and trained so that it 'only' has access to specific info... we need loads more info of the design, hosting, training and restrictions of the LLM to paint a detailed picture of how this will work, and how it can / will 'preserve data sovereignty' etc.

**Response:** Anyone adopting the design of ChatMap needs to consider this topic. If Sideways.earth is funded for this, we will undertake a research process for the design that will align with fair data practices. The initial release will rely on publicly available data, and further iterations will dive deeper in how to properly gate data that needs different levels of protection.


## Key Features



* Curation of trusted information, and integration of curators as part of the systems design
* Conversational Interface
* Natural language interactions to find organizations, resources, or people
* Contextual understanding of queries
* Ability to clarify needs and refine searches through dialogue
* Accessible to non-technical users
* Translation and multiple language capabilities
* Future: Integration with access control through Verifiable Credentials, to be able to integrate gated content 


## Training data

The seed training data collection will be done based on existing knowledge in the bioregional and ecological sectors:



* The table in [Regenerative Knowledge Initiatives ](#regenerative-knowledge-initiatives-system-design-comparison-10)serves as a starting list for seeding ChatMap.
* Partners and bioregions who want to participate can add their wikis, reports and other information.
* Murmurations.network participants who are involved in any type of social or ecological work will also be considered for the seed data phase. 

For Phase 1, only publicly available information will be used in ChatMap. A data engineer will be responsible for schema mapping, entity resolution, and data validation.

Knowledge expansion will take place through AI-assisted knowledge expansion and a software engineer working with different tools to follow through on websites and public data that are associated with the initial seed information. 


## User journeys


### Knowledge contributor journeys


#### Bioregioning knowledge commons authorizes use of their content database.

This user journey is specific to organizations that maintain some kind of database or vetted list. They can indicate two levels of trust, “included” and “vetted”. An inclusive list might be a list of all organizations that claim to be doing work in the bioregion. A vetted list is a trusted group that either has long-term relationships or has gone through some type of due diligence process. Initially ChatMap can only use public information, so the database needs to be public, or be a list that includes the public-facing websites of the organizations included.



1. ChatMap core team issues an invitation to contribute to the ChatMap commons.
2. User clicks the invitation to reach the Knowledge Input interface. 

    
![Addinfo](images/Images/Images/CM2-Addinfo.jpg)


3. The user indicates the type of database or list they are uploading (wiki, online database, csv, etc.) and the link of the public information.
4. The user indicates the trust level. It may be that there is a column in the database or rating system in the database that needs to be described to ChatMap.
5. ChatMap ingests the information, and includes the level of trust in the organizations as part of its algorithm for queries.

**Author’s note:** I think we should have public and private areas. For organizations we authorize, perhaps we can use some kind of OTP, so we aren't doing the provisioning on our side, but there is vetting or tracking of contributions? We need to think more deeply about this.


#### Unknown individual indicates a resource

Any individual can contribute a link or a list of bookmarks to the system. These are considered untrusted or neutral unless confirmed by the curation group or indicated as trusted by one of the authorized knowledge contributors. 



1. An individual goes to the contribution page. 
    
![base input](images/Images/CM3-BaseInput.jpg)

2. The individual gives identifying information (to prevent bots and trolls).
3. The individual adds a URL or uploads a list of URLs or bookmarks related to the ChatMap database.
4. ChatMap thanks them and sends them an email to indicate receipt of the information.


### Knowledge consumer journeys


#### Petra the planner gets a consolidated calender


#### Backpack Zack plans a journey

For this use case, the individual will receive the output in a map format.



1. Zack discusses in the chat interface his requirements for travel. He chats about where he is going, what types of organizations he wants to interview for his documentary, how long he wants to stay in each place, etc.
2. (Future feature) Zack shows ChatMap his collection of Verifiable Credentials ([see Verifiable Community](https://github.com/SidewaysEarth/VerifiableCommunity)) that indicate his “good standing” status where he has stayed in the past. Locations might require knowledge of whether Zack is a non-smoker, is certified as a member of a sustainability organization, etc.
3. ChatMap makes different suggestions of routes, and eventually Zack and ChatMap reach agreement about the route.
4. ChatMap provides an itinerary suggestion, with a readable map for OSM, as well as an itinerary that allows Zack to reach out to get permission to stay in each place.
5. As Zack gets confirmations or rejections, he can go back to ChatMap to discuss alternatives.


#### Vani the volunteer finds her vibe group



<p id="gdcalert5" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image4.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert6">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![Workd](images/CM1-Vani.png)

![Chatscreen](images/CM2-Vani.png)



![Discuss](images/CM3-Vani.png)



![4thchat](images/CM4-Vani.png)



![5chat](images/CM5-Vani.png)




![6chat](images/CM6-Vani.png)



![CN2-Vani](images/CM7-Vani.png)


![stuff](images/CM8-Vani.png)



#### Future: Freddie the funder finds a founder 


### Knowledge curator journeys

New curators can join, and based on their alignment with existing curators (as determined algorithmically), over time they will reach levels of trustworthiness. If a curator joins and they are consistently ranking websites differently than other curators, they will be removed from the curation team. 


#### Izzie the info junkie indicates trustworthy and bogus content

Izzie loves to review the work of others as well as tag content he finds trustworthy. He has worked in some of the big institutions claiming to do green transition work and has an eye for greenwashing. He uses the ChatMap curation interface to add new content as he views it, through a plug-in to his browser. When new curators enter the system, Izzie gets to rate some of the sites they have added. His long-term membership in the system allows the system to calibrate which new curators are reliable. 


#### Cammie the coordinator uploads a list of trusted sources

Cammie is the coordinator and convener of her bioregion. She has collected a list of several hundred groups in her region who are working on regeneration. Of those projects, she has 40 trusted projects that her team vouches for as “truly regenerative” according to their internal criteria. Cammie uploads both lists, and ChatMap recognizes the two different categories of trusted and unknown. Every six months, Cammie updates her lists with new organizations that have joined. In rare occasions she will mark an organization as not being sketchy or not-regenerative according to her bioregional coordination team’s assessment. 


#### Norm the participant notes that some of the sources are sketchy

Norm has been using ChatMap to find organizations who are interested in working with him and his team on a local river cleanup project. As a result, he has been actually speaking to and meeting with many of the organizations within his region, as well as those further up and down the river. Through his visits, he has found some sites of organizations that are actually “greenwashing” entities for local industry, as well as some organizations which are inactive and should be removed from the database. He uses the curation interface to indicate these different entities and websites as trustworthy, neutral, or sketchy.


#### Chuck the new contributor joins 

Chuck loves browsing the web and has built up his own assessment of trustworthy and sketchy sites. He joins the curation team by uploading his lists of which sites he finds reliable. ChatMap is able to compare those websites to the assessments of other curators in the system. If there is a general alignment (Chuck agrees with 80% of the rankings of other curators.), Chuck is approved as a new curator. For the first 6 months of his participation, when Chuck marks new information as reliable or sketchy, his assessments are reviewed by other curators such as Izzie. Over time, Chuck becomes a full member of the curation team if his perspectives align with the general perspectives of the curation team. 


#### Vani tells about her experience after volunteering.


![stuff](images/CN1- Vani.png)




Vani’s experience is leveraged for curation, and given a high reliability grade. Because Vani actually took action, her experience is considered a first-person account rather than just a general curation for weighting in the Trust score. 


## Trust score

The initial trust score for ChatMap will provide an intentional bias towards sources working on the ground and a bias against corporate and institutional media. The Trust Score will be based on the initial seed data providers and the initial set of curators. To avoid pitfalls of “Page Rank” and other types of precise ranking, the Trust Score will indicate only three potential scores:



* Trusted
* Unknown
* Sketchy

The Trust score is designed to provide basic results that are validated by participants in the network. Participants will be able to give feedback to ChatMap during their discussions. Curators and coordinators of lists will be able to indicate their selection of trusted organizations. 

The Trust Score of ChatMap will develop based on several types of input. First of all, the initial sites that are uploaded by trusted knowledge providers are considered the basis of trustworthy sites. As curators give their ratings, every knowledge source continues to vary in its reliability. ChatMap answers and outputs will adhere to the prioritization of trusted sources. When giving information that is based on sketchy sources or those with reliability that is unknown, ChatMap can inform the user that they are given 


### Bias

The initial developers of the LLM will have a tremendous amount of control over the initial trust score. The intention is to create an API or other type of training capability so that any group of people could create their own trust scores based on the sites they want to start out with as generally trustworthy. 


### Alternative trust scores

ChatMap should be able to take all information sources in the training set and either discard them, or mark them all as neutral. This would allow a group to start from their own training set and their own set of curators. This way, the same set of online sources (or a new set of online sources) can be given a name and Trust Score, based on the communities who believe in a particular set of trusted sources and trusted curators. 

The Alternative Trust Score capability points at the possibility that ChatMap could be used for a completely different type of network. For example, a group looking to address food security might create their own training data, curation team, and develop an alternative Trust score. Ultimately, we would like ChatMap to be able to provide different interfaces for different groups, based on their own perspective on the “truth”. 


### Adjustable trust

In future versions it would be possible to create a user-adjustable trust score. ChatMap users could indicate their favorite trusted sources, use sliders to indicate the types of authorities they feel comfortable trusting, etc. We also envision the integration of credentialing such as the [Verifiable Community](github.com/SidewaysEarth/VerifiableCommunity/) credentials for gated content and customization of output.

The idea behind gated content would be that people could log into ChatMap with an identity wallet, expose the credentials relevant to their search, and get customized output. For example, someone who is a member of an Ecovillage might be able to see some locations that are hidden to those who are not verifiable members. 


## Estimated budget requirements

The following budget estimate is 100% AI-generated, unlike the rest of the text in this document. It does not discuss deployment and adoption costs.  


### **1. Define Project Scope**



1. **Problem Type**: Is it classification, regression, generative AI, reinforcement learning, etc.?
2. **Model Complexity**:
3. Simple (e.g., logistic regression, decision trees)
4. Medium (e.g., CNN for image classification, basic NLP models)
5. Advanced (e.g., large language models like GPT-4, custom deep learning architectures)
6. **Data Needs**:
7. Existing datasets (cheaper) vs. collecting new data (expensive)
8. Data cleaning & labeling costs


### **2. Cost Breakdown**


#### **A. Labor Costs (Biggest Expense)**



1. **AI Engineers/Data Scientists**:
2. Junior: $50–$100/hr
3. Senior: $100–$250/hr
4. **Machine Learning Engineers (for deployment)**: $80–$200/hr
5. **Project Duration**:
6. Prototype (1–3 months)
7. Full-scale development (3–12+ months)


#### **B. Data Costs**



1. **Public Datasets**: Free–$10,000 (e.g., Kaggle, Hugging Face, government data)
2. **Proprietary Data**: $5,000–$100,000+ (if purchasing or collecting)
3. **Data Labeling**:
4. Manual labeling: $0.10–$5 per sample (e.g., $5,000 for 50k labeled images)
5. Automated tools (cheaper but may need refinement)


#### **C. Infrastructure & Cloud Costs**



1. **Training**:
2. Small models (CPU/entry GPU): $0–$500/month
3. Medium models (single high-end GPU): $500–$3,000/month
4. Large models (multi-GPU/TPU clusters): $5,000–$50,000+
5. **Deployment**:
6. Cloud APIs (e.g., AWS SageMaker, Google Vertex AI): $500–$10,000/month
7. Self-hosted (requires DevOps expertise)


#### **D. Software & Tools**



1. Open-source (free) vs. Enterprise licenses (e.g., TensorFlow Enterprise, MATLAB)
2. MLOps tools (Weights & Biases, MLflow): $0–$1,000/month


#### **E. Miscellaneous**



1. **Consulting/Review**: $5,000–$50,000 (if hiring external experts)
2. **Regulatory/Compliance**: Varies (e.g., GDPR, HIPAA considerations)


### **3. Budget Ranges (Rough Estimates)**


```
Project Scale Budget Range Timeline
```



<table>
  <tr>
   <td><strong>Proof of Concept</strong>
   </td>
   <td>$10,000–$50,000
   </td>
   <td>1–3 months
   </td>
  </tr>
  <tr>
   <td><strong>MVP (Mid-Complexity)</strong>
   </td>
   <td>$50,000–$200,000
   </td>
   <td>3–6 months
   </td>
  </tr>
  <tr>
   <td><strong>Enterprise-Grade</strong>
   </td>
   <td>$200,000–$1M+
   </td>
   <td>6–18 months
   </td>
  </tr>
</table>



### **4. Cost-Saving Tips**



1. Use pre-trained models (e.g., fine-tuning LLMs instead of training from scratch).
2. Start with open-source tools before investing in enterprise solutions.
3. Leverage cloud credits (AWS, Google Cloud, Azure often offer startup discounts).
4. Outsource labeling to cost-effective providers (e.g., Scale AI, Labelbox).
