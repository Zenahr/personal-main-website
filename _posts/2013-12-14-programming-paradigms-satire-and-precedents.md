---
layout: post
title: Programming - Paradigms, Satire, and Precedents
date: 2013-12-14 07:28 -05:00
type: post
image: cplusequality.png
categories:
- Rant
tags:
- C+=
---

I'm not normally one to get absorbed into drama or gossip on the internet, but this evening I found myself a bit agitated, but not for the reason you might initially assume.

{% include post_image.liquid filename="cplusequality.png" %} 

#### Introducing C+=
    C+= (pronounced either C-plus-Equality, or See Equality) is a feminist programming language, created to smash the toxic Patriarchy that is inherent in and that permeates all current computer programming languages. Inspired by the <a href="http://www.hastac.org/blogs/ari-schlesinger/2013/11/26/feminism-and-programming-languages" target="_blank">ground-breaking feminist research of Arielle Schlesinger</a>.


C+= was created by the [Feminist Software Foundation](http://feministsoftwarefoundation.org/), whose language philosophy entails the following:

    1. The language is to be strictly interpreted using feminist theory. Under no circumstances should the language be compiled, as compilation and the use of a compiler imposes an oppressive and toxic relationship between the high-level descriptive language and the low-level machine code that does all the labo(u)r. Instead, C+= is interpreted, which fosters communication, itself a strong female trait.


    2. No constants or persistence. Rigidity is masculine; the feminine is fluid. I.e., fluid mechanics is hard for men 'because it deals with "feminine" fluids in contrast to "masculine" rigid mechanics'.

    3. No state. The State is The Man. 'Nuff said. Hence, the language should be purely functional.

    4. Women are better than men with natural language. Hence, the language should be English-based like HyperCard/LiveCode.

    5. No class hierarchy or other stigmata of OOP (objectification-oriented programming). In fact, as an intersectional acknowledgement of Class Struggle our language will have no classes at all.

    6. On the off chance that objects do mysteriously manifest, there should be no object inheritance, as inheritance is a tool of the Patriarchy. Instead, there will be object reparations.

    7. Societal influences have made men often focus on the exterior appearances of women. This poisons our society and renders relationships to be shallow, chauvinistic, and debases our standards of beauty. To combat that, C+= is to tackle only audio and text I/O, and never graphics.

    8. Unicode is the preferred character encoding due to its enabling the diverse aesthetic experiences and functionality that is beyond ASCII. UTF-8 is the encoding of choice for C+=.

    9. Women are more social than men. Hence, social coding should be the only option. The code only runs if it is in a public repo.

    10. Instead of "running" a program, which implies thin privilege and pressure to "work out", programs are "given birth". After birth, a program rolls for a 40% chance of executing literally as the code is written, 40% of being "psychoanalytically incompatible", and 40% of executing by a metaphorical epistemology the order of the functions found in main().

    11. Programs are never to be ["forked"](https://en.wikipedia.org/wiki/Fork_(system_call)), as the word has clear misogynistic tendencies and is deeply problematic. Instead, programmers may never demand "forking", but ask for the program to voluntarily give permission. "Forking" will henceforth be called "consenting", and it is entirely up to the program to decide if the consent stands valid, regardless of the progress of the system clock.

    12. Forced program termination is not allowed unless the program consents to it. The process is part of the choice of the program, not the programmer.

    13. Licensing: the Feminist Software Foundation License.


Here is some example FizzBuzz code written in C+=:

    #consider <FEMINIST_RAGE.Xir>;

    // TODO replace main() as Progrym entry point; "structured
    // programming" is classist oppression
    // TODO2: main() is now womain()

    // NB one does not argue with C+= Progryms; one makes requests, which
    // the Progrym is free to consider or ignore as she pleases
    xe womain (xe RequestCount, strong *RequestList[]) {
    // NB typically patriarchal fizzbuzz enshrines socially
    // constructed limits as immutable fact; here we expose this
    // subtle mental tyranny for what it truly is

    xe ArbitraryBeginning accepts(present(-50));
    xe ArbitraryEnd accepts(present(50));

    // naturally, everything revolves around this
    xe ThePlaceBetween accepts(present(0));

    among(ThePlaceBetween accepts(ArbitraryBeginning),
          ThePlaceBetween honors(ArbitraryEnd),
          ThePlaceBetween improvesBy(present(1))) {
        check(ThePlaceBetween envelops(present(3))) {
            yell(present("Fizz"));
        }
        recheck(ThePlaceBetween envelops(present(5))) {
            yell(present("Buzz"));
        }
        unpack {
            // strength &amp; independence!
            yell(present(ThePlaceBetween));
        };

        yell(present("\n"));
    };
    present(Satisfaction);
};

By now, I hope you would realize that this is in fact satirical. Personally, I found the whole thing quite humorous and well-constructed in regards to the amount of effort and detail put into it, code examples and all. Now I know what you're thinking. "Gee, how will satire mocking feminism be perceived on the internet?". This is where things get interesting... 


{% include post_image.liquid filename="cplusequality-cloudflare.png" class="center-block" %} 

The project was initially hosted on [Github](https://github.com/FeministSoftwareFoundation/C-plus-Equality), that is until Github decided to pull it due to harassment complaints. Who was being harassed? Nobody. At least not by the project owners. It seems that there were various people, namely feminists, who were being impersonated and had commits to the project being sent under their fraudulent identities. Maybe I'm missing something, but it seems just a **tad** bit excessive to close the entire repository for an incident caused by a few select individuals who didn't even own the repository. The project eventually moved to [BitBucket](https://bitbucket.org/FeministSoftwareFoundation/c-plus-equality) and the [complaints](https://bitbucket.org/site/master/issue/8629/harassing-repository) soon followed, just as baseless and shallow as before. There were even individuals trying to get the domain dropped by CloudFlare. It became quite apparent that these people were acting on emotion and not any sort of actual logic. Naturally, as with any ethical "debate", there is a astounding amount of hypocrisy and generalizations that just point out the inconsistencies (or possible similarities) between the two parties.

{% include post_image.liquid filename="cplusequality-generalizations.png" class="center-block" %} 

Some people lack the ability to separate a difference of opinion and actual harassment. Pointing fingers at the wrong people (the repository owner) just makes it worse. Just because you don't agree with the project ethically is no excuse for blatant censorship, it doesn't matter how to try to spin it. If you do succeed with censoring the other party, you should be aware of the [Streisand effect](http://en.wikipedia.org/wiki/Streisand_effect). This becomes even more crucial when you consider that the project was spawned out of 4chan.

Overall, I am quite disappointed in Github for the way that they handled (or mishandled rather) this situation. In an attempt to save face, they jumped the gun and quite possibly set a precedent for similar situations in the future. A repo owner should not have to do background checks on each individuals wanting to commit. The entire situation is a result of hypersensitivity and some people's inability to take into consideration that their outlash could have real world effects. An incident involving [gendered pronouns](https://github.com/joyent/libuv/pull/1015) a few weeks back was depressingly similar.

It's quite obvious that this project is misogynistic, satirical or not, but that's not the problem I have with it. My issue with this whole situation is the blatant censorship and corrosive mindset of "I don't like this, take it down" that constantly plagues the internet. People need to learn to value free speech over their own ideals, otherwise we're looking at a very bleak future. Attempting to censor those with different opinions will only promote chilling effects, encourage polarization of those involved, and further degrade any sense of intelligent discussion there may be.

As of writing this, BitBucket has not removed the repository. Jesse Yowell from Atlassian has stated:

    We are aware of this and it is currently being reviewed by our legal team.



Hopefully they will properly think this through, not just for public relations sake, but for the long-term effects it could pose. It'd be a shame to see them make the same mistake as Github.

C+= Sources:

[Homepage](http://feministsoftwarefoundation.org/)

[BitBucket Repo](https://bitbucket.org/FeministSoftwareFoundation/c-plus-equality)

#### Update 12/15/2013
Erik van Zijst of Atlassian has [stated](https://bitbucket.org/site/master/issue/8629/harassing-repository#comment-7363170) that they will not be removing the repo:

    We have no intentions to censor at this point.

#### Update 12/19/2013
Contradicting the previous statement, the repo has been removed (along with forks, both public and private). Scott Farquhar has [commented](https://bitbucket.org/site/master/issue/8629/harassing-repository#comment-7416620) stating:

    After further consideration, we have decided to remove this repository. While our End User Agreement explicitly prohibits the posting of content that is "racially or ethnically offensive," we believe it is consistent with the spirit of our agreement to also prohibit content that is offensive toward a specific gender. We will update our End User Agreement to make this prohibition more explicit.


Great job, updating your end user agreement for the sake of saving face.

