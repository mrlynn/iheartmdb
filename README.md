# Atlas Event Ice Breaker - A Poll Example w/ Charts

This is a simple MongoDB Atlas Stitch App using Query Anywhere and MongoDB Charts to ask an ice breaker question to a classroom then plot the results.

It was last used at an Atlas Brewery event, hence the beer question.

To use this for your own event, or for research:

1. Deploy a [https://cloud.mongodb.com](MongoDB Atlas Cluster)
2. Create a [https://docs.mongodb.com/stitch/procedures/create-stitch-app/](Stitch App)
3. Create an [https://docs.mongodb.com/stitch/authentication/anonymous/](anonymous auth provider)
4. Create a [https://docs.mongodb.com/stitch/mongodb/configure-advanced-rules/index.html](rule in Stitch) to allow anyone to read/write their own data to the `welcome.responses` collection
5. Copy stitch app ID and replace it in `index.html`
6. Modify the questions to suit - these are in `poll.html`.
7. Change the `hero.png` image to suit.
8. Create a graph or graphs you want in [https://charts.mongodb.com/](MongoDB Charts)
9. Copy [https://docs.mongodb.com/charts/master/embedded-chart-options/index.html](unverified iframe URL) and add those URLs to the `results.html` `CHARTSURIS` array.
