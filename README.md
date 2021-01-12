# EXPERIMENT: Sound Art with AI
**Final project for the Building AI course**

I wanted to do something with machine learning and sound. I also wanted to learn how to make use of open source code shared in Github.

So I downloaded [the AI Drum Machine](https://github.com/googlecreativelab/aiexperiments-drum-machine), learned to make it work and added new sounds to it.

## Summary
<!--test-->
* I wanted to learn about AI methods and classifying sound
* The project has a sonic outcome, which is interesting
* I wanted to learn how to experiment with open source code shared in Github.

## Problems it will solve

Which problems does your idea solve? How common or frequent is this problem?

This is how you make a list, if you need one:
* problem 1
* problem 2
* etc.

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

### How is it used?

* Find project in [Experiments with Google](https://experiments.withgoogle.com/experiments)
* Download (or fork) project [from the repository](https://github.com/googlecreativelab/aiexperiments-drum-machine)
* Set up node and webpack
* import sounds from the Sonic Pi sound collection
* run the program and experiment!


## Challenges

My skills are limited, it will take me a while before I can contribute to the project through Github


### Data sources
Code created by [Kyle McDonald](https://github.com/kylemcdonald), [Manny Tan](https://github.com/mannytan), [Yotam Mann](https://github.com/tambien), and [Google Creative Lab](https://github.com/googlecreativelab/). 
Copyright 2016 Google Inc. All Rights Reserved.

Licensed under the Apache License, Version 2.0

Sound samples: 
* freesound.org, only samples licenced [CC0](https://creativecommons.org/publicdomain/zero/1.0/)
* samples from Sonic Pi programming environment, licenced [CC0 1.0 Universal Public Domain Dedication](https://creativecommons.org/publicdomain/zero/1.0/)


## AI methods used

t-SNE ( t-Distributed Stochastic Neighbor Embedding)

I had no idea something like this existed, now I'm going through a [description of the method here](https://medium.com/analytics-vidhya/what-is-t-sne-37bfb920e431).

And I'm trying to identify concepts that are now familiar to me thanks to Elements of AI courses.

t-SNE concepts I'm somehow familiar with

nearest neighbor, Euclidian distance, clustering, supervised learning...

## What next?
I'd like to improve the drum sequencer part in this project. Adding the option to use some Garageband type of rhythm patterns which are musically more pleasant would be great.
