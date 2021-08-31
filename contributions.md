# Home Team Contribution Guidelines

As a small team with a straightforward objective we don't really need to go overboard on setting up rules to officially contribute. However, there are some useful 
things we can do to keep our messes seperate and the project moving forward at a reasonable pace for the coming months.

## Commit to the MVP

Ultimately, we want to deliver something useful. At the end of SP21, we had most of the core features needed for basic functionality. It is critical that nothing we do 
from this point on jeopardizes the work that we already put in on the project.

1. Before submitting a pull request for any major changes to the back end you should be able to verify that a user can create an account, sign up for and pay for an event,
view their events, and so forth. Likewise, an admin should have the ability to add/remove/confirm users and events. These should be verified PER FEATURE. The code we have 
now isn't a jungle, we should strive to keep it that way.

1. Before submitting a change to the front end, you should attempt to verify that it looks sound on multiple screen types. Bootstrap should make this trivial, but it is always
better to be safe than sorry. MVC's inate separation of concerns makes it very unlikely that front end changes will have major side effects elsewhere. If you are doing a front
end task, simply consider the Razor code as untouchable until you change objectives.

1. Due to our set up as a web interactive environment with a lot of external systems, automated testing for major components will likely not be worth the time
investment to implement. It might be a pain to sign up a new user for every feature, but that 20 minutes could save hours or days in the long run.

1. If you notice a bug, use [Github's issue system] to track it and bring it up to the relevant party in discord.

## Misc

1. Claim your task on Trello, there's no need to have multiple people on the same task unless they are directly collaborating.
1. Reach out to Todd/Kevin for any database issue, Will for an AWS issue, and Johnny for Mobile.
1. Visual Studio should have us handled for linting/style/run/test and most other concerns. If you want to bring in an external tool, mention it in discord.
1. It should go without saying, but we should all be working with forks of Kevin's repo rather than clones.
1. Try to find a feature example in Microsoft's [official documentation] for ASP.NET before jumping to Google. 

[official documentation]:https://docs.microsoft.com/en-us/aspnet/tutorials
[Github's issue system]:https://docs.github.com/en/issues
