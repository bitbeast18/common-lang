# common-lang
A general purpose programming language that can be transpiled to any other language.

### key points 
* The language can be used for writing software applications of all domains. That's why the term 'General Purpose'.
* The main design goal is to allow for transpiling the code written in `common-lang` to any other language.
* The `sdk` comes with the `compiler`, `analyser`, `formatter`, `package manager`, `core libraries` and `transpiler`.
* The `transpiler` can be used along with the `plugins`, that are language specific. 

## Is it necessary to create another programming language?
> Short answer: Absolutely Yes!

Ever thought why can't there be a universal programming that can serve all the purposes? I won't answer it here. Google has `1,19,00,00,000` answers for you. Consider any porgramming language, they are all built in the same way, parse, generate and run. What makes them different is the philosophy they carry. Every time there's a new philosophy people build a new programming language. But along with that one needs to build a whole ecosystem of community, libraries and support tools which takes much more time and effort than the language itself. One basic principal of software design is `DRY` which stands for Don't Repeat Yourself! But wait aren't we repeating all the above stuff atleast twice a year. Hmm! Here comes `common-lang` into the picture. Let's talk how this new language tries to solve the problem. 
* Generally, there are two main reasons for a new programming language.
    - A new Domain/Use case.
    - Disagreement with existing languages.
    
* Domain specific
Remember why you started learning some language X? Oh maybe you were interested in machine learning, or some other fancy doomain. Yes languages are highly domain dependent. Every platform has some set of requirements that needs to satisfied. Take systems programming, it needs to allow some crazy optmisations, it needs to allow for some low level stuff, it should support faster builds and so on. Similarly, every language needs to have a specific design of the interface that developers use to write software. It needs to be nice with developers as well as the machine. Thats a tough task. But thats just another design. Remember `design`. If we just keep the users aside for the moment, we can bring in what `common-lang` has to offer. This is the reason we need a language that can be transpiled to any other existing language. Just to make the machine or the platform happy. And about the users, lets see in the next section.

* Disagreement with existing languages.
Now, although domain of use plays a great role in the design of the language,but ultimately the only need of a programming language is to create enough abstraction for its users. So here comes the users of the language. Sometimes it feels that half of the internet is filled just with opinion wars and I can't mention the other half here. But preference is something that affected the families of languages more than the need for that language. You can find hundreds of posts talking about something like, should you use `i++` or `++i`. Wait! Is that's even a topic to discuss? Anyways, but this is a problem that needs atmost attention if we really aim to build the kind of language we are talking about. Now there have been numerous attempts to solve this problem but the approach our language uses is a brand new fancy term called `Design as package`. Import the constructs for the domain. Thats all it means. Now that not some new invention. We have been using these for a long time but they are usually the result of a bad design or an attempt by a drowning language to introduce modern constructs. Here we use it as the main design principle. So rather than an invention its a change of perspective.

So, these arguments convince us to start building a new language that can serve as a common ground of development. As a prototype we will be first building yet another language called `cp-lang`. Check for updates in the respective repository.

Also if you think my thoughts are naive and what ever I wrote above is trash please let me know by raising an issue. 

