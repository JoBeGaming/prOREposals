<!--
Created by Jobe, Trailers, Amelium, Imated and others xdxd
-->

# VSADE Scheme and additional Role System for the Open Redstone Engineers Server

> [!Note]
> This is to document, and give an overview of, what people have suggested so far. 

## Overview

- Rank Requirements
- Rankup Procedures
- Rank Perks
- Transition Period
<!--Fast Track, where certain members can get the higher rank faster for some time.-->

## About Naming:

### Rank:

A rank is the “level” of a person. Ranks are ordered from those easiest to get to those harder to reach. A person can only have one rank at a time. Skipping ranks is not allowed (except possibly for the transition period). Ranks cannot be taken away, unless absolutely necessary (or during transition). An example for a current rank would be Student.

### Role:

Roles are not part of the rank system. They serve as additional indicators of permissions granted by Staff, to help the community. Multiple roles can be held at the same time. An example for a current role would be Staff, as (current) Builders and Engineers can have permissions for Staff / Administration too.

## Suggested Ranks ([V]-[S]-[A]-[D]-[E] Scheme):

Each Rank requires already having all previous Ranks.

### V - Visitor

#### Requirements:

- Visiting the Minecraft Server using a NON CRACKED Account

#### Benefits:

- Patrick Usage for very limited set of commands, e.g. `,wb` to lessen potential for spam. TBD

### S - Student

#### Requirements:

- Linked Discourse Account
- Agreeing to the Rules

#### Benefits:

- Student Rank, possibly the ability to use Patrick with cooldown on some commands
- Student Plot (128x128)

### A - Apprentice

#### Requirements:

- Linked Discourse Account
- Application on Discourse
- RCA (Perhaps also other?)
- Binary addition & Subtraction (with 2s Complement)
- Conversion between Binary, Hexadecimal and Decimal
- Redstone Mechanic Basics <!--TBD specify-->
- Boolean Algebra
- Fundamental Circuits <!--TBD-->
- Binary Test Score of at most 2 Questions wrong in less than 9 Minutes

#### Benefits:

- Either full WE Access, or limit it after X Months, with limited size, less commands, and fewer editable blocks, no entities and no NBT usable
- Single Build Plot (256x256), second (additional) Student Plot (128x128, so 256x128 total if they are connected)
- No Patrick Cooldown (for default commands, see <!--TODO: PROPOSAL/LINK-->)
- If the person was active on either the Discourse, the Discord or the Minecraft server (not just AFK, TBD) in the last 3 months, they are eligible to vote
- If the person was active on the Discourse, Discord and Minecraft Server (not just AFK, TBD) in the last 3 months, and they have been a Student for over a year, they are eligible to be voted as a Moderator.

### D - Designer

#### Requirements:

- Application on Discourse
- CCA and at least one of CSA, CLE, CLA, PPA
- Bussing techniques in Binary and Hexadecimal
- Serial / long distance transmission
- Staggering
- Diodes (horizontal + vert)
- Wire crosses?
- Operations (including NOPs) in assembly and uops
- CPU architecture
- RISC/CISC/Von Neumann/Harvard/Modified Harvard?
- ISA
- CPU components
  - ALU and associated operations
  - Memory
  - Registers (SDR and Real DR, Single Read)
  - RAM
  - Dataloop
  - Program Counter / PC with JUMP and Flags
  - Control Logic
- Simple Programming Knowledge in any language + simple Assembly language (or universal, e.g. URCL)

#### Benefits:

- Second Build Plot (256x256, so 512x256 if they are connected)
- Full World Edit Access with bigger size limit (smaller than current)
- A Plot on the `/play` server.
- Access to the `/survival` server.
- Being able to become TeachORE or Trialer if deemed eligible by Staff, see the application process for the Ranks.

<!--Alternative Requirement idea: “Baby’s First CPU”, i.e. a VERY simple one. (No/Small ram, any speed, some isa/instructions, some rom, no ports/io needed, single cycle or more)-->

### E - Engineer

#### Requirements:

- Application on Discourse
- Impressive Build (Pipelined CPU, GPU, …) AND advanced programming knowledge (e.g. programms being run on a CPU)

#### Benefits:

- 2x2 Builder Plot (512x512 is connected)
- Access to MCHRPS server
- Bigger WE Size limit
- WE on the `/play` server.

## Proposed Roles (Permissions)

<!---
trialer (trusted? <- clashed with @Trusted role in discord, for non-linked accounts)
helper
developer
organizator
mainainer of a specific project used by ORE
- schematio
- wol
- patrick
- univOREsity organizer
-->

Roles aren't shown like normal ranks, of which you can only possess one at a time. The can be shown in-game via a hover over the name of a user, and via the given roles in the discord. A solution for the discourse may also be found, so given permissions can be obvious at once. A system with e.g. permission and ping roles in the discord might be applied (similar to e.g. the Python Discord Server), so e.g. `@mods` can be pinged, and those with permissions to help in a situation can be pinged too. For Discourse and Minecraft, an option to show a specific role next to the rank may be added.

### Trialer

#### Requirements:

- Community / Staff Trust <!--TBD-->
- Potentially performing a Trial with at least one Staff Member present
- Builder-level knowledge (see [D Rank Benefits](#D---Designer))

#### Benefits:

- Being able to Trial Student to Apprentice and Apprentice to Designer
<!-- Possibly Above / Other? (Student to builder pre-revamp, anything up to builder post-revamp?)-->

### Helper

Might also be viewed as alternative helper in case of offenses including Staff. Can help to calm down situations involving cases where injustice from Staff is being felt by a member.

#### Requirements:

- Community / Staff Trust <!--TBD-->
- Voted in by Staff (can apply, then once a month there is a vote, and like only those with 2/3rds of Staff approval get the role) <!--TBD application system-->

#### Benefits:

- Minor Staff Permissions, e.g. Kick and Timeout
- Can provide more insight durring Staff meetings
- notifies Staff about potential problems found
- Can post in locked Discourse / Discord Threads to Help in Discussions
- Can lock & unlock posts
- Can hide posts
- Can reply to appeals in Discourse, not with accepting / rejecting them

## Transition Period

What happens to current builders? Currently, there are three options:

- They can be moved to apprentice rank
  Could cause issues if apprentice rank perks are lower than that of the builder
  More fair since the requirements match more closely
- They can be moved to builder
  Potentially less fair since requirements for new builder are higher
  Lower influx of trials/tests required when revamp day comes
- They could be required to have an Application (simple-ish) and automatically get accepted -> higher rank, or rejected->lower rank

---

Notes about the transition period and the Trialer Role

<!--Potentially have some people pre-promoted that we know are close to engineer rank? <- Similar to Trialer/Trusted Role?!-->

We could test the Trialer role pre-revamp to potentially see how it works for current Builder trials. Some Moderators have already let Builders run trials, these people would be a great fit as the first people in this role (kinda a pilot program for pre-revamp could work). These people could help with the influx of trials needed for ranking up from the Apprentice rank. The Trialers are guaranteed the new "Builder" rank ([Designer](#D---Designer)) on revamp day and would help run Apprentice and Designer Trials post-revamp (especially if the decision is made to have current Builders get Apprentice rank on revamp day).

[V]: #V---Visitor "Visitor Rank"
[S]: #S---Student "Student Rank"
[A]: #A---Apprentice "Apprentice Rank"
[D]: #D---Designer "Designer Rank"
[E]: #E---Engineer "Engineer Rank"
