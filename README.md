## Real questions from committees

### Common
- What motivates you to be a senior software engineer? (What is your goal to become a senior software engineer?) (What motivates you to get the next level?)
  - What does it mean to be a Senior Specialist? Please explain new challenges and responsibilities.
  - What is the difference between L2 and L3 engineer?
- What challenges or big goals would you like set for yourself being Cheif Software Engineer.
- Please, name the phases of Software Development Life Cycle?
- Talk about SDLC in context of your project.

### Code Quality
- Which code review tools you know/use? Your criterias for good code.
- What is code review in your opinion?
- How you'll setup code review for team of 5 devs with different skillsets?
- What are your criterias of Good Code that can be merged during review process?
- Have you ever practiced code review on your project? How would you setup code review process from scratch?
- In general, could you please describe the role of automation in development process?
- You come to an existing project and you see no code guidelines established there and you see mess and mixture of styles which is difficult to read and understand. Describe your actions.
- What practices/approaches do you know which helps to improve code quality?
- Code review - have you tried it, what is it for, is it helpful? What are the shortcomings & benefits of it?
- What are the signs of the bad code?
- How often do you refactor code? What are the reasons which force you to refactor code?
- Imagine the situation that you come to an existing project and see no coding guidelines established there and see issues coming out of this. What would you do?
- Exactly what kind of documentations did you create for your project?
- What do you mean by a good code?
- How do you maintain code quality in your project?
- What development methodology do you use in your project? 
- What you don't like in your project? How can you improve this?
- Which code review tools you know/use? Your criterias for good code.
- Do you use software design principles in your practice? Could you tell which design principles do you use and why you need them?
- How do you understand that the code is good/bad?
- What is Temporal Coupling?
- What code metrics (software metrics) do you know?
- Do you measure cyclomatic complexity of the codebase?
- Can you tell some negative parts of using SOLID principles?
- Which ESLint plugins do you use on your projects? Why these?
- What are the differences between code quality and product quality?

### Unit/Integration testing
- How you can use tests while re-writing legacy code?
- What are the differences between TDD and BDD aproaches. What JS frameworks for TDD/BDD you know?
- What tools are you using to test ability of your site to look equally in necessary browsers?
- What's the difference between unit, functional, acceptance, and integration tests?
    - Which problems these solves?
    - Best practices?
    - Drawback? Coverage?
- What are benefits of TDD?
- How do you test your code?
- How will you convince your team member to start using TDD? What are the benefits of TDD?
- What is your Unit Tests covering process? What is acceptable Code Coverage level?
- What is better White or Black testing?
- What is the Testing Pyramid?
- Can you describe what are the main differences between Jasmine and Mocha?
- How you can be sure that code is really tested? What does 100% code coverage means? (AAA, Mutation testing)

### JS && DOM && CSS
- What is the event delegation? What type of events we have in (browser) JavaScript? What is the idea of event delegation?
- What is WeakMap/Symbol/Set?
- Why do we need iterators in js (ES6)? How we can use them?
- What const is for, your opinion?
- ES6 Temporal dead-zone
- What is the difference between “for .. in” loop vs “for .. of” loop?
- What is the difference between Array.from() and Array.of()
- If I define 2 functions with the same name in the same scope, which one will be executed?
- Which types of inheritance implementation in JS you know/use?
  - Could you expain all ways how to inherit one object from another?
- ES5 / ES6 new features || language supersets (e.g. SASS, TypeScript)
- What was the most interesting crossbrowser issue you came across? How did you fix it?
- What techniques you can use to avoid callback hell?
- Please talk about DOM event handling (capturing/bubbling).
- Please explain the event bubbling process in JS.
- What is the difference between preventDefault and stopPropagation event methods?
- What were your pitfalls for delivering project audit while you were contributing to the FED CC
- Browser caching possibilities?
- What's your experience with in-browser storages? IndexedDB? What type of db is indexeddb? What are the differences from RDBs and NoSQL dbs?
- Experience in building mobile, desktop, tv or any other different from the browser environment applications?
- Common dev environent setup? What dev environment should include for FE app?
- Talk about build process/CI on your project. Why Grunt/Gulp/... is used?
  - Let’s imagine you need to implement CI on a new project. What will be your actions?
  - What build tools are you using in your projects? Why?
