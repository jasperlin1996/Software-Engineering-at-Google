**CHAPTER** **2**

# How to Work Well on Teams 

# 第二章 如何进行团队协作

​																											**Written by Brian Fitzpatrick Edited by Riona MacNamara**

Because this chapter is about the cultural and social aspects of software engineering at Google, it makes sense to begin by focusing on the one variable over which you definitely have control: you.

因为本章是从文化和社会方面来介绍谷歌软件工程，首先从焦距与一个你完全控制的变量开始：你自己。

People are inherently imperfect—we like to say that humans are mostly a collection of intermittent bugs. But before you can understand the bugs in your coworkers, you need to understand the bugs in yourself. We’re going to ask you to think about your own reactions, behaviors, and attitudes—and in return, we hope you gain some real insight into how to become a more efficient and successful software engineer who spends less energy dealing with people-related problems and more time writing great code.

人天生是不完美的——我们常说，人类大多是一个个不同缺陷的组成集合。但是，在你了解同事身上的缺陷之前，你需要了解自己身上的缺陷。我们将要求你反思自己的反应、行为和态度——作为回报，我们希望你能够真正了解如何成为一名更高效、更成功的软件工程师，减少处理与人相关的问题的精力，花更多的时间编写牛逼的代码。

The critical idea in this chapter is that software development is a team endeavor. And to succeed on an engineering team—or in any other creative collaboration—you need to reorganize your behaviors around the core principles of humility, respect, and trust.

本章的关键思想是，软件开发是团队的努力。要在工程团队或任何其他创造性合作中取得成功，你需要围绕谦逊、尊重和信任的核心原则重新定义你的行为。

Before we get ahead of ourselves, let’s begin by observing how software engineers tend to behave in general.

在我们超越自己之前，让我们首先观察软件工程师的一般行为。

## Help Me Hide My Code
For the past 20 years, my colleague Ben1 and I have spoken at many programming conferences. In 2006, we launched Google’s (now deprecated) open source Project Hosting service, and at first, we used to get lots of questions and requests about the product. But around mid-2008, we began to notice a trend in the sort of requests we were getting:
	“Can you please give Subversion on Google Code the ability to hide specific branches?”
	“Can you make it possible to create open source projects that start out hidden to the world and then are revealed when they’re ready?”
	“Hi, I want to rewrite all my code from scratch, can you please wipe all the history?”
Can you spot a common theme to these requests?

在过去的20年里，我和我的同事Ben在很多编程会议上演讲。 在2006年，我们推出了 Google的开源项目托管服务（现已弃用），在开始时，我们收到很多关于该产品的问题和请求。但到了2008年年中左右，我们发现，我们收到的请求中很多是这样的：

​	“你能否让Google Code上的 Subversion能够隐藏指定分支？” 

​	“你能否让创建的开源项目开始时对外隐藏，在它们准备好后再公开？” 

​	“嗨，我想从头开始重构我所有的代码，你能把所有的历史记录都删除吗？”

你能找出这些要求的共同点吗？

The answer is insecurity. People are afraid of others seeing and judging their work in progress. In one sense, insecurity is just a part of human nature—nobody likes to be criticized, especially for things that aren’t finished. Recognizing this theme tipped us off to a more general trend within software development: insecurity is actually a symptom of a larger problem.

答案是缺乏安全感。人们害怕别人看到和评价他们正在进行的工作。从某种意义上说，缺乏安全感是人性的一部分——没有人喜欢被批评，尤其是那些没有完成的事情。认识到这个主题让我们看到了软件开发中一个更普遍的趋势：缺乏安全实际上是一个更大问题的征兆。



## The Genius Myth天才的神话
Many humans have the instinct to find and worship idols. For software engineers, those might be Linus Torvalds, Guido Van Rossum, Bill Gates—all heroes who changed the world with heroic feats. Linus wrote Linux by himself, right?

许多人有寻找和崇拜偶像的本能。对于软件工程师来说，他们可能是Linus Torvalds, Guido Van Rossum, Bill Gates——他们都是改变世界的英雄。是Linus自己写的Linux？

Actually, what Linus did was write just the beginnings of a proof-of-concept Unix- like kernel and show it to an email list. That was no small accomplishment, and it was definitely an impressive achievement, but it was just the tip of the iceberg. Linux is hundreds of times bigger than that initial kernel and was developed by thousands of smart people. Linus’ real achievement was to lead these people and coordinate their work; Linux is the shining result not of his original idea, but of the collective labor of the community. (And Unix itself was not entirely written by Ken Thompson and Dennis Ritchie, but by a group of smart people at Bell Labs.)

实际上，Linus所做的只是编写了概念验证类Unix内核的开头，并将电子邮件发送出去。这是不小的成就，绝对是一个令人印象深刻的成就，但这只是冰山一角。Linux比最初的内核大几百倍，是由成千上万的聪明人开发的。Linus真正的成就是领导并协调他们的完成工作；Linux不仅仅是他最初创意的成果，更是社区集体努力的成果。（Unix本身并非完全由肯·汤普森和丹尼斯·里奇编写，而是由贝尔实验室的一群聪明人编写的。）

