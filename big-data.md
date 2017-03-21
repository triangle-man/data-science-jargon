# Big Data

"Big Data" is more of a marketing term than a term of the art. It means, perhaps, "using all your data to make decisions, not just summaries or samples". Sometimes it means "so much data that you can't store it all on one computer and must use special techniques and systems" (and can therefore be used to sell such techniques and systems).

Traditional statistics is often concerned with what can be learned from either aggregated data or samples of the full set of data. For example, we might conduct an opionion poll using fewer people than the whole population; or we might conduct an agricultural experiment using carefully selected variations of the possible conditions.

This is very useful when data is expensive to collect or to manage. These days, data seems to be available in profusion (although whether it actually carries more _information_ is quite another matter) and so people have thought that perhaps we could use "all the data." Such analysis requires larger databases, faster computers, and sometimes different analytical approaches.

For example, a supermarket might wish to understand its customers' purchasing habits. In the old days, it would perhaps survey a selection of customers and categorise them by how frequently they shopped, how much they spent in each shop, what fraction of the shop is food, and so on. Nowadays, the supermarket knows (or anyway, has in its database) precisely what products each customer put in their trolley on each shop, at least for those customers with loyalty cards. Rather than trying to extract tiny nuggets of information with recondite statistical techniques, the hope is with enough data about sufficiently many different possibilities the answer might be found much more directly.

Surely we must be able to use that data to learn a lot about our customers? 

*Hadley Wickham* has opinined that of all problems classed as "big data", the majority are probably actually "small data" problems once you've chosen the right subset or sample or summary. Of the rest, most are really "lots of small data problems" -- in the example above, perhaps we target each customer with a bespoke offer but use a summary of their spending habits to do so. Only a few problems are "irretrievably big": his example is recommender systems.

See also *the curse of dimensionality*.








