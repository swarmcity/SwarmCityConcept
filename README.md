# Swarm City High Level Roadmap 

### How to use this document
Every Episode is a development sprint. Each Episode consists of a set of Epics devs must work through in order to create the functionalities highlighted in the Episode.

After each sprint the dev team will show a functioning DApp demo in which the scenario described by the Episode is played out. 

Once an Episode is completed, devs are free to move on to the ensuing Episode.

### Glossary 
Check out this document to learn more about the general concepts of Swarm City.
- Hashtags
- Hives
- Storefronts
- ...

----

General remarks
- In the api documentation, always indicate which component the API is "helping" > storage, messaging or transactions. 
- insert the concepts (hashtags / storefronts / hives / ...)
___

# Season 0 (Pilot) [DONE]

## S00 E01: All beginnings are hard

In Episode 1 of the pilot-season: Terminal is born! 

User stories:
- [x] https://github.com/swarmcity/SwarmCityConcept/issues/3
- [x] https://github.com/swarmcity/SwarmCityConcept/issues/2
- [x] https://github.com/swarmcity/SwarmCityConcept/issues/4
- [x]  https://github.com/swarmcity/SwarmCityConcept/issues/6
 
___


# Season 1

## S01 E01: First Request

In episode 1, Frank is really excited to start using Swarm City. Whenever he gets excited by something, Frank throws himself whole hog into it. And so without delay he creates and posts his first request.

Frank would like someone to translate his "Decentralise Now!" manifesto in exchange for 20 SWT. He posts this request in the marketplace known as #Settler, because #Settler is a place where early adopters go to do such things.

Frank is on /new-request, filling in the description: "Translate my 1 page manifesto from English to Dutch." and the amount: "20 SWT". Frank sets the request's location to "Worldwide". 

