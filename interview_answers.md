# Interview Answers
Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. These will not be counted as a part of your sprint score but will be helpful for preparing you for your endorsement interview, and enhancing overall understanding.

1. What problem does the context API help solve?
    Context API helps us move props easier than prop drilling. We can also share the state across the whole app or just as much as we need.

2. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?

    Actions are objexts that contain information. They are inside of the store. A reducer is a function that takes in the action and the state and returns a new state based on the action. The store is an immutable object. It holds the state. The store is known as the 'single source of truth' because it is immutable so the only way it can be changed is if you dispatch it with an action within the reducer. 

3. What does `redux-thunk` allow us to do? How does it change our `action-creators`?

    Thunk allows us to write action creators that return functions instead of an action. Action-creators are functions that creates actions.

4. What is your favorite state management system you've learned and this sprint? Please explain why!
    My favorite state management has to be Redux. It makes the code clean and seperate. You dont have to worry about throwing props around and losing where it is. You can also easily debug where something goes wrong by console logging.