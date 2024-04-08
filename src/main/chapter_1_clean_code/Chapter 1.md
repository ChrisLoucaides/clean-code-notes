# Chapter 1: Clean Code

### There will be code

Suggestion that we are close to the end of code - This book was released in 2008,
yet it mentions code generation - "Programmers won't be needed". This is more 
than relevant today with GenAI tools.

However, at the end of the day code specifies requirements. The level of abstraction
of languages will continue to increase but this does not mean code will be eliminated.
Even if code is generated, it needs a certain level and detail and understanding to
write a prompt to generate exactly what the specification wants.

A machine that will be able to create exactly what a customer wants will never
exist. Tools that help us format requirements into code will always exist and get
better - but they will never reach a point where they are able to generate code 
precisely based on requirements.

### Bad Code

Many businesses will rush to get their product out to market. The issue with this? Bugs, unmaintainable
code, that will inevitable lead to that product's (and maybe the company's) demise. 

We have all written bad code at some point in our lives. Again, the reason behind this is often
that we are in a rush. Taking time to think about the code we write - making it human-readable
will save time in the long run.

### The Total Cost of Owning a Mess

A team's productivity when working on a codebase over time will tend to fall due
to the messiness of the code.

In the beginning, teams will move fast, changes made will affect other areas of the 
codebase - requiring monkey-patching that needs to be understood. If this is not refactored,
after applying this fix, technical debt increases, making code very hard to understand,
especially in a few years time when new devs join the team.

### The Grand Redesign in the Sky

Eventually a team will put their foot down, and complain to management that this application
will cost them more to maintain in the long run, compared to building it properly from
scratch.

When management finally gives in, a new team is racing to re-build that application,
to the point where the current project is at. However, this in itself, could also
end up going the same way as that original project, and we now find ourselves back
to the total cost of owning a mess.

### Attitude
Why does good code rot so quickly into bad code? The answer a lot of the time is simply
our attitude. To quote Uncle Bob himself, "We are unprofessional."

We often point fingers to requirements, schedules, managers and marketers. They shouldn't
bear the blame. They come to developers for information to make certain commitments to stakeholders.
What if they don't? We should still tell them what we think. Most managers want the truth,
even if they don't like it.

An analogy is used here: imagine being a doctor, and you have a patient that insisted you 
stop spending too much time washing your hands before operating on them. You *should* 
instantly refuse. The point here is that as a doctor (or a developer), you will have
more knowledge than your patient (or the manager), to avoid potential risks.

Hence, it is unprofessional for devs to bend to the will of managers, that don't understand
the value of good code. While they may defend the schedule, you should defend your code with
equal passion.

### The Primal Conundrum
Developers with a few years of experience are aware of the ramifications of previous
messes, which ultimately slow things down. However, due to deadline pressure, this
doesn't stop devs making messes  in order to go faster.

In other words *they don't take the time* to go *fast*.

True professionals know that you won't make the deadline by making that mess. The only
way to go fast is by keeping the project's code clean at all times.