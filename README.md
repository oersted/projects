# Projects: To-Do list

## SCITODATE

Status: Mar 2016 - ongoing

This is my main priority, and my job now. The vision for SCITODATE is to collect, index and analyze large collections of academic articles to extract global business and science insight.

## Bonobo

Status: Jan 2017 - inactive

Bonobo is a lightweight ETL framework that I very much like, I would love to use it in my day-to-day work. However, there's a dealbreaker: there's no way to do parallel processing with it. I have decided to implement it myself.

## Quantum Computing

Status: Dec 2017 - inactive

The field has always intreagued me. I have a good foundation already, but I want to learn more. My goal is to learn the current state of "quantum programming" and to answer key questions, like what exactly makes quantum computing superior, and what kinds of algorithms can be accelerated with it. This is a more theoretical project, so the end product will be a post explaining my learnings, or a series of them.

## Numer.ai

Status: Nov 2017 - inactive

Numer.ai is a unique machine learning competition on stock prediction. However, the stock data is highly offuscated, to the point where the competition is a pure machine learning task, with ~50 features and simple binary classification. It is also unique in that not only the few top people get a reward, thanks to their meta-model architecture and use of cryptocurrency.

Anyways, I've been always intreagued of the idea of making a pure "money making machine". I have also never participated in a ML competition or worked on a simple and pure ML task. So I chose Numer.ai.

## Choice of Games + Alexa

I want to develop an Alexa front-end for Choice of Games. These games are very simple, mostly just text and decisions, with some basic JS business logic and a bare-bones HTML front-end, it's all in GitHub. Alexa skills are developed with Javascript, so it seems feasible to link both.

## Luna

I've been waiting for luna-lang to release for a long time. I've always been interested in visual programming and this project has the potential to actually break through. However, the first big release doesn't include multi language interoperability and it looks like only Haskell, C and Javascript interoperability are planned. Bummer... I really wanted to use it with Python. The first step is to learn the language. I may consider implementing Python interoperability myself, but it may be too ambitious of me.

## Research visualizer

In my job at SCITODATE I have to read a lot of academic articles to see what is possible and keep up. However, the amount of relevant publications I come by on email updates and following references from other articles is overwhelming. There are tons of tools for bibliography management, I don't want to reinvent the wheel, I wish this existed, but I haven't found anything that solves my exact problem.

The core of the issue is that I loose track of all the different branches of research I'm doing, because they all pile up in the same place. If I'm reading an article and I select 5 references that I want to follow up on, they get on top of the pile, and next time I come by I tend to read the top ones. The issue is that other older to-read papers get buried so I tend to follow research in a snakey linear somewhat random way, instead of pushing different fronts rationally.

I want a graph dashboard where I can keep track of clusters of articles I've read, so I can see all the research topics at a glance and decide which to push on each session. I also want to keep proper track of the stuff I've read, which also tends to dissapear into the void.

Key features:
* Easily registering to-read papers.
* Clear distinction between read and to-read papers.
* Visual organization with clusters by topic and reference edges.
* One of the main axis should be time, the year of publication is very relevant.

Could use this as a base: https://github.com/TobLoef/text2mindmap
It would be enough to add hierarchy (a node links to another graph, zoom) and proper markdown support.

## Something with Scala

I've wanted to learn Scala for a while. I've read the documentation, but I forget about it, so I need a self contained project that motivates me to use Scala and dig deeper. I don't know what I will make, but making a DNS server keeps popping into my mind for some reason.

## Get into Reinforcement Learning

I have a good base of classical Machine Learning and I am decently updated on the progress of Deep Learning, but Reinforcement Learning has escaped my eye. I want to get into it, probably by watching an introductory lecture first, there's plenty of very good ones around. I am not so interested in movement agents that act in physical simulations such as games, even if they seem to be the main focus of the field. I've never been too interested in robotics and it extends to this area too. However, I am rather interested in applying RL to NLP and in keeping on top of the first steps that are being done towards General Inteligence, where they train RL agents to interact with the environment through text, like a chat bot or a player of Interactive Fiction games.

