<p align = "center" draggable=”false” ><img src="https://user-images.githubusercontent.com/37101144/161836199-fdb0219d-0361-4988-bf26-48b0fad160a3.png"
     width="200px"
     height="auto"/>
</p>

# <h1 align="center" id="heading">Monitoring Drift</h1>


## Background
*Please review the weekly narrative [here](https://great-yamamomo-5c3.notion.site/Week-15-Monitoring-and-Automating-ML-Workflows-and-Pipelines-bfaed8129b4d49b8a888dd48f1d54ad1)*

It's important to continously monitor your models as to keep track of data and model drift. A good example of what happens when note monitoring is [Tay](https://en.wikipedia.org/wiki/Tay_(bot)), a chatter bot on twitter that went from giving pleasant greetings to tweeting explicit and racist remarks in under 16 hours by learning off of others. To make sure our model is always focusing on the features we're interested and keeping a consistent behavior in its predictions, we need monitoring.

## :hammer_and_wrench: Pre-Work
The requirements for this week are:
- `docker`
- `requests`
- `sklearn` (in requirements file to be installed)
- `boxkite` (in requirements file to be installed)