On that same note, did Guido Van Rossum personally write all of Python? Certainly, he wrote the first version. But hundreds of others were responsible for contributing to subsequent versions, including ideas, features, and bug fixes. Steve Jobs led an entire team that built the Macintosh, and although Bill Gates is known for writing a BASIC interpreter for early home computers, his bigger achievement was building a successful company around MS-DOS. Yet they all became leaders and symbols of the collective achievements of their communities. The Genius Myth is the tendency that we as humans need to ascribe the success of a team to a single person/leader.

同样，Guido Van Rossum是否亲自编写了所有Python？当然，他写了第一个版本。但还有数百人为后续版本做出贡献，包括想法、功能和bug修复。史蒂夫·乔布斯领导了一个建造麦金塔的整个团队，尽管比尔·盖茨以为早期家用电脑编写BASIC解释器而闻名，但他更大的成就是围绕MS-DOS系统建立了一家成功的公司。然而，他们都成为集体成就的领袖和象征。天才的神话是一种趋势，即我们需要将团队的成功归因于一个人/领导者。

And what about Michael Jordan?
It’s the same story. We idolized him, but the fact is that he didn’t win every basketball game by himself. His true genius was in the way he worked with his team. The team’s coach, Phil Jackson, was extremely clever, and his coaching techniques are legendary.

那么Michael Jordan呢？

这是同一个故事。我们崇拜他，但事实是他并不是一个人赢得每一场篮球比赛的。他真正的牛逼在于他与团队合作的方式。这支球队的教练Phil Jackson非常聪明，他的教练技术堪称传奇。

He recognized that one player alone never wins a championship, and so he assembled an entire “dream team” around MJ. This team was a well-oiled machine—at least as impressive as Michael himself.

他认识到只有一个球员永远无法赢得冠军，因此他围绕Michael Jordan组建了一支完美的“梦之队”。这支球队是一台运转良好的机器——至少和迈克尔本人一样令人印象深刻。

So, why do we repeatedly idolize the individual in these stories? Why do people buy products endorsed by celebrities? Why do we want to buy Michelle Obama’s dress or Michael Jordan’s shoes?

那么，为什么我们在这些故事中一再崇拜个人呢？为什么人们会购买名人代言的产品？我们为什么要买米歇尔·奥巴马的裙子或Michael Jordan的鞋子？

Celebrity is a big part of it. Humans have a natural instinct to find leaders and role models, idolize them, and attempt to imitate them. We all need heroes for inspiration, and the programming world has its heroes, too. The phenomenon of “techie- celebrity” has almost spilled over into mythology. We all want to write something world-changing like Linux or design the next brilliant programming language.

名人效应是一个重要原因。人类有寻找领导者和榜样的本能，崇拜他们，并试图模仿他们。我们都需要英雄来激发灵感，编程世界也有自己的英雄。“科技名人”已经几乎被神化，我们都想写一些改变世界的东西，比如Linux或者设计下一种优秀的编程语言。

Deep down, many engineers secretly wish to be seen as geniuses. This fantasy goes something like this:
•	You are struck by an awesome new concept.
•	You vanish into your cave for weeks or months, slaving away at a perfect implementation of your idea.
•	You then “unleash” your software on the world, shocking everyone with your genius.
•	Your peers are astonished by your cleverness.
•	People line up to use your software.
•	Fame and fortune follow naturally.

在内心深处，许多工程师暗中希望被视为天才。这种幻想是这样的：

- 您会被一个了不起的新概念所震撼。
- 你消失数周或数月躲在洞穴中，努力实现你的理想。
- 然后世界上“发布”你的软件，用你的天才震撼每个人。
- 你的同龄人对你的聪明感到惊讶。
- 人们排队使用你的软件。
- 名利自然随之而来。

But hold on: time for a reality check. You’re probably not a genius.

是时候回归现实了。你很可能不是天才。

No offense, of course—we’re sure that you’re a very intelligent person. But do you realize how rare actual geniuses really are? Sure, you write code, and that’s a tricky skill. But even if you are a genius, it turns out that that’s not enough. Geniuses still make mistakes, and having brilliant ideas and elite programming skills doesn’t guarantee that your software will be a hit. Worse, you might find yourself solving only analytical problems and not human problems. Being a genius is most definitely not an excuse for being a jerk: anyone—genius or not—with poor social skills tends to be a poor teammate. The vast majority of the work at Google (and at most companies!) doesn’t require genius-level intellect, but 100% of the work requires a minimal level of social skills. What will make or break your career, especially at a company like Google, is how well you collaborate with others.