- Could you please describe an ideal project for you? Which processes, workflow, tools would you use?
- What are disadvantages of webpack?
- Describe the methods of building web UI: Progressive Enhancement and Graceful Degradation.
- Explain the JavaScript Event Loop.
- Explain difference between microtask and macrotask within an event loop context.
- What is asynchronous programming, and why is it important in JavaScript?
- What's the difference between an "attribute" and a "property" in DOM?
- Could you describe the pitfalls you may face with in development for mobile devices? (What are the difficulties you may face?) (Is there a special aspects of developing applications in JavaScript for mobile (browser) and for desktop (browser) ?)
- What is the difference between arrow function and function expression? 
- Can you compare the managing async code by promises and by Observables (pros and cons)?
- What is strict mode? what are the advantages and disadvantages to using it?
- Could you name the disadvantages of transpiling to javascript?
- What does * { box-sizing: border-box; } do? What are its advantages?
- Is there multi-threading in JavaScript?
- What is immutability? Why do you need it? How can you ensure immutability in JavaScript?
- Please, talk about ES2015 modules, what ES2015 modules exports? What is the difference between commonjs modules and ES2015 modules?
- As you know ES6 classes are just syntactic sugar. What happens in reality when you create class A? What happens when you want inherit class B from class A?

### CSS
- What is specificity in CSS?
- What CSS preprocessors you know/use? Pros and cons?

### TypeScript
- Compare TypeScript vs Flow, what features they provide, what problems they solve?
- What are the disadvantages of TypeScript?
- How we can increase the speed of TypeScript compilation process? Can we sacrifice typechecking?
- TypeScript: difference between interfaces and types?
- What are generic types in Typescript?

### Node.js
- What is an error-first callback?
- What kind of streams are there in nodejs?
- Describe how method pipe works.
- The difference between nextTick and setImmediate?
- Can you name some points from twelve factor application methodology?
- What is the preferred method of resolving unhandled exceptions in Node.js?
- How does Node.js support multi-processor platforms, and does it fully utilize all processor resources?
- How do you understand non-blocking and async functions? Is there a difference between them?
- Can you name the rules of interoperability between CJS and ESM modules?

### Browser internals. Performance optimization.
- Possible ways to speedup your javascript code execution time? Hidden classes? try/catch?
- What is hardware acceleration?
- What do you mean by performance optimizations?
- How do you usally deal with perfomance issues?
- What kind of perfomance issues do you know?
- Which tools you use to trace them?
- Which technices you know or applied to solve memory leaks? Describe some of your personal experience in solving such issues.
- What is the memory leak? What are the reasons of memory leaks? What kind of coding errors can cause them?
- What tools do you use while improving performance?
- How did you know that the performance improved?
- Which memory leaks have you ever found and what tools did you use to find them?
- How do you usally deal with perfomance issues?
- What kind of perfomance issues do you know?
- Which tools you use to trace them?
- Which technices you now or applied to solve memory leaks? Describe some of your personal experience in solving such issues.
- How do you understand that you need to improve performance of your application? How do you convince client that you need to do this.
- How would you improve website load time / performance?
- Imagine you have table and there are hundreds columns and thousands of rows. What kind of optimization techniques can be applied?
- What general optimization techniques do you know?
- Parallel threads on FE. Have you worked with them?
- What are the downsides of working with web workers?
- What the difference between asynchronous and parallel threads?
- Could you please describe in details what performance techniques have you applied for your project?
- How do you achieve lazy loading of the modules?
- What about the first load time for SPA and MPA applications?
- Have you had any caching issues within your application?

### Security
- Same origin policy, CORS.
- What are the techniques that can help to avoid the same origin policy?
- Different types of XSS?
- How do you prevent XSS?
- Content Security Policy headers values, quote few examples?
- How would you initiate manual security code review of Node.js applications?
- Let’s says that you have node application, and some dependency has critical vulnerability which recently discovered. What will be your actions?
- When you are working with the SPA application what are the signs that you need use state container (like Redux in React)?
- What does immutable mean to you?
- Can you please give us a short overview of single page applications and multi page applications and pros and cons for using which of them?

