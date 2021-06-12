---
title: "BlockChain; A Theoretical Primer..!"
date: 2019-06-17T23:53:00+01:00
hideLastModified: true
summary: "A non-technical introduction to BlockChain"
summaryImage: "Blockchain.jpg"
tags: ["custom_image", "custom_summary"]
socialshare: true
---

For millennia, people have tried to maintain and track information using a Ledger: a very basic,
simple sequential/chronological collection of data. Their usefulness ranged from recording the
number of sacks of barley to barrels of whiskey, from tracking the runs in a cricket match to the bets
on it, from counting all the ghosts in the villages to counting the friendly ones amongst them. It was,
and still is, about ledgers.

With time, human activity has changed, diversified, expanded and the activities have only been ever
increasing. What has evolved alongside, are also the methods that we use for recording and
synchronizing information. Information started becoming digital in the last century and our ledgers
harmoniously transitioned from paper sheets to computers. What did not change however, was that
these ledgers could only be updated by a central authority. This concentration of power implied that
if the trusted authority was to go rogue, there would be nothing preventing that. So there’s nothing
but trust, to trust. This has unfortunately become more prevalent in the post internet era and we
can cite examples for it. What if my bank decided to stop paying me interest on my savings account?
They can do it. What if Facebook decided to change my profile picture to that of a leprechaun? They
can do it too.

Since the advent of the internet our worlds are more connected. In this age of digital interactions,
we have yearned for something more collaborative and more resilient. This system would need to
work at scale and not be aligned to any motive, incentive or ideology. There was a need for a trust
less system. To avoid any misinterpretations, when I say ‘trust less’, I mean a system that is
independent of the trust factor. It does not mean a system that cannot be trusted.
Circa 2009 and Blockchain was invented to precisely solve for this asymmetry of trust. It is a
mechanism that eliminates the concept of basing our trust on a central authority. It allows unlinked
entities, who might all have vested interests in altering their shared information, to agree upon a
single dataset and hence it is a way to come up with a consensus involving multiple parties. In the
realm of Computer Science, this problem (that Blockchain is built to solve for) is referred to as the
Byzantine General’s problem and the gist of which is as below.

Consider we have four generals hatching a plan to lay siege on a city. The only way they can
communicate with each other is via a messenger. For the plan to succeed, three of them need to
attack at the same time and they do not know if one of these four is unreliable. This unreliable
general can modify the attack message and cause the attack to fail. One way to overcome this would
be to supply a history of all the messages that were sent with a proof that they are unaltered. If the
generals see that one of their peers has sent a message that differs from theirs, they would identify
him as a traitor. If 3 of the 4 generals here are good, the correct message will be obvious. A more
detailed and illustrious version of the problem can be found [here](https://coincentral.com/byzantine-generals-problem/).


Let us try to understand this problem with a real life example as well. Let’s say, I am trying to sell my
collection of stamps online and find a potential buyer. However, I do not know if this buyer is legit
and if he really has the means to buy my collection. Similar to the Byzantine Generals example, we
can never be sure that the buyer indeed has enough funds to buy the stamps. As it stand today, I
need to depend upon a trusted middle-man like PayPal to bridge this trust deficit. Once PayPal
credits the funds to me, I can deliver my collection of stamps to the buyer. However, the services of
this middleman -PayPal- come at a cost and take time. With Blockchain, the need for this middleman
is eliminated, thereby saving time and cost.

Now that we have an overview of Blockchain, let’s have a look how this works in real life.
Number of computers (nodes), that want to share data, are joined into a network and they are all
running a Blockchain software. As data enters the network, it is grouped together in ‘blocks’ for
verification. In this process, all the computers on the network vote on the block of data, saying, in
effect, ‘all seems good to me’ (or not). A block rejection leads to a re-voting when the next block is
submitted. Alternatively, if the current block is verified successfully, it gets added to the entire past
record of validated data blocks and a connected ‘chain of blocks’ is formed. This chain is stored on all
the participating computers in the network. In a rare event, if you were tempted to cheat, and alter
a past transaction, you would need to somehow do that across all the computers in the system or
join the system with sufficient new computers to vote your cheats into ‘fact’. This is also sometimes
referred to as the 51% attack. As it stands today, such attacks are rare, as it would require
computing power superseding that of millions of computers in the world (all of which are part of a
network).

As is evident, there’s a tonne of technical detail that is involved in making a Blockchain function.
The [original white paper](https://bitcoin.org/bitcoin.pdf) describing the design of the first blockhain based system is a highly
recommended read.