无意冒犯，我们当然相信你是个非常聪明的人。但你要知道真正的天才有多稀有吗？当然，你需要编写代码，这是一项棘手的技能。即使你是个天才，会编程还不够。天才仍然会犯错误，拥有卓越的想法和精英编程技能并不能保证你的软件会大受欢迎。更糟糕的是，你可能会发现自己只解决了分析性问题，而没有解决人的问题。作为一个天才绝对不是成为一个混蛋的借口： 天才与否，社交能力差的人，往往是一个猪队友。谷歌（以及大多数公司！）的绝大多数工作不需要天才水平的智力，但100%的工作需要最低水平的社交技能。决定你职业生涯成败，尤其是在谷歌这样的公司，更取决于你与他人合作的程度。

It turns out that this Genius Myth is just another manifestation of our insecurity. Many programmers are afraid to share work they’ve only just started because it means peers will see their mistakes and know the author of the code is not a genius.

事实证明，这种天才神话只是我们缺乏安全感的另一种表现。许多程序员害怕分享他们刚刚开始的工作，因为这意味着同行会看到他们的错误，知道代码的作者不是天才。

To quote a friend:
	*I know I get SERIOUSLY insecure about people looking before something is done. Like they are going to seriously judge me and think I’m an idiot.*

引用一位朋友的话：

​	*我知道，别人在我完成某事之前就来看，会让我感到非常不安全。好像他们会认真地评判我，认为我是个白痴。*

This is an extremely common feeling among programmers, and the natural reaction is to hide in a cave, work, work, work, and then polish, polish, polish, sure that no one will see your goof-ups and that you’ll still have a chance to unveil your masterpiece when you’re done. Hide away until your code is perfect.

这是程序员群体中非常普遍的感觉，第一反应就是躲到山洞里，工作，工作，努力工作，然后打磨，打磨，再打磨，确定没有人会看到你的错误后，当你完成后，你才会揭开你的作品面纱。躲起来吧，直到你的代码变得完美。

Another common motivation for hiding your work is the fear that another programmer might take your idea and run with it before you get around to working on it. By keeping it secret, you control the idea.

隐藏工作的另一个常见动机是担心另一个程序员可能会在你开始工作之前就拿着你的想法跑了。通过保密，你可以控制这个想法。

We know what you’re probably thinking now: so what? Shouldn’t people be allowed to work however they want?
Actually, no. In this case, we assert that you’re doing it wrong, and it is a big deal. Here’s why.

我们知道你现在在想什么：那又怎样？难道不应该允许我随心所欲地工作吗？

事实上，不应该。在这种情况下，我们断定你错了，很是一个大错误。原因如下。



## Hiding Considered Harmful 隐藏不利
If you spend all of your time working alone, you’re increasing the risk of unnecessary failure and cheating your potential for growth. Even though software development is deeply intellectual work that can require deep concentration and alone time, you must play that off against the value (and need!) for collaboration and review.

如果你把所有的时间都花在独自工作上，增加了不必要失败的风险，耽误了你的成长潜力。尽管软件开发是一项需要高度集中精力和独处时间的深度智力工作，但你必须权衡协作和审查的价值（以及需求！）。

First of all, how do you even know whether you’re on the right track?

首先，你怎么知道自己是否在正确的轨道上？

Imagine you’re a bicycle-design enthusiast, and one day you get a brilliant idea for a completely new way to design a gear shifter. You order parts and proceed to spend weeks holed up in your garage trying to build a prototype. When your neighbor— also a bike advocate—asks you what’s up, you decide not to talk about it. You don’t want anyone to know about your project until it’s absolutely perfect. Another few months go by and you’re having trouble making your prototype work correctly. But because you’re working in secrecy, it’s impossible to solicit advice from your mechanically inclined friends.

想象一下，你是一个自行车设计爱好者，有一天你有了一个牛逼的想法，可以用一种全新的方式来设计变速器。你订购零件，然后花数周时间躲在车库里，尝试制造一个原型。当你的邻居——也是自行车倡导者——问你怎么了，你决定闭口不谈。你不想让任何人知道你的项目，直到它绝对完美。又过几个月，你在让原型运行时遇到了麻烦。但因为你是在保密的情况下工作，所以不可能征求你那些有机械专家朋友的意见。

Then, one day your neighbor pulls his bike out of his garage with a radical new gear- shifting mechanism. Turns out he’s been building something very similar to your invention, but with the help of some friends down at the bike shop. At this point, you’re exasperated. You show him your work. He points out that your design had some simple flaws—ones that might have been fixed in the first week if you had shown him. There are a number of lessons to learn here.

然后，有一天，你的邻居将他的自行车从车库中拉出，这辆自行车使用一种全新的换档机构。事实表明，他也在制造一些与你的发明非常相似的东西，但是他得到了自行车店的一些朋友的帮助。这时候，你很生气。你给他看你的原型。他指出，你的设计有一些简单的缺陷，如果你给他看的话，这些缺陷可能在第一周就被修复了。这里有许多教训要学习。

