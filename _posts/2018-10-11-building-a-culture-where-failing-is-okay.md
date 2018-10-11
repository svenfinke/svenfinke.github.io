---
layout: post
published: false
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
- Boyscouting: Refactor code if you hit something that is bad. Build up knowledge about code that you have not written
- Improve upon tests: Everyone should write tests and also write tests

