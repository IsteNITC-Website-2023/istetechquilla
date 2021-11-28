+++
author = "Aadarsh Jayadeep"
cover = "/images/techquilla-draft-spotify.jpg"
date = 2021-11-27T19:30:00Z
description = "Inside the magic behind Spotify’s recommendation algorithm."
designer = "G M Himalatha "
tags = []
title = "Decoding Spotify's Recommendation Algorithm"

+++
Since the dawn of the internet, the music industry has faced a myriad of changes. From the launch of iTunes and the iPod to the emergence of music streaming business models, there have been quite a few changes in how people listen to music. One of the biggest epithets in music industry products to come out in the last 15 years is Spotify. The Swedish music streaming service has an impressive catalogue and has achieved an explosive level of popularity.

Spotify researchers have developed a vast number of endorsement engines featuring AI. The two main Spotify features which utilize the implemented AI and recommender systems are its Home screen and Discover Weekly. From Spotify’s Discover Weekly service, these playlists were carefully curated by an algorithm and the more you use Spotify, the better it perceives you and ameliorates your recommendations. Since the launch of its service, it has gained over 150 million paid subscribers and tracks from its playlists have been streamed 1.7 billion times!

Let’s say that someone uploads a song to Spotify. It only has 25 listeners and no mentions on the internet. For this song to end up on someone’s Discover Weekly playlist, Spotify must use the raw audio model, which analyzes the audio of a song to see the similarities between other songs. What are the consequences of biased recommendations in a subscription-based service like Spotify? The repercussions are small for the consumer. But it was actually the unexpected COVID-19 pandemic that solidified the foothold of digital streaming, with subscription services seeing massive growth over the last year. Although it was expected that many new services would flounder along the way, media subscription services saw wide-scale growth and adoption almost across the board.

Spotify uses the stream counts of the tracks that people listen to as well as other data points that route if the user added the song to a playlist or went to the artist’s page. The platform is constantly watching how its hundreds of millions of users enlist different types of music in order to feed them more of what they like.

![](/images/spot1.png)

Just like other social media platforms, Spotify’s algorithm is driven by statistics. Spotify, unlike Netflix, does not have a star rating for its songs. Instead, Spotify is driven by implicit feedback, i.e., it isn't based on ratings but on the user’s interaction with its software. The main innards in Discover Weekly, it turns out, are other people. Spotify begins by looking at the 4 billion or so playlists created by its users - each one a reflection of some music fan’s tastes and sensibilities. Those human selections and the array of anthems form the core of Discover Weekly’s recommendations.

#### **_The 30-second Spotify-friendly rule:_**

Spotify’s sweet spot for comprehending whether a user relishes a song seems to be 30 seconds. If a listener gets past the 30-second mark of the track - that’s a positive hint of data. Plus, that’s the point at which a stream is monetized. The spike in listeners, truncated skip times and listening to tracks just after release trigger the engine to drive other patrons to recommend these based on the experience of other listeners on the same tenet.

#### ![](/images/spot2.png)

In a 2015 interview with Quartz, Spotify's Product Director, **Matthew Ogle,** who has since resigned from the company, mentioned that skipping before the 30-second mark is the equivalent of a thumbs down for the Discover Weekly playlist. The algorithm seems to be working very well for the streaming giant among other competitors.

#### **OKAY, IT’S POPULAR. BUT WHY?**

The first contrivance one notices on Spotify is on the home screen, where the computation starts and is governed by an AI system called _BaRT - Bandits for Recommendations as Treatments_. BaRT is the reason why one doesn’t go on searching for an appropriate playlist to listen to on Spotify. BaRT’s outcome totally depends on whether one listens to the tracks recommended in the ‘shelves’ or ‘rows’ on their home screen. _Collaborative filtering_ is one of the basic techniques for building recommender systems. In terms of Spotify, Discover Weekly and other playlists are created using collaborative filtering, based on the user’s listening history, in tandem with songs enjoyed by users who seem to have a similar history. Additionally, Spotify uses “Taste Analysis Data” to establish a Taste Profile. This technology, developed by Echo Nest, groups music users who frequently listen to into clusters and not genres, as the human categorization of music is largely dependent and are evident in Spotify’s Discover Weekly and Daily Mix playlists intimation, clustering algorithms that agnate to Spotify’s group data based on their resemblance.

![](/images/spot3.jpg)

The company makes it clear in research that the success of all these algorithmic services is only possible because every action you make on the service is tracked and logged. Take, for instance, _automatic playlist continuation_. This feature analyzes the songs in a certain playlist and tries to predict the music that would come next - as if the person who created it had just kept adding music. Spotify wanted new ways to think about how it should be fabricating those features, so it released a “Million Playlist Dataset” of user-generated Spotify playlists that could be used to understand the traits of what humans scrutinize a good set of tracks.

Algorithms can be tucked into all sorts of crevices on Spotify. As many other companies do, Spotify brands its technical innovations in order to indicate an original approach to a known challenge. As presented in this article, everything can be boiled down to basic AI tools. So if we put aside a large amount of data needed to train these models, anyone who understands these mathematical solutions can make their own recommender system. It is important to remember, however, that ultimately these algorithms are trained and designed. Despite the often hyperbolic coverage it receives, the overarching umbrella of AI in and of itself relies heavily on machine learning and ML fairness.

> _Aadarsh Jayadeep_