### Early Detection 提早发现
If you keep your great idea hidden from the world and refuse to show anyone anything until the implementation is polished, you’re taking a huge gamble. It’s easy to make fundamental design mistakes early on. You risk reinventing wheels.2 And you forfeit the benefits of collaboration, too: notice how much faster your neighbor moved by working with others? This is why people dip their toes in the water before jumping in the deep end: you need to make sure that you’re working on the right thing, you’re doing it correctly, and it hasn’t been done before. The chances of an early misstep are high. The more feedback you solicit early on, the more you lower this risk.3 Remember the tried-and-true mantra of “Fail early, fail fast, fail often.”

如果你对世界隐瞒你的牛逼想法，并在未完美之前拒绝向任何人展示，那么你就是在进行一场下注巨大的赌博。早期很容易犯基本的设计错误。你冒着重新发明轮子的风险。2而且你也失去了协作的好处：注意到你的邻居通过与他人合作而效率有多高？这就是人们在跳入深水区之前将脚趾浸入水中的原因：你需要确保你在做正确的事情，你在做正确的事情，而且以前从未做过。早期失误的可能性很高。你越早征求反馈，这种风险就越低。3记住“早失败、快失败、经常失败”这句经得起考验的至理名言。

Early sharing isn’t just about preventing personal missteps and getting your ideas vetted. It’s also important to strengthen what we call the bus factor of your project.

早期分享不仅仅是为了防止个人失误和检验你的想法。加强我们称之为项目的巴士因子。



### The Bus Factor 巴士因子
Bus factor (noun): the number of people that need to get hit by a bus before your project is completely doomed.
How dispersed is the knowledge and know-how in your project? If you’re the only person who understands how the prototype code works, you might enjoy good job security—but if you get hit by a bus, the project is toast. If you’re working with a colleague, however, you’ve doubled the bus factor. And if you have a small team designing and prototyping together, things are even better—the project won’t be marooned when a team member disappears. Remember: team members might not literally be hit by buses, but other unpredictable life events still happen. Someone might get married, move away, leave the company, or take leave to care for a sick relative. Ensuring that there is at least good documentation in addition to a primary and a secondary owner for each area of responsibility helps future-proof your project’s success and increases your project’s bus factor. Hopefully most engineers recognize that it is better to be one part of a successful project than the critical part of a failed project.
Beyond the bus factor, there’s the issue of overall pace of progress. It’s easy to forget that working alone is often a tough slog, much slower than people want to admit. How much do you learn when working alone? How fast do you move? Google and Stack Overflow are great sources of opinions and information, but they’re no substitute for actual human experience. Working with other people directly increases the collective wisdom behind the effort. When you become stuck on something absurd, how much time do you waste pulling yourself out of the hole? Think about how

```
2	Literally, if you are, in fact, a bike designer.
3	I should note that sometimes it’s dangerous to get too much feedback too early in the process if you’re still unsure of your general direction or goal.
```

different the experience would be if you had a couple of peers to look over your shoulder and tell you—instantly—how you goofed and how to get past the problem. This is exactly why teams sit together (or do pair programming) in software engineering companies. Programming is hard. Software engineering is even harder. You need that second pair of eyes.
### Pace of Progress
Here’s another analogy. Think about how you work with your compiler. When you sit down to write a large piece of software, do you spend days writing 10,000 lines of code, and then, after writing that final, perfect line, press the “compile” button for the very first time? Of course you don’t. Can you imagine what sort of disaster would result? Programmers work best in tight feedback loops: write a new function, compile. Add a test, compile. Refactor some code, compile. This way, we discover and fix typos and bugs as soon as possible after generating code. We want the compiler at our side for every little step; some environments can even compile our code as we type. This is how we keep code quality high and make sure our software is evolving correctly, bit by bit. The current DevOps philosophy toward tech productivity is explicit about these sorts of goals: get feedback as early as possible, test as early as possible, and think about security and production environments as early as possible. This is all bundled into the idea of “shifting left” in the developer workflow; the earlier we find a problem, the cheaper it is to fix it.
The same sort of rapid feedback loop is needed not just at the code level, but at the whole-project level, too. Ambitious projects evolve quickly and must adapt to changing environments as they go. Projects run into unpredictable design obstacles or political hazards, or we simply discover that things aren’t working as planned. Requirements morph unexpectedly. How do you get that feedback loop so that you know the instant your plans or designs need to change? Answer: by working in a team. Most engineers know the quote, “Many eyes make all bugs shallow,” but a better version might be, “Many eyes make sure your project stays relevant and on track.” People working in caves awaken to discover that while their original vision might be complete, the world has changed and their project has become irrelevant.

------

