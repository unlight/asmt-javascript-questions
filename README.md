## Real questions from committees

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
- Please explane the event bubbling process in JS.
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
- Could you describe pitfalls you may face with in development for mobile devices? (What are the difficulties you may face)
- What is the difference between arrow function and function expression? 
- Can you compare the managing async code by promises and by Observables (pros and cons)?
- What is strict mode? what are the advantages and disadvantages to using it?
- Could you name the disadvantages of transpiling to javascript?
- What does * { box-sizing: border-box; } do? What are its advantages?
- Is there multi-threading in JavaScript?
- What is immutability? Why do you need it? How can you ensure immutability in JavaScript?

### CSS
- What is specificity in CSS?
- What CSS preprocessors you know/use? Pros and cons?

### TypeScript
- Compare TypeScript vs Flow, what features they provide, what problems they solve?
- What are the disadvantages of TypeScript?
- How we can increase the speed of TypeScript compilation process by sacrificing typechecking?
- TypeScript: difference between interfaces and types?
- What are generic types in Typescript?

### Node.js
- What kind of streams are there in nodejs?
- Describe how method pipe works.
- The difference between nextTick and setImmediate?

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

### Security
- Same origin policy, CORS.
- Different types of XSS?
- How do you prevent XSS?
- Content Security Policy headers values, quote few examples?
- How would you initiate manual security code review of Node.js applications?
- Let’s says that you have node application, and some dependency has critical vulnerability which recently discovered. What will be your actions?

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

### Angular.JS
- What is disadvantages of using filters in templates in angular.js?
- What is the theoretically recommended maximum of the watchers in your angular page?
- What is the git submodules and why you should or not should to use them?
- How you can improve infinite scroll performance in angular?
- Describe how digest cycle works?
- Could you explain difference between `$scope.$eval` and `$scope.$evalAsync`?

### Angular X
- How does Angular2 AoT compilation works?

### Interview
- How do you rate candidates? What skills do you rate as the most important for the company?
- How do you prepare for the interview? Do you use tricky questions or practice tasks?
- Describe how would you interview people for the certain project. What kind of questions or topics are most important to get the right candidate?
- What are the most important things for you in the feedback for the intreviewee?
- Have you participated in technical interviews? If yes, what was the most challenged question from you?

### Mentoring
- What was the most difficult/interesting/exciting about mentoring new people?
- We've seen in your PRF that some of your mentees failed to complete the course. Could you describe why and propose how to avoid such situations in future
- Besides the university trainee program have you had the chance to lead a team or some people yet? How did you start ramping up? 
- What are those skills which make you a good mentor?
- Could you please describe the University Trainee Program? What was your role?
- What results of mentoring (for yourself) can you mention?
- What techniques did you use while mentoring?

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

### Agile Scrum Kanban
- What is scrum methodology? 
- What are story points? 
- How do you estimate your tasks?
- What criterias you will use to prioritize tasks between you and your mentee/subordinates?
- What differences between Scrum and Kanban metodologies. Why Scrum/Kanban/Waterfall is more applicable for you project?
  - When can’t we use SCRUM?
- What you will do in case you see that your original estimation was wrong and you need overtime to finish till deadline.
- Talk about SDLC in context of your project.
- What is the use of Planning & Retrospective meetings?
- In your opinion, why is agile methodology so popular today?
- Could you please explain your current development process? Have you ever thought about switching to another development process (Kanban)? Are there advantages or disadvantages in switching to Kanban?
- Could you please compare kanban and scrum?
- How would you handle the situation when you realize that estimation was wrong  and you cannot complete some feature in time?
- Your customer wants a new feature to be done, which requires usage of some absolutely new technology which you have no idea about. Your actions in this case?
- In general, how do you provide user story estimations? Is it story points or just actual time(days/hours)? In your opinion, which approach is better?
- If you underestimated some task and don’t have more time to implement it. What will be your actions?
- Please explain process from getting Visual Design until the approved prototype.
- How do you estimate your tasks?
- What would you do in case you realize that you won’t be able to deliver planned functionality in time and your estimations were wrong?
- How do you prioritize your tasks? How do you estimate your tasks? For example you need to decide which task is more important for you right now. What will you do?
- What is better under-estimation or over-estimation?
- Let’s imagine you need to create ‘Send Email’ form from Gmail. What are your estimates and why?
- What estimation techniques do you know?
- Describe your steps if you realize that you wrongly estimated some stories and sprint fails?
- What will you do if the customer wants to change some story in the middle or at the end of the sprint?
- From your opinion, which artefact is unnesessary in SCRUM?

### Other
- Please, name the basic steps of software development process
- What sources did you use for keeping you knowledge up to date and learning new thing?
- How do you keep yourself up-to-date?
- What FED technologies do you consider that will be very popular in the nearest future. How do you exploit and promote them?
- Self-development - ways, techniques, practices, etc.
- What is your goal to become a senior software engineer?
  - What does it mean to be a Senior Specialist? Please explain new challenges and responsibilities.
  - What is the difference between L2 and L3 engineer?
- What challenges or big goals would you like set for yourself being Cheif Software Engineer.
- What concrete problems have you faced so far? Mention a few examples.
- What would you do if you can’t find the solution?
- Please describe your problem solving skill a bit more. What do you exactly do if you face a problem?
- How do you prioritize your tasks? How do you estimate your tasks? For example you need to decide which task is more important for you right now. What will you do?
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
- https://github.com/Yonet/Angular2-Interview-Questions
- https://github.com/gdi2290/ngExam
- https://github.com/nishant8BITS/123-Essential-JavaScript-Interview-Question
- http://davidshariff.com/quiz/
- http://thatjsdude.com/interview/index.html
- http://davidshariff.com/js-quiz/
- https://github.com/ChiperSoft/InterviewThis
- http://davidshariff.com/blog/preparing-for-a-front-end-web-development-interview-in-2017/
- https://medium.freecodecamp.com/cracking-the-front-end-interview-9a34cd46237
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
