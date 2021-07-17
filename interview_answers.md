# Interview Answers
Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. These will not be counted as a part of your sprint score but will be helpful for preparing you for your endorsement interview, and enhancing overall understanding.

1. What are the main differences between a stateful and a functional component?
*A Functional component has less control over state and logic.*
*A stateful or class component has a render method that returns html and has more control over state and locic of the component*
2. When does a componentWillMount function be called? What about a componentWillUpdate?
*componentWillMount will be called immediatly after the component is inserted into the tree (aka. mounted)*
*componentWillUpdate is called immediatly after the state is updated. usually via user interaction*
3. Define stateful logic.
*Stateful logic is logic that deals with the state. setState functions. usually a handleClick or Handle Submit type things*
4. What are the three step of creating a successful test? What is done in each phase?
*Arrange, Act, Assert*
**Arange- rendering the component your testing**
**Act- the things you need to do the test.(userevents, variables, getting areas of the component)**
**Assert- the things that should or shouldnt be on screen after the Act part is done**