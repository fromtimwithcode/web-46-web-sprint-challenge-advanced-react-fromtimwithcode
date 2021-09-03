# Interview Answers

Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. These will not be counted as a part of your sprint score but will be helpful for preparing you for your endorsement interview, and enhancing overall understanding.

1. What are the main differences between a stateful and a functional component?
   -Stateful components handle non-visual tasks like handling, updating, and manipulating state, whereas functional components usually handle the visual side of things like rendering.

2. When does a componentWillMount function be called? What about a componentWillUpdate?
   -componentWillMount is only called once after the first render.
   -compnentWillUpdate is called every time a re-render occurs.

3. Define stateful logic.

- State logic updates, manipulates, or handles state.

4. What are the three step of creating a successful test? What is done in each phase?
   -Arrange: Setup the React component we are testing.
   -Act: Execute our behavior (if there is one).
   -Assert: Extract the response element and check (if necessary) that it is what we expect it to be.
