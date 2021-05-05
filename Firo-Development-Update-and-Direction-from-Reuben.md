Hi guys this is Reuben I'm the project steward of Firo and it's been a while since I last made the video.

Uh you know Spline Apple is doing an awesome job uh with you know doing the Firo Frontier that gives updates in again like you know five minutes videos but I thought uh you know I'll give a little bit of more details especially on the development side as to what's been happening.

I guess the one of the number one uh things that people have been asking about is ProgPoW which is a new proof-of-work algorithm that's a lot more lightweight than MTP, FPGA and ASIC resistant and it's been audited and proven so it really works and it is a really awesome proof-of-work algorithm that focuses on graphics cards.

Now a couple of weeks ago we did a [counter-hiccup] where the external developer that we initially engaged uh didn't deliver the ProgPoW up to spec which is kind of unfortunate.

Especially we have been really explicit but no worries we have actually engaged a new developer and his name is Andrea Lanfranchini.

I hope I'm pronouncing it right and he's actually one of the co-authors of ProgPoW.

So you know if he can't code it I don't think anyone can.

He is We are in much better hands now and we are looking forward to a 0.9.4 ProgPoW implementation soon.

Uh we do hope to get this on testnet maybe in the next month or so.

But you know we aren't in any uh hurry uh but we are definitely it's one of our near-term goals uh especially when we want to see uh if we can you know bring down the rate of our blockchain growth and definitely ProgPoW really help with that.

So you know you don't have to worry so much because there are a lot of ProgPoW miners out there.

Uh you know we wouldn't have to wait for like you know custom support is going to be a lot more lightweight on existing pools so we do expect you know pools to easily upgrade.

So we think this is very positive uh movement into ensuring that you know we still get good distribution of coin into the mining public.

Especially GPU miners and also to keep our blockchain lightweight and scalable which MTP didn't quite provide.

So I hope that's uh enough updates on ProgPoW and the other thing that we've been really working on in the past few weeks has been reactivating the Lelantus as you as you have seen I think probably about a week ago we reactivated the Lelantus.

We you know caught certain things that were not initially found in the audit uh but you know everything's been resolved and we've actually taken additional steps to harden the Lelantus.

It's not been easy and been really diving into it but you know especially uh you know with the help of our research team with uh Levon with Peter Aram and you know Aaron who has been really who just joined us recently and we've been really looking looking really deeply into both the coding and the cryptography and so far we think we've done all the the steps that we need.

We are not going to be rushing into the Lelantus version two.

We are reworking to make sure that the paper is you know as as perfect as we can make it to be so there are no oversights and but definitely you know the Lelantus version two is a priority but we're not uh rushing to it we're going to make sure that our Lelantus version one is in a good state and it does look uh so far to be the case.

We are seeing a much increase you know activity with the Lelantus transactions so you know if anyone's watching this please do download our core wallet make sure to anonymize Lelantus as much as you can and we'll be also having an event uh quite soon to incentivize people to anonymize their funds so stay tuned for that.

Another thing that we've been really looking into are sort of decentralized exchange integration and uh previously you know of course like we we were looking at Ren right which is like uh the Ren network and the uh the possibility of having renFIRO.

Now for some reason uh the Ren team has has kind of missed certain deadlines in regards to us you know they and we they said that maybe in summer they would integrate us but we are not we're not going to kind of um hold our breath on that and wait for them uh but instead we are now looking at and two other alternatives uh seriously one which is THORChain uh which is has big benefits over Ren because uh people can swap in this native form that means there's no need to wrap it in like EIP, P-20 or ERC-20.

There's no need for custody so it's almost like you know um swaps of uh coins in its native format so that is really really uh important to us.

Another thing that we've been actually looking at is AtomicDEX which was actually quoted by the guys at Komodo.

It's a separate uh thing and it doesn't require Komodo to run.

It's totally open source and Firo is actually already integrated with AtomicDEX and it's I gave it a go.

I think some of you also possibly participated in their stress test and it's actually very promising so it's quite surprising that it hasn't hasn't seen the publicity that we think it deserves.

So we're looking very hard into uh whether AtomicDEX is the right solution to us because first of all we already integrated it maybe we just need to like you know port it and make sure that it works within our wallet and now we have a Dex for Firo directly with um uh you know directly within our wallet so it's all usable compared to a THORChain integration which requires quite a bit of work.

I did speak to to Kai I did speak to the THORChain team they are keen to borders but it is and is not not so straightforward requires quite a lot of integration work.

So why not both you know we we at the same time we don't want to split our liquidity over too many Dex uh atomic that seems to be like you know promising.

