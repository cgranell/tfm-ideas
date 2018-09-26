# tfm-ideas
Ideas for master theses / projects    

## Research lines
* Spatial analysis of playability areas and socio-economic aspects
* gamified apps/LBS in urban contexts to enhace mobility
* GIS/spatial operators in education
 
## Get inspired by
* [Community experiments](https://experiments.withgoogle.com/)
* [Objectifier Spatial Programming (OSP)](https://experiments.withgoogle.com/ai/objectifier-spatial-programming)
* [Visualizing High-Dimensional Space](https://experiments.withgoogle.com/ai/visualizing-high-dimensional-space)
 
## Master projects done 

### Visualization and visual analytics of geospatial data for psychological treatment
*Summary*: a visualization tool based on Luis' metric analytical framework, which is aimed to better interpret the results of interventions in the treatment of certain psychological disorders such as Agoraphobia or Depression. In collaboration with LABPSITEC. It was developed by Iskandaryan Ditsuhi (EM student) in the period Sep 2017 - Mar 2018, with the title [Visualization and visual analytics of geospatial data for psychological treatment](http://repositori.uji.es/xmlui/handle/10234/173976). 

### Mental health app builder: a case study to battle addictions
*EM Student*: Fanawani (Fana) Gebremeskel

*Hypothesis*: Location patterns from patients's phone sensors are correlated with depressive symptoms. In other words, the extent to which changes in
depressive symptoms can be predicted with movement data remains yet unclear. 

*Summary*: In the field of health, the location and movements of a patient is a key resource for the treatment of mental disorders (e.g., depression, agoraphobia, gambling addictions, etc.). Surprisingly, even to date, psychologists mostly rely on pen and paper, asking the patient to meticulously write down their location, movement and habits. Despite the best intentions of the patient, such data is objective and incomplete. Furthermore, there is a delay between the data collection (usually daily), and data delivery and processing (usually during a weekly or bi-weekly session with the psychologist), and the treatment can thus only be adjusted/tailored to the data with the same delay.

Using modern technologies, the cycle of data collection - data delivery - data processing/interpretation can be significantly improved. First, the use of mobile technologies (i.e., GPS, ubiquitous internet connectivity) allows to accurately track and store user’s location and trajectories, and also to interact, in real-time, with the user (i.e., notifications). Second, GIS technologies allow to analyse and interpret the obtained mobility data, and take appropriate actions (e.g., geo-fencing, trajectory analysis, etc.). Third, visualisation and visual analytics allows to visualise and interpret the data in such a way that it specifically support treatments of a mental disorder.

The objective of this thesis is to develop a case study to test the mental health app builder to treat addictions. This includes gathering and understanding the requirements of such an app, generating the app using the mental health app builder, adding new features - if needed - to the mental health app builder, testing the generated app with therapists (access to psychologists/therapists is available). 

We hereby note that, for the requirements gathering, testing and experiments, access to psychologists/therapists is available through GEOTEC collaboration with LABPSYTECH, a group of psychologists/therapists at UJI. This thesis is performed in close cooperation with the creator of the mental health app builder, who will assist with any extensions needed.

*Methods*: Location analysis, JavaScript programming, data visualisation, (possibly Android programming)

*Related work*: At GEOTEC, we developed a mental health app builder, a application generation framework accessible via a web interface, that allows health professionals to generate a mobile application for the treatment of a particular mental disorder. The framework therefore offers some basic geospatial building blocks (location tracking, trajectory recording, geo-fencing), communication building blocks (notifications) and a basic visualisation of collected data by therapists (map-based view). The framework has been successfully tested to build an app to treat depression.

*Notes*: For the tasks of requirements gathering, testing and experiments, access to psychologists/therapists is available through GEOTEC collaboration with LABPSYTECH, a group of psychologists/therapists at UJI. This thesis is performed in close cooperation with the creator of the mental health app builder, who will assist with any extensions needed.

### Conceptualisation of mobility neighbourhoods through the lens of cyclists

*EM Student*: Fabián Rodolfo Perotti

*Hypothesis*: Mobility is a multi-dimensional, multi-faceted concept that may lead to multiple interpretations. 

*Summary*: Much research has put the focus on monitoring mobility behaviour in the sense of detecting differences in the mobility behaviour of distinct profiles of people (or types of transport modes). For example, locals and tourists move differently in a city, as each profile visits more frequently certain places and takes certain routes than the other. Or confronting taxis’ and private cars’ mobility. Assessing **where, when and how** a person travels and moves has been and is the aim of mobility behaviour. 

However, there are different dimensions that make the detection and assessment of mobility behaviour difficult. Scale, for example. Sometimes, we want to study mobility behaviour at an individual level. Other times, we are interested in the aggregation, i.e. group level, to detect overall mobility patterns for urban planning purposes and sustainable mobility/transport policies. No focus, though, has been put in detecting whether a particular individual (or moving object) behaves differently from day to day in terms of mobility (due to new mobility habits, new travel routes, new transport modes, update street network, etc.). Mobility is a multi-dimensional phenomenon. When (temporal dimension), where (spatial dimension) and how (transport mode) are well-understood dimensions of mobility behaviour on past mobility studies. Yet, these dimensions have been studied/seen static because no attention has been put on the dynamics of mobility behaviour itself: why does behaviour change, what (and what not) triggers such changes, how long does that change endure, what impact this change produces, does this impact produce a local network effect to surrounding/nearby people or moving objects, does otherwise it produce a network effect at scale?, etc.

The aim of the thesis is to take a fresh perspective to explore and conceptualise the dynamics of mobility behaviour change from the perspective of cyclists. Mobility behaviour is the result of a set of endogenous (internal) factors (speed, transport mode, etc.) and exogenous (external) factors (weather conditions, built environment, traffic conditions, road type, road conditions, etc.). Based on a replica of human senses (sight, hearing, taste, smell, and touch), the idea is to mimic **how cyclists sense mobility and the environment**: sensing organs associated with each sense send information to our brains to help us understand and perceive the world around us. A way to characterise mobility and interaction with other moving objects may be based on the five human senses. 

The focus of this work is to explain the effect that geographic distance (or speed, or visibility) has on cyclists with respect to mobility interactions and, simultaneously, to understand the interplay between the endogenous and exogenous factors and their spatial context. As a result, a proof-of-concept tool to visually test (e.g. isochrone map/lines) the concept of mobility neighbourhoods from cyclists' perspective will be produced. 

*Related work*: Literature on mobility, movement analysis, [thick mobility](thick) as mobility data (trajectories) can only mobilise people and change things when it becomes thick with social and contextual meaning. To link to Diego's open dataset of bicycle trips in cities.

*Methods*: Theoretical approach, literature review, proof-of-concept 


## Master project proposals 

### How diverse are my routes? Innovative visualisations of human trajectories (small multiples)

*Hypothesis*: the diversity of trajectories can be a predictor of depressive symptoms (or other phenomena). 

*Summary*: he goal is to design and generate one or more innovative piece(s) of visualisation in order to explore humans' routes. In general, mobility patterns and behaviour may be useful for a variety of applications, such as urban planning, personal health, contamination or, as the proposed case study in this thesis, mental health. The idea of this thesis is to characterise mobility patterns based on an index of diversity in order to respond to the question: how diverse are patient's routes over the last week, or two weeks? To this aim, the student will explore and develop (novel) visualisation technique(s).

A proposed example type of visualisation is small multiples. The student can work on an improved version of small multiples (coloured, annotations, interactive) as a way to visually compare routes over the past weeks, and so to determine the variability of the routes taken by patients. Small multiples might take the form of a matrix, where each row refers to a patient, and each column refers to a day. As a result, each cell would contain a representation of the trajectory/route, with the aim to make explicit how diverse trajectories are compared to time and patients. How might small multiples be classified (and coloured) based on the index of diversity? Other questions in collaboration with the users of these novel visualisation designs will surely emerge during the project. 

Small multiples is the proposed example visualisation, but the student may also propose his/her own novel visualisation technique to develop.

Resulting code will be integrated into an existing R library/package for innovative analysis and visualisation of trajectory data. Input data will be based on real experiments, collected through the GEOTEC's mental health app builder, In summary, the ultimate goal is to make it easy for everyone (patients, therapists, ...) to understand mobility patterns and behaviour visually. 

*Related work*: [Visualise your Strava routes with R](https://www.r-bloggers.com/visualize-your-strava-routes-with-r/amp/); [GEOTEC's mental health app builder](https://geo-games-builder.firebaseapp.com/login).

*Methods*: programming, data visualisation, visual analytics, trajectories, diversity index. 


### The geography of scholarly publications at UJI

*Hypothesis*: Researcher's spatial position determines collaboration patterns. Do you work with your next door colleague? 

*Summary*: Scholarly publication is a key indicator or variable for university decision makers as it determines to certain extent the degree of research, innovation and knowledge achieved by an individual, group, and even the entire institution. Rather than looking at scholarly publications as a metric to measure productive researchers or research groups, we attempt to explain scholarly publication taken a spatial perspective. Relevant questions that are of interest in this thesis are: What is the role and relevance of an individual’s spatial position on a campus? And that of a research group?.  

The idea of the project is to examine the collaboration patterns of the research groups and faculties at UJI, through their academic output (papers available at the institutional repository) over the last 5 or 10 years, and in relation to the organisational structures in terms of institutional affiliation (faculty, department/institute, research group) and spatial configuration (building) inside the campus . This type of work has been traditionally explored through network theory. The novelty is to complement network theory with spatial distribution and mapping of intra-building and intra-department collaboration. Resulting application will take the form of a web-based Shiny application and R package.

This project is part of an is expected to contribute to a larger project called **Atlas of UJI: 10 data visualisations to explain the impact of UJI**

*Related work*: [An exploration of collaborative scientific production at MIT through spatial organization and institutional affiliation](http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0179334)

*Methods*: Network analysis, intra-building and intra-department collaboration, mapping and clustering building-level data, Local indicators of spatial association (LISA), geo big data    

### EM GEOTEC and the World: 10-year traces of international students
*Hypothesis*: Impact of EM GEOTEC is uniformly distributed over geographical areas/countries. 

*Summary*: The idea is to design and generate a piece of visualisation in order to explore the spatial relationships, impacts, and coverage of past internacional students of the EM GEOTEC. Not only will we focus on the home countries of the students, but most importantly, on where they are now, to spatially and temporally explore their professional/academic career paths after graduation. The generated tool may definitively become an institutional  tool to regularly assess and verify the impact of the EM GEOTEC as future students  graduate.

This project is part of an is expected to contribute to a larger project called **Atlas of UJI: 10 data visualisations to explain the impact of UJI**

*Related work*: [MIT-World](http://senseable.mit.edu/mit-world)

*Methods*: Network analysis, JavaScript programming, data visualisation, interactive and reactive programming, temporal dimension

## Others

Title: **New interfaces for spatial operators for kids**

Summary: Kids and young people are increasingly being accustomed to map-based interfaces. Even though they can do basic map interactions such as pan, zoom in, zoom out, and locate landmarks, to understand the use and need of spatial operator is still challenging. The topic aims to design and implement a new way to make the semantics and usage of spatial operators understandable and easy to use for kind and young people. 
Status: pending

Title: **Location-based services via street name signs**

Summary: Visitors in cities do not have sometimes GPS connections nor paper maps. An alternative idea can be to use street name signs as proxy for location-based services. Lost users an take a picture of the closer street name sign and the system is able perform spatial services according to the user's location. The underlying idea is to connect both worlds, real and virtual, to solve a problem. This is referred in the literature as "Blended Spaces"
Status: pending
Related work: Paulo Dias Almeida et al, 2016. [Where the streets Have known Names](https://link.springer.com/chapter/10.1007/978-3-319-42089-9_1), with the idea to VR/AR with schoolchildren for education purpose labelled as "Know uyour city through explorign street names"

Title: **Geoproximity for unemployment (young) people** 

Summary: Imagine a jobless person strolling the city. As he is approaching to a place (employer) offering a job, he is prompted with the job offer. The employers can create a job add by simply sending a message (twitter, whatup). The idea is to add some value to the traditional “waiter wanted” sign hold on the door.
Status: pending

Title: **Activity maps**

Summary: Creation of on-demand, personalised maps in function of the actual activity (and/or emotion) one is doing (and/or feeling). That is, producing customised maps on the fly for runners, walkers, drivers, bikers, etc..
Status: pending

Title: Something with new IoT sensors "particles" (The ones Alberto is using)
....
Status: pending

Title: **Tangible programming with IoT sensors "particles"**

Summary: Inspired by [projectbloks](https://projectbloks.withgoogle.com/), the idea is to use physical blocks or bricks augmented with small IoT sensors to program. The physical combination of blocks will be translated into actual code (i.e. sketch ). Could spatial operators be represented and combined using tangible blocks?
Status: pending

Title: **Users able to process** 

Summary: Over the last few years, the world has gradually transformed from an expensive, slow, focused, planned and conducted collection of data by an ad hoc, massive, unplanned data collection carried out by anyone, at any time and wherever. This transition is exemplified by the decadence of Geographic Information Systems (GIS) until relatively recently in favour of the dominating concept of Volunteered Geographic Information (VGI). Nevertheless, the processing or analysis had always been beyond the reach of citizens. What we pursue is to democratize the ability of processing spatial data among the large public, educate on spatial operators and on the critical skill of undertanding how data is transformed. Just as VGI has done with the production of data, we want citizens be able to choose how and when they process their data.
Status: pending


Title: **Georreferencing scholarly publications at UJI** 

Summary: To investigate distinct ways to georreference a research paper (title, keyworks, content, auuthors' affiliation) and create a visualisation tool to support visual analytics 

This project is part of a larger project called **Atlas of UJI: 10 key  visualisations to explain the impact of UJI**

Related work: [GEOUP4](http://revistes.upc.edu/geoup4)
Status: pending
Methods: NLP, programming, web mapping, research data, visual clustering


Title: **Research reusability and the Geosciences**

Summary: This is related to the ongoing effort to define RR for the Geosciences. In particular, I would be interested in working on the the interpretastion of VGI and reproducibilty in the concext of advancing science when user-generated data is beaing used for reserach. There are important qu that remain open in the interplay of the sporadic nature of VGI adn researh reproducibility. 
Status: pending

Title: **One-time maps for crowdsourced knowledge base**

Summary: Based on the collaboration with Barbara Hoffer (See gdrive document)
Status: pending

Title: **The geography of employability data**

Summary: University Observatory
This project is part of a larger project called **Atlas of UJI: 10 key  visualisations to explain the impact of UJI**
 
Status: pending


Title: **Bike sharing scheme and tram/bus transport in Castellon**

Summary: To understand the relationship, and the impact of events that happens between bike sharing and other transportation modes. The newly emergent and increasingly popular dockless bike sharing scheme provides new opportunities as well as challenges to non-motorised mobility studies. Because bikes
are significantly more evenly distributed in urban spaces rather than only being available or having to be returned to docking stations. The spatiotemporal usage patterns and travel flows of dockless bikes are more complex to analyse compared with the more fixed docking station schemes. Existing studies of dockless bike sharing are very limited and have focused on the management of bike fleets (Palet al., 2017) or the planning of cycling infrastructures (Bao et al., 2017). This project is part of a larger project called **Atlas of UJI: 10 key  visualisations to explain the impact of UJI**

Pal, A., & Zhang, Y. (2017). Free-floating bike sharing: solving
real-life largescale static rebalancing problems. Transportation
Research Part C Emerging Technologies, 80, 92-116.

Bao, J., He, T., Ruan, S., Li, Y., & Zheng, Y. (2017). Planning
Bike Lanes based on Sharing-Bikes' Trajectories. ACM
SIGKDD International Conference on Knowledge Discovery
and Data Mining (pp.1377-1386).

Title: **From place of residence to place of activity: spatiotemporal mapping of population density**

Summary: Population is a crucial variable for the social sciences, the geosciences, and for policy support in many domains. Yet, our knowledge of its spatial distribution is still nowadays very incomplete. Population is a temporally dynamic variable, with major shifts in its distribution occurring in daily and seasonal cycles, resulting in rapidly changing densities. While spatially detailed representations of residential population  maps can be used as proxies for night-time population distribution, the distribution of population for other time frames is practically unknown at almost every spatial scale.

The location of population during the day is determined by the location of economic, social and leisure facilities which pull population off their residences, driving commuting flows and other forms of daily trips. Daytime population distribution thus varies greatly from night-time distribution, and it is much more challenging to infer.

Related: ENACT project (“ENhancing ACTivity and population mapping”), https://ec.europa.eu/jrc/en/publication/enhancing-activity-and-population-mapping-exploratory-research-project-interim-report

Title: **Impact of the Tobler’s first law of geography (Tobler, 1970)**.
Summary: Explore the literature works (1970-today) that reference or explicitly mention Tobler Law, and analyse their motives to do so, creating a network of influences of the Tobler law. In what application domanis is Tobler's first law of geography mention? What is the variability of the impact of this law? [Waldo R. Tobler](https://www.tandfonline.com/doi/full/10.1080/15230406.2018.1447399)

Title: **Europeana - Platial analysis, processing and visualisation**

Summary: [Europeana Collections](https://www.europeana.eu/) provides access to over 50 million digitised items such as  books, music, artworks and more. It has a set fo [APIs](https://pro.europeana.eu/resources/apis) to build applications. Based on a few, key use cases, the idea of the project is to explore the use and exploitation of Europeana Collection resources from the spatio-temporal perspective, to approach these resources to European citzens thorough easy-to-use applications. Much more elaborated work might be platial analysys, as opossed to well-known spatial analysis, to initiate a new research line on Place-based research (Andres' thesis?) related to digital humanities/social science resources. Enrich place information of entity data   

Related: [MDPI IJGI Special Issue "Place-Based Research in GIScience and Geoinformatics"](http://www.mdpi.com/journal/ijgi/special_issues/place-based); [MDPI IJGI Special Issue "Data Acquisition and Processing in Cultural Heritage"](http://www.mdpi.com/journal/ijgi/special_issues/Cultural_Heritage_IJGI)


Title: **Dynamics of mobility - Castellon**

Summary: Based on bicicas matrix data, create a simulation that show the among of trips between dodge stations 


Title: **New use case of Blockchain in GIScience**

Summary: Look at blckchain.md file in RR folder.


NOTE: A system to collect, organise and classify papers about a theme. Related Siabato's works: Siabato et al  (2017) [An Annotated Bibliography on Spatiotemporal Modelling Trends](https://www.graphyonline.com/archives/archivedownload.php?pid=IJEES-135). Int J Earth Environ Sci 2: 135; and 
Siabato et al (2014). [TimeBliography: A Dynamic and Online Bibliography on Temporal GIS](https://doi.org/10.1111/tgis.12080 ). T GIS 18(6): 799-816

NOTE: See also AI in precission medicine, microsoft research

NOTE: LOOK AT THE MAILBOX, TAGS TODO, TFM-Ideas, Project Ideas

NOTE: Have a look at [selected projects from Visualizar 17 Migraciones](
https://www.medialab-prado.es/en/news/visualizar17-migraciones-selected-projects-announced). Rewrite Altas of UJI's projects?

NOTE: [ROpenSpain](https://ropenspain.es/)




