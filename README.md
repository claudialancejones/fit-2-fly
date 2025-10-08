# Fit 4 Fun

Final project for the Building AI course

## Summary

This is an app that tracks your fitness activities. Each fitness goal reached earns the user points. Once a user earns a certain number of points, they can redeem them in exchange for prizes (e.g. discounted flights, dinner for two, theatre tickets, etc.). Activites are tracked via a watch - either a user's personal watch or a fit4fun watch - that connects to the app. Activites are tracked using data such as HR, step count, breathing rate, duration, GPS, etc. Different activities earn different amounts of points (e.g. 10,000 steps per day earns fewer then 45min run). There is a maximum number of points users can earn per day to prevent overrtraining.


## Background

People often lack motivation to get in shape for holidays/special occassions, or just in general. This gives them an incentive as it connects the idea of fitness to fun activites. I am an ex-professional athlete, turned personal trainer. I left my 10-year-long athletics career due to a loss of motivation. Biggest regret of my life, and I don't want others to make the same mistake, whatever level of fitness they may be. The next generation are becoming more interested in fitness, they also love to track their training. This allows them to earn fun experiences from training, helping them with motivation.

This is how you make a list, if you need one:
* problem 1
* problem 2
* etc.


## How is it used?

Describe the process of using the solution. In what kind situations is the solution needed (environment, time, etc.)? Who are the users, what kinds of needs should be taken into account?

Images will make your README look nice!
Once you upload an image to your repository, you can link link to it like this (replace the URL with file path, if you've uploaded an image to Github.)
![Cat](https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg)

If you need to resize images, you have to use an HTML tag, like this:
<img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg" width="300">

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
