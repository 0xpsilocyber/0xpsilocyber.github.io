
## My path into Infosec -- Part 1

---
title: "My Path into Infosec"
date: 2025-08-20T19:45:26-07:00
draft: false
---

## Greetings & Special Thanks
> ℹ️  **Heads Up:** I write specifically keeping editing to a minimum. There are likely spelling, grammatical mistakes. I prefer to keep my thoughts as close to raw as possible, and sometimes that means going off on tangents. Thank you for reading, if you are not dissuaded.


Hi, my name is Ricky, and at the time of this writing, I'm a senior incident responder for Google Cloud, specifically, I have built many of the processes that are utilized across GCP for responding to threats of various sizes and scale. 

While that may sound impressive, it was not done in a vacuum, I learned from some of the best, specifically -- folks like [Matt Linton](https://mattlinton.com/blog/provingnegatives.html), [John Strand](https://www.blackhillsinfosec.com/team/john-strand/), [Jake Williams](https://infosec.exchange/@malwarejake), [Rob Lee](https://www.sans.org/profiles/rob-lee), [Lesley Carhart](https://tisiphone.net/), either through personal 1:1 mentorship, classes, or in general reading their blogs and education. All folks I look up to, admire, and aspire to become as I grow further in my career.

In addition, I've been lucky, privileged even, to work with amazing folks from Google who have honed and built up our IR processes for over a decade, influenced by processes such as the [Incident Command System (ICS)](https://emilms.fema.gov/is_0029a/groups/27.html). So while I may have constructed many of our new processes, I would not have been able to do so without the historical context and learnings of those who came before me, and are still improving to this day.

--- 

## Professional TL;DR

At a glance, this is my professional profile: 

* 15 years DFIR experience.
* Former: (GS, Civilian) US-GOV, DoD, USAF, Gov Contracting, Rackspace, Amazon, Blackbaud, ARM.
* ~20 certs, GIAC galore.
* Bachelor's degree from a small university in San Antonio.
* Currently finishing Master's degree w/ SANS.
* Responded to threats of many different sizes and scales. 

--- 

## My Path to DFIR

So here's where we get a little heavy I suppose. 

### Where I Come From
I was born and raised in San Antonio, Texas. I did not come from wealth, nor did I come from a family with any sort of professional AND/OR formal education. My father was a gangster, worked the streets, utilized our familial ties to cartel interests to be part of and engaged with underworld markets. My mother, not much better, was drawn into that same life, growing up around shootings, drug deals, was just a normal part of life for me. 

As you can imagine, my parents didn't really raise me. I was tossed between whomever in my family would take responsibility for me week over week; if I recall correctly, I believe I was about *10 years old when my grandmother took me into a her small ranch* out in Lytle/Atascosa Texas. It was my **first time** with **my own bedroom**, if that gives you any indication of the life I had lead up until that point.

Growing up, I spent much of my time alone. -- As a neurodiverse child in this environment, --  I found my own way to keep busy and distracted from.. Well the hell that was my childhood. That spurred particularly in my **interest w/ computers.** You see, my parents would show up **occasionally** in my life, and would love bomb me with gifts either via illicit gains or to *act* as well as they could to emulate paternal instincts. It wasn't until I was much older that I saw this for what it was. 

So every now and then, my father/mother would show up with a game console, or a computer, it was the only way they seemed to know to communicate with me. And well, to be frank, I am grateful they did that, because I would not be where I am without access to such tools. But beyond that, I had little in terms of life guidance, mentorship, I figured out a lot on my own... Little did I know that figuring shit out on my own, would be the primary theme of the life I have lived up until now.

> ✨  **Fun Fact:** I started getting trouble for *hacking* and messing with computers as early as the 4th grade lol.

### Tinkering, Gaming, Music -- the early years.

Well, now that you know that fun little bit of my background, this is the part where I share my Rocky Balboa montage of tinkering and breaking shit for fun and gainz. You see, I hated the life of crime my family spurred from. I remember once even crying in a Chuck E. Cheese because my mother wanted me to steal tokens from a machine to use on other games, Lol. But still, they taught me lessons of thievery, force, exploitation, general roguish behavior to get ahead in life. It always felt wrong.. But that was how I was raised early on. I was not an angel, but I did my best considering the environment.

Looking back on it all, it’s no wonder I ended up in a career doing my best to respond to people and organizations that wish to cause harm.

#### Escaping To the Country

Thankfully, my grandmother showed me the value of hardwork, dedication, peace, quiet. She was a hard woman, dropped out of school in the 7th grade to tend to the familial ranch, pick cotton, raise animals, eventually she became a seamstress for Levi's between 1950-90's. Funnily enough, she ended up becoming an in-home assistant providing medical care to people who couldn't take care of themselves. I say funny, because she was doing this well into her late 70's taking care of people who were much younger than her. That being said, she is a hardworker, and is still to this day working on her yard, stayin' young.

So with that backstory, most of my middle / highschool years, I lived alone on the ranch. I would explore the country, the lakes, go for walks on my own, little to no supervision, and found my own world out there in the country. I'd walk around with my cdplayer, blasting Linkin Park, Evancesence, Papa Roach, I thought I was so cool, Lol. But as you can imagine, I'd get bored, and would start *tinkering.*

> ✨  **Fun Fact:** Amy Lee began her singing career at 16 on an album called 'Origins.' I would use Kazaa and Limewire to find hidden music by artists I liked. One of my favorite songs by her was *[Listen to the Rain](https://www.youtube.com/watch?v=tOc1O1OYO0U)* I would listen to this song frequently on stormy nights in Texas.


#### The Infosec Seed is Planted

Next thing you know, I'm hacking apart my old HP desktop -- I wanted to play games, -- but I did not have the computational, nay, the graphical power to do so. So I started learning how to break apart my games, mod in additional resources, learn how to squeeze as much performance as I could out of my systems. I'd run Google searches in the library at school, print out guides, take them home -- much different time from nowadays haha.

> ✨  **Fun Fact:** I would modify the hell out Command & Conquer: Tiberium Sun & Unreal Tournament 99

Then I discovered *hacking*. How? Well, Viruses, hackers, crackers, phreakers, would be showcased in magazines like *Game Informer* or I'd watch interesting segments on *G4TV*, in addition, imagine seeing *Ghost in the Shell* and other such CyberPunk works on *Adult Swim*. As mentioned before I had little to no supervision, I would just watch shit lol. Shoutout for Goku for teaching me to believe in myself. ✌️

One day, I believe I was about 12 years old; I recall there was a *Defcon* documentary on *TLC* (back when they still shared educational material lmao.) -- at least I think it was TLC, it could have been Discovery. -- But anyway, at this time in my little life, I was a little emo/goth/punk/rocker kid and expressed myself through dark music and other such things. I was a frequent shopper at the *Hot Topic* 😎

And you know what I saw? Adult badass punkers, alternative life style folks, all showcasing their deep knowledge of hacking, breaking things, and joining together in community. People **unafraid** to show who they are, be loud, wild, while maintaining high degrees of intelligence.

I knew, I wanted to be part of that. I knew that was my culture. I knew that one day, I'd be there, I'd do anything to be there.

And I did it.

### My actual start -- Highschool

My freshman year of high-school, I joined a *computer maintenance* course taught by an immigrant, mentor, teacher, & life-coach, from Haiti: Mr. C. I'll never forget, his words those early days.

 > *Get your A+, Network +, Security +, and I guarantee you will leave highschool your Sr. year earning $40,000-50,000 a year.*
 > 
 > -- Mr. C

For someone like me? That was all I needed to hear. That was the guiding principal, the north star I needed to find my way. And frankly? Mr. C was right. He was so right. My life & career have been growing ever since that day ~17-18 years ago. 

So I did it, I earned my certifications, and eventually was qualified to join an early college program in San Antonio that would take students from all surrounding school district and place them in a classroom with college professors. 

> ✨  **Fun Fact:** I was a bit of an overachiever, I ended up graduating highschool with an A+, Net+, Sec+, C|EH (ew), and a CCNA.

This is now my Junior year in highschool, I've earned an A+ and a Network+, and I've started getting recognition from the school board, principal, superintendent, it was whole thing. -- It was fucking horrifying. Why? Because now you know my background, and it **feels** like it was all happening suddenly. I'm getting all this recognition and award, but back home, it was just quiet, me and the country. My family didn't understand it, nor really tried to. My family never really showed up to my recognition ceremonies, and I knew that the teachers knew my situation, the administration, it was like a quiet, somber, elephant in the room. At this point, I'm also starting to become isolated from friends, people started treating me differently.. It was a constant balance of stress, excitement, loneliness. 

The more I felt isolated, the more it pushed me to go further. I had nothing else, but the fruits of success provided through my professional and academic careers.

#### Back to the College Program

So as mentioned previously, we are now skipping to my Jr. year in highschool -- *year 3* -- I’m now part of this Information Technology & Security Academy (ITSA) in San Antonio. 

Well as part of this program, we were expected to show up to class at about 8am. Between 8am -> 12pm, we were in college, then after, we went back to our home highschools. 

Well, my professors knew I had obtained a couple certifications and I was asked to build & lead a team for a program called *[Cyber Patriot](https://www.uscyberpatriot.org/
)*. It was the first of it's kind, but it mostly focused on -- what we now call threat hunting, -- vulnerability management and simple mitigation implementations. 

Throughout the flow of the competition, students were handed vulnerable images, and through those images, the students were expected to identify security flaws and fix them. The scoring bot on the system would catch these fixes and provide a score where you were going up against other highschool students across the entire United States. The images were typically Windows Servers, Linux Servers, even Cisco IOS images. 

Well, me and the team? We took third place nationally in Washington DC that year. So much so, [we received recognition and praise across the entire city of San Antonio](https://www.mysanantonio.com/news/local/article/high-school-grads-landing-high-tech-security-3677823.php
).

![A photo of me with a banana in the background](/images/profile-banana.jpg) 

> ✨  **Fun Fact:** I was hot shit c;

#### Young Hacker Hired by the Military, yep, it's me.

Well, in San Antonio is where Lackland AFB is located, where at the time, the 33rd Network Warfare Squadron was located. Somehow, through CyberPatriot, the Air Force Association and the Mayor's office, they found a way to get me and my team **Secret** clearances and internships in the Airforce's SOC. To put this into perspective, I am 16 years old. I come from a hard background, I lost myself in computers, hacking, the sub-culture, now I'm being thrown into a military environment. It was wild.

And this was my first job in Infosec. I learned how: 
* To tune IPS/IDS sensors.
* Build IR processes & playbooks.
* Learned to never tell my commanding officer that I was 'bored'
* Respond to security events, analyze logs, network telemetry, apply investigative techniques.

> ✨  **Fun Fact:** I once told my supervisor I was bored. Said supervisor had me shred classified documents for two days straight to teach me a lesson. Joke was on them though,I enjoyed sitting there having a mundane task lmaao.

This experience will likely be a blog in and of itself. But TL;DR. I started very young in this career, a career that is atypical. 

At this stage, I was 16, I was making my own money, able to live by my own rules, and once I had that taste of independence, I never looked back. I carried that further into my 20's where I worked, and worked, and worked, to achieve further and go beyond so far and away from where I came from.

I'm 32 now, it's been a long path, but I'm grateful I ended up where I did. That first taste of independence set the stage for the next 16 years of my career, a story I'll share in Part 2.

---

### So what's next?

Well this is just part 1 of this series, as I get time, I'll add in more details on what I did after high-school, but this is general synopsis of my origin. I get asked quite a bit "how did you get started?" and well, as you can imagine, my story is not standard. Hell, my story is still be written, but I'll be sharing more here over time. 

---

### Music that inspired this post, music you should listen to while reading.

So when I write, when I share these memories, there's a soundtrack playing in my head, this section is dedicated to that music that got me through some of the hardest days of my life growing up. I recommend playing these songs while reading to understand where I'm coming from.

* [Imaginary -- Evanescence](https://open.spotify.com/track/7q6CybWAg3uYLgS5tDWqmd)
* [Scars -- Papa Roach](https://open.spotify.com/track/1UREw2MCfU0xwBzCAjxlUD)
* [A Place for My Head -- Linkin Park](https://open.spotify.com/track/4rbc5CkMyU3F2kwiZLO2z6?si=641749a7bcda41f5)
* [Crossroads -- Bone Thugz](https://open.spotify.com/track/5KSJ9k1FYjFLnIRlJT2wF8?si=1ed368e5da3d4d7b)
* 
* [Nutshell -- Alice in Chains](https://open.spotify.com/track/2JuasWPUodaUxf5nwNpciQ?si=273038d232974e01)
* [ Fully Alive -- Flyleaf](https://open.spotify.com/track/4BIWl6xOUupdv3jpWtPSDC?si=909d9913cc094d89)
* [ 44. Caliber Love Letter -- AlexisOnFire](https://open.spotify.com/track/1ir5oMNuxrNeCwUJFaEyum?si=d284c844047a49f3)
* [Short Stories w/ Tragic Endings -- From Autumn to Ashes](https://open.spotify.com/track/4eRtGBzP92gjIMOtal2kNB?si=baf3b37b3aab41aa)
* [The Only Medicine -- Scary Kids Scaring Kids](https://open.spotify.com/track/4G8tbcZbPGGltARlf4ALkl?si=ae9405da49774211)
* [Monument -- A Day to Remember](https://open.spotify.com/track/6WII5QTkLtW5SglluYlBNY?si=066dd577e82a47f9)
* 