### Architecture and design patterns
- Please compare pros and cons for Single-page and Multi-page application approaches.
- Can you provide examples of GoF/GRASP patterns used on your project? Do you know what SOLID principles means?
- Why are design patterns are good?
- What is good architecture? What are the goals that architecture tries to solve?
- What MV*-like architectural patterns do you know? Have used any? What are the differences?
- What is Flux? What's the difference from MV*-like approach?
- Redux vs Flux - differences?
- What is IoC?
- Which software architecrure trends you faced with? Docker and microservices?
- What criterias you will use to select technologies for your project?
- How you will you design/implement 2-way binding without 3rd party libraries and frameworks? Which patterns you will use?
- How you will improve functionality of 3rd party library on your project?
- Single page applications - how do you think why are they so popular now? What are good/bad things about server-side & client-side rendering?
- What do you think about isomorphic applications? What are their benefits? What problems can they cause?
- What design patterns you are using mostly in your code?
- What is the use of design patterns? What problems do they solve? How can they help in communication?
- Could you mention a few design patterns you usually use in your front end code?
- What the differences between MV* patterns? Could you give examples of MV* patterns in frameworks?
- Could you tell more about patterns you had to use?
- Explain pros and cons of development using the components approach?
- In your opinion, what is better composition or inheritance? Why?
- Please compare GraphQL and REST (pros and cons)?
  - How we will implement version in GraphQL?
- What microservices patterns do you know?

### Build Tools
- Could you please compare Gulp and Webpack?
- Do you use Webpack on your project? Which version?
- Why are you using CI on your project?

### Frameworks
- What is the main difference from your point of view between JS framework XXX and YYY.
- What are benefits and shortcomings of AngularJS, what do you like in 2.0 (if know)
- Describe the weak points of AngularJS and how can we deal with them.
- What is(are) killer feature(-es) of Angular JS, what would you personally highlight in this technology?
- Declarative vs Imperative programming in its application to Angular and/or HTML/CSS/JS apps. Shortcomings and benefits of each approach.
- How would you convince me to change my webapp to use Angular.js if I were a customer and I didn’t know anything about technical details?
- Your favorite FE framework.
- Imagine you need to choose framework for your new project. Which criterias will you use to make decision?
  - What are you actions when you need to decide between two libraries that you’ll use in your project?
- Imagine you write your own custom framework for project needs. Could you please compare your framework with anyone, you're familiar with (AngularJS, Backbone, etc). Do you adree that developing custom framework might be efficient than using existing one and why?
- How to improve performance of react components?
- What is Pure Component in react?
- Redux principles: What is pure function? Where it came from (what paradigm)?
- How "reselect library" improves performance? How do you measure perf? When reselect optimizations not working?
- What is main difference between Redux and Facebook Flux library?
- What better in your opinion - one-way or two-way data binding, why? What is better to use (prefer) in Angular?
- What performance optimization techniques do you know in AngularJS?
- Describe lifecycle of directive in AngularJS?
- What are general recipes for optimizing Angular application?
- What is the problem with angular watchers? Can you please describe it?
- Speaking about components model in Angular - did it use any optimizations for not to iterate all watchers?
- How do you structure angular modules within your application? How do you identify that is a separate module. If you have one big module for all application - what are pros and cons of such approach.
- How do you usually integrate not Angular based 3rd party modules in your application?
- Apply and digest calls - why do you use it?
- What was the most complex architectural decision you made on your project?
- Concerning interceptors in Angular have you worked with them?

### React
- Speaking about the React. What’s the difference between state and props?
- How do you implement the situation when child component wants to update the parent state? What are the good practices?
- What happens when you call setState in React?
- When you are working with the SPA application what are the signs that you need use state container (like Redux in React)?
- What does immutable mean to you?
- Speaking about the DOM, what kind of DOM does React use?
- What are the difference between virtual DOM and shadow DOM?
- What React patterns are being used mostly in your code?
- Could you please describe three Redux fundamental principles?
- Stateful and stateless components. What is better? Pros and cons?
- What’s the main selling point of React to you. Why did you chose to go with React?
- What is JSX and how come we can write it in our JavaScript code — how do the browser recognize it?
- What are the main 2 types of components you can declare in React, and when would you use one over another.
- Since we mentioned life cycle — can you walk me through the cycle of mounting a stateful component? What functions are called in what order? Where would you place a request for data from the API? Why?
- Can you explain the idea of “lifting the state up”?