**Case Study: Engineers and Offices**
Twenty-five years ago, conventional wisdom stated that for an engineer to be produc‐
tive, they needed to have their own office with a door that closed. This was suppos‐
edly the only way they could have big, uninterrupted slabs of time to deeply
concentrate on writing reams of code.
I think that it’s not only unnecessary for most engineers4 to be in a private office, it’s downright dangerous. Software today is written by teams, not individuals, and a high- bandwidth, readily available connection to the rest of your team is even more valuable than your internet connection. You can have all the uninterrupted time in the world, but if you’re using it to work on the wrong thing, you’re wasting your time.
Unfortunately, it seems that modern-day tech companies (including Google, in some cases) have swung the pendulum to the exact opposite extreme. Walk into their offices and you’ll often find engineers clustered together in massive rooms—a hundred or more people together—with no walls whatsoever. This “open floor plan” is now a topic of huge debate and, as a result, hostility toward open offices is on the rise. The tiniest conversation becomes public, and people end up not talking for risk of annoying dozens of neighbors. This is just as bad as private offices!
We think the middle ground is really the best solution. Group teams of four to eight people together in small rooms (or large offices) to make it easy (and non- embarrassing) for spontaneous conversation to happen.
Of course, in any situation, individual engineers still need a way to filter out noise and interruptions, which is why most teams I’ve seen have developed a way to communicate that they’re currently busy and that you should limit interruptions. Some of us used to work on a team with a vocal interrupt protocol: if you wanted to talk, you would say “Breakpoint Mary,” where Mary was the name of the person you wanted to talk to. If Mary was at a point where she could stop, she would swing her chair around and listen. If Mary was too busy, she’d just say “ack,” and you’d go on with other things until she finished with her current head state.
Other teams have tokens or stuffed animals that team members put on their monitor to signify that they should be interrupted only in case of emergency. Still other teams give out noise-canceling headphones to engineers to make it easier to deal with background noise—in fact, in many companies, the very act of wearing headphones is a common signal that means “don’t disturb me unless it’s really important.” Many engineers tend to go into headphones-only mode when coding, which may be useful for short spurts but, if used all the time, can be just as bad for collaboration as walling yourself off in an office.
Don’t misunderstand us—we still think engineers need uninterrupted time to focus on writing code, but we think they need a high-bandwidth, low-friction connection to their team just as much. If less-knowledgeable people on your team feel that there’s a barrier to asking you a question, it’s a problem: finding the right balance is an art.

------

```
4	I do, however, acknowledge that serious introverts likely need more peace, quiet, and alone time than most people and might benefit from a quieter environment, if not their own office.
```

### In Short, Don’t Hide

So, what “hiding” boils down to is this: working alone is inherently riskier than working with others. Even though you might be afraid of someone stealing your idea or thinking you’re not intelligent, you should be much more concerned about wasting huge swaths of your time toiling away on the wrong thing.

Don’t become another statistic.

## It’s All About the Team
So, let’s back up now and put all of these ideas together.
The point we’ve been hammering away at is that, in the realm of programming, lone craftspeople are extremely rare—and even when they do exist, they don’t perform superhuman achievements in a vacuum; their world-changing accomplishment is almost always the result of a spark of inspiration followed by a heroic team effort.
A great team makes brilliant use of its superstars, but the whole is always greater than the sum of its parts. But creating a superstar team is fiendishly difficult.
Let’s put this idea into simpler words: software engineering is a team endeavor.
This concept directly contradicts the inner Genius Programmer fantasy so many of us hold, but it’s not enough to be brilliant when you’re alone in your hacker’s lair. You’re not going to change the world or delight millions of computer users by hiding and preparing your secret invention. You need to work with other people. Share your vision. Divide the labor. Learn from others. Create a brilliant team.
Consider this: how many pieces of widely used, successful software can you name that were truly written by a single person? (Some people might say “LaTeX,” but it’s hardly “widely used,” unless you consider the number of people writing scientific papers to be a statistically significant portion of all computer users!)
High-functioning teams are gold and the true key to success. You should be aiming for this experience however you can.

### The Three Pillars of Social Interaction
So, if teamwork is the best route to producing great software, how does one build (or find) a great team?
To reach collaborative nirvana, you first need to learn and embrace what I call the “three pillars” of social skills. These three principles aren’t just about greasing the wheels of relationships; they’re the foundation on which all healthy interaction and collaboration are based:
*Pillar 1: Humility*
	You are not the center of the universe (nor is your code!). You’re neither omniscient nor infallible. You’re open to self-improvement.
*Pillar 2: Respect*
	You genuinely care about others you work with. You treat them kindly and appreciate their abilities and accomplishments.
*Pillar 3: Trust*
	You believe others are competent and will do the right thing, and you’re OK with letting them drive when appropriate.5

