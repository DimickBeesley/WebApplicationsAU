CSSAssignment-ProlificGrowth	 -	 Dimick Beesley

My experience with animation in CSS and Javascript is very limited, so I wanted to go with a very simple story of growth with a little plant. I wanted to include a hand that followed the cursor and plant the seed. Then have clouds appear and have the user drag it over until it rained and transform the landscape with foliage, but it became clear to me that was a bit ambitious for me with the time and experience I had. I wanted to make all the assets myself so I drew the growing, the blooming plant, and the little hole myself.

For the first transition I thought it made enough sense to just delete the seed div when it collided with the hole image to make it seem as if it had been planted.

I needed a little help from chatGPT to get the second transition from the little plant to the blooming plant. I wanted to have a more smooth interpolation between the two like I was used to in Blender animation, but the best I could coax out of our AI friend was changing the src and playing with opacity so that's what I did.

It seemed like clicking was a pretty straight forward way to trigger the second transition, so I ran with that!

I know it wasn't especially smooth or pretty, but I hope you enjoy it at least a little!