### Angular.JS
- What is disadvantages of using filters in templates in angular.js?
- What is the theoretically recommended maximum of the watchers in your angular page?
- What is the git submodules and why you should or not should to use them?
- How you can improve infinite scroll performance in angular?
- Describe how digest cycle works?
- Could you explain difference between `$scope.$eval` and `$scope.$evalAsync`?
- Explain what is linking function and type of linking function?

### Angular X
- How does Angular2 AoT compilation works?

### Interview
- How do you rate candidates? What skills do you rate as the most important for the company?
- How do you prepare for the interview? Do you use tricky questions or practice tasks?
- Describe how would you interview people for the certain project. What kind of questions or topics are most important to get the right candidate?
- What are the most important things for you in the feedback for the intreviewee?
- Have you participated in technical interviews? If yes, what was the most challenged question from you?
- How do you think what are the roles of Scrum Master?
- In a scale of 100% how much time (in percent) you are spending for a coding part and how much for a leadership?
- How do you keep the development base high in your team?
- Have you participated in Scrum of Scrums session?
- Do you remember an internal conflict that you have to resolve somehow?
- Как бы ты сделал ... (проект, процесс, воркфлоу) в идеальном мире (сговорчивый заказчик, есть все необходымые тулы и время).
- About time management on your project - how do you ensure that estimations are met? How do you manage work in your Agile environment to make sure that there are enough time that estimations are met?
- Question about speaking with the customer. You know customer may be a big problem when you are choosing framework or technology stack. What are the main points that you can use to prove customer that your technology stack is the best choice? What if customer wants to add obsolete plugin to your brand new Angular 4 application - what will be your arguments?

### Mentoring
- What was the most difficult/interesting/exciting about mentoring new people?
- We've seen in your PRF that some of your mentees failed to complete the course. Could you describe why and propose how to avoid such situations in future
- Besides the university trainee program have you had the chance to lead a team or some people yet? How did you start ramping up? 
- What are those skills which make you a good mentor?
- Could you please describe the University Trainee Program? What was your role?
- What results of mentoring (for yourself) can you mention?
- What techniques did you use while mentoring?
- How did you measure mentee’s success? (You was a mentor, how did you understand that your mentoring was successful)?

### Team managment & Communication
- Team management: how to ensure, team is on track, how to delegate tasks
- Imagine the conflict situation in your team: 2 specialists discussed 2 different approaches and this technical issue became personal conflict. Your actions?
- You wrote that one of your goal is to take a role of JS/FE Technical Lead. Can you explain what responsibilities you do on this Project as a TL?
- How would you handle a conflict between two skilled developer in your team regarding preferred coding style?
- What would you do if one of your team mates unexpectedly become ill for two weeks? How would you reduce the negative effect in such situation?
- How do you share your knowledge across the team and abroad? Is it some tech-talk sessions, or workshops, or trainings, or you just come to each person in case of any difficulties and come up with the solution together?
- How do you check that your team development work is on the right track?
- As a lead developer is it your responsibility to check whether your team members follow the processes?
- How do you handle conflicts?
- How do you think what was the quality, which helped you to achieve leading role? How did you managed to accomplish this, convinced others that you are the person to play a lead role.
- What would you do if customer comes to you with a big and challenging task and says “I want it to be done in a week”, but even your raw and optimistic estimate tells you that it will require at least 2 weeks?
- Your customer wants a new feature to be done, which requires usage of some absolutely new technology which you have no idea about. Your actions in this case?
- What does your ramp-up process looks like? How would you optimize it?
- How do you manage motivation issues in case of your team and in case of yourself, if any?
- Explain delegation process, how you delegate tasks to team members?
- Have you ever chance to increase the performance of your team? What would you do if you need to speed up development process in your team?
- What was the most difficult in communication with customer? How did you deal with communication issues?
- Please describe the most popular problems you faced working with customers and how you sorted them out?
- How does your team agree ideas? How conflicts are mitigated.
- What does transparency mean to you in terms of project managing?
- Have you ever had the chance to influence a decision?
- Imagine situtation: your customer would like to use some outdated technology which not you and not your team would like to use. What will you do?
- “Provided a "third-party free" solutions” - how you choose them and promote to customer. (tricky question about licences).
- How do you handle the situations when some member of your team comes to you with difficulties he faced, but you are overwhelmed with work?
- Describe your actions when customer wants a new feature, and hesitating which way to go - adapt already existing CMS system, or write everything from a scratch.
- Customer requests to migrate Desktop version of the product to mobile devices. Could you please describe your specific questions?
- Some developer from project you technically lead/coordinate came to you with proposal to apply ES6 (ECMA2015). Your actions? Will you reject that proposal? Apply? Why it worth or not worth to apply?
- How do you explain ‘dependency injection’ pattern to someone who has no experience working with it?
- Recall last conflict/hard situation with client. How it was solved? What could be done better?
- What is better delegate task or responsibilty?
- Client said “This new feature should be done today?”, but you understand you’ll need a week to finish it. What will you do?
- Imagine one of your colleagues has written some code that you don't agree with. What will you do?
- If a member of your team makes mistakes, delivers buggy code, make delays, what actions would you take?

