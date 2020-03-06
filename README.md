# Atlas Event Ice Breaker - A Poll Example w/ Charts

This is a simple MongoDB Atlas Stitch App using Query Anywhere and MongoDB Charts to ask an ice breaker question to a classroom then plot the results.

To use this for your own event, or for research:

1. Deploy a [MongoDB Atlas cluster](https://cloud.mongodb.com)
2. Create a [Stitch App](https://docs.mongodb.com/stitch/procedures/create-stitch-app/)
3. Create an [anonymous auth provider)[https://docs.mongodb.com/stitch/authentication/anonymous/)
4. Create a [rule in Stitch)[https://docs.mongodb.com/stitch/mongodb/configure-advanced-rules/index.html) to allow anyone to read/write their own data to the `welcome.responses` collection
5. Copy stitch app ID and replace it in `index.html`
6. Modify the questions to suit - these are in `poll.html`.
7. Change the `hero.png` image to suit.
8. Create a graph or graphs you want in [MongoDB Charts](https://charts.mongodb.com/)
9. Copy [unverified iframe URL](https://docs.mongodb.com/charts/master/embedded-chart-options/index.html) and add those URLs to the `results.html` `CHARTSURIS` array.
