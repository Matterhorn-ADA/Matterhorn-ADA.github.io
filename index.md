---
layout: default
---

## Let's get emotional, we already got physical..

<sup>
Marie Sadler <br>
Pedro Abranches de Figueiredo Simões de Carvalho <br>
Matyas Lustig <br>
</sup>

In our data story we explore conflicts all over the world and the public attention they receive. We harness the huge [GDELT 2.0](https://www.gdeltproject.org/) dataset consisting of events collected every day from thousands media channels of the world's news. We focus on sentiment analysis, on the emotions conflicts tend to arouse with respect to their distinct features. We ask ourselves questions such as whether some regions are payed more attention than others, if news articles get more emotionally involved in conflicts occuring closer to our homes, or whether we tend to depict particular regions, nations or ethnicities by some steady emotional patterns. Throughout our research we hope to lift the shroud of how equally media report on the worlds conflicts and whether some bias exists.
{: style="text-align: justify"}


### Where the news come from ?

<iframe src="https://matterhorn-ada.github.io/urls-log.html" width="100%" height="400px" frameBorder="0" scrolling="no"></iframe>
<br>
On the map we can see the number of news sources per country (on logarithmic scale) from whose GDELT collects the data. The USA outranks other countries massively creating a great bias in our dataset which we further deal with. There is obviously a strong relation between the number of news servers and the significance of the country in the world politics.
{: style="text-align: justify"}


### Do we care about all? (q2 - no of articles / country)
Are some countries ignored in the news? Is the number of conflicts taking place in a country in relation with the number of mentions in the media depending on where the conflict has happened?
{: style="text-align: justify"}

<iframe src="//plot.ly/~matterhorn_ada/3.embed" width="100%" height="400" frameborder="0" scrolling="no"></iframe>

*The number of events reported in the period 2015-2017 are grouped by the countries where they happened and the number of articles sums up all the GDELT news articles these events received. Typically, an event is mentioned in about 5 to 10 news articles, but this number can exceed 100 and more. The size of the bubbles is proportional to the population of the country.*
{: style="text-align: justify"}


### How much is too much? (q4 - bias, corr, norm)
Do we have a saturation limit? Does increasing number of conflicts make people feel worse and worse or is there some limit?
{: style="text-align: justify"}

<iframe width="100%" height="400" frameborder="0" scrolling="no" src="//plot.ly/~StudentUni/3.embed"></iframe>


### How large is our circle of empathy? (q1 - dist and avg tone)
Are we emotionally biased? Do the number of conflicts or their distance from our home define our emotions? 
{: style="text-align: justify"}

If it is not the importance of an event that shapes the emotional tone of an article, is there maybe another feature? From the previous analysis, we gathered that it is rather difficult to associate emotions to events, and that the overall positiveness and negativity of an event might be washed out if calculated by an aggregation of several news sources. We thus dig a step further, and focus on the individual news article reporting an event and we try to see whether the distance between an event and the news article source influence how we perceive the incident. We define an emotional charge which integrates the polarity and the tone of an individual article and look for a trend when plotted against the geographic distance of event and source location. 
{: style="text-align: justify"}

<iframe width="100%" height="400" frameborder="0" scrolling="no" src="//plot.ly/~matterhorn_ada/6.embed"></iframe>

*The emotional charge of an article (measure of polarity and tone) vs the geographic distance between an event and the news source calculated by the Great-Circle distance formula. Only a fraction of the all the GDELT events in the 2015-2017 period is plotted (0.01%).*
{: style="text-align: justify"}

The figure speaks for itself: the number of kilometres separating the event and the source is not in relation with the emotional charge. What about the instinctive impression that controversial events accompanied with emotional debates reach a larger fraction of the population? If we have a closer look at the figure, we see that events occurring in countries where generally a lot of events occur and which are rather countries playing an important role in the international politics have a higher chance to be mentioned all around the globe, than events happening in countries less known in the world (as example, we chose Malawi, a small African country). Hence, it seems as if a breaking news, independent of how emotional or not it is, can reach a large number of people.
{: style="text-align: justify"}


### Are we emotionally predictable? (q3 - model)
Can we observe patterns of emotions with respect to a country, religion or an ethnical group? Can we derive a model predicting emotions in case of a new conflict based on its specific features?
{: style="text-align: justify"}


### Hysteric or ice queen? (q5 - words)
Are some nations more emotional? Do we see sensitivity differences between some countries or actors?
{: style="text-align: justify"}



















> "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Back up your stuff with solid, clean citations. Footnotes can be written in markdown and appear like this.[^1] Use as many as you like.[^2]

### Font awesome is also included

<i class="fa fa-quote-left fa-3x fa-pull-left fa-border"></i> Now you can use all the cool icons you want! [Font Awesome](http://fontawesome.io) is indeed awesome. But wait, you don't need this sweetness and you don't want that little bit of load time from the font awesome css? No problem, just disable it in the `config.yml` file, and it won't be loaded.

<ul class="fa-ul">
  <li><i class="fa-li fa fa-check-square"></i>you can make lists...</li>
  <li><i class="fa-li fa fa-check-square-o"></i>with cool icons like this,</li>
  <li><i class="fa-li fa fa-spinner fa-spin"></i>even ones that move!</li>
</ul>

If you need them, you can stick any of the [605 icons](http://fontawesome.io/icons/) anywhere, with any size you like. ([See documentation](http://fontawesome.io/examples/))

<i class="fa fa-building"></i>&nbsp;&nbsp;<i class="fa fa-bus fa-lg"></i>&nbsp;&nbsp;<i class="fa fa-cube fa-2x"></i>&nbsp;&nbsp;<i class="fa fa-paper-plane fa-3x"></i>&nbsp;&nbsp;<i class="fa fa-camera-retro fa-4x">

<img src="images/hello.svg" alt="sample image">

##### Footnotes:

[^1]: This is a footnote. Click to return.

[^2]: Here is another.
