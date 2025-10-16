# Fit 4 Fun

Final project for the Building AI course

## Summary

This is an app that tracks your fitness activities. Each fitness goal reached earns the user points. Once a user earns a certain number of points, they can redeem them in exchange for prizes (e.g. discounted flights, dinner for two, theatre tickets, etc.). Activites are tracked via a watch - either a user's personal watch or a fit4fun watch - that connects to the app. Activites are tracked using data such as HR, step count, breathing rate, duration, GPS, etc. Different activities earn different amounts of points (e.g. 10,000 steps per day earns fewer than a 45min interval session). There is a maximum number of points users can earn per day to prevent overtraining.


## Background

People often lack motivation to get in shape for holidays/special occassions, or just in general. This gives them an incentive as it connects the idea of fitness to fun activites. I am an ex-professional athlete, turned personal trainer. I left my 10-year-long athletics career due to a loss of motivation. It was the biggest regret of my life, so I am passionate about helping others remain committed to exercise, whatever level of fitness they may be. Additionally, the younger generations are becoming more interested in fitness, and they also love to track their training. This allows them to earn fun experiences from training and stay committed.


## How is it used?

Fit4Fun is really effective as it can benefit people of any age and any fitness background. Earning redeemable points is just one feature of the app, users will also have access to training programmes, nutrition plans/advice, the option to book into classes/events, and even meet personal trainers. Each user will go through a consultation process (slightly more in-depth PAR-Q). This can be carried out using AI: users will answer a series of health/fitness related questions, AI will then analyse their responses, log the data, and flag any concerns (e.g. individuals with disabilities, or at risk of a stroke etc. will not see the same suggestions on their app's feed as able-bodied people).


<img src="https://github.com/claudialancejones/fit-2-fly/blob/main/girl%20in%20gym.png" width="300">

This is how you create code examples:
```
def main():
   countries = ['Denmark', 'Finland', 'Iceland', 'Norway', 'Sweden']
   pop = [5615000, 5439000, 324000, 5080000, 9609000]   # not actually needed in this exercise...
   fishers = [1891, 2652, 3800, 11611, 1757]

   totPop = sum(pop)
   totFish = sum(fishers)

   # write your solution here

   for i in range(len(countries)):
      print("%s %.2f%%" % (countries[i], 100.0))    # current just prints 100%

main()
```


## Data sources and AI methods
Where does your data come from? Do you collect it yourself or do you use data collected by someone else?
If you need to use links, here's an example:
[Twitter API](https://developer.twitter.com/en/docs)

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

## Challenges

What does your project _not_ solve? Which limitations and ethical considerations should be taken into account when deploying a solution like this?

## What next?

How could your project grow and become something even more? What kind of skills, what kind of assistance would you  need to move on? 


## Acknowledgments

* list here the sources of inspiration 
* do not use code, images, data etc. from others without permission
* when you have permission to use other people's materials, always mention the original creator and the open source / Creative Commons licence they've used
  <br>For example: [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
* etc
