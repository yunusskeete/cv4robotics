# What Computer Vision for Robotics Needs
(A position and intent statement by [Yunus Skeete](https://github.com/yunusskeete).)

In order to achieve general-purpose robotics, we cannot reply on primitive visual backbones and offload all advanced reasoning to language models alone - robotics requires much more active perception.
We need visual AI models capable of understand:
1. **what an object is**,
1. **its size, shape and position**, and
1. **how it relates to all other objects**,
...simply by observing the world through images and video.
Then we can add reasoning, memory and language.

## Technical Challenges
For robots to *see* the world intelligently, like humans, we must develop self-supervised instance level semantic, spatial and relational representation learning capabilities.
We must solve the following problems:

### Representation Associativity
Humans excel at assigning functional meaning - "representation learning".
We learn what objects are and how they relate by observing how they co-occur in different contexts.
For example, we naturally associate a fork and a knife when we see them together on a table.
To us, these associations are common sense.
For AI, it's not as simple.

Teaching AI "representation associativity" is key to instilling common sense about how things relate and function together.

### Hierarchical and Decompositional Representation Learning
Guess what's being described from these features:
1. leg
1. ear
1. trunk

(Answer: Elephant.)

Humans are great at identifying objects as sets of constituent parts.
This ability helps us understand an object's form, function, similarities and differences.
AI, however, lacks this capability.

We must teach AI to emulate this human ability - breaking objects into components understanding them as the sum of their parts.

## Yunus Skeete - Committed to these solutions
I have been engaging with these research problems through [Spatial Intelligence](https://www.spatial-intelligence.co.uk/our-research/non-technical), and I am keen to join/collaborate with commercial applications of their solutions.
I strongly believe that ***whoever best describes the problem is most likely to solve it,*** so I search for others who have a firm grasp on such research.
Let's do something great!
