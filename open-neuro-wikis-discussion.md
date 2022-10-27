
# Open Call about wikis and digital infrastructure 

Date: 26 October 2022

Time: 17:00 UTC

Duration: 1 hour

Hosts: André Maia Chagas (he/him), Matías Andina (he/him) and Cecilia Herbert (she/her)  from Open Neuroscience

Speaker: Jonny Saunders (they/them)



**About Open Neuroscience **

Open Neuroscience is a network of collaborators keeping track and curating interesting open source projects related to neurosciences on  [http://open-neuroscience.com](http://open-neuroscience.com).

We also hosted the Open Neuro Seminar Series via World Wide Science, where speakers shared their open tools and methods for neuroscience. Playlist here: [https://www.youtube.com/playlist?list=PLeoLaqf1K3qrwP1o4TUnKAR6d6xNb\_b0M](https://www.youtube.com/playlist?list=PLeoLaqf1K3qrwP1o4TUnKAR6d6xNb\_b0M) 

openeuroscience@gmail.com



**Jonny Saunders**

Jonny is an information liberationist that is strategizing with groups across disciplines to rebuild basic scholarly infrastructure. They believe we can use the prodigious resources of publicly funded science to do our part in dismantling informational capital - by replacing our broken systems, we can seed the technology and social organizations to claw back the world owned by surveillance conglomerates from publishers to cloud landlords.

   

## Goal of today's meeting

       We are interested in learning what is the best way/infrastructure to manage the content we curate on (ie can we make it interoperable, more user friendly, easy to copy/move/replicate? ).   



## Agenda

Intro by André, short presentation by Jonny, and discussion to follow.

**Join the call**  this call has ended

   * **Please note that this call will be recorded**
   * The video will be available on the []YouTube channel: [][https://www.youtube.com/channel/UCHPvi\_HaEU7OQgXQBh9ECvQ/videos]([]https://www.youtube.com/channel/UCHPvi\_HaEU7OQgXQBh9ECvQ/videos[])[] [] in the next few days
   * Turn on your webcam if you don’t mind sharing your face (or off if you do!)


## The Challenge

There are many groups in the open-source space. We each build systems/things that do not talk well to each other. 

These systems/things are difficult to find and maintain in the long-term. 



## The Tool

Good documentation transforms tribal knowledge into institutional knowledge. (source: [https://twitter.com/documentwrites/status/1584930963590905856)](https://twitter.com/documentwrites/status/1584930963590905856))

Wikis provide an opportunity for building long-lasting interoperable systems of documentation for open tools and software. 



## The Critical Evaluation

What are the principal challenges for building interoperable systems in the open space? How do wikis address that challenge?

What are good ways for collaboration?



## 👥 Roll call

   * Name / Project / social handles (twitter, GitHub, etc.) / \_emoji mood \_
   * Matias Andina  / Open Neuroscience / @NeuroMLA
   * Cecilia Herbert  / Open Neuroscience and Open Ephys Production Site / @ChuckleScience 🙌
   * Andre Maia Chagas / Open Neuroscience \& Sussex Neuroscience / @Chagas\_am
   * Jonny Saunders / @json\_dirs
   * Tim Fallon, PhD NIH F32 Postdoctoral fellow (SIO/UCSD San Diego, CA, USA; @photocyte)
   *  Sarah Hutton, MLIS and (ABD) PhD, Amherst, Massachusetts U.S. @schutton / Research and Community Engagement Lead, Internet of Production Alliance / Research Affiliate, UMass Amherst  [https://www.linkedin.com/in/sarahhutton/](https://www.linkedin.com/in/sarahhutton/)
   * Andy Lustig, Engineer in Karpova Lab at Janelia Research Campus, pyControl, @alustig3
   * John Flournoy / Research Scientist in psych+neuro at Harvard University; remote in San Diego, CA / @flourn0@fediscience.org / @flourn0  🙃
   * Rich Trott / UCSF Library \& Node.js / @Trott / 😬
   * David Nicholson / Engineer, Embedded Intelligence / dev/maintainer, vocalpy ([https://github.com/vocalpy)](https://github.com/vocalpy)) / pyOpenSci / US-RSE / NickleDave (gh), @nicholdav (bird app) / 😼






## 👥 Wikis and digital infrastructure (Jonny Saunders)

### 👥 Live notes about the talk:

   * Difficult to follow best practices: link things togehter, documentation, share with the community.
   * Stucturally disincentivized to do this. Formats in academia not meant for this. Academia *actively discourages* this via tenure/promotion/publishing/funding policy.
   * Contextual info about doing research e.g. glue wiki [https://jvoigts.scripts.mit.edu/blog/category/spike-sorting/](https://jvoigts.scripts.mit.edu/blog/category/spike-sorting/)
   * What is the knowledge that is needed to perform experiments? Is it fully captured by the current publication system?
   *  [https://xkcd.com/927/](https://xkcd.com/927/) we need more standards! what if everyone does not want to adapt to the same strategy? 
   * Can we crowd-source editing/curation of such documentation?  Should we do it?  How do we handle version control?
   * semantic wiki = human readable + computer readable database
   * e.g. from autopilot wiki with dxf file, pdf file, stl files. represented with triplet links.  subject–predicate–object . semantic wiki links built with colons. abstract representation.
   * categories are "properties"
   * templates used for laying out data in a particular way and also grouping a set of properties together. bult with curly braces. any changes to the template are reflected on the entries.
   * forms allow us to edit templates (fills in the fields of the tempates). have autocomplete functionality using tokens.
   * page schemas using a plugin extension to manage the generation of forms and templates
   * managing linking - what was this called structure sth?
   * can hold persistent object identifiers
   * ata ingestion technique: APIs to edit the page via bot. so e.g. take ON structured info, parse it and port it into wiki
   * selector for interfacing with other repositories: selecting classes with CSS. then pushing it through the injection. maitaining origin URL to BUILD TOGETHER.
   * Capture first and organize later anagora.org. link wiki to conversations in different media.
   * wikis as transitional piece




## 👥 Discussion order and notes

   * Tim Fallon's Question: Could the Semantic Wiki concept be used as a WYSIWYG electronic lab notebook with a library of pre-existing templates, for bench scientists that don’t want to think about schemas or MediaWiki text at all? See also, this recent thread on the DIYBio google group: [https://groups.google.com/g/diybio/c/-9QjGsH0OT8/m/KqXlro6eEwAJ](https://groups.google.com/g/diybio/c/-9QjGsH0OT8/m/KqXlro6eEwAJ)
       * visual interface available. some examples in which this approach works well for lab notebooks. promted input (forms) helps.
   * Funding incentives promote creation of novel repositories/indices instead of centralizing. How can we make sure people can have their own flavours? If we do it with bots, who's gonna write the bots to scrape? Can we tap into the funding structure to do this? 
       * demostrating what is possible to get funders to fund flexible data infrastructure instead of specific repositories and databases. e.g. US currently
   * JCF: I feel like seeing examples is super helpful. Is there a list of egs somewhere? I want to see this used as a lab notebook, as a "journal article", as a "journal", etc... also how do i actually start using this?
   * Sarah Hutton: Has there been any persona workshopping to establish a direction for UI dev? I’d be really curious to learn what the assumed user base is, given the current conversation around an undergraduate student’s approach, vs a researcher’s, vs a community member's.
   * Sarah Hutton: following up on the funding question that Jonny just fielded - you mentioned putting use cases in front of major funders - which do you think would be the most compelling? I am currently considering a new discussion in open medical devices as a compelling use case (it's currently an email thread)... others?
   *  Ceci: what is the top level? one wiki to rule them all? how do wikis talk between each other (maybe I missed this), where are they hosted
       * I like to think about it in a "federated" context (for now, pending some work building p2p systems) where the wikis can all import/reuse/etc. writing from each other. I think ward cunningham's (creator of first wiki) fedwiki project is really interesting in this regard [https://github.com/fedwiki/wiki](https://github.com/fedwiki/wiki) . So not necessarily one wiki to rule them all, but many wikis that are linked together that build a larger ecosystem that is neither a singular monoculture nor a disconnected sea of everything yno? -jonny
       * Also they are hosted anywhere! I can show y'all how this works. but tl;dr is any computer with a stable IP (eg. like a rented server or smth), then buy a domain and point it at that machine in its DNS records, and boom there's ya wiki.
   * David Nicholson: Can we have schema builders that are easier to use?
       * working on it
   * David: Talking about bigger repositories to engulf others. Default metadata standards stemming from a "winner take all appraoch" bc of whatever reason. Funders get stakeholders "in the same room". Would that be useful?
       * Andre: forking efforts. maybe short term there is a winner but in the long term this goes back.
       * Jonny: holistic view of seeing this social process of forking. 




## 👥 Comments

Sarah:

Yes, I agree - building the larger community is what I’m really interested in for my work!

Yes, this is really taking a look at changing the economy of knowledge production.

Opinions differ on that in librarianship.

Yes, absolutely. It’s more about ontologies and shared vocabulary than the tooling.

lovin’ everything you’re saying



Exactly, addressing in-the-moment, contextualized schema to suit your needs. But CONNECTING it to preexisting structures.

Tying this all in with the growing global conversation surrounding public interest technology would be really interesting





Tim: I’ll also make a pitch: I’m a big user of the Bits In Bio slack channel, which has >2000 people in it, if there isn’t already a Slack / Channel for this particular community (those attending this seminar), and people want to connect afterwards, would be happy to make a channel on Bits In Bio for this



John: Funding from or in collaboration with other open-science type groups? OSF? or like the Internet Archive? or even dare i say it effective altruism philanthropies?



John Flournoy: <3 you jonny so good to see this stuff in conversation and am so excited for this stuff



About social benefit of crediting within the triplet system

Hmm, yes - this deep crediting process relates (for me) to alt-metrics and how they can be leveraged

And to push institutions further - push uni policy in tenure/promotion cycles to recognize repo contributions and place higher value on community participation (if they don’t already)





## 🗣️ Interesting links share

   * [https://wiki.auto-pi-lot.com/index.php/Autopilot\_Wiki](https://wiki.auto-pi-lot.com/index.php/Autopilot\_Wiki)
   * [https://bioprotocols.github.io/labop/](https://bioprotocols.github.io/labop/) <- Tim in the meeting, is one of the core members of the LabOP project (and is writing this text), please reach out or join the group if you find semantic lab protocols interesting!
   * Playlist for the Open Neuro Seminar Series about open source tools and methos for neuroscience [https://www.youtube.com/playlist?list=PLeoLaqf1K3qrwP1o4TUnKAR6d6xNb\_b0M](https://www.youtube.com/playlist?list=PLeoLaqf1K3qrwP1o4TUnKAR6d6xNb\_b0M) 
   * Jonny's talk about Autopilot on Open Neuro Seminar Series [https://www.youtube.com/watch?v=c4-pxDakdFE\&list=PLeoLaqf1K3qrwP1o4TUnKAR6d6xNb\_b0M\&index=12\&t=289s](https://www.youtube.com/watch?v=c4-pxDakdFE\&list=PLeoLaqf1K3qrwP1o4TUnKAR6d6xNb\_b0M\&index=12\&t=289s) 
   * [https://schema.org/](https://schema.org/)
   * anagora.org
   * Tim Fallon's invite to a Zoom meeting tomorrow at 11:00AM Pacific, to discuss community organization around an open database for labware (i.e. plates, flasks, whatever). Might be interesting to people in this group(Get in touch with Tim, @photocyte or my academic email, easy to guess and around the web)
   * [https://bitsinbio.org/](https://bitsinbio.org/) <- I’ll also make a pitch: I’m a big user of the Bits In Bio Slack community, which has >2000 people in it, if there isn’t already a Slack / Channel for this particular community (those attending this seminar), and people want to connect afterwards, would be happy to make a channel on Bits In Bio for this
   * FOLIO the future of libraries is open [https://www.folio.org/](https://www.folio.org/)
   * [https://activitypub.rocks/](https://activitypub.rocks/)
   * [https://bitsinbio.org/](https://bitsinbio.org/)
   * [https://github.com/fedwiki/wiki](https://github.com/fedwiki/wiki) 




## 🗣️ Closing and next steps

Get a space to chat: Gitter is part of Matrix now. Can be part of sth larger later. Discourse?

We will send an email to connect.



Implement wikis in ON



### Q\&A for after the call

Have any questions? Add them below with your email. We will respond to these via email

   * 



### Feedback

What worked?

   * 

   *  
What didn’t work?

   *  
   * 

What would you change?

   *  
   *  
What surprised you?

   *  
   *  
   * 





Reference: Mozilla Open leadership Framework, Open Life Science

License: CC BY 4.0, Open Life Science (OLS-4), 2021