### Agile Scrum Kanban
- What is scrum methodology? 
- What are story points? 
- How do you estimate your tasks?
- What criterias you will use to prioritize tasks between you and your mentee/subordinates?
- What differences between Scrum and Kanban metodologies. Why Scrum/Kanban/Waterfall is more applicable for you project?
  - When can’t we use SCRUM?
- What you will do in case you see that your original estimation was wrong and you need overtime to finish till deadline.
- What is the use of Planning & Retrospective meetings?
- In your opinion, why is agile methodology so popular today?
- Could you please explain your current development process? Have you ever thought about switching to another development process (Kanban)? Are there advantages or disadvantages in switching to Kanban?
- Could you please compare kanban and scrum?
- How would you handle the situation when you realize that estimation was wrong  and you cannot complete some feature in time?
- Your customer wants a new feature to be done, which requires usage of some absolutely new technology which you have no idea about. Your actions in this case?
- In general, how do you provide user story estimations? Is it story points or just actual time(days/hours)? In your opinion, which approach is better?
- If you underestimated some task and don’t have more time to implement it. What will be your actions?
- Please explain process from getting Visual Design until the approved prototype.
- What would you do in case you realize that you won’t be able to deliver planned functionality in time and your estimations were wrong?
- How do you prioritize your tasks? For example you need to decide which task is more important for you right now. What will you do?
- What is better under-estimation or over-estimation?
- Let’s imagine you need to create ‘Send Email’ form from Gmail. What will be your estimates and why?
- What estimation techniques do you know?
- Describe your steps if you realize that you wrongly estimated some stories and sprint fails?
- What will you do if the customer wants to change some story in the middle or at the end of the sprint?
- In your opinion, which artefact is unnesessary in SCRUM?
- What software development techniques are you using on your project and what other techniques do you know?
- In which case do you use Agile methodologies and in which case Waterfall methodology?
- Lets imagine that you are a scrum master. What will you do, if customer wants to implement a brand new feature right now, and your team is in the middle of current sprint?

### Other
- Please, name the basic steps of software development process
- What sources did you use for keeping you knowledge up to date and learning new thing?
- How do you keep yourself up-to-date?
- What FED technologies do you consider that will be very popular in the nearest future. How do you exploit and promote them?
- Self-development - ways, techniques, practices, etc.
- What concrete problems have you faced so far? Mention a few examples.
- What would you do if you can’t find the solution?
- Please describe your problem solving skill a bit more. What do you exactly do if you face a problem?
- How do you estimate your tasks?
- How do you prioritize your tasks? For example you need to decide which task is more important for you right now. What will you do?
- What was your most challenging task?
- What Front End technologies have you used recently on your projects?
- How do you improve the quality of your work? How can you be sure that your work is well done?
- Do you perform any technique to manage your time?
- Could you please tell us what your daily routine in the office is like?
- Could you let us know how you usually follow the latest technologies? Can you mention a few example you just read about and being excited to make a try with?
- Have you ever had the chance to improve a process in any area of your work?
- What are your actions when you/someone discovers a bug in production?
- What kind of documents you’ve created recently (UML diagrams, etc.)?
- Describe how do you manage and eliminate a technical debt on your project?
- How do you convince client to eliminate tech debt?
- What will be your actions if critical bug on production was discovered?
- What “feature complete" means for you?
- Imagine you start a new project. How would you decide which build tool use? Webpack, Grunt or Gulp?
- What is extreme programming? What techniques did you use?
- What is the difference between responsive and adaptive web design? What would you choose and why?
- What does Key Developer role mean?
- You are starting new project from scratch, what frameworks, arch patterns would you choose and why?
- What is semantic versioning?
- What internal EPAM initiatives do you know? In which of them you participate?
- How do you understand "Definition of Done"?
- What is "Definition of Ready"?
- Tell us about loaded and difficult day for the last 2 weeks. Something went wrong? How do you deal with it?
  - Расскажите о нагружённом и сложном дне за последние 2 недели. Что пошло не так? Как вы с этим справились?
