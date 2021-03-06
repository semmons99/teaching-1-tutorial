# Mentoring an RMU Session

So, you've volunteered to mentor a session at RMU and Greg has accepted you, congratulations. You have a lot of work ahead of you, and just as when you took the Core Skills course yourself, you're going to get out what you put in. One thing the mentors coming before you and I would like to stress is to treat the mentees with respect. They are your peers and future fellow alumni. We all remember how difficult and challenging the core course was; make sure you help them, not hinder them.

## Communication Channels

I'm going to assume since you agreed to mentor, that you're willing to put a good chunk of time aside to help your mentees. However, most of us have work, school, etc. throughout the week and cannot dedicate the same time Greg does. Don't worry about it; whatever time you give to your mentees will be helpful.

So, the first thing to think of when mentoring is to decide upon your communication channels that you will frequent. RMU has three major communication channels as of this writing: IRC, mailing lists and university-web. I suggest trying to only focus on one or two communication channels while mentoring so you do not get overwhelmed. You should make yourself flexible so that you can help students who use any of the communication channels; but by declaring up front the best way to contact you is, for example, the mailing list, you can hopefully get more students contacting you via your preferred method and will send less time managing communications then mentoring.

### IRC

To successfully mentor students on IRC you're going to have to develop a plan. You should either declare office hours, much like Greg, or lurk throughout the day and have a good alert when someone pings you. I wouldn't suggest making IRC your primary contact point do to potential time differences between yourself and the mentees. One final tip regarding IRC. If you plan on being on IRC a lot, make sure to engage with the students, even when they're not asking for help. Ask them how it's going on an assignment, where they're from, etc. IRC can be a much more intimate setting for discussions than any of the other communication channels; so it is important to mindful of this.

### Mailing lists

In all of the sessions I've been in, whether as a student or a mentor, the mailing list has always become the primary communications channel between everyone. It combines the threaded discussions and activity log of university-web with the more intimate nature of IRC. Mentoring on the mailing list isn't difficult, but I do have some tips that have helped me. First, use and email client that manages threads. This will help you follow a discussion much easier. Next, don't just hit reply and start typing. Pick and choose sections of the previous message(s) and comment on them one at a time. Everyone has already seen the prior messages, so there is no reason to include them in their entirety each time. Finally, anytime you see a request for review and you do not have time at that moment to review their code, you should mark that mail and come back to it later. In Gmail, I mark all requests for review with a star, and once I have provided a review, I remove the star. By doing this, I can make sure that I don't miss anyones request.

### University-web

University-web is coming along, but can be one of the more daunting and difficult communication channels to mentor with. There are two major components that you will use, the Submissions and the Activity Log. The Submissions is where students propose their projects/assignments, request reviews from Greg and on occasion, run discussions. It would be a daunting task if you were to try and look at all the submissions on a daily basis for updates, and that's where the Activity Log comes in. The Activity Log is just like it sounds, a listing of all the activity that has happened based on your current context. For example if you are at the root of a course, you'll see the activity for the entire course, if you're on a specific assignment you'll see the activity log for just that assignment. You can use the activity log to browse what is has been occurring, and jump into the discussion as you feel appropriate. I personally treat this area as readonly, and only look through it the day of a checkpoint. But I have seen other mentors who comment on it almost exclusively, putting a message on the mailing list to check university-web when they've made a comment.

## Reviewing Code

If you haven't work on your code reading much, welcome to boot camp. You are in for three weeks of intense work. Reviewing code will be the most important task you'll have as a mentor. It helps your mentees learn to write better code, and acts as a buffer for Greg, making sure simple design and style problems are mostly weeded out before the students request formal reviews from him.

Here are a few tips to help you through code reviews. First, clone the students repo and poke around. If they have tests, run them. Fire up IRB and play with their classes and modules. Now that you've got an idea of how their code works open up a blank document, read through their code and brain dump. Things to look at are overall project design, class/module design, method implementations, and style. Once you've brain dumped, you should organize your thoughts into a coherent package. With things listed in the most important to least important. This is one of the key points Greg has taught me. If you simply brain dump, you're not teaching, your telling. By organizing your thoughts into a logical package you are on the road to teaching. Finally, if you're stretched for time, it is much better to provide a deep review on a small portion of a mentees project, than to give them a shallow review of the whole.

### Class/Module Design and Overall Project Design

These are just taking another step back from individual methods and looking at entire classes/modules or the entire project. Should the class/module be refactored? Are they following standard project layout? Is everything in a giant file? These are things that should be pointed out. Again, don't just say, "ugh, everything is in one big file." Explain to them how and why a project is typically laid out.

### Method Implementations

Here is where you should address concerns regarding how a method actually works. Could it be simplified via recursion? Could it be refactored? One of the simplest refactoring is usually extraction. But, don't just say, this method could use some refactoring, or this method is a candidate for extraction. When working with intermediate developers, they might not see it. You need to provide them with an example, or refactor their code for them and present it as a gist. When someone has spent a lot of time working on something, it is often hard for them to step back and see these issues, they need you to pull them out by showing them the forest when they're stuck on the trees.

### Style

Style might be a matter of taste, but there are common things that every Ruby programmer should be doing if they're code is going to be accepted by the community. Simple things, such as lining up "=", "=>", etc. or indenting two spaces and not using tabs. Essentially, go through the style guide [here](https://github.com/rmu/wiki/wiki/Style-Guide) and point out any problems. It's not usually enough to just point out the style guide, it's much more helpful if you point out some issues first, and how to correct them, before sending a student to the style guide.

## Further Tips

Often students can feel stuck or overwhelmed; perhaps they've bitten off more than they can chew. On the other hand, often students can be found obsessing about a minor part of the project, avoiding the main implementation. Many of us have been in this situation before. If you find a student in this situation, encourage them to reassess their project, narrow the scope, and prioritize individual pieces of code. Sometimes this can go a lot further than doing a code review itself.

Avoid trying to solve the problem for the student, it won't do them any good. And if you're mentoring multiple students, you won't have the time to do it anyway.

## Closing Thoughts

There's a secret to Mentoring that you don't often hear. You are going to learn as much, from your mentees as they are from you. You are going to be tackling all kinds of code of various styles, strength and weaknesses. Unless you've worked on substantial projects before, this is an experience you've never had.

Don't feel discouraged if after writing a detailed treatise on why a students code should be refactored and how, they respond with, "no I did it this way because it's..." If you've made your argument and they just reject it, at least you've tried. In the same vein, if you write something and Greg comes back going, "well actually" (or "no, that's bullshit"), don't worry about it. Both you and the student will gain a better understanding after Greg's explanation, and you have something new to share the next time the same question comes around (and if you are mentoring more than one session, you'll see it come up again).

Overall, work hard and keep up on your communication channels and you'll have a great experience mentoring at RMU. You'll be helping programmers who are in the same position you once were, and will take away valuable knowledge that you can use elsewhere in your life.
