https://www.youtube.com/watch?v=KPPH4uSISnI

Hey everyone Spline Apple here with a very special Firo Frontier informational bulletin.

Today we're going to be discussing the attack on our brand new Lelantus protocol that occurred just a few weeks ago.

Before we begin I just want to say that no funds are at risk and we are set to reactivate Lelantus very soon.

So without further ado let's jump right in.

[Music]

Early February an unknown attacker utilized Firo's Lelantus privacy protocol to forge fake proofs  
in an attempt to generate new coins which led to abnormalities in the system.

The Firo team swiftly noticed this and they use their emergency switch functionality to temporarily  
disable Lelantus until the situation could be resolved.

If you're new around here allow me to briefly define the emergency switch functionality.

Basically the community voted for Firo's development team to have a kill switch on the Lelantus protocol for one year.

They did this because with the revolutionary nature of Lelantus even with audits it's possible that an attack was overlooked  
and the switch allowed the team to mitigate damage while resolving the issue.

This is a centralization trade-off but please note a few things.

One the kill switch is temporary and is set to expire after one year from Lelantus activation after which they will not have this power.

Two in hindsight this decision allowed the team to quickly address the problem.

With Lelantus temporarily disabled the attacker is no longer able to use this or any other attack while work is being done to fix the problem.

So what happened I mean wasn't Lelantus audited before we deployed it onto the main net?

Well yeah it was and we did that with some of the best companies in the space in both our cryptographic library and the math behind it.

However in the process of translating the math into the code some things were overlooked with bleeding edge technology comes at risk.

And different people that we've hired after disabling Lelantus have caught these different issues.

I know an issue sounds very vague so allow me to briefly describe the attack.

The attacker forges a spend but in order to make it seem legit he time travels back a bit to set up the necessary events.

More specifically the attacker starts constructing the first proof halfway through though he stops and starts making a different proof.

Upon completing the second one he goes back and edits the first proof doing the necessary back calculation  
to make both proofs work together to make the math check out.

The math in question is making the serial numbers balance to fool the verifier.

If done properly the attacker can duplicate his funds making this a double spending attack.

If that was a little hard to follow this might help.

A normal commitment in the protocol looks like somebody saying I have this list of ingredients I will use them to make this specific dish.

And then the verifiers ensure that the ingredients were indeed in used.

The flaw of the implementation allowed the attacker to announce the dish he was making first  
but then retroactively find the ingredients after his declaration

I hope that helped elaborate the situation a little.

Please be patient as we'll have a more formal presentation of the attack soon in some form.

So with all that in mind what's being done and when will Lelantus come back online?

To the first question earlier in the video I alluded to the fact that we have many different parties  
working behind the scenes to iron out any further issues.

Among them are Trail of Bits who did the initial audit and Dr. Sarang Noether who has  
done work with the Monero research lab in the past.

They join our resident cryptographer Aram and top-notch development team  
in the task of bringing Lelantus back to you all as soon as possible.

To answer the second question we have actually done all the necessary fixes.

We're just taking the opportunity to add several other additions to further bolster safety.

We will be releasing binary sometime next week and activating a week after.

I hope that this update has answered a few questions that anyone might have had regarding this incident.

The Firo team takes privacy very seriously and we want to make sure that everyone is secure using this coin which belongs to us all.

For more information I would strongly recommend checking the Firo forum for this and everything else about Firo

Don't forget to like subscribe and hit the bell notification.

For more of the Firo Frontier and of course more about Firo.

This is Spline Apple signing off.
