
# Diary Ideation

This diary explains what happened when and which decisions were taken during the project

## 17.10.2016: Kickoff Offenbach 
`Jens, Christian, Marco, Thorsten`

What happened?
Design thinking light:
- Brainstorming about Question "How might we show to whom? with our digital example the strength of our iCSD-platform / community?"
- Ideation results in three main use cases: Invite friend, digital menu, rate by twitter
- First sketching for screens
- First rough user story map
- Results/Work has been captured afterwards in realtimenboard (find link in [GIT]).

Decisions:
 - make the example more digital following SMACT: should work on mobile devices, dashboard might include some analytics, social by twitter integration and social logins, IoT is omitted)
 - example should be easy, should follow KISS (keep it small and simple), easy to understand
 - domain of example should be independent from industry sector -> stick to the restaurant example
 - example is mainly for cap-employees in order to learn devon and start quickly. The implementation (code) of the example should include serveral best practises.
 - payment should not be included
 - reporting: dashboard for chief (e.g. daily reports, twitter review) shall exist, but postponed for later release
 - participating roles in the example:
   - customer is the new role in the center. use cases should be built for this role.
   - the role cook and waiter are removed
   - main operational entities are order and table bookings
   - chief does still exist for dashboard

## After 17.10.2016: Developing of personas, scenarios, prototype plus user story map 
`Jens, Sebastian`

For each main use case first personas and scenarios and first screens (wireframes) are defined based on previous, rough user story map. Outcome of discussion is used to refine user story map and to finalize the scenarios.
Outcome: Axure Prototype with Screens, Scenarios, User Story Map

## 07.12.2016: Pablo Javier Martinez Calvo and Jaime Moncho Llorca create first Visual Design (color, layout, pictures)
`Pablo Javier Martinez Calvo, Jaime Moncho Llorca`

Starting from first mockups Pablo and Jaime create first Axure prototype with visual design. Afterwards Jens incorporates the current state of the scenarios.

Further changes:  
- Changed primary color from blue to green
- removed visual selection of table (out of scope)
- some layout changes (moved filter from left to top, added order-basket directly on main page)

## 22.12.2016: Review before Christmas
`Jens, Christian, Marco, Thorsten, Rainer`

Jens presents scenarios and prototype: Everyone is satisfied with solution :-)

except:

- Minor changes in layout and color.
- Filter:
  - Layout of filter should be changed
  - filter should exist, only a few filter criteria are enough in order to show how to implement a filter
  - sorting should be included
- switching of languages added
- login (only username and password) required, no maintainance of user profile needed so far


## 05.01.2017: Coverpage to shape the common visison
In order to shape a shared vision for the example Jens creates a cover page (see [GIT]) representing his understanding of the vision.

## 06.01.2017: Mobile first?
`Lukas Birn, Florian Bemm`

Lukas and Florian start developing screens following mobile first approach.

## 07.03.2017: Low fidelity design
`Jens Bartelheimer, Jaime Moncho, Santos Jiménez`

In this phase **low fidelity wireframes** are designed by Jaime Moncho.

A wireframe is a static, **low-fidelity representation of the product**, and in the world of user experience, a basic guideline of the website or app – the skeletal framework – for both designers and developers to follow.

Developers use wireframes to better understand the **core functionality** of an app, whereas designers may use them to show the **navigation flow** between site screens.

With wireframes, you dedicate time solely to answering **crucial layout, structure, and organization** questions before the team iterates on visual details.

The main reason to design the low fidelity wireframes was to get aligned with the latest front end components and conventions proposed by Santos Jiménez in this [presentation].

**Summary of the proposal:**

- Use Angular CLI as the main tool to develop, build and test components. With Angular CLI:
  - [Angular 2 Official Style Guide] is followed.
  - Webpack is included as the default builder and bundler tool.
  - Karma is bundled as the default tests runner.
- Follow Material Design specifications in the UI design guide in order to: 
  - Get the Mobile First approach.
  - Get a fully responsive application. 
  - Use the most modern design patterns and conventions developed by Google.
- Use [Covalent] UI framework as a superset of Material Design Components for Angular 2+ to build easily layouts and interfaces. This framework uses Material Design components for Angular 2 as dependency and is very well documented. 

Jens will check this proposal and the low fidelity designs to comment, request changes or approve them. 

The Angular 2 developer team will be able to use these low fidelity designs to build the UI components and behaviour before having the high fidelity ones. Jaime will create the high fidelity designs in parallel when the first ones are approved.

## 24.03.2017: First Sprint Planning
`Roberto García, Jaime Moncho, Cristóbal Belda, Marc Burmester, José Manuel Sánchez, Santos Jiménez`

We held the first sprint planning meeting where we made the user stories estimation for this sprint using **Planning Poker** at [this link](https://play.planningpoker.com/play/game/qgZ2bIlY). 

Also, we agreed the proposed schedule of future events and meetings:

- Sprint 1 Planning	24/03/2017
- Sprint 1 Start 27/03/2017
- Sprint 1 Review 27/04/2017 (Holy Week holidays)
- Sprint 1 Retrospective 28/04/2017
- Sprint 2 Planning 02/05/2017
- Sprint 2 Start 03/05/2017
- Sprint 2 Review	25/05/2017
- Two daily meetings every week. 
  - Preferably mondays and thursdays. 

## 28.03.2017: High fidelity wireframes Sprint 1
`Jens Bartelheimer, Jaime Moncho, Santos Jiménez`

Jaime send high fidelity wireframes to Jens and Santos.

A high fidelity wireframe is a design model of the final UI of our app. The general idea of a high-fidelity prototype is to represent as close to the final product as possible.

Jens will check this proposal.

[GIT]: https://github.com/devonfw/devon-methodology/tree/master/ideation/MyThaiStar
[presentation]:https://docs.google.com/presentation/d/18B2zZvTJJEIlZvqCvW57sjlWavX_IorBuxk4oeTRL6s/edit#slide=id.g1d14f6509a_0_3
[Angular 2 Official Style Guide]:https://angular.io/docs/ts/latest/guide/style-guide.html
[Covalent]:https://teradata.github.io/covalent/