- Have you demotivated employees? Tell us what you have taken to correct the situation.
  - Были ли у вас демотивированные сотрудники? Расскажите, что вы предприняли, чтобы исправить ситуацию.
- You have a release, and the PM asks you to include a feature that is 95% ready, with no tests, but the client wants to see it on PROD. What do you say to your PM?
- Do you know any webpack's competitors?
- Have you faced any failures in your development career and if you had please describe the worst one and what you’ve learned from it?

### Unsorted
- How did you decide between choosing webpack and gulp/grunt setup?
- What are pros and cons of Scrum? What’s the difference between Scrum and Kanban? When can’t we use SCRUM?
- What are your actions when you/someone discovers a bug in production?
- What kind of documents you’ve created recently?
- Let’s imagine you need to create ‘Send Email’ form from Gmail. What are your estimates and why?
- What estimation approaches do you know?
- How to improve performance of react components?
- What is Pure Component in react?
- Redux principles: What is pure function? Where it came from (What paradigm)?
- How "reselect library" improves performance? How do you measure perf? When reselect optimizations not working?
- What is main difference between Redux and Facebook Flux library?
- You mentioned in your form that you mentored junior and newcomer. Was it successful and why? How do you think you may improve your mentoring skills?
- What techniques did you use? What was the outcome?
- How did you measure mentee’s success?
- Mentoring vs Coaching?
- Could you describe pitfalls you may face with in development for mobile devices? (What are the difficulties you may face )
- What’s the difference between WeakMap and WeakSet? What’s their difference from Map and Set?
- What better in your opinion - one-way or two-way data binding, why?
- How would you improve website load time / performance?
- What design patterns you are using mostly in your code? What problems design patterns help to solve?
- You wrote you performed code reviews, What do you usually do (or will do) if somebody doesn't agree with your review comments?
- Explain delegation process, how you delegate tasks to team members?
- Imagine you need to choose framework for your new project. Which criterias will you use to make decision?
- How do you mentor? Please describe a mentoring session held by you.
- Could you expain all ways how to inherit one object from another?
- When we need to care about memory leaks and start search for performance issues? Describe how will you deal with that performance issues?
- Describe the difference between `<script>`, `<script async>` and `<script defer>`
- Describe the weak spots of angularjs and how can we deal with them?
- How do you understand that you need to improve performance of your application? How do you convince client that you need to do this.
- What SOLID is? Could you tell how do you use solid in your work?
- TDD & BDD, what the difference, which one do you prefer?
- Please describe how do you manage and eliminate a technical debt on your project?
- How do you convince client to eliminate tech debt?
- Describe your steps if you realize that you wrongly estimated some stories and sprint fails?
- Could you explain a role of Key Developer on a project?
- What is a recent technical challenge you experienced and how did you solve it?
- What’s the difference between L2 and L3?
- What are pros and cons of Scrum? What’s the difference between Scrum and Kanban? When can’t we use SCRUM?
- How do you deal with conflicts during the code review process?
- How do you explain ‘dependency injection’ pattern to someone who has no experience working with it?
- How do you debug performance issues?
- What are your actions when you/someone discovers a bug in production?
- What kind of documents you’ve created recently?
- What are you actions when you need to decide between two libraries that you’ll use in your project?
- How do you improve your team lead and team work skills? How do you measure your success?
- How we can increase the speed of TypeScript compilation process?
- Choose any design pattern and describe it.
- Let’s says that you have node app, and some dependency has critical vulnerability which recently discovered. What will be your actions?
- Node. How method pipe works?
- What kind of streams are exists in nodejs?
- How do you understand CI/CD processes?
- What “feature complete" means for you?
- What performance optimization techniques do you know in AngularJS?
- Please describe lifecycle of directive in AngularJS?
- What is the main difference between gulp and grunt? What is better?
- How is organized build process on your project? What can be improved?
- What is extreme programming? What techniques did you use?
- What is the difference between responsive and adaptive web design? What would you choose and why?
- How do you understand that the code is good/bad?
- What does Key Developer role mean?
- What techniques did you use while mentoring?
- Recall last conflict/hard situation with client. How it was solved? What could be done better?
- When Scrum/Kanban can’t be used?
- What is better White or Black testing?
- What estimation techniques do you know?
- How do you decide what to delegate and why? => What is better delegate task or responsibilty?
- You’r starting new project from scratch, what frameworks, arch patterns would you choose and why?
- Client said “This new feature should be done today?”, but you understand you’ll need a week to finish it. What will you do?
- What programming paradigms do you know?
- Your website is making a lot of HTTP with over 40 icons and a couple very large gif images. How could you reduce the number of requests?
- What is your favorite features in latest ES specifications?
- Describe your steps if you realize that you wrongly estimated some stories and sprint fails?
- What Cross-Origin Resource Sharing (CORS) technics do you know?
- Do you you know something about HTTP protocol version 2, what advantages does it provide in comparison of HTTP v1?
- Your customer wants a new feature to be done, which requires usage of some absolutely new technology which you have no idea about. Your actions in this case?
- Explain pros and cons of animation with CSS and Javascript?
- How do you deal with conflicts during the code review process?
- How would you define velocity of your team, and what it is used for?
- What is code review, what kind of tools do we have for that? Different types of code review? In the context of CI which is better and why?
- What is mobile first design? How would you create a new material design in Angular?
- Imagine one of your colleagues has written some code that you don't agree with. What will you do?
- Is there multi-threading in JavaScript?
- How to understand that it's time to refactor something? How can you convince client that refactoring is needed?
- What is immutability? Why do you need it? How can you ensure immutability in JavaScript?
- What is better under-estimation or over-estimation? Why?
- You have a release, and the PM asks you to include a feature that is 95% ready, with no tests, but the client wants to see it on PROD. What do you say to your PM?
- Post and pre commit code review what are the pros and cons? In the context of CI, which oen would you use and why?
- Angular 1 vs 2. Comparison. What are the main improvements?
- Dependency injection. What is it needed for?
- What is the functional programming? And the difference between OOP. Pros and cons. Have you used lodash or other functional libs?
- How to convince some members of your team in that their approach is wrong?
- What is disadvantages of using filters in templates in AngularJs?
- Git Flow. What kind of Git branching strategies are you familiar with? What are benefits and drawbacks of those?
- What are the differences between code quality and product quality?
- You've a burden of obsolete technology on the project, utilized by the customer. It will slow down future progress of the project. What shoul you do?
- What are the main pros and cons SPA?
- From the architectural point of view Pros and Cons of SPA?
- Memory leaks in SPA, what's the main cause? How to detect?
- When leading project, how did you delegated tasks and controled subordinates?
- Situ: customer says "the application is slow"? What are your steps?
- From the grow form - flux. What can you say about?
- What's the difference between flux and redux?
- Situ: you start a new prj. Which framework to select?
- How did you do the code review? Which tools did you use?
- What do you know about technical debts?
- What's the process of technical debt management?
- Which design patterns you think the most useful for you?
- What kind of conflicts did you have? How you managed them? What would you change if you could?
- Do you have an idea of kind of conflicts may happen between people?
- What types of conflicts may, must and must not be escalated? Briefly.
- Have you ever had failure tasks and/or projects?
- Vanilla script (pure js) - the good and bad things?
- What role does testing play in dev cycle?
- "5" == 5 is it good or bad?
- Which are ES6 features you like?
- What transpilers do you use?
- What Webpack is able to do?
- Any static analysis tools?
- Where did you get the soft-skill knowledge from?
- Which SW development methodologies do you know?
- How do you do your technical tasks estimations?
- When would you use a component over a directive?
- Why is isolate scope an important concept?
- How does the $digest cycle work?
- Give an example of an immutable operation in JavaScript
- Why ng-controller - is bad?
- What is an http interceptor and what are good use cases for it?
- What is $q and when would you use it?
- What is the difference between a stateful and stateless component?
- When is convenient to make refactoring?
- What is the difference between Stub & Mock?
- AAA (Arrange, Act, Assert) pattern is a common way of writing unit test
- What are the benefits and drawbacks of unit tests? SOLID and TDD?
- What's the difference between unit, functional and E2E tests?
- How do you handle subjective (opinions vs facts) disputes?
- What are the main attributes of a leader?
- What is it to be a mentor/presentor? How do you organize the process, strategy? Resources?
- How did you handle (mis)communication with your last customer?
- What are the main goals of conferences and tech/social meetups for you?
- How do you handle bad mood?
- How does supervision affect your productivity (delivery)?
- What's the difference between Scrum and Kanban?
- What software best practices did you use on your last project and why?
- Why would you refactor Angular app into React? What reasons?
- How did you improve performance on the last project and what kind?
- What is quality code?
- What are the pros/cons of JS? Compare to other langs, if poss. What benefits/downsides did ES6 bring in?
- What's the difference between FE vs BE development?
- What do you like about Node the most, if you were to compare it to other BE frameworks/languages?
- What tools do you use during refactoring and debugging?
- What was, in your opinion, the best architecture of one of your projects and why?
- How is responsive design different to static?
- How did you split tasks with others (pair programming, delegation, coordination etc)?
- How do you handle broken CI pipeline?
- What will you do, if the requirements are unclear?
- What kind of ideas did you suggest to improve your last project? How did it help?
- How do you estimate a project? Especially alone. What factors, metrics do you use?
- If a member of your team makes mistakes, delivers buggy code, make delays, what actions would you take? 
- What were pitfalls of migrations from Angular 1 to Angular 2?

