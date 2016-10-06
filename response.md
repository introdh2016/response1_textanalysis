Topic modeling is a fascinating way of exploring data, and it provides a number of opportunities to further analyze text. My topic model explored 794 research articles from the *Journal of Latin American Studies*. Published by the Cambridge University Press, it features research on Latin American economics, history anthropology, geography, among many other fields. While it is useful in discovering common topics throughout a corpus of texts, it leaves a lot to be desired with this journal given the inability to track topics over time, and having to infer the discourse from the topics provided which can be problematic.  

An initial topic model of the magazine was flawed, given there were no Spanish stop words, leading to a topic that was made of articles like la, el, and los, and conjunctions like para, por, and con. Because it is an academic journal, worlds like vol and pp were counted.

![alt text](https://66.media.tumblr.com/00f446f633d70abededf33ef377b58b3/tumblr_inline_oelprbk8201qdjg6s_540.jpg "No stop words")

After accounting for and eliminating Spanish stop words, the topics became clearer.  A run of fifty topics was very thorough, but to an extent repetitive. The benefits of doing a topic model with fifty topics is the inclusion of individual countries and the studies done about them, like Bolivia and the coca industry, Chile and its political turmoil in the 70s, as well as Cuba and the revolution. 

![alt text](https://67.media.tumblr.com/aeb7ab1ed128de6330f6f6414ca1f1a6/tumblr_inline_oelprsPCMV1qdjg6s_540.jpg "Sample from 50")

A potential downside to this is the assumption that the only scholarship done on a particular country is what is shown by the topic model. Small countries tend to be grouped together, which can lead to the assumption that there is little scholarship or that they are all talked about together rather than separately: 
>“39	0.03668	nicaragua guatemala salvador central costa honduras rica san nicaraguan somoza guatemalan america american managua sandinista state arbenz jose honduran.” 

Another issue is names of places, and given that many cities and regions in Latin America have multi-word names, it can create topic models like this one for Brazil:

>“11	0.05538	brazil brazilian rio paulo janeiro sao brasil state coffee federal vargas minas portuguese national kubitschek club brazilians brasileira gerais”

Nine of the words are names of places, which can show the importance of these places but can also take up a lot of space in a topic group. Another issue with fifty topics is they tend to become repetitive, rotating between economics, government, and social issues.  

Reducing the number of topics down to ten proves to be too small and too general, leaving out a number of countries and topics. It would lead one to assume that the only countries in Latin America are Mexico, Brazil, Argentina, and Cuba. 
![alt text](https://66.media.tumblr.com/028360816337061cca665577416e9860/tumblr_inline_oelprkZVW51qdjg6s_540.jpg "10 Topics")

Twenty five topics seems a happy medium, able to encompass a number of topics relating to Latin American studies while not becoming too repetitive. These topics can be used to begin discussions on colonial government and its effects on modern Latin America, the prevalence of social rights and labor reform, the growth in indigenous studies in Latin America, religion and gender relations, the role of agriculture, and the influence of the United States in Latin American policy and governance.   
![alt text](https://67.media.tumblr.com/ec84afbba9b05f36041362e365f442b3/tumblr_inline_oelpwxX1pb1qdjg6s_540.jpg "1-11")
![alt text](https://66.media.tumblr.com/c74814f0d5d39eeaa7feaad8295d2275/tumblr_inline_oelprzEJno1qdjg6s_540.jpg "12-25")

The limitations with this is the inability to see what is being discussed, and how it is being discussed individually. Latin American studies has a great deal of revisionist studies, and the changes in how events are understood and interpreted is lost in the topic modeling due to the inability to track dates and inability to closely read texts. While it is possible for people like Cameron Blevins and mining Martha Ballard’s diary, the difference is the diary is a single corpus, and it is easier to do a close reading to look for certain topics in the text, which is not as easy with the *Journal of Latin American Studies*.(Blevins, personal blog, 2009) Blevins has a familiarity with the text and the subject that is not possible with this journal, and can easily track shifts in Ballard's writing that is not easily done with the *Journal*.(Blevins, personal blog, 2009) While it is a large body of text that Brett says is necessary for topic modeling, it is by multiple authors from different backgrounds and areas of study, and while there is a way to understand the results, it is not a complete and nuanced understanding of Latin American studies as presented by the *Journal*.(Brett, Journal of Digital Humanities, 2012)

Topic modeling is full of potential, and for an unfamiliar reader, a topic model of the *Journal of Latin American Studies* can give a brief overview of the main areas of study in Latin American history. But it is only an overview, and does not provide information on the number of times a topic was discussed, how it was discussed, it cannot give a reader the layers of complexity surrounding Latin American history, and cannot discuss the individual and varied actions and reactions around certain topics in different parts of Latin America. Chile did not have the same workers’ rights movement as Brazil, and that is lost in the topic models.