After submitting his request, he sees it on page /hashtag (of #Settler). Frank taps on his item to see the detail. In the detail, he finds and then grabs the shareable link and posts it on Facebook.

Who, oh who, will respond to Frank's request?

#### New epics in this episode:
- [ ] As a Seeker, I can share the relevant location range of my request so providers can choose if it’s relevant to them.
https://github.com/swarmcity/SwarmCityConcept/issues/18

- [ ] As a seeker, I can post a new request in a hashtag, describing what I am asking for and how much SWT I am offering,  so providers can see what my need is.
https://github.com/swarmcity/SwarmCityConcept/issues/7

- [ ] As a user, I can see all the items in a hashtag, so I know the activity of myself and other people.
https://github.com/swarmcity/SwarmCityConcept/issues/8

- [ ] As a user, I see the detail-view of a request/deal I’m active in so I can verify all the details of this request/deal.
https://github.com/swarmcity/SwarmCityConcept/issues/9


## S01 E02: Talking Shop

In episode 2, two people reply to Frank's request.

Alice sees Frank's request on Facebook. She taps it, and gets transported by way of the internet to swarm.city. Here Alice can see the details of the request, and she decides to reply.

Tom is already on Swarm City, specifically on page /hashtag of #Settler. He also is intrigued by Frank's request, and taps it to see the detail. Tom decides to reply as well. 

Frank sees the two replies. Who will he choose?

#### New epics in this episode:
- [ ] As a provider, I can reply to a request so I can express my interest in entering into this deal.
https://github.com/swarmcity/SwarmCityConcept/issues/10

- [ ] As a user, I can see the replies to a request.
https://github.com/swarmcity/SwarmCityConcept/issues/11

## S01 E03: The Burden of Choice

In episode 3, Frank has to decide who he wants to choose as a provider for his request.

Frank gets to know the reputation of the repliers, Alice and Tom. Alice's reputation is sketchy, so he chooses Tom to become the Provider.

Tom is very happy, and agrees to the deal. 

Will they successfully complete this deal, or is there a conflict waiting around the corner?

#### New epics in this episode:
- [ ] As a user, I see another user’s reputation so I can interpret it to decide on the trustworthiness of the other user.
https://github.com/swarmcity/SwarmCityConcept/issues/12

- [ ] As a seeker, I choose one of the repliers to become my provider so we can enter in a deal.
https://github.com/swarmcity/SwarmCityConcept/issues/13

- [ ] As a Provider, I accept and fund the deal, so the Seeker and I are engaged in a deal.
https://github.com/swarmcity/SwarmCityConcept/issues/15

## S01 E04: The Successful Deal

In episode 4, Frank and Tom successfully complete a deal.

When a deal is successfully completed both users gain reputation. Frank can view his new reputation, while Tom verifies that he received his SWT. 

Finally Tom's got his SWT. He knows it opens up a whole new world of possibilities. What will he do with his newly gained capital?

#### New epics in this episode:
- [ ] As a seeker, I payout the deal, so the provider gets the funds and reputation tokens are created for me and the provider.
https://github.com/swarmcity/SwarmCityConcept/issues/14

- [ ] As a user, I can see my reputation balances so I can check how other users perceive me.
https://github.com/swarmcity/SwarmCityConcept/issues/17

## S01 E05: Going sour
In episode 5, Tom tries to make up his mind about what to request first. There's so many possibilities. 

After pondering on it, he makes a new request and selects Brenda as a provider, resulting in a deal between Brenda and Tom. 

Even though Brenda agreed to the deal, she never shows up. Tom wonders where she is so he sends her a chat message in their shared deal. 

Brenda replies ("Damn, it's just too far for me, Dick!"), which of course makes Tom seriously pissed off. He's resorted to his last option: initiating conflict resolution. Will Tom get his satisfaction?

#### New epics in this episode:
- [ ] As a user, I can chat so I can communicate about the deal.
https://hackmd.io/gdx3zM9oTX27re5DzDmI_Q?both

- [ ] As a user, I can start a conflict about the deal so I can get my SWT back.
https://hackmd.io/C9NJhFISQGmZrm512R9ZEA

## S01 E06: Finding peace
In episode 6 we meet Crystal, the marketplace maintainer. She is responsible for resolving the conflict between Tom and Brenda.

Crystal checks the details of their deal. She joins the chat with Tom and Brenda, and starts communicating with them. She hears both sides of the argument.

Crystal resolves the conflict in favor of Tom. Brenda realizes it was her own fault. (For one thing, spelling your customer's name right is important.) Will she do a better job next time? 

#### New epics in this episode:
- [ ] As a hashtagmaintainer I can resolve conflicts so users have a safe and fair marketplace.
https://hackmd.io/HWL38ETcTv2u5_kAbjwmIg

## S01 E07: Searching New Horizons
In episode 7, Brenda tries to reply to a request on a different hashtag.

Brenda sees the hashtaglist and chooses a different hashtag she's interested in. She learned from her previous mistake, and this time filters the list to only see requests nearby. She concludes she'll have a better chance of fulfilling requests that occur in her general neighborhood.

Brenda sees Gary's request. It's nearby, and it's the amount she's looking for, so she responds to Gary's request. Gary picks Brenda as the provider, but by that time Brenda is passed out on the couch.

Gary loses his patience with Brenda, so he deselects her and picks someone else.

#### New epics in this episode:
- [ ] As a user, I can see all the hashtags with the number of done deals for each hashtag, so I can see the activity in Swarm City. https://hackmd.io/DIjO_Oj_TsCDgUa4RQ0vFw

FAFFY WORK NEEDED
- [ ] As a user, I can filter the hashtagItems on my geo-range of choice so I can see items in my area.
https://hackmd.io/7oaEEzeVSsaHMDYWUtZ8jA?view

END FAFFY WORK NEEDED

- [ ] As seeker, I can deselect the replier I previously selected, so I can choose another one.
https://hackmd.io/OpwbB8YoSfKZRYn1_oKRRw
- [ ] As a provider, I can see when a seeker deselects me, so I know I’m no longer selected. https://hackmd.io/VXi71fKaSaG7NbSwvvDHhQ


## S01 E08: Bad Luck Gary

In episode 8, Gary has no luck with his deal, so he just gives up.

After deselecting Brenda, Gary selects Pepe as a Provider. Unfortunaly, Pepe declines which leaves Gary's deal without a Provider. This makes Gary totally fed up with Swarm City, cancelling his deal. Will Gary ever do a new request in Swarm.city?

#### New epics in this episode:
FAFFY WORK NEEDED

- [ ] As a provider, I decline the selection, so I can express I'm no longer interested in fullfilling the request.

FAFFY END WORK NEEDED

- [ ] As a seeker, I can cancel my request, so the request is no longer on the hashtag.
https://hackmd.io/zL84umAnREmgP0F7fwjgag


## S01 E09: Rollercoastin' Brenda

In episode 09, Brenda wakes up and sees how the deal has played out.

Upon waking up, she reaches for her phone and sees a new notification: "You are selected", which fills her with joy. Right after she sees "You have been unselected", realising that being passed out on the couch made her miss the deal completely.

She's a bit pissed off about it and contacts the hashtagmaintainer to get some education. 

#### New epics in this episode:
- [ ] As a user, I get notified so I can quickly navigate to the actionnable items. 
https://hackmd.io/4e3-o36mSZmApAV8AXCPHg

FAFFY AND FLURKEL WORK NEEDED
- [ ] As a user, I can find the contact details for the hashtag, so I can contact the hashtagmaintainer 
https://hackmd.io/Vp8-fwJiSBetu8ymG2pmpg
END FAFFY AND FLURKEL WORK NEEDED


## S01 E10: Multiple Identities & Device Sync
In episode 10, we meet Barry. He wants to buy a sexdoll. Of course he wants to keep this private, so he uses a different identity.
When he comes home, he uses his desktop computer to check the replies.

Will someone find out it's him?

#### New epics in this episode:
- [ ] As a user, I choose an identity to do a request with, so I can have control over how people perceive me (privacy).
- [ ] As a user, I can connect a new device with an existing device so all my devices are in sync.

## S01 E11: Alternate Reality
In episode 11, we meet Johnny.
Johnny is a long time fan of Swarm City and still has his original wallet. He's going to try to do a request. 

He restores his account and finds out there's a vault in his wallet now. 
Will he figure out how to use his tokens?

#### New epics in this episode
- [ ] As a user, I can bridge my SWT to another Ethereum network, so I can do transactions without worrying about gas prices and Ethereum's scaling problem.
https://hackmd.io/2ULp-spFSPqiqR04ulezUw


-----

# Season 2: Readying the DOM
Where Swarm City is prepared to do storefronts

## S02 E01
Hashtag creation

## S02 E02
Preparing the dom for storefront

-----

# Season 3: Hives
Where Swarm City meets Aragon

## S03 E01

-----

With ♡ from Swarm City
