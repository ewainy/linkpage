# Linkpage
Sweet and simple page for links which include an image, an about section, social links and twitter timeline preview.

## About
Includes: 
- An avatar style image with descriptive alt text
- My name
- About me and my tech experience, with keywords highlighted in pink

## Links
Includes: 
- Link for LinkedIn
- Link for GitHub
- Link for Portfolio (Under Construction and stylised accordingly)
- Link for Hashnode Blog

Links have a gradient background colour and hover effects to include a multi-colour glow, movement and slower transition

## Tweets
**Additional Feature**
Includes 
- A heading and my twitter handle
- Twitter timeline embedded

### Twitter timeline embed
The twitter timeline inherits height and width from it's parent so I :

- gave it a height of 500 
- wrapped it in a div tag so I can customise it
- In my styles sheet I gave the div a width of 48% to look as close to buttons for full screen
- In my styles sheet I gave the div a width of 75% for mobile view

**data-chrome**
With data chrome attribute you can customise the twitter embed, I chose:

- Transparent
- No header
- No footer
- No borders

Transparent on it's own doesnt seem to work for me so I also targetted .twitter-timeline to add transparency

I then styled my div with gradient colour background, a black curved border and some padding and margin.


[Link to twitter docs - timelines](https://developer.twitter.com/en/docs/twitter-for-websites/timelines/overview)


