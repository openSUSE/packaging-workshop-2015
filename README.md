# Packaging workshop 2015

Preparation for the packaging workshop 2015.

The [openSUSE Conference](https://events.opensuse.org/conference/oSC15) in The Hague from May 01 - 04, 2015 will also have some nice talks and workshops around packaging. Currently we plan to organize a whole day with presentations and workshops around packaging from beginner sessions to discussions with experts around everything you can imagine (especially after a few beers ;-)

If you want to get your packaging topics covered during that workshops, please open issues here, so they don't get lost.

Current list of topics in a slightly unordered list:

## 1. The idea behind packaging (presentation):
* Why do we need RPM (or a package manager) at all?
* Ever tried to deploy a security fix after you installed something from source?
* Software lifecycle does not end after "deploy & start"
* What are the real benefits for a user?
* What are the real benefits for a developer?
* What is the different view of a packager and a developer? (roles)
* What is the benefit for a distribution?

## 2. Very basic
* from the usual triple ./configure; make; make install to an rpm specfile
* try it out on a simple example

## --- switch to workshop style ---

## 3. "Using the openSUSE Build Service with osc"
* get account
* home project
* new packages
* check in and checkout
* changelog
* patches to pristine sources
* collboration (branching)
* devel project vs. home project
* Concentrate on osc but make references to webui

## 4. Intermediate topics
* build dependencies
* runtime dependencies
* %files tricks
* subpackages
* shared and static library packages

## 5. More advanced (specific?) Packaging topics
* services (sysv and systemd)
* security in packaging (minimal permissions, different users and groups, apparmor/selinux)
* security considerations for the packaged files too, such as suid, etc
* how to get a dbus services/suid/default start granted?
** perl
** python
** ruby
*' Probably not cover Java, nodejs
* package updates done correctly: differences between install and update of an installed package (%pre %post %*un %*in , order,  etc)
** %triggers? epoch?
** http://fedoraproject.org/wiki/Packaging:ScriptletSnippets#Syntax

## 6. Collaboration and communication
* Communication is important: where to find the right people to help you; where to discuss proposals and how to interact with reviewers
* Reject is not "they are mean to me"
* Most common challenges -- packaging policies  => get feedback from dimstar and friends  

* Patch policy
* What does it take to be a responsible packager

## License

The content found here is licensed under [Creative Commons Attribution-NonCommercial 4.0 International][CC-BY-NC-4.0]


[CC-BY-NC-4.0](https://creativecommons.org/licenses/by-nc/4.0/)
