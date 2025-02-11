---
title: "Consensus"
date: 2021-08-09T21:41:42-04:00
tags:
- sapling
---


Consensus in human systems is actually usually pretty easy because of the social layer of society. This [fault tolerance](thoughts/fault%20tolerance.md) against 51% attacks is due to the fact that convincing the community that any engineered 'truth' is the real on requires subverting every trusted member in the community, most notably media and news sources (also why systems of authoritarian power are so scary). 

A difficult problem for [governance](thoughts/governance.md) within [communities](thoughts/communities.md)

## Algorithmic Consensus
There are four requirements to such an algorithm:

1. Validity. The result must be a value that was submitted by at least one of the processes. The consensus algorithm cannot just make up a value.
2. Uniform agreement. All nodes must select the same value.
3. Integrity. A node can select only a single value. That is, a node cannot announce one outcome and later change its mind.
4. Termination. Also known as progress, every node must eventually reach a decision.

## Consensus and Humming in the IETF
[Source: IETF](https://datatracker.ietf.org/doc/html/rfc7282)

On rough consensus
- Humming as 'temp checks' for people to voice disagreement but default assumption is optimistic trust
- "While counting heads might give a good guess as to what the rough consensus will be, doing so can allow important minority views to get lost in the noise. One of the strengths of a consensus model is that minority views are addressed, and using a rough consensus model should not take away from that."
- "We can't know who the "members" of any given working group would be at any one time, and we certainly can't know who all of the "members" of the IETF would be: That's why we refer to "participants" in the IETF; the IETF doesn't really have "members". Indeed, we often recruit additional implementers and other experts into working groups in order to ensure that broader views are brought into the discussion. So, voting is simply not practical."