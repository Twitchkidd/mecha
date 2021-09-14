# Multiple Environment Config/Hosting Arrangement (Mecha!)

## Config Repos

Time to split up /dots. With marvin as the example environment name, do we go with dots-marvin? Yea, right? Then who else do we have ... raspberrypi and JES-Pavilion, so, maketh the repos.

[ Maketh the repos ]

## Remotes

For old repos, I'll have to fix one by one, but moving forward I want to just type git origins and have it do the thing, and then git push to both, though I think I need to look up whether there's a better way to do that than how I'm thinking.

[ Multi remote push best practices search ]

Okay, so we want to add both remotes and set upstream, then create a new remote that pushes to both with git push all BRANCH?

## To Future Me!

You just have to do marvin and trim everything down, and git push all is fine. Remember to make the dots-marvin folder, put some stuff in old, init the repo, create the remote repos, copy over the gitorigins function, make sure you're good to go having changed the dd script to dots-marvin everywhere, and to git push all
