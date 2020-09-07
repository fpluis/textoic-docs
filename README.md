# Key terms and concepts

Issues such as semantic ambiguity can't be automatically detected, and therefore they are not described here. Here we include only _detectable_ issues.

Of all the issues that a machine can detect, some can be automatically replaced. "We're in the process of remodeling the system" can always become "We're remodeling the system". These are _replaceable_ issues.

Replaceable issues contrast with issues that force a _rewrite_. For example, take the cliche constructions that signal something is the author's opinion, like "As far as I am concerned". If it has already been established that the text shows the author's opinion, they should be removed. Otherwise, there are simpler alternatives like "I believe".

This document covers all the _detectable_ issues handled by Textoic.

# Issues

## Weak language

Using weak verbs like "be", "get" or "become" plus an adjective to express an action that already has a verb. Examples:
1) Become/get smaller => shrink
2) Be unsure => doubt
3) Become aware of => realize

Other instances of weak language are:
1) Weak modifiers like "rather" or "somewhat"
2) Doubting language like "may have been the reason why"

## Replaceable negatives

Every pattern "not + adj/adv/v" where there is an unambiguous complementary antonym. This category includes the double negative. Examples:
1) not sure => unsure
2) not unlucky => lucky
3) not forget => remember
4) not fresh => stale

Negative patterns with ambigous words or gradable adjectives are not included, for example, 
1) not freezing => hot? barely cold? scorching? lukewarm?
2) not leave => take? stay? continue?

# Replaceable intensifiers

Every pattern "very/really + adjective/adverb" for which there is a stronger word. Examples:
1) Very bad => awful
2) Really dry => arid
3) Very large => huge or giant

# Passives

Passive sentences suck the blood out of prose, leaving it cold and impersonal. There are two types of passives depending on whether or not they have an agent:
1) Partial passives: They have no passive agent as in "The fields were covered in snow".
2) Full passive: They have a passive agent as in "Stories were told by the people around the campfire".

Partial passives are the lesser evil: they make sense for events without subjects. Additionally, they can't be automatically rewritten, so it is up to you to rewrite them if you so wish.

Full passives have no excuse. If the sentence structure is simple enough, Textoic will offer a replacement with the sentence already in the positive. Since this is an automatic process, we recommend that you check everything is correct. Also sometimes, converting a bad passive to active exposes other problems.

# Redundancies

Phrases and choices of words that say the same thing twice, such as
1) added bonus => bonus
2) actual fact => fact
3) introduce for the first time => introduce
4) brief moment => moment

# Personal opinion

Constructions that signal something is the author's opinion. Context often dictates whether something is the author's opinion or not, so these constructions are at best noise and at worst pedantic. Examples:
1) From my own personal perspective.
2) The way I feel about it.
3) In my humble opinion (or its abbreviations "imo" and "imho")

All of these can be replaced by "I think" or "I believe". The only acceptable use case is to mark explicitly that something is the author's opinion in a context where there is other people's opinions. For example:
1) (During a conversation) "John says we must wait. _I think_ we should act now".
2) (In an essay) "Some experts claim collapse was unavoidable. I believe it was more likely due to the circumstances at the time".

## Inelegant variation

Some writers use phrases to replace a more common word or phrase for the purpose of not repeating the same words or phrases over and over. There are many such variations which are inelegant and you should avoid:
1) As a result of => because
2) Be cognizant of => know
3) Utilize => use

## Empty phrases

Some phrases are pure noise with no meaning. Removing only improves the writing:
1) All things being equal.
2) At the end of the day.
3) The fact that.

## Cliches

These are overused expressions that most readers have already seen a hundred times before and add nothing new to your writing:
1) Bite off more than you can chew => overextend.
2) Few and far between => scarce.
3) In this day and age => now.

## Filler constructions

Constructions that have simpler replacements that reduce noise. Examples:
1) "it + verb + to + verb" constructions: "It sucks to wait" => "Waiting sucks". 

## Proper punctuation

Matthew Butterick has [a chapter of his book Practical Typography](https://practicaltypography.com/straight-and-curly-quotes.html) explaining the uses of straight and curly quotes. This rule finds single and double quotes and offers to replace them with their curly counterparts.

## Deeply nested clauses

Connecting sentences is one of the main problems a writer faces. Sometimes there are too many ideas in a single sentence, joined through any combination of coordination and subordination. This rule attempts to identify sentences that are too deeply nested, thus making it hard for a reader to follow. 

## Slurs

Insults that target race ("nigger", "spic"), sexual orientation ("faggot", "tranny") or disability ("midget", "retard").

## Sexual words

Sexually explicit nouns ("cock", "tit", "shit) and verbs ("fuck", "cock", "gangbang").