If you perform a root-cause analysis on almost any social conflict, you can ultimately trace it back to a lack of humility, respect, and/or trust. That might sound implausible at first, but give it a try. Think about some nasty or uncomfortable social situation currently in your life. At the basest level, is everyone being appropriately humble? Are people really respecting one another? Is there mutual trust?
### Why Do These Pillars Matter?
When you began this chapter, you probably weren’t planning to sign up for some sort of weekly support group. We empathize. Dealing with social problems can be difficult: people are messy, unpredictable, and often annoying to interface with. Rather than putting energy into analyzing social situations and making strategic moves, it’s tempting to write off the whole effort. It’s much easier to hang out with a predictable compiler, isn’t it? Why bother with the social stuff at all?
Here’s a quote from a famous lecture by Richard Hamming:
	By taking the trouble to tell jokes to the secretaries and being a little friendly, I got superb secretarial help. For instance, one time for some idiot reason all the reproducing services at Murray Hill were tied up. Don’t ask me how, but they were. I wanted something done. My secretary called up somebody at Holmdel, hopped [into] the company car, made the hour-long trip down and got it reproduced, and then came back. It was a payoff for the times I had made an effort to cheer her up, tell her jokes and be friendly; it was that little extra work that later paid off for me. By realizing you have to use the system and studying how to get the system to do your work, you learn how to adapt the system to your desires.

The moral is this: do not underestimate the power of playing the social game. It’s not about tricking or manipulating people; it’s about creating relationships to get things done. Relationships always outlast projects. When you’ve got richer relationships with your coworkers, they’ll be more willing to go the extra mile when you need them.

```
5	This is incredibly difficult if you’ve been burned in the past by delegating to incompetent people.
```

### Humility, Respect, and Trust in Practice
All of this preaching about humility, respect, and trust sounds like a sermon. Let’s come out of the clouds and think about how to apply these ideas in real-life situations. We’re going to examine a list of specific behaviors and examples that you can start with. Many of them might sound obvious at first, but after you begin thinking about them, you’ll notice how often you (and your peers) are guilty of not following them—we’ve certainly noticed this about ourselves!

#### Lose the ego
OK, this is sort of a simpler way of telling someone without enough humility to lose their ’tude. Nobody wants to work with someone who consistently behaves like they’re the most important person in the room. Even if you know you’re the wisest person in the discussion, don’t wave it in people’s faces. For example, do you always feel like you need to have the first or last word on every subject? Do you feel the need to comment on every detail in a proposal or discussion? Or do you know somebody who does these things?
Although it’s important to be humble, that doesn’t mean you need to be a doormat; there’s nothing wrong with self-confidence. Just don’t come off like a know-it-all. Even better, think about going for a “collective” ego, instead; rather than worrying about whether you’re personally awesome, try to build a sense of team accomplishment and group pride. For example, the Apache Software Foundation has a long history of creating communities around software projects. These communities have incredibly strong identities and reject people who are more concerned with self- promotion.
Ego manifests itself in many ways, and a lot of the time, it can get in the way of your productivity and slow you down. Here’s another great story from Hamming’s lecture that illustrates this point perfectly (emphasis ours):
	John Tukey almost always dressed very casually. He would go into an important office and it would take a long time before the other fellow realized that this is a first-class man and he had better listen. For a long time, John has had to overcome this kind of hostility. It’s wasted effort! I didn’t say you should conform; I said, “The appearance of conforming gets you a long way.” If you chose to assert your ego in any number of ways, “I am going to do it my way,” you pay a small steady price throughout the whole of your professional career. And this, over a whole lifetime, adds up to an enormous amount of needless trouble. […] By realizing you have to use the system and studying how to get the system to do your work, you learn how to adapt the system to your desires. Or you can fight it steadily, as a small, undeclared war, for the whole of your life.


#### Learn to give and take criticism
A few years ago, Joe started a new job as a programmer. After his first week, he really began digging into the codebase. Because he cared about what was going on, he started gently questioning other teammates about their contributions. He sent simple code reviews by email, politely asking about design assumptions or pointing out places where logic could be improved. After a couple of weeks, he was summoned to his director’s office. “What’s the problem?” Joe asked. “Did I do something wrong?” The director looked concerned: “We’ve had a lot of complaints about your behavior, Joe. Apparently, you’ve been really harsh toward your teammates, criticizing them left and right. They’re upset. You need to tone it down.” Joe was utterly baffled. Surely, he thought, his code reviews should have been welcomed and appreciated by his peers. In this case, however, Joe should have been more sensitive to the team’s widespread insecurity and should have used a subtler means to introduce code reviews into the culture—perhaps even something as simple as discussing the idea with the team in advance and asking team members to try it out for a few weeks.
In a professional software engineering environment, criticism is almost never personal—it’s usually just part of the process of making a better project. The trick is to make sure you (and those around you) understand the difference between a constructive criticism of someone’s creative output and a flat-out assault against someone’s character. The latter is useless—it’s petty and nearly impossible to act on. The former can (and should!) be helpful and give guidance on how to improve. And, most important, it’s imbued with respect: the person giving the constructive criticism genuinely cares about the other person and wants them to improve themselves or their work. Learn to respect your peers and give constructive criticism politely. If you truly respect someone, you’ll be motivated to choose tactful, helpful phrasing—a skill acquired with much practice. We cover this much more in Chapter 9.
On the other side of the conversation, you need to learn to accept criticism as well. This means not just being humble about your skills, but trusting that the other person has your best interests (and those of your project!) at heart and doesn’t actually think you’re an idiot. Programming is a skill like anything else: it improves with practice. If a peer pointed out ways in which you could improve your juggling, would you take it as an attack on your character and value as a human being? We hope not. In the same way, your self-worth shouldn’t be connected to the code you write—or any creative project you build. To repeat ourselves: you are not your code. Say that over and over. You are not what you make. You need to not only believe it yourself, but get your coworkers to believe it, too.
For example, if you have an insecure collaborator, here’s what not to say: “Man, you totally got the control flow wrong on that method there. You should be using the standard xyzzy code pattern like everyone else.” This feedback is full of antipatterns: you’re telling someone they’re “wrong” (as if the world were black and white), demanding they change something, and accusing them of creating something that goes against what everyone else is doing (making them feel stupid). Your coworker will immediately be put on the offense, and their response is bound to be overly emotional.
A better way to say the same thing might be, “Hey, I’m confused by the control flow in this section here. I wonder if the xyzzy code pattern might make this clearer and easier to maintain?” Notice how you’re using humility to make the question about you, not them. They’re not wrong; you’re just having trouble understanding the code. The suggestion is merely offered up as a way to clarify things for poor little you while possibly helping the project’s long-term sustainability goals. You’re also not demanding anything—you’re giving your collaborator the ability to peacefully reject the suggestion. The discussion stays focused on the code itself, not on anyone’s value or coding skills.

#### Fail fast and iterate
There’s a well-known urban legend in the business world about a manager who makes a mistake and loses an impressive $10 million. He dejectedly goes into the office the next day and starts packing up his desk, and when he gets the inevitable “the CEO wants to see you in his office” call, he trudges into the CEO’s office and quietly slides a piece of paper across the desk.
“What’s this?” asks the CEO.
“My resignation,” says the executive. “I assume you called me in here to fire me.”
“Fire you?” responds the CEO, incredulously. “Why would I fire you? I just spent $10 million training you!”6
It’s an extreme story, to be sure, but the CEO in this story understands that firing the executive wouldn’t undo the $10 million loss, and it would compound it by losing a valuable executive who he can be very sure won’t make that kind of mistake again.
At Google, one of our favorite mottos is that “Failure is an option.” It’s widely recognized that if you’re not failing now and then, you’re not being innovative enough or taking enough risks. Failure is viewed as a golden opportunity to learn and improve for the next go-around.7 In fact, Thomas Edison is often quoted as saying, “If I find 10,000 ways something won’t work, I haven’t failed. I am not discouraged, because every wrong attempt discarded is another step forward.”
Over in Google X—the division that works on “moonshots” like self-driving cars and internet access delivered by balloons—failure is deliberately built into its incentive system. People come up with outlandish ideas and coworkers are actively encouraged to shoot them down as fast as possible. Individuals are rewarded (and even compete) to see how many ideas they can disprove or invalidate in a fixed period of time. Only when a concept truly cannot be debunked at a whiteboard by all peers does it proceed to early prototype.

```
6	You can find a dozen variants of this legend on the web, attributed to different famous managers.
7	By the same token, if you do the same thing over and over and keep failing, it’s not failure, it’s incompetence.
```
### Blameless Post-Mortem Culture
The key to learning from your mistakes is to document your failures by performing a root-cause analysis and writing up a “postmortem,” as it’s called at Google (and many other companies). Take extra care to make sure the postmortem document isn’t just a useless list of apologies or excuses or finger-pointing—that’s not its purpose. A proper postmortem should always contain an explanation of what was learned and what is going to change as a result of the learning experience. Then, make sure that the postmortem is readily accessible and that the team really follows through on the proposed changes. Properly documenting failures also makes it easier for other people (present and future) to know what happened and avoid repeating history. Don’t erase your tracks—light them up like a runway for those who follow you!
A good postmortem should include the following:
•	A brief summary of the event
•	A timeline of the event, from discovery through investigation to resolution
•	The primary cause of the event
•	Impact and damage assessment
•	A set of action items (with owners) to fix the problem immediately
•	A set of action items to prevent the event from happening again
•	Lessons learned

