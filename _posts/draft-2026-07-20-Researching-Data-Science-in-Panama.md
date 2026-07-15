---
layout: post
title:UCSB STRI Advanced Data Science Researching Training in Panama
date: 2026-07-20
featured-img: 
---

# UCSB STRI Advanced Data Science Researching Training in Panama

The coordinators of the ["University of California Santa Barbara (UCSB) Smithsonian Scholars Program"](https://oep.ucsb.edu/programs/smithsonian-scholars-program) came to Moorpark College for an informational session, of which I attended, and then applied. As stated on the official website, "The program aims to engage diverse students in experiential learning centered on multi-disciplinary conservation strategies, biodiversity research, and green careers in STEM." For about 4 weeks, we have discussions, online lectures, and assignments to learn [R programming](https://www.r-project.org/) in [Posit cloud](https://posit.cloud/). The students accepted into the advanced section of the program go to Panama for one week, where they are to learn in depth about the applications of data science in field work, as well as how to observe with the lens of computational analysis. 

**abbreviations, for reference**
- UCSB = University of California, Santa Barbara
- STRI = Smithsonian Tropical Research Intitute
<br>

## Day 1: The Flight (7/8/2026)
I departed with my father from my house closer to 4PM, and after picking up some in-n-out, I arrived at the airport promptly at 7PM; boarding started at 9PM, and we flew out at 10PM. I was the first to get through TSA and arrive at the gate, so I waited for the rest of the team in the lobby. On the plane, I started reading "Frankenstein" by Mary Shelley and did a bit of drawing; it was a six hour flight. 
<img src="https://github.com/CaptainSapphire/PH-s-Blog/blob/main/assets/July%202026/IMG_8082.png?raw=true" alt="Sunrise from the plane" width = 500> <br> <br>


## Day 2: Casco Viejo & The Educational Center (7/9/2026)
We landed, and took transportation to the Radission, the hotel we were staying in. We explored Casco Viejo for a while and had lunch; I had a couple of empanadas. From there, we went to the STRI "Auditorio Earl S. Tupper" (the STRI center) to pick up our guest passes. We then took a tour of [Punta Culebra](https://stri.si.edu/es/visitenos/punta-culebra), the nature and educational center.
<br><br>
Punta Culebra had a few different sections of educational rooms; climate change awareness/"Agua Salud" project, frogs, snake/shark/fossils (fluid-preserved specimen), outdoor nursing shark tank, outdoor butterfly habitat/bug dome, mini-aquarium/fish room, and finally there was the overlook. 
**What I learned from each room:**
- Agua Salud Project

## Day 3: Casco Viejo Again & The Symposium (7/10/2026)


![Symposium Poster](https://stri.si.edu/sites/default/files/event/images/fellowsymp2026-04.jpg)

## Day 4: Flight and Welcome to Mt. Totumas (7/11/2026)


## Day 5: Queztal Trail Loop & Camera Trap Presentation (7/12/2026)
The daily morning from this day on is waking up at 7:00AM, having breakfast from 7:30AM-8:00AM, and going out to hike. 

## Day 6: Puma Trail, Device Deployment,  Data Science Lecture #1 (7/13/2026)


## Day 7: Big Tree Trail, Data Science Lecture #2, Night Hike  (7/14/2026)
After the morning routine, at 8:30AM we departed for the Big Tree Loop Trail. On the trail, we saw spider monkeys, all types of bugs, and birds. 
- We saw some spider monkeys a couple of times throughout the hike; they were energetic, but meant no harm.
- We got a good view of the three-wattled bellbird, a bird popular amongst anyone who visits this region due to its unique call and appearance
- At the very end of the trail, we saw the Quetzal, a colorful bird that is highly praised by the locals. I had the opportunity to get a picture using my phone through the scope the trail guide brought with us.
<br><br>
The morning hike this time served less to educate us about field data and more about the field itself; learning about what to observe, and practicing keeping an eye out for any motion or sound that could indicate life is nearby.
<img src="https://github.com/CaptainSapphire/PH-s-Blog/blob/main/assets/July%202026/IMG_9494.png?raw=true" alt="Quetzal Picture" width = 500> <br> <br>

<br><br>
After lunch and a break, had our second discussion on R programming. This day focused on "For Loops" in R, which I had not heard of prior to a friend mentioning it once or twice. 
```
Lesson 2 Notes 7/14
abstract = having variables in it; for loops abstract vectors

iterating across items in a collection

iterating across vector _---> interating across individual items across the vector

presence-absence matrix = community matrix

community = entire species list in this circumstance, but generally the whole in an area
community matrix = presence and absence of a species of a particular site

hard coded = coded in and not using a loop to pull the index

```
For the homework, I found some ways to take on the challenge question and shared it with my peers. One of the peer-mentors said it was a creative solution, since I solved the question without using match() or factor(). While I will not publish my solution publically (as they likey reuse these repositories, and I wouldn't want to ruin it for next years students), I will say there are multiple ways of approaching this problem. Given we didn't learn match() or factor(), I had to work out my own solution. I feel that my skillset is more on the data science side than in ecology/biology, so it works out well that the other students here understand those logistics and can explain what certain things mean, while I can explain R. 
<br>
I really enjoy the programming sections of this course. The hiking and outdoorsy sections are wonderful and feel almost magical, but nothing feels better than getting the right answer on your own, after trying over and over for it. **After all, a winner is a loser who kept trying.**
<br><br>
After dinner, we went for a night hike! We stargazed for a bit before taking off, and then on the hike (which was a shortened version of the Queztal Loop) we saw some possums and frogs. It was really nice. 

## Day 8: Cascado Trail, Data Science Lecture #3  (7/15/2026)
The morning hike was peaceful at the start, we passed by a couple of waterfalls, and then it was a lot of uphill. I didn't mind it much, as I was able to take it at my own pace, even though it was warming up/the sun was coming out. The data discussion was relatively short this day, but the most important concept covered was the various "join" functions, mutating datasets and merging columns or rows into a singular dataset. The challenge was short but incredibly satisfying, as I worked through it on my own again. While I finished around the same time, a bit earlier, than my peers, I feel that the rush to finish first is not a good measure of how much I understand the subject. My notes from the lecture are below, but most of my notes are in the assignment, where I commented on the example code.

```
Lesson 3 Notes, 7/15

the thing right before the loop is create the place where you put the answer, and right after the loop is a line we were deposit the result in the correct location

huge component of integrating data and whatnot is learning to juggle the various names (latin names, field names, etc)

There's an entire key for every scientific name across many taxonomy birds, open source; reference for the final project

the first argument of left join is the stuff you want to keep/grab 

when you do a join, check what got messed up (records_named ,, filter and count )

interjoin = only the elements that are common between datasets

morphological trait (body trait)
ecological traits are defined very loosely
every species has traits

icun status = how endangered a species is

the data lifecycle
- the many uses for data
- the stages of work associated with using it across its lifespan
- planning to collect data -> collecting -> analyzing -> storing -> publishing -> archiving in a final destination
```


# Final Thoughts & Conclusions
