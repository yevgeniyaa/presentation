### Presentation transcript


Hello, my name is Yevgeniya Anossova and today, in the scope of the task in the RSS, I'm going to give you a short presentation and the theme of my presentation is TS Introduction. So, let's start.


I want to start from telling what is TS actually. It is the typed superset of JavaScript as you can see it on your screen. It's an open-source programming language, it is maintained by Microsoft since they created it in 2012. All existing JavaScript programs are also valid TypeScript programs as it transcompiles to JS. It may be used for both: client-side and server-side. TypeScript was designed for developers who build large-scaled apps. It was based on all the disadvantages of JS, and all that additional stuff that was added to it, like syntactical extensions, the class-based oriented programming support and static typings, - all that was done for easing the developers life, for making their code more supportable, more readable and just more easily maintainable. 


Talking about the history: as you can see, first version of TS was 0.8, it appeared on October 2012. Every two years new main version appears. The latest is Typescript 3.0. It was released in the summer of 2018. So it is in a quite active stage of maintenance. New features are being added there all the time now.


Talking about the compatibility with JS: as I've told you TypeScript is a strict superset of ECMAScript 2015, which is itself a superset of ECMAScript 5, commonly referred to as JavaScript. As such, all JavaScript programs are also valid TypeScript programs, and TypeScript programs can seamlessly consume JavaScript.


The benefits of using TS. They all are listed on your screen - static typing, modules, namespaces and strong OOP support, compilation step to JS, - all these allow you to easily catch errors, give you documentation, code is more predictable, it is easier to debug it, easier to organize the code. That all is for covering the disadvantages which were mentioned here before (which are the main disadvantages of JS).


Now you can see the TS popularity chart. It's from Google Trends. TS is gaining it's popularity even now.


Let's talk about the development tools which you can use while developing on TS. These would be text editors with TS support, compiler (TS compiler), integration with build automation tools and linting tools.


Talking about text editors: as I've told you, it was Microsoft who developed TS, so initially only Microsoft's Visual Studio Platform had support for TS, but later a lot of popular IDEs and text editors via plugins or by adding the build-it support started to support TS. So, here you can see all of them.


Compiler. TS compiler, it's name is tsc, is also written in TS. So, it can be compiled to plain JS as any TS code and of course it can be executed in any JS engine, f.e. in browser. Compiler package comes bundled with a script host that can execute the compiler. It is also available as a Node.js package that uses Node.js as a host.


Talking about integration with build automation tools: on your screen you can see the list of tools which already has support for TS and actually these are the most popular ones. All they already have the support.


Linting tools. Teams of TS, TSLint and ESLint together in the beginning of this year have released a new package - typescript-eslint package, which can be used as a linting tool and it's recommended to use this tool.


So, let's start to create some code on TS. Of course, we have to start from installing TS. For installing TS you may just open the terminal and type the command that you can see on your screen - npm install -g typescript. Later, after the installing, you can verify that it was installed successfuly by running the command tsc -v. If everything was ok, it will display the version of TS that you've installed.


Writing some code. Now you can open your favourite IDE or text editor and create the file 'main.ts'. As you can see TS uses .ts extension for it. Now you can write few lines of code, they are listed on your screen. It is plain JS and as you know JS is also a valid TS, so we will use it now. The next step will be to compile our TS into JS because browsers can not read TS.


For compiling we can use several different methods. First is in terminal using previously mentioned tsc compiler. Later it can be done directly in IDE or text editor. And it can be done using some automated task runners such as gulp.


We will use the first way, which was the terminal, because it is beginner friendly and the easiest one. So we'll just run the tsc main.ts command and we will get our JS file at the end. It would be replaced if you already have main.js file in the same path. Also here you can see some examples on how you can compile multiple files at once. One is just by listing them and the second is by using the wildcard.


So, in our case, we'll use the tsc main.ts command.


Advanced compiling. You may use the --watch option to compile a TypeScript file when changes are made. This would automatically compile new file for you. Also you can use tsconfig.json file. It's usually created for big projects or for projects with a lot of code. It can make your life easier and I advise you to look on it more closely.


Data types. As TS name hints, it's JS with types. So what actually are the benefits that they give us? They ensure reliability and scalability, help us in hunting down bugs and errors, help to properly document our code.


Here you may see the examples. First - the code is written on TS, later it's compiled in JS. As you can see, in JS there are no typings at all, they are just removed and you get plain JS code.


These are the three base data types which I've mentioned - any type, build-in types and user-defined types. 


Any type is actually a superset of all data types in TS. When you declare a variable as any you say that it can be any type. You are asking not to check the type of that variable by specyfing it as any.


Build-in types. The most popular are number, string, boolean, void, null and undefined.


User-defined types are enum, class, interface, array and tuple.


Now let's take a closer look on the OOP support and briefly see what features does TS allow us to use. These are classes and interfaces.


Talking about classes: as you know, in general in OOP, class is the template of objects. For declaring class in TS you may use the class keyword as it is shown here. Now JS also has build-in support for classes and the syntax is quite similar. At first we are declaring two properties - items and pages with specifying their types. Then we use constructor and specifying what types of arguments it should consume. Later we are declaring our class method. At the end you see how we create the object and how we are calling it's method.


The concept of interfaces is another powerfull feature of TS. It allows you to define the structure of variables. When you later compile your interfaces to JS they are simply being removed. Here you can see the example of Food interface. We are using the keyword interface for that. Later in out function speak we are telling that we expect object of particular type with particular properties. Our compiler will be able to check if we pass the desired object or not.


Ok, I've already told everything that I wanted. I've given you the brief overview of what TS is. I hope that now you'll be able to make a decision on if you like it or if you don't, if you need it or probably, you don't need it at all. It's gaining a lot of popularity now. I think it's worth your attention, it's worth to try to dig deeper into this theme. I hope you liked my presentation. Thank you. I would be glad if you could ask me some questions but you can not. Thank you and bye bye.