**Edit:** [This](http://www.wildml.com/2018/02/introduction-to-learning-to-trade-with-reinforcement-learning/?utm_campaign=Revue%20newsletter&utm_medium=Newsletter&utm_source=The%20Wild%20Week%20in%20AI) popped up in my inbox a few weeks back. Actually, automatic crypto traiding might also be an interesting topic to get into. This very much ties into my "money making machine" project.

## Text based game

Now and then I get really excited about this and then I abandon it. This is a very ambitious project with revatively low return, but I love it.

From Dwarf Fortress and Cataclysim we know that not having graphics (or really simple graphics) enables the creation of incredibly deep and complex games. It is simply much cheaper to add features so these games achieve a state where the developer has thought of every possible interaction, which makes these sandbox games, ironically, feel really life-like and bottomless, despite the lack of proper graphics.

However, I've searched and searched, and I have not yet found an equivalent game which is focused on story, decision making and worldbuilding. My thinking is, that doing away with graphics opens the door to huge open worlds, complex branching stories and actual meaninful choice, instead of the ilusion of it. And yes, I have looked deep into Interactive Fiction, MUD, MUSH and all the rest. Interactive Fiction tends to be linear, very puzzle heavy (much like point n' clicks) and most of them are not that big. MUDs are more like rogue-likes like Cataclysm, where combat and stats are the main focus. MUSHs can come close to what I want, they are often big open virtual worlds full of complex lore, but they are all about role-playing multiplayer social play; which is awesome, but not what I'm talking about.

From the Choice of Games brand, I have discovered that text games can be made to feel more life-like than any other gendre in terms of decision making if the back-end is offuscated. Even if the internal logic is incredibly simple, if choices are offuscated enough, players end up relying on their common sense and world knowledge instead of trying to get the best dice rolls. This is extremely satisfying as it has made me feel like I'm taking real world decisions, because the consequences are hidden and unpredictable, although fair and logical. Very grey decisions, nothing like the "good" and "bad" choices in something like Mass Effect.

I would like to make an open world game focused on what makes text shine. I don't want to attempt simulating game objects or combat. I want a game where knowledge is the currency for progression. Nothing is locked, you just need to go to the right NPC and ask the right question or give the right information in exchange. This is demostrated to be very enjoyable by games like Her Story. Fallen London and it's successor, Sunless Sea, also use knowledge as items and currency, although in a very different way; more gamey than I would like, but smart. My biggest influence here is Event[0], which uses knowledge bases to interpret questions and keep track of knowledge items in a concrete but in a hidden manner; a good compromise.

Most importantly, I want this game to be collaborative. I need it to be so, for it to be big. I envision the game itself as a singleplayer game, but I want a community around it building the world, the people and the stories in it, constantly expanding. Very much like a wiki. This means that there will be a point in the project where I will need to focus on awareness, documentation and a very intuitive toolset to extend the game without needing coding skills. I want this to be the heaven for worldbuilders. The best analogy I can think of is being a writer in the Westworld park. I want to replicate that fantasy.

## Fast N-gram index

Implement a fast in-memory N-gram index, as I cannot find one already implemented. I will probably make it with Cython. The obvious application is to perform fast fuzzy matching on a predetermined set of strings.

## Get into Cryptocurrency Arbitrage

I've previously thought about getting into crypto trading from a Deep Learning standpoint, which I'm more familiar with. But arbitrage actually sounds more approachable, and fun, to start with. Just find a market with a good API and start prototyping something.

https://blog.evjang.com/2018/08/dijkstras.html

## Command line performance monitoring dashboard

It is so often that I find myself with a dozen terminals open while diagnosing bottlnecks of large-scale data engineering processes. htop, iotop, nethogs, slurm, top (for usr/kernel/idle/wait numbers), a couple of watch commands to monitor file sizes and directories, the progress bar of the process... I'm a fan of netdata, but setup is not trivial, it is web based, it is lacking on single process stats and it is not build to have all relevant metrics in front of you at the same time.

I just want to build a simple command line dashboard like htop or slurm with all (most) the relevant metrics to diagnose bottlenecks in front of you (Network, Disk I/O, CPU, Memory, File cache, Swap, heavy malloc/free/gc...). Just on a single machine is enough for this project, not on a cluster. It will be a fun exercise in command line UI.
