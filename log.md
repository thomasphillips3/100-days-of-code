# Thomas Phillips 100 Days Of Code - Log

### Day 8: June 20, 2017
##### Google C++ Course - Getting Started

**Today's Progress**: Completed the [Getting Started section](https://developers.google.com/edu/c++/getting-started) of Google C++ Course.
- Created a wrapper around g++ to compile code with stricter rules
- [Formatting output with cout](http://www.cplusplus.com/reference/ostream/ostream/)

**Thoughts:** While creating the gccp binary, I learned about permissions on Mac. I wasn't able to move my newly-created binary to /bin or /usr/bin, even as root. I found [this answer on SO](https://stackoverflow.com/questions/32659348/operation-not-permitted-when-on-root-el-capitan-rootless-disabled), which told me about [System Integrity Protection](https://apple.stackexchange.com/questions/193368/what-is-the-rootless-feature-in-el-capitan-really) on Mac. Instead of removing SIP, I installed it to usr/local/bin.

**Links to work:**
- [gccp](https://gist.github.com/thomasphillips3/b378f6b81e16f770f5608cdd839d835e)
- [hello.cpp](https://gist.github.com/thomasphillips3/5cd4d872e521645f829347fa9859749f)
- [hello2.cpp](https://gist.github.com/thomasphillips3/585c9c43bd5c63dcf54876a9d1362ef5)
**********

### Day 7: June 18, 2017
##### Remove static images - Park Players Website

**Today's Progress:** Since I'm hosting in AWS, I want to only edit the HTML file, and store all assets (images, CSS, JS files) in AWS or in a CDN.

**Thoughts:** While updating the images, I noticed some formatting issues have arisen. I'm using GitHub to track issues now. Part of becoming a better coder is learning to use the tools.

**Link to work:** [Repo](https://github.com/thomasphillips3/parkplayers/issues/1)
**********

### Day 6: June 13, 2017
##### C day

**Today's Progress**: I realized my understanding of C is mad rusty. Decided to look at a bunch of C project repos on GitHub.
* [Terminal Games](https://github.com/stillmotion/terminal-games)
* [Linux](https://github.com/torvalds/linux)
* [Darknet: Open Source Neural Networks in C](https://github.com/pjreddie/darknet÷)

Also, I played around with C in XCode a bit.

**Thoughts:** I want the experience of learning to program like I should have had in college. I am going to take my time and understand all the code I read. Going through all these C project repositories gave me a sense of how C looks, and what people use it for, versus newer languages (Java, Swift, JavaScript, Python, etc).

So I'm going to start with the Terminal Games repo. The games seem to be just outside of the bounds of my understanding. It'll challenge me, but not discourage me.
**********

### Day 5: June 12, 2017
##### Serialization in C++

**Today's Progress**: [Serialization (pt. 1)](http://davidederosa.com/basic-blockchain-programming/serialization-part-one/) of [Davide De Rosa's Blockchain Programming Tutorial](http://davidederosa.com/basic-blockchain-programming/).

**Thoughts:** I started reading this a while ago, but wanted to actually run the code. This was a learning process as well, getting my computer set up for C++. I found a couple plug-ins for Atom. I think I'll try to make that work.

I am making good progress, but going to sleep now...at 2:40 am. The last issue I encountered was [Undefined symbols for architecture x86_64](https://stackoverflow.com/questions/18751868/undefined-symbols-for-architecture-x86-64-compiling-problems). I'll work on it tomorrow.

**Link to work:** [ex-hashes.c](https://github.com/thomasphillips3/basic-blockchain-programming/blob/master/ex-hashes.c)
**********

### Day 4: June 11, 2017
##### Park Players Website

**Today's Progress**: Began uploading all assets to their own S3 bucket. Replaced pics with correct sizes.

**Thoughts:** I have never gotten fully into web development. I think I have always looked at it as easier than other languages, so I never bothered to get good at it. I like that HTML and CSS styling kinda helps me understand Android styling as well.

**Link to work:** [Park Players](https://github.com/thomasphillips3/parkplayers/commit/28b2dbe9293b293f83a18a02fecfdc524cd613d9)
**********

### Day 3: June 10, 2017
##### Park Players Website

**Today's Progress**: Began uploading all assets to their own S3 bucket. Replaced pics with correct sizes.

**Thoughts:** I have never gotten fully into web development. I think I have always looked at it as easier than other languages, so I never bothered to get good at it. I like that HTML and CSS styling kinda helps me understand Android styling as well.

**Link to work:** [Park Players](https://github.com/thomasphillips3/parkplayers/commit/28b2dbe9293b293f83a18a02fecfdc524cd613d9)
**********

### Day 2: June 9, 2017
##### Rotation Handling and Styles & Themes

**Today's Progress**: Read about handling rotations in Big Nerd Ranch Chapter 18. There are two different ways - retain the fragment or override onSavedInstanceState(Bundle).

Applied themes and styles to the Beatbox app. Learned to traverse the theme hierarchy to find the appropriate attributes to override.

**Thoughts:** This was helpful in understanding how to customize the look of my app. I definitely want to spend some time specifically on styling. I'm going to get back into the Letters to Myself project.

**Link to work:** [Beatbox](https://github.com/thomasphillips3/Beatbox/commit/87f61e0f327f6c3fd475d67ed673f825773f14ff)
**********

### Day 1: June 8, 2017
##### BeatBox

**Today's Progress**: Learned about SoundPool and assets. Big Nerd Ranch chapters 18 and 19.

**Thoughts:** Starting to take my time and learn subjects more thoroughly, instead of just copying code to finish the chapters quicker.

**Link to work:** [BeatBox](https://github.com/thomasphillips3/Beatbox)
**********



### Day: Date
##### Title/ Project

**Today's Progress**:

**Thoughts:**

**Link to work:** [Repo](#)
**********
