---
layout: post
published: true
title: Building a culture where failing is okay
subtitle: And nobody will get fired because prod is down
tags: coding culture
---
In Germany we established a culture where we have to blame someone if failures happen. Something went wrong on production and something has written that code, that person is probably the one that has to take the responsibility for this and live with the consequences. I for myself nearly got fired once because there was a critical bug that the customer complained about. My boss had to take some kind of action so I got an adhortatory letter so that something like that does not happen again.

The problem with this: Everyone is making mistakes and sometimes they hit something critical. Taking these heavy measures and punishing the one responsible will only create an environment of fear and if something goes wrong, everyone will try to hide this and fix this silently without anyone noticing. This is a very toxic situation that you don't want to end up in.

## Proper handling of mistakes

There should always be a team responsible for a product. If something goes horribly wrong, the team has to take responsibility, they have to fix this. They work together and will try to fix this situation as good and as quick as possible. And they will make sure that something like that does not happen again.

What is the difference now? First of all: Nobody is in the danger of being fired. The team is working together to solve the issue and to get things right again. Nobody needs to try to hide failures, escalating a bug to the whole team will only result in more people trying to fix the thing, not in someone being blamed.

If the situation is resolved, let the case rest for at least a day. Then have a "post-mortem" meeting about this. Why did this happen? How can you prevent this in the future? Important: It's not about: 'Jimmy did not check his if-condition!', but about 'The faulty if-condition made it to production, how can we improve Code Reviews so cover this? Why was no test failing?'. It is not about the 'Who', but about the 'Why'!

## Early shared responsibility

Code Reviews are a good way spread the responsibility among multiple people. Even if you are still in the mindset of blaming the responsible developers, you now have to blame at least 2 devlopers as someone did a review and the faulty code was not discovered. This can be a good way to establish a new mindset.

But there are other things that you can do:

- Spread knowledge among the team: Try not to create "experts" for specific parts of your project
- Boyscouting: Refactor code if you hit something that is bad. This will also help you to build up knowledge about code that you have not written
- Improve tests: Everyone should write tests, not only for "their own" code
- Pair programming: Do hard things together. This is also great to get new people into the codebase
- Post Mortem: If something went really wrong, talk about that afterwards. Find ways to prevent this in the future

## Nobody is responsible? ANARCHY!

It can be hard to really make that shift. Especially managers tend to stick to the old system and they try to hold single persons accountable for mistakes. If they suddenly can't do that because the whole team is responsible, they do have a problem. They can't fire them all. But this is not necessary at all. If the teammembers are proud of what they build, if they are interested in making it as good and stable as possible, then this is enough to keep them going.
Even if something went awfully wrong, they are most probably well aware of that and they will make sure that this is not happening again. The key at this point is motivation. Screaming at somebody, threatening them to get fired or blaming them in front of the whole company is not motivating anybody.

## TLDR;

Think about the "Why" or "What" when something goes wrong, not "Who". Blaming someone is not fixing the problem nor does it help to prevent this in the future. Bring the team together and create a working atmosphere where everyone is proud of what they create. Failures are chances to improve your application. If a failure is handled in the right way, then it will never happen again.