### Terms in few words / one sentence
* closure
* observable
* specificity
* temporal dead zone

### Task
```Text
You are requested as an architect and technology consultant into project
aiming to manufacture Google Spreadsheets analogue (full-stack solution)

Customer asked to prepare technology stack (both for back-end and front-end) for
the target application (frameworks, libs, bundle and build tools, testing).
Customer also wants to know a vision on possible application architecture.

Opportunity details
Target devices: PC, Tablet*
Target browser: Modern Browsers
Team: 4 persons with different skillsets (D1, D2, D3, D4)
(we don't need to provide a team composition, since it could be one of the questions)
```

## Want more?
- https://github.com/h5bp/Front-end-Developer-Interview-Questions
- https://github.com/arialdomartini/Back-End-Developer-Interview-Questions
- https://github.com/yangshun/front-end-interview-handbook
- https://github.com/Yonet/Angular2-Interview-Questions
- https://github.com/gdi2290/ngExam
- https://github.com/nishant8BITS/123-Essential-JavaScript-Interview-Question
- http://davidshariff.com/quiz/
- http://thatjsdude.com/interview/index.html
- http://davidshariff.com/js-quiz/
- https://github.com/ChiperSoft/InterviewThis
- http://davidshariff.com/blog/preparing-for-a-front-end-web-development-interview-in-2017/
- https://medium.freecodecamp.com/cracking-the-front-end-interview-9a34cd46237
- https://github.com/sudheerj/reactjs-interview-questions
- https://github.com/MaximAbramchuck/awesome-interview-questions
  - https://github.com/MaximAbramchuck/awesome-interview-questions#javascript
  - https://github.com/MaximAbramchuck/awesome-interview-questions#angularjs
  - https://github.com/MaximAbramchuck/awesome-interview-questions#less
  - https://github.com/MaximAbramchuck/awesome-interview-questions#nodejs
  - https://github.com/MaximAbramchuck/awesome-interview-questions#reactjs
  - https://github.com/MaximAbramchuck/awesome-interview-questions#design-patterns

## Contributors
* [Aliaksei Krauchanka](https://github.com/npocto-leshka)
* [Alex Karlovich](https://github.com/karlovich)
* [Vadzim Budzishyn](https://github.com/vadzimbudzishyn)
* [Kanstantsin Yatskevich](https://github.com/kyatskevich)