So while we are still looking at the THORChain integration perhaps the the Komodo AtomicDEX might be a more near-term solution that would actually work for us.

So you know I appreciate everyone's thoughts um you know I do recommend giving AtomicDEX a try uh you know I'll probably put a bit more liquidity there so everyone can play around with it, but it'd be very interesting to see which is the best solution right there.

The other thing that we have been actually uh starting to work on is Instant Send and you know because we have our masternodes you know we have chainlocks so that means uh you know we are able to have instant transactions that are confirmed in the matter of seconds and that that we think would be a real first because it would mean we would be I guess the first private truly private cryptocurrency that has uh almost instant confirmations which I think is really big uh and of course uh I think that's a great usability boost. once we integrate it so we're starting work on that.

The other thing that we've been also looking at is the elysium tokenization layer um we have made really good progress on it we've updated it with the latest Lelantus changes and it seems to be working we'll be deploying on testnet relatively soon so we'll keep you guys posted uh you know and you know hopefully we'll get uh some people you know building their own tokens or even like election uh small little elections right on Firo blockchain using the Lelantus technology

It'd be really good to see a stable coin being built on the elysium layer.

So another thing that we've been also thinking about is you know to what extent do we want more Defi integrations.

We've seen I guess decent taker on the Sushi uh you know we would actually like to see more.

It's actually giving a pretty good return uh and there's also we've also launched uh a farm with value Defi on the BSC network and we're being mindful because these integrations do uh a lot of the time they're not for free right now we have to provide uh liquidity incentives meaning that we have to pay uh people in Firo which it is definitely you know a drain on our resources.

We I currently see as a bit of like a marketing expense to you know be able to um how to say reach out to new communities especially those in the Defi space but at the end of the day we have to make sure that this is something that will last on and not just for the farming incentives right.

Uh and I know some people have been asking like why are you on this uh you know automated market maker buy on on you on this Dex now uh we can always create any sort of pair with any Dex but of course we need to you know put our liquidity there and if you want some sort of farming or liquidity incentives those figures can be quite substantial like for example I won't name names but one of the major AMMs if you want to be like a recognized liquidity farm you have to come up with like a six figure USD amount and that they will match as well.

Uh I'm not sure whether we are seeing the type of interest that would warrant such an expense given that it is a significant amount of money that could be spent on expanding our team expanding our research and stuff like that or even improving our UI.

Now another thing that people have been asking about is the mobile wallet uh you know I'm I'm putting this as a very high priority especially now that Lelantus version one is coming down you know we've got everything down and uh you know we are working hard on on building uh our own native uh mobile wallet so you know we've heard you we have three three developers working on it and hopefully maybe we might want to accelerate it further but we'll see how that goes.

We're also working on a reskin of our electron wallet uh to kind of make it more snazzy it's already pretty good and I think the better has been out.

We're probably releasing a new beta in next one or two days and everyone can give it a go.

We think that's a huge step in improving usability of it but we still think that you know we could look it make it look a lot more sharp and because we believe that you know user experience is really important.

So I hope this kind of covers like you know all the stuff that we've been working on we're really working on cutting-edge privacy technology especially on the research side we have been looking at Lelantus optimization uh I think uh Aaron has come up with like some range proof optimizations.

Aram has been working on a light wallet design where you can sync it without you know downloading the entire blockchain with pretty high you know without like you know without relying on centralized services.

So all of the usability issues um that you know people are facing now we are coming up with very cool solutions up for them.

So I hope that gives you an overview of what we've been doing on the development side uh you know we have also started on the kind of like outreach community outreach side we are starting a Firo volunteer like team where people who want to help with outreach can do so and earn some small amounts of Firo you know it's not gonna like you know it's not gonna be like a full-time job but I think it'd be a nice way to kind of reward people that are passionate you know they have been promoting and talking about Firo and it's a nice way to earn some side income.

Uh so if you are passionate about Firo and you would like to help contribute and get the world out about how cool our Firo is and our technology.

I would really really appreciate that you know uh that makes it a more community effort and you know we want to make sure that we stand on our own benefits there's no need for misleading.

So always be honest if you're part of the volunteer community we definitely do not want to disparage other projects or say untruth so we would heart we hold ourselves to a very high uh I guess like moral standard.

So um if you would like to see more of this let me know in the comments um you know probably I would have more [armor-sessions] you know and maybe in Telegram where people can just pop in and ask questions.

That's a great way but if you have anything you know I'll be looking at the comments so don't hesitate to ask.

So this is Reuben signing off.

Thank you very much.