#### Learn patience
Years ago, I was writing a tool to convert CVS repositories to Subversion (and later, Git). Due to the vagaries of CVS, I kept unearthing bizarre bugs. Because my longtime friend and coworker Karl knew CVS quite intimately, we decided we should work together to fix these bugs.
A problem arose when we began pair programming: I’m a bottom-up engineer who is content to dive into the muck and dig my way out by trying a lot of things quickly and skimming over the details. Karl, however, is a top-down engineer who wants to get the full lay of the land and dive into the implementation of almost every method on the call stack before proceeding to tackle the bug. This resulted in some epic interpersonal conflicts, disagreements, and the occasional heated argument. It got to the point at which the two of us simply couldn’t pair-program together: it was too frustrating for us both.
That said, we had a longstanding history of trust and respect for each other. Combined with patience, this helped us work out a new method of collaborating. We would sit together at the computer, identify the bug, and then split up and attack the problem from two directions at once (top-down and bottom-up) before coming back together with our findings. Our patience and willingness to improvise new working styles not only saved the project, but also our friendship.
#### Be open to influence
The more open you are to influence, the more you are able to influence; the more vulnerable you are, the stronger you appear. These statements sound like bizarre contradictions. But everyone can think of someone they’ve worked with who is just maddeningly stubborn—no matter how much people try to persuade them, they dig their heels in even more. What eventually happens to such team members? In our experience, people stop listening to their opinions or objections; instead, they end up “routing around” them like an obstacle everyone takes for granted. You certainly don’t want to be that person, so keep this idea in your head: it’s OK for someone else to change your mind. In the opening chapter of this book, we said that engineering is inherently about trade-offs. It’s impossible for you to be right about everything all the time unless you have an unchanging environment and perfect knowledge, so of course you should change your mind when presented with new evidence. Choose your battles carefully: to be heard properly, you first need to listen to others. It’s better to do this listening before putting a stake in the ground or firmly announcing a decision—if you’re constantly changing your mind, people will think you’re wishy-washy.
The idea of vulnerability can seem strange, too. If someone admits ignorance of the topic at hand or the solution to a problem, what sort of credibility will they have in a group? Vulnerability is a show of weakness, and that destroys trust, right?
Not true. Admitting that you’ve made a mistake or you’re simply out of your league can increase your status over the long run. In fact, the willingness to express vulnerability is an outward show of humility, it demonstrates accountability and the willingness to take responsibility, and it’s a signal that you trust others’ opinions. In return, people end up respecting your honesty and strength. Sometimes, the best thing you can do is just say, “I don’t know.”
Professional politicians, for example, are notorious for never admitting error or ignorance, even when it’s patently obvious that they’re wrong or unknowledgeable about a subject. This behavior exists primarily because politicians are constantly under attack by their opponents, and it’s why most people don’t believe a word that politicians say. When you’re writing software, however, you don’t need to be continually on the defensive—your teammates are collaborators, not competitors. You all have the same goal.


### Being Googley
At Google, we have our own internal version of the principles of “humility, respect, and trust” when it comes to behavior and human interactions.
From the earliest days of our culture, we often referred to actions as being “Googley” or “not Googley.” The word was never explicitly defined; rather, everyone just sort of took it to mean “don’t be evil” or “do the right thing” or “be good to each other.” Over time, people also started using the term “Googley” as an informal test for culture-fit whenever we would interview a candidate for an engineering job, or when writing internal performance reviews of one another. People would often express opinions about others using the term; for example, “the person coded well, but didn’t seem to have a very Googley attitude.”
Of course, we eventually realized that the term “Googley” was being overloaded with meaning; worse yet, it could become a source of unconscious bias in hiring or evaluations. If “Googley” means something different to every employee, we run the risk of the term starting to mean “is just like me.” Obviously, that’s not a good test for hiring
—we don’t want to hire people “just like me,” but people from a diverse set of backgrounds and with different opinions and experiences. An interviewer’s personal desire to have a beer with a candidate (or coworker) should never be considered a valid signal about somebody else’s performance or ability to thrive at Google.
Google eventually fixed the problem by explicitly defining a rubric for what we mean by “Googleyness”—a set of attributes and behaviors that we look for that represent strong leadership and exemplify “humility, respect, and trust”:
*Thrives in ambiguity*
	Can deal with conflicting messages or directions, build consensus, and make progress against a problem, even when the environment is constantly shifting.
*Values feedback*
	Has humility to both receive and give feedback gracefully and understands how valuable feedback is for personal (and team) development.
*Challenges status quo*
	Is able to set ambitious goals and pursue them even when there might be resistance or inertia from others.
*Puts the user first*
	Has empathy and respect for users of Google’s products and pursues actions that are in their best interests.
*Cares about the team*
	Has empathy and respect for coworkers and actively works to help them without being asked, improving team cohesion.
*Does the right thing*
	Has a strong sense of ethics about everything they do; willing to make difficult or inconvenient decisions to protect the integrity of the team and product.


Now that we have these best-practice behaviors better defined, we’ve begun to shy away from using the term “Googley.” It’s always better to be specific about expectations!

## Conclusion
The foundation for almost any software endeavor—of almost any size—is a well- functioning team. Although the Genius Myth of the solo software developer still persists, the truth is that no one really goes it alone. For a software organization to stand the test of time, it must have a healthy culture, rooted in humility, trust, and respect that revolves around the team, rather than the individual. Further, the creative nature of software development requires that people take risks and occasionally fail; for people to accept that failure, a healthy team environment must exist.

## TL;DRs
•	Be aware of the trade-offs of working in isolation.
•	Acknowledge the amount of time that you and your team spend communicating and in interpersonal conflict. A small investment in understanding personalities and working styles of yourself and others can go a long way toward improving productivity.
•	If you want to work effectively with a team or a large organization, be aware of your preferred working style and that of others.










