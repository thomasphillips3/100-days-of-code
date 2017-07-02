# Thomas Phillips 100 Days Of Code - Log

### Day 15: July 1, 2017
##### Letters to My Future Self (CSS)

**Today's Progress**:
Did more of the cover.

**Thoughts:**
CSS is tough. Flexbox doesn't all the way make sense. I punched the floor, then figured shit out. 

**Link to work:** [More design](https://github.com/thomasphillips3/letters/commit/40dba6ca2d3ff60c5d693a3b8928393d97b6581e)
**********
**********
### Day 14: June 30, 2017
##### Letters to My Future Self (CSS)

**Today's Progress**:
Did most of the cover.

**Thoughts:**
CSS is tough.

**Link to work:** [Cover design](https://github.com/thomasphillips3/letters/commit/9bf94c89490b16314dc23f999c719c6e2a1d3af8)
**********
**********

### Day 13: June 29, 2017
##### Android Intents and Tasks

**Today's Progress**:
-
**Thoughts:**
I'm using the canary version of Android Studio, so when I added the RecyclerView dependency, it added the version from the alpha library. I changed the version in the `build.gradle` file and re-synced, and everything is fine.

**Link to work:** [Initial commit](https://github.com/thomasphillips3/NerdLauncher/commit/491319c8f528624e1589b681f1a2c1bd6b90019b)
**********
**********

### Day 12: June 28, 2017
##### Hashes in C

**Today's Progress**:
- I wanted to understand OpenSSL library better, so I played around with ex-hashes.c. I changed the example string to my name. I checked the hash by piping the ouput from `echo` to `openssl` as follows `echo -n "Thomas" | openssl sha256`.

**Thoughts:**

**Link to work:** [Repo](#)
**********
**********
### Day 11: June 26, 2017
##### Accessing Google APIs

**Today's Progress**:
- Read and worked through Google [Accessing Google APIs guide](https://developers.google.com/android/guides/api-client)
- Learned how to set up Google Play Services in an Android app
- Learned how to make synchronous and asynchronous calls

**Thoughts:**
This is good for helping me understand how Android Studio handles dependencies. I've been having some confusion with Gradle and adding dependencies. Now, I know the process
- Make sure the Google Support Repository is available on the local machine using SDK Manager
- Add Google Support Repository to the project by adding a new build rule under `dependencies` for the latest version of `play-services` in the app's `build.gradle` file

Adding the Google Play Support library to an Android app has helped me understand what I need to do to link the the G++ compiler to the OpenSSL Library. I'm on a plane again, so I can't look up the exact command right now, but I think it's `g++ -l /path-to/openssl`.

**********

##### Mongoose

**Today's Progress**:
- [Mongoose Getting Started Guide](http://mongoosejs.com/docs/)

**Thoughts:**
- Mongoose is to help decrease the amount of boilerplate code you have to get up and running in MongoDB.

**********

##### Serialization (pt. 2) in basic blockchain programming

**Today's Progress**:
- Finished [Serialization (pt. 1)](http://davidederosa.com/basic-blockchain-programming/serialization-part-one/)
- Finished [Serialization (pt. 2)](http://davidederosa.com/basic-blockchain-programming/serialization-part-two/index.html)

**Thoughts:**
- Studied the example on hashes (ex-hashes.c). Changed the code to get different hashes. I understand the example pretty well. The hardest part so far was learning to include the OpenSSL library during compilation. My C++ experience in Engin101 at U of M was brief. I learned how to include header files, but not external libraries. I got it to work with `gcc -I /usr/local/opt/openssl/include/ -L /usr/local/opt/openssl/lib/ ex-hashes.c -lcrypto`. SUUUUPER excited!!!

- Learned about encoding variables of different lengths with `varints`

**Link to work:**
- [ex-hashes.c](https://github.com/thomasphillips3/basic-blockchain-programming/blob/master/ex-hashes.c)
- [ex-varints.c](https://github.com/thomasphillips3/basic-blockchain-programming/blob/master/ex-varints.c)

**********

##### Letters to My Future Self (CSS)
![Letters book](https://m.media-amazon.com/images/S/aplus-media/vc/cee89df3-5b81-4c21-b4fe-04c3095a5698.jpg)

**Today's Progress**:
- I have a book called Letters to My Future Self. I'm practicing styling with CSS by replicating the book in code.

**Thoughts:**

**Link to work:**
- [Letters](https://github.com/thomasphillips3/letters/commit/4043edd6414f67354cd1a081f0de9ef730f5ce19)
**********
**********

### Day 10: June 23, 2017
##### Android - XML Drawables

**Today's Progress**:
- Read about 9-Patch images
- Read about Mipmap images

**Thoughts:** I'm on a plane, and don't have access to the file used to create the 9-patch png in my Beatbox app, but I get it.

Mipmaps I still don't really get. Gotta check this out more later.

**********
##### C++

**Today's Progress**:
- Recursion

**Thoughts:**
I wrote a simple app to find the GCD, and remembered things about C++ I had forgotten. I initially wrote my gcd function below main(). I forgot if I want to do it this way, I have to declare the function above main. The other option is to just put main under gcd in the code.

**********

**Link to work:**
- [Greatest Common Denominator](https://gist.github.com/thomasphillips3/eb5ec5b50869334e92ba904b910d48b0)
- [Animal Afforder](https://gist.github.com/thomasphillips3/07948a1935f79274e476f005b21a6893)

##### Bitcoin/ C

**Today's Progress**: Read through some basic crypto stuff again. I understand how the code works, but am still having trouble linking to the `openssl` headers. I gotta figure this out.

**Thoughts:**

**Link to work:**
- [basic-blockchain-programming](https://github.com/thomasphillips3/basic-blockchain-programming)
**********
**********

### Day 9: June 21, 2017
##### Google C++ Course - Getting Started

**Today's Progress**:
- Continued the [Getting Started section](https://developers.google.com/edu/c++/getting-started) of Google C++ Course.

**Thoughts:**

**Link to work:**
- [Times table](https://gist.github.com/thomasphillips3/483bf68709a5985ae8f83e78f4e722c3)
- [Guessing Game](https://gist.github.com/thomasphillips3/a3b2cedf2ceadbbdea14d5fac60ca636)
**********
**********

### Day 8: June 20, 2017
##### Google C++ Course - Getting Started

**Today's Progress**: Started the [Getting Started section](https://developers.google.com/edu/c++/getting-started) of Google C++ Course.
- Created a wrapper around g++ to compile code with stricter rules
- [Formatting output with cout](http://www.cplusplus.com/reference/ostream/ostream/)

**Thoughts:** While creating the gccp binary, I learned about permissions on Mac. I wasn't able to move my newly-created binary to /bin or /usr/bin, even as root. I found [this answer on SO](https://stackoverflow.com/questions/32659348/operation-not-permitted-when-on-root-el-capitan-rootless-disabled), which told me about [System Integrity Protection](https://apple.stackexchange.com/questions/193368/what-is-the-rootless-feature-in-el-capitan-really) on Mac. Instead of removing SIP, I installed it to usr/local/bin.

**Links to work:**
- [gccp](https://gist.github.com/thomasphillips3/b378f6b81e16f770f5608cdd839d835e)
- [hello.cpp](https://gist.github.com/thomasphillips3/5cd4d872e521645f829347fa9859749f)
- [hello2.cpp](https://gist.github.com/thomasphillips3/585c9c43bd5c63dcf54876a9d1362ef5)
**********

##### Calculator

**Today's Progress**: Developing iOS 10 Apps with Swift - Lecture 2: [MVC](https://itunes.apple.com/us/course/2-mvc-ios-xcode-and-swift-demonstration/id1198467120?i=1000381073277&mt=2).

**Thoughts:** Swift and iOS do things differently than Java and Android. It's a challenge getting used to both at the same time, but I think it's helping me grasp the overall concepts better. Seeing MVC in both settings is definitely helping me understand that better.

**Link to work:**
- [Built out the Controller](https://github.com/thomasphillips3/Calculator/commit/81a6bbf2d4b209c72da5bacb5a245b292a4b5743)
- [Made layout work across all iOS devices](https://github.com/thomasphillips3/Calculator/commit/ed3ad47859fec61e8f3a9d3a4ce39f628490f93c)
**********
**********

### Day 7: June 18, 2017
##### Remove static images - Park Players Website

**Today's Progress:** Since I'm hosting in AWS, I want to only edit the HTML file, and store all assets (images, CSS, JS files) in AWS or in a CDN.

**Thoughts:** While updating the images, I noticed some formatting issues have arisen. I'm using GitHub to track issues now. Part of becoming a better coder is learning to use the tools.

**Link to work:** [Repo](https://github.com/thomasphillips3/parkplayers/issues/1)
**********
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
**********

### Day 5: June 12, 2017
##### Serialization in C++

**Today's Progress**: [Serialization (pt. 1)](http://davidederosa.com/basic-blockchain-programming/serialization-part-one/) of [Davide De Rosa's Blockchain Programming Tutorial](http://davidederosa.com/basic-blockchain-programming/).

**Thoughts:** I started reading this a while ago, but wanted to actually run the code. This was a learning process as well, getting my computer set up for C++. I found a couple plug-ins for Atom. I think I'll try to make that work.

I am making good progress, but going to sleep now...at 2:40 am. The last issue I encountered was [Undefined symbols for architecture x86_64](https://stackoverflow.com/questions/18751868/undefined-symbols-for-architecture-x86-64-compiling-problems). I'll work on it tomorrow.

**Link to work:** [ex-hashes.c](https://github.com/thomasphillips3/basic-blockchain-programming/blob/master/ex-hashes.c)
**********
**********

### Day 4: June 11, 2017
##### Park Players Website

**Today's Progress**: Began uploading all assets to their own S3 bucket. Replaced pics with correct sizes.

**Thoughts:** I have never gotten fully into web development. I think I have always looked at it as easier than other languages, so I never bothered to get good at it. I like that HTML and CSS styling kinda helps me understand Android styling as well.

**Link to work:** [Park Players](https://github.com/thomasphillips3/parkplayers/commit/28b2dbe9293b293f83a18a02fecfdc524cd613d9)
**********
**********

### Day 3: June 10, 2017
##### Park Players Website

**Today's Progress**: Began uploading all assets to their own S3 bucket. Replaced pics with correct sizes.

**Thoughts:** I have never gotten fully into web development. I think I have always looked at it as easier than other languages, so I never bothered to get good at it. I like that HTML and CSS styling kinda helps me understand Android styling as well.

**Link to work:** [Park Players](https://github.com/thomasphillips3/parkplayers/commit/28b2dbe9293b293f83a18a02fecfdc524cd613d9)
**********
**********

### Day 2: June 9, 2017
##### Rotation Handling and Styles & Themes

**Today's Progress**: Read about handling rotations in Big Nerd Ranch Chapter 18. There are two different ways - retain the fragment or override onSavedInstanceState(Bundle).

Applied themes and styles to the Beatbox app. Learned to traverse the theme hierarchy to find the appropriate attributes to override.

**Thoughts:** This was helpful in understanding how to customize the look of my app. I definitely want to spend some time specifically on styling. I'm going to get back into the Letters to Myself project.

**Link to work:** [Beatbox](https://github.com/thomasphillips3/Beatbox/commit/87f61e0f327f6c3fd475d67ed673f825773f14ff)
**********
**********

### Day 1: June 8, 2017
##### BeatBox

**Today's Progress**: Learned about SoundPool and assets. Big Nerd Ranch chapters 18 and 19.

**Thoughts:** Starting to take my time and learn subjects more thoroughly, instead of just copying code to finish the chapters quicker.

**Link to work:** [BeatBox](https://github.com/thomasphillips3/Beatbox)
**********
**********



### Day: Date
##### Title/ Project

**Today's Progress**:

**Thoughts:**

**Link to work:** [Repo](#)
**********
**********
