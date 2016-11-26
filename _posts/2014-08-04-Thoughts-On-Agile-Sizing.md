## Who should size? Those doing the work.
In traditional waterfall SDLC, managers decide how long certain units of work, all of which have a *scope* (a set of requirements), 
will take. The more experienced the manager is in actual development and how well they know their development team will hopefully 
impact the correctness of their decision. Experienced engineers usually end up on the manager track due to their background in actual development, which allows them to, 
again hopefully, perceive the difficulty of a unit of work and thereby be more accurate in the time they think a unit of work will take.  However, not many developers choose 
to go into the managerial role which means people with a limited understanding of actual development usually make the decision.
They do not do so blindly; they usually make the decision with input from a seasoned developer, 
sometimes called an architect, who can provide insight into what he or she feels it might take.

The problem with this approach, as with other parts of waterfall, is the wrong person or group of people are making the decision
instead of those doing the work. One of the issues this approach has is that assumptions are made on behalf of those doing the
work, such as: how proficient those doing the work are with a given technology and how knowledgeable the workers are with the
concept or problem that the work is meant to solve.

Another problem that arises is the loss of critical details regarding the unit which are described during the decision making
process, but for one reason or another do not make it to those doing the work.  Missing these details, those doing the work
will not realize a problem until they stumble upon it and will have to seek out those who do know, *if* those people are still around. Those doing the work might also, unfortunately, make assumptions which could lead to bugs.  This is a loss of a ubiquitous language between the domain experts and the workers.

There is still yet another problem that arises even if the first two I mentioned are avoided (through extreme teamwork and documentation), which is that abstractions of the problem domain are made, usually by the architects, which may not be understood or *even correct*, which impact how a system is built by those doing the work.  If those abstractions are not clearly understood or worse, they are incorrect (unsound), then the builders will have to come up with something on their own which may not be what the system requires.

These three problems together usually lead to one of a few possible outcomes: deadlines are missed, the system ships with many bugs if it's a product, or the project is cancelled and payment not received.

Therefore in agile, the people who size a unit of work, called a story, are those that will actually perform the work.  This has the benefits of all members being able to give their input of the factors that impact the effort involved, all members, including domain experts, forming a ubiquitous language that is detailed, and abstractions can be understood and rapidly changed if necessary.

Thanks for reading! Check back for the next post on Agile Estimation!
