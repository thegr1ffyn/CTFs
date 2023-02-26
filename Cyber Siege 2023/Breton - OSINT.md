# Breton | OSINT | Hamza Haroon

What time and location did I last ping on last year’s Valentine's Day? Fun Fact: Last time I checked I had 1437 pounds in my account and I was tagged in 2020. Flag Format: AOF{xx:xx:xxAM_XXXXXXXXX}

I live here: 

[https://www.youtube.com/watch?v=S8qbu7ZcTYM](https://www.youtube.com/watch?v=S8qbu7ZcTYM)

## Solution:

So we are being asked to find the location and time of ping of something. We are also told that it has 1437 pounds. The other hint tells us that it is under the water, so it makes sense that our subject is a sea creature with 1437 pounds weight. Lets google:

![Untitled](Breton%20OSINT%20Hamza%20Haroon%20fa840591e6734b199e4dc602292ea1e5/Untitled.png)

The first article shows some motivation. Lets see:

![Untitled](Breton%20OSINT%20Hamza%20Haroon%20fa840591e6734b199e4dc602292ea1e5/Untitled%201.png)

So now we have found the name of the shark, Breton. Interestingly, the name of the challenge is also the name of the shark we are talking about.

Now, the challenge asks us to find the location and time when the shark last pinged on Valentine's Day. Now we know that Valentine's Day is on 14 February every year. We are told that we are finding last year's ping. this means that our date becomes 14 February 2022.

Lets research what website tracks shark activities. 

![Untitled](Breton%20OSINT%20Hamza%20Haroon%20fa840591e6734b199e4dc602292ea1e5/Untitled%202.png)

Let's find location of Breton shark.

[OCEARCH Shark Tracker](https://www.ocearch.org/tracker/detail/breton)

![Untitled](Breton%20OSINT%20Hamza%20Haroon%20fa840591e6734b199e4dc602292ea1e5/Untitled%203.png)

Here is our first half of flag.

AOF{7:49:46AM

Now to find second half, we can see on our screen that the location is “Onslow Bay”.

This is our second half.

So the flag becomes:

`AOF{7:49:46AM_ONSLOWBAY}`