Charybdis
=========

A Web and telnet server for online roleplay communities

Charybdis aims to provide a complete application environment for running online text-based collaborative storytelling communities.  Whereas past communities focused on the telnet protocol and accumulated an ecosystem of arcane clients with diverse features and limitations, Charybdis targets modern web browsers with HTML5/JavaScript/Websockets for the primary supported user client.

Proper telnet support for both bare telnet clients and for more traditional MUD/MUSH/MUCK/MOO clients is on the agenda before a release, but is not intended to be the flagship use-case.

## Design goals

The Charybdis design calls for a suite of application functionality to promote optimal communication, interactivity, and durable long-term record-keeping as needed by general online roleplay communities:
* A basic wiki with both free-form and structured data for describing game-rules, the setting, character details, and a running historical commentary.
* A basic forum for providing easy short-term communication, long term records of that communication, and easy tools for promoting results of decisions to the wiki.  Much like the wiki, this message board will have an extensible hierarchical namespace. (A unification of web forums and the in-game bboard systems)
* User email-like messages for more directly targeted offline communication. (analogous to MU `@mail`)
* Realtime communication between users in a variety of modes:
    * Direct user-to-user (analogous to MU paging)
    * Persistent and transitory topic-focused and group-focused broadcast domains (analogous to MU chat channels)
    * RP Session communication, consisting of: (analogous to MU `say/pose/@emit/ooc/+roll`)
        * Agreed-upon setting poses, optionally auto-inserted from the relevant wiki location description fields
        * User poses for their character(s), NPCs, or setting details
        * OOC (out of character) communication
        * Dice rolls and other game-rules detail
    * An unobtrusive, configurable notification and contact management interface
* A comprehensive, easy-to-learn, extensible, scalable issue tracking system. (analogous to MU apps such as Anomaly Jobs)

Many specific design choices are taken with this project that contrast with prior efforts:
* Each of the sub-systems described above must be tightly integrated, rather than separate applications.
* Telnet is not the primary target.
* No attempt is made to make the internal core server code end-user accessible, except in the form normally available with any open-source project.
* No attempt is made for backward compatibility with existing server code.

## Current status

No, it doesn't do anything yet.  Go away.  (heh)
