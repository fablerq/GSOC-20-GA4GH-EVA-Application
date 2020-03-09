This is the first test draft of my application. At this state of writing, it should show approximate idea of what I am planning to do.

## About Me

I am Anatolii Shulzhenko, a 2nd year undergraduate Computer Science student at Saint Petersburg State University of Telecommunications, Russia. I have confident experience with Java, Scala and Python. Also in my past I worked with frontend technologies. Having knowledge in Software Development helped me to get an Scala internship at Tinkoff bank at the end of 1st course of study, where I used Scala, Java, Git and learned Docker, ELK stack. I also [completed](https://www.udemy.com/certificate/UC-OVB627O5/) a MOOC course about Java at Udemy last year. And my university background comprises of Alrogithms, Operating Systems and Programming. Currently I do the majority of my programming on a Ubuntu, however, I have access to a Windows platform and some virtual  machines.  

And apart from these, I am also one of the mentors of local students-developers community called Bonch.dev. With them I participated in 6 hackathons during the last year and we [won](https://vk.com/photo-167489566_457240230/) one. Also I have been involved in a bunch of different projects inside this community, using such frameworks like Laravel, VueJs, Django and Spring Boot.

Regarding to my biology knowledge background, I think I need to be honest - it's quite small, I am just starting my journey in it and willing to study.

Some examples of my open-source code you can find here:
- https://github.com/fablerq/Java-JNA-multithreading. Final project, written with Spring Boot and Java, which I made to complete the course of  Algorithmic Foundation on my first year of study. It's a multithreading implementation of lagrange interpolation algorithm with various Java wrappers over native C++ functions, which official WinApi uses. Also I used here different types of c++ threads synchronizations (pipes, mutex, events) via Java Native Access library.
- https://github.com/fablerq/DotaDictionary, full-featured REST API web service written with Akka HTTP and Scala about an year ago, which provides information how often a certain word could be found in any cybersport media. Used IBM Text-to-Speech API, Yandex Translate API, Aylien "Text Extractor" API

Of course, if my proposal is accepted, I will be able to work at least 30 hours a week through the whole summer. Only by the end of June I will have exams so on this date my activity may be a little bit lower, but my productivity will be the same.

Info:
- Github: https://github.com/fablerq
- Gitlab: https://gitlab.com/fablerq
- Email: anatoliyshulz@gmail.com
- Timezone: MSK

### Why GSOC with EVA «Reference registry + contig alias search» via GA4GH

GA4GH in general and EVA in particular have a big mission and large worldwide goal of providing genomic data for human health. This is amazing and impressive. Participation and contributing to the development of such project inspires me. Because it has a global mission that benefits all of the humanity. 

Also, the choice of this specific project is determined by my current skillset (JVM based) and biology knowledge requirements - I see that they are not so big, so I could easily start investigating about the topic. I would also like to take part because the successful completion of the project will give me an additional competitive advantage in enrolling in the local bioinformatics [club](https://vk.com/bioinf) (as I mentioned in the letter).

Overall I want to choose this project because I see that is totally reachable for me in scheduled time, inspires me and can lead me in my life goals. 

### Why me

I am a self-taught programmer who learns quickly and eager to learn things which passions me. I am good at working with different teams and also take my work seriously. I have the required programming skills and I am familiar with the developer guidelines and projects workflow. And also as I mentioned earlier I consider this project totally reachable for me, which I will show in timeline later after initial call. And is why I am excited to attempt to implement it.

## Goals

> ***Label: should it be the separate service or improved version of existed EVA-ws repository?***

Implement a feature of cross referencing chromosomes/contigs using different nomenclatures from NCBI, ENA or Ensembl.

Other goals:
- Maintenance: Mechanism for ingesting new aliases. Possibly periodically.
- Provide the sequence MD5 and SHA1 along with the aliases. Related to refget.
- Support scaffolds and one-to-many equivalences. 
- Given a Genbank or Refseq chromosome, provide also the species and/or assembly.
- Assembly aliases. 

## Brief timeline

> ***Label: this is just a brief draft what could be done, will change significantly next weeks***

### Pre-GSOC period [Apr 27th - May 17th]

- A detailed study of the biological background needed for this project for better understanding and defining corner cases

- Setting a blog for further writing posts, where I will introduce what I’ve been done in any certain week.

- Discussions about possible improvements with mentors

- Reading NCBI and EVA documentations and existing backend and frontend repositories' codebase.

### First Coding Period

Week 1 [May 18th - May 24th]

- Architectural tasks

Week 2, 3 [May 25th - June 7th]

- Main implementation

Week 4, 5 [June 8th - June 19th]

- Main implementation

### Second Coding Period

Week 6, 7 [June 20th - July 5th]

- Provide the sequence MD5 and SHA1 along with the aliases

Week 8, 9 [July 6th - July 17th]

- Modify the current EVA frontend interface for new functionality with aliases

### Final Coding Period

Week 10 - 11 [July 18th - August 2nd]

- Extra time to handle additional goals

- Writing tests

Week 12 - 13 [July 3th - August 16rd]

- Continue to refactor and improve the quality of the code written for the project
  
- Making sure the codebase is complete with test-cases and documentation. Making sure the code is deployable in production
  
- Wrap-up and finish working on remaining issues

- Prepare a final project report

### Post GSOC period
  
- Once GSOC 2020 is over, I will continue to be part of organization. I will have in-depth knowledge about the topic and would love to upgrade it further.  
  
## Additional goals
  During the phases one and two of this GSOC project, I will understand in more detail the possibilities and weaknesses of the new system, allowing me to implement additional functionality or to fix existing bugs
  
 

