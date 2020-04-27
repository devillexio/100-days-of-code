# 100 Days Of Code - Log

### Day 1: April 4, 2020

**Today's Progress**: Created the repo for the toy project. Set up command line argument parsing to get the country slug from the user. Chose to use the [Coronavirus COVID19 API](https://covid19api.com), which has good documentation. Made the API call and figured out how to process the response body JSON. Used goroutines and a channel to get the different statuses.

**Thoughts:** I've done a lot of Golang tutorials and reading over the last year, but I'm really excited to build something that is mostly fun and semi-useful. The COVID19 pandemic is bascically going to dominate much of our lives for at least the next while, so I thought why not let something positive come out of it and learn something new.

**Link to work:** [covid19](https://github.com/devillexio/covid19)

### Day 2: April 5, 2020

**Today's Progress**: Researched how command line flags work in #Golang. Didn't end up using them, but learned something new! Also added a calculation for the "active" status on the covid19 command line utility, saving the need for another API call.

**Thoughts:** I quite like the way Golang's standard library supports command-line flags. I may try build a different utility soon to play around with another API, and maybe work with some less depressing data. Not quite sure yet, but I know it'll be fun and probably have something to do with cats!

**Link to work:** [covid19](https://github.com/devillexio/covid19)

### Day 3: April 6, 2020

**Today's Progress**: Did a Binary Search exercise on the #Golang track of exercism. Really can't recommend @exercism_io enough. Great platform with excellent humans!

**Thoughts:** It's been a while since I've done a Binary Search. Was a good opportunity to use a `for` and `switch`.

**Link to work:** [exercism.io](https://exercism.io/tracks/go/exercises/binary-search/solutions/8b8baa3968c442aeb474ad3b1d61ccd1)

### Day 4: April 7, 2020

**Today's Progress**: Read the guides for Battlesnake and cloned the starter project for Go. Excited to get into the details over the coming days and joining the various tournament streams on Twitch!

**Thoughts:** I was really bummed out when Battlesnake 2020 was cancelled because of the _pandemic that shall not be named_. Luckily the decision was made to make it an all online event!

**Link to work:** [sawtooth](https://github.com/devillexio/sawtooth)

### Day 5: April 8, 2020

**Today's Progress**: Spent time reading up on different approaches for playing the game of snake. Also watched interviews with previous tournament winners. Definitely going to have to start simple. Will look into basic obstacle avoidance next.

**Thoughts:** I'm both excited and overwhelmed by the challenge. Since this is the first time I'm doing something like this, I'm going to take the advice of one of the contestents and start with very simple obstable avoidance.

**Link to work:** [sawtooth](https://github.com/devillexio/sawtooth)

### Day 6: April 9, 2020

**Today's Progress**: Got "The Go Programming Language" book and started reading the chapter on testing. I thought I might as well start dabbling with unit testing as well!

**Thoughts:** Happy that I bought a couple of Golang books. It's been a few years since I've read programming books. I usually find them tedious and often outdated. Luckily with Golang's philosophy of keeping the language relatively simple and stable, the books are still very relevant even after a few years.

**Link to work:** [sawtooth](https://github.com/devillexio/sawtooth)

### Day 7: April 10, 2020

**Today's Progress**: Took the day pretty easy and continued to read "The Go Programming Language." Interesting reading about the origin of #Golang and the language that inspired it

**Thoughts:** I'm really enjoying learning about the origins of Golang and what I would describe as the ethos of the language. It really reminds me of why I fell in love with programming to begin with.

### Day 8: April 11, 2020

**Today's Progress**: I watched the Battlesnake tutorial on getting started with Go, and felt inspired to complete a simple snake. I also added tests, which was new and fun! I decided to enter the Rookie division for the "Stay Home and Code" Battlesnake tournament, 'cause why not!

**Thoughts:** I hit the reset and started from scratch with my Battlesnake. I chose to not worry about hunting food or avoiding enemies and instead focus on just avoiding walls. I wasn't going to enter this year's competition but thought I have nothing to lose.

**Link to work:** [sawtooth](https://github.com/devillexio/sawtooth)

### Day 9: April 12, 2020

**Today's Progress**: Wrote some pseudocode for the next iteration of the Battlesnake I'm working on. The next thing to add is some basic collision detection. Having a lot of fun with it.

**Thoughts:** I'm really enjoying Golang and Battlesnake. I'm excited about adding some more complicated logic over the coming days. I also like the fact that I'm adding tests as I go, so I don't break existing logic while working on new features.

**Link to work:** [sawtooth](https://github.com/devillexio/sawtooth)

### Day 10: April 13, 2020

**Today's Progress**: Finished chapter 1 of The Go Programming Language. Also decided to create another Battlesnake with a slightly more sophisticated strategy. Really enjoying applying TDD to the process!

**Thoughts:** I'm taking my time with the book (The Go Programming Language). I want to absorb as much as possible and also give myself a chance to try all of the challenges at the end of each section.

I also decided to rather create another snake than to update the wall-hugging Sawtooth. This will give me more freedom to start from scratch and to see what happens.

**Link to work:** [rockmaw](https://github.com/devillexio/rockmaw)

### Day 11: April 14, 2020

**Today's Progress**: Added wall avoidance to the Battlesnake, as well as calculating where the nearest food is. Continuing to also add unit tests as I go along. So far so good!

**Thoughts:** Enjoying working on Battlesnake a lot. I'm quite excited to finish up the logic and see how it performs against my previous, simpler version. 

**Link to work:** [rockmaw](https://github.com/devillexio/rockmaw)

### Day 12: April 15, 2020

**Today's Progress**: Finished the first version of the Battlesnake and entered it into the Rookie league! The best thing was I only worked off of my unit tests and it worked perfectly on the first try after deployment! #ThePowerOfTests

**Thoughts:** I was super surprised and happy to see that the Battlesnake worked as intended first time after deployment. It just goes to show the importance of unit tests, and the power of TDD! I think I've solved most of the easy tasks and looking forward to tackling some of the more complicated problems.

**Link to work:** 
- [rockmaw](https://github.com/devillexio/rockmaw)
- See "Rockworm" on [Battlesnake.io](https://play.battlesnake.com/arena/stay-home-and-code-rookie/)

### Day 13: April 16, 2020

**Today's Progress**: Added head-to-head collision avoidance to the Battlesnake. Struggling to figure out how to prevent the snake from blocking itself in, but I'll get there!

**Thoughts:** Today was equally rewarding and frustrating. Made progress on both head-to-head collision detection and avoiding boxing in oneself. Still have some work to do on the latter.

**Link to work:** 
- [rockmaw](https://github.com/devillexio/rockmaw)
- See "Rockworm" on [Battlesnake.io](https://play.battlesnake.com/arena/stay-home-and-code-rookie/)

### Day 14: April 17, 2020

**Today's Progress**: Added logic to prevent the snake from being trapped. Not completely happy with the way it turned out. Still had fun and learned a lot though!

**Thoughts:** I really don't like the latest code I've written. I think I'll give it a few days and then revisit it.

**Link to work:** 
- [rockmaw](https://github.com/devillexio/rockmaw)
- See "Rockworm" on [Battlesnake.io](https://play.battlesnake.com/arena/stay-home-and-code-rookie/)

### Day 15: April 18, 2020

**Today's Progress**: Took it easy and continued reading Chapter 2 of "The Go Programming Language".

**Thoughts:** The more I read this book, the more I just love Go. I think you need to know a couple of languages, and have been coding for a few years to fully appreciate Golang's design choices. Before trying Go I read a lot of "Go vs <insert language here>" articles, but I realise now these articles often bashed Golang without fully understanding it's purpose.

### Day 16: April 19, 2020

**Today's Progress**: Finished reading Chapter 2 of "The Go Programming Language". I also watched a live stream by Battlesnake where they discussed some easy strategies and tactics. I'm quite keen to apply some of these to the snake I'm working on.

**Thoughts:** Really enjoyed the presentation by Aurora Walker during the Battlesnake live stream. I enjoyed her methodical approach to tackling one problem at a time, and I'm also keen to give some of the strategies a try.

### Day 17: April 20, 2020

**Today's Progress**: Did some cleanup of the code after attending the Battlesnake workshop by Aurora Walker. Excited to add some additional strategies over the next few days.

**Thoughts:** I had some time to reflect on Aurora's talk and she really did a good job of breaking down the concepts - got me re-energized to make some improvements to my Battlesnake code.

**Link to work:** 
- [rockmaw](https://github.com/devillexio/rockmaw)
- See "Rockworm" on [Battlesnake.io](https://play.battlesnake.com/arena/stay-home-and-code-rookie/)

### Day 18: April 21, 2020

**Today's Progress**: Continued working on refactoring the Battlesnake code. Completed the code cleanup and started working on a second strategy.

**Thoughts:** Slow and steady wins the race. Not making huge progress every day, but happy that at least some progress is being made.

**Link to work:** 
- [rockmaw](https://github.com/devillexio/rockmaw)
- See "Rockworm" on [Battlesnake.io](https://play.battlesnake.com/arena/stay-home-and-code-rookie/)

### Day 19: April 22, 2020

**Today's Progress**: Fixed up the second strategy. There are still some bugs, but I'm pretty happy with the progress. It should be good enough for the tournament this weekend.

**Thoughts:** It's really true what they say. Battlesnake is easy to understand, but very difficult to master. Lots of fun, with just a touch of frustration. :-)

**Link to work:** 
- [rockmaw](https://github.com/devillexio/rockmaw)
- See "Rockworm" on [Battlesnake.io](https://play.battlesnake.com/arena/stay-home-and-code-rookie/)

### Day 20: April 23, 2020

**Today's Progress**: Reading Chapter 3 of The Go Programming Language. Busy learning about the basic types.

**Thoughts:** The last few days have been tough and it's been difficult staying motivated. This is probably mostly due to what's going on with the world. Just taking everything day by day.

**Link to work:**
- [The Go Programming Language](https://www.gopl.io) book

### Day 21: April 24, 2020

**Today's Progress**: Continued reading Chapter 3 and attended some excellent Battlesnake workshops.

**Thoughts:** Really impressed with the Battlesnake community and the quality of the workshops they organized.

**Link to work:**
- [The Go Programming Language](https://www.gopl.io) book

### Day 22: April 25, 2020

**Today's Progress**: Watched the Battlesnake Stay Home and Code live event and finished Chapter 3 of “The Go Programming Language”. Well done to all the teams that competed, and congratulations to the winners! 

**Thoughts:** Quite impressed with the quality of the Battlesnake tournament and I'm happy that I got to take part, even though my snake's performance was pretty dismal. :-)

**Link to work:**
- [The Go Programming Language](https://www.gopl.io) book

### Day 23: April 26, 2020

**Today's Progress**: Continued reading The Go Programming Language. Busy with Chapter 4 now. Really enjoying the ebook version but thinking of getting a physical copy too. This is such a great reference to have around. 

**Thoughts:** I'm surprised at how much I'm learning from this book. I'm never been a big fan of learning programming from books, but I've been really surprised by this one.

**Link to work:**
- [The Go Programming Language](https://www.gopl.io) book
