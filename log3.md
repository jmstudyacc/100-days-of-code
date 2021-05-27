# 100 Days Of Code - Log

### Day 51: May 14, 2021

**Today's Progress**: More work on Concurrency Utilities in Java. Wrapping up the section on Semaphores and moving on to CountDownLatches

**Thoughts:** Pretty interesting seeing how the different synchronization methods work. Enjoyed playing around with the Semaphores to effectively break the program or change the order of the program. Bears remembering that these are just synchronization tools. You can make the thread do whatever you want when the permit is provided!

**Link to work:** 
https://github.com/jmstudyacc/java_practice


### Day 52: May 15, 2021

**Today's Progress**: Sharpening skills again on Hackerrank ahead of Wednesday exam

**Thoughts**: Not a great session today, pretty tired and struggled to really get to grips with the work. Some work on Hackerrank and looked into the BigDecimal problem that was lingering. Don't fully understand the solution so some debugging needed to see it in action.

**Link(s) to work**:
https://github.com/jmstudyacc/java_practice


### Day 53: May 16, 2021

**Today's Progress**: Working through the Mock exam for the PoP2 Java exam on Wednesday

**Thoughts**: It was really easy. Too easy if the PoP1 exam is anything to measure against. I will continue with the 2019 and 2020 exam papers as I aleady know they are more difficult. Biggest concerns for me right now? A coherent approach to constructing classes probably and my arch-nemesis Matrices.

**Link(s) to work**:
https://github.com/jmstudyacc/java_practice


### Day 54: May 17, 2021 

**Today's Progress**: Worked through the Jun 2019 mock exam

**Thoughts**: On the whole I think it was a positive experience, there was one problem that I really struggled with and that was using HashMaps in a way to store days values and the values of those days. Mental gymnastics for me to get through that even with the solutions provided - took plenty of notes on it and tried to understand it better. The rest of the exam was easier to wrap my head around. The same can be more or less said for the 2020 exam paper, but the difficulty could vary so wildly!

**Link(s) to work**:
https://github.com/jmstudyacc/java_practice


### Day 55: May 18, 2021 

**Today's Progress**: Worked through lambda expressions to have some understanding of them

**Thoughts**: Lambda expressions are pretty powerful and feel somewhat similar to Match statements that I've come across before in Rust. The work on Lambdas has helped improve my understanding of where they appear somewhat in Rust. It was a pretty cool session today, see how you can take an expression and reverse strings, toggle cases and replace chracters.

**Link(s) to work**:
https://github.com/jmstudyacc/java_practice


### Day 56: May 19, 2021

**Today's Progress**: Java exam today and did some studying up on Iterators() in Java

**Thoughts**: Bliss, finally finished with my obligation to learn Java. That may change if I pass my core exams and go back for the 2nd year. However, at present I am going to forget about it as I've never really been a fan. Looked at Iterators() today as deleting from an arraylist is a damn nightmare and more Lambda expression studies.

**Link(s) to work**:
[Update once timings allow]


### Day 57: May 22, 2021 

**Today's Progress**: Working on Unity Game Development

**Thoughts**: Well, my streak was officially broken! Not that I care, I'm just going to carry on with the challenge as usual. I have been spending a few days on trying to play with Unity to make some games. I don't yet know how to upload games properly to Unity but once I do I'll provide a link!

**Link(s) to work**:


### Day 58: May 23, 2021 

**Today's Progress**: Further work on Unity game dev

**Thoughts**: Animated my player now! The charcater has an idle animation, a walk animation and a jump animation. I need to investigate how we would go about creating a sliding aniamtion. I have got the animation clip ready, but need to think about how the code will work. Also, not yet implemented a means of checking for key double presses...

**Link(s) to work**: Unity + GitHub still eludes me


### Day 59: May 24, 2021 

**Today's Progress**: Rust is back on the menu!

**Thoughts**: Today saw me going gladly back to Rust as I took notes on error handling in Rust. Plenty more work to get through before I understand it. So far I've looked at the concepts of recoverable & unrecoverable errors, the panic! macro and what happens by default (walking up the stack and cleaning it). Also been checking out the Result<T, E> enum to see how that works - looks like my previous work with Generics in Java helps fill that gap!

**Link(s) to work**:
No links at present, but I have something greater planned for these notes...

### Day 60: May 25, 2021

**Today's Progress**: Further work on Error Handling

**Thoughts**: Continuing on through 'The Book' chapter 9 on Error Handling. It's pretty interesting see how Rust deals with error handling. Admittedly it now makes
things a bit clearer as I'm understanding why some code suggestions are written the way they are. Using the ? operator to eliminate a lot of the match expressions is really cool and I can definitely see that as useful later on. 

**Link(s) to work**:
No link - weekend will be spent getting things formatted more coherently.


### Day 61: May 26, 2021

**Today's Progress**: Finished off Error Handling chapter

**Thoughts**: This was a fun chapter, heck, this book in its entirety is fun! I can't wait to get to the testing section and the project work. Error handling today, so looking at when to use panic! and when to return Result<T, E>. The crux of the matter seems to be if you expect that an error could occur and/or an error could be catastrophic for your code. Simple enough really. There was also more work on using the ? operator and how you can chain them together to get some really concise snippets of code. I personally liked this one:

  let mut s = String::new();

  File::open("hello.txt")?.read_to_string(&mut s)?;
  Ok(s)
            
Although it turns out you can do it just with:

fn read_username_from_string() -> Result<String, io::Error> {
  fs::read_to_string("hello.txt')    
  }

**Link(s) to work**:
As above


### Day 62: 

**Today's Progress**: 

**Thoughts**: 

**Link(s) to work**:



### Day 63: 

**Today's Progress**: 

**Thoughts**: 

**Link(s) to work**:



### Day 64: 

**Today's Progress**: 

**Thoughts**: 

**Link(s) to work**:



### Day 65: 

**Today's Progress**: 

**Thoughts**: 

**Link(s) to work**:



### Day 66: 

**Today's Progress**: 

**Thoughts**: 

**Link(s) to work**:



### Day 67: 

**Today's Progress**: 

**Thoughts**: 

**Link(s) to work**:



### Day 68: 

**Today's Progress**: 

**Thoughts**: 

**Link(s) to work**:



### Day 69: 

**Today's Progress**: 

**Thoughts**: 

**Link(s) to work**:



### Day 70: 

**Today's Progress**: 

**Thoughts**: 

**Link(s) to work**:



### Day 71: 

**Today's Progress**: 

**Thoughts**: 

**Link(s) to work**:



### Day 72: 

**Today's Progress**: 

**Thoughts**: 

**Link(s) to work**:



### Day 73: 

**Today's Progress**: 

**Thoughts**: 

**Link(s) to work**:


### Day 74: 

**Today's Progress**: 

**Thoughts**: 

**Link(s) to work**:


### Day 75: 

**Today's Progress**: 

**Thoughts**: 

**Link(s) to work**:
