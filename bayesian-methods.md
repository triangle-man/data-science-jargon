# Bayesian methods

At the beginning of Tom Stoppard's play _Rosencrantz and Guildenstern are Dead_, the two eponymous characters are playing a game: Guildenstern is throwing coins, and Rosencrantz is guessing "heads". It's always heads.

 ROS: Eighty-five in a row - beaten the record!

GUIL: Don't be absurd.

 ROS: Easily!

GUIL (angrily): Is that it, then? Is that all?
 
 ROS: What?
 
GUIL: A new record? Is that as far as you prepared to go?

 ROS: Well...

GUIL: No questions? Not even a pause?

 ROS: You spun it yourself.

GUIL: Not a flicker of doubt?

Guildenstern has -- like you and me -- a certain belief in the likelihood of a coin coming up heads: namely, he _strongly believes_ that it's as likely to come up heads as tails. Given that belief, the empirically observed data (85 heads in a row!) is _extremely_ surprising. So surprising, in fact, that Guildenstern is moved to re-examine those beliefs he has previously so firmly held.

Guildenstern is a Bayesian. He starts with a belief about the world, then he determines how surprised he is by the way the world is, given his belief: if he is very surprised, he alters his belief; if he is not very surprised, he sees no great reason to change his mind.

(It's less clear to me what Rosencrantz is thinking. Certainly, he is not very surprised.)

Of course, all of this really ought to be encoded by numbers, specifically as probabilities. *Bayes' rule* (or *Bayes' theorem*) is a principled method for doing what Guildenstern is doing intuitively. It's the rule that tells Bayesians how to compute their new beliefs (expressed as probabilities) from their original ones, in the light of data. Just for this reason, Bayes' rule is at the heart of some machine learning systems. *Bayesian methods* (in statistics, or machine learning) are those which make of Bayes' rule to allow the system to learn from data.

Incidentally, there's a particular jargon that goes along with all this: One's original belief is called one's _prior_ (meaning, one's prior view of the probability of world being a certain way; prior, that is, to seeing some data); and likewise one's revised belief is called the _posterior_.

One might wonder, aren't we all Bayesians? In a sense we are. There are many situations in which everyone agrees that Bayes' rule is the right rule to use. 

But there are also certain philosophical differences between statisticians. I am never entirely sure how deep these differences run but one can see them at play in the decision in 2013 of the England and Wales Court of Appeal (Nulty & others v Milton Keynes Borough Council). The judge wrote (in paragraph 37):

> The chances of something happening in the future may be expressed in terms of
> percentage. Epidemiological evidence may enable doctors to say that on average
> smokers increase their risk of lung cancer by X%. But you cannot properly say
> that there is a 25 per cent chance that something has happened [...]. Either
> it has or it has not.

To a Bayesian, probabilities can, in fact, be used to quantify our _degree of belief_ in something about which we are uncertain, including past events; they are, moreover, the _correct_ way to express this uncertainty. 

See also: *Frequentist*.

