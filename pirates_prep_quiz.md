# React Requests - Pirate API Quiz

## # Requesting All Pirates

Question 1

Which component is responsible for requesting all the pirates?

**A Pirate.Container.js**

Question 2

Which hook do we use to carry out the requestAll() method and when does it get triggered?

**A The Mount of PirateContainer.**

Question 3

The requestAll() method creates a new instance of Request in order to gain the functionality to carry out various forms of request. Where is the Request class?

**A In the helpers package.**

Question 4

Which method are we using from the Request class here?

**A get() on each promise**

Question 5

The PirateList component is in charge of rendering a list of pirate components. What is the pirateNodes function returning?

**A Pirate container tag for each pirate mapped from props.pirates**

# Viewing a Single Pirate

Question 1

In the browser, when we click on one of the pirates names in the pirate list, our app renders a PirateDetail component. PirateDetail is in charge of rendering the information for a single pirate. But where is it getting its props passed down from?

**PirateContainer**

Question 2

```js
if (!pirate){
 return "Loading..."
}
```

What is the purpose of this code in PirateDetail?

**A Its an early return with code that wont break, that will stop the rest running if Pirate is falsey** 

Question 3

In PirateDetail, to delete a pirate, we have a button with a listener "onClick" which triggers a function called "handleDelete". The handleDelete function uses a function onDelete. Where is it receiving onDelete from?

**A PirateContainer**

# Bonus Points Questions

Question 1

In PirateContainer, what does Promise.all return?

**A the response/get request from each of the array of promises then sets the array of responses to their own state**

Question 2

Ideally, we want our state to live at the top of our component chain, except in one other scenario. This is when our component contains a, what?

**A i think it depends on the use case, what component is in charge of what?  I think you might mean an Input too, but in that case i'd use a useRef i think? I dont quite get this question**
