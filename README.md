# actions-learnings
This repo is used for github actions learning and pratice

# Key Elements of Github actions
 - workflows
 - jobs
 - steps

Workflows is the first thing we build/do to get a action to work

Workflows contains jobs, and each jobs contains steps.
You have as many jobs and as many steps we can.

Workflows are attached to a github repo.
It contains one or more jobs.
Triggered upon Events(push,pull based on events)

Based on the event type, Jobs are activated.
Jobs define a Runner(execution env)
It contains one or more steps.
Run in paraller(default) or in sequential
Can be conditional.

Steps is a shell script command or an Actions.
Can use custom or third part actions.
These steps are executed in order.
Can be conditional