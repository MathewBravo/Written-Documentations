# State in React

### Local States

This type of state belongs to a single component. Things like the input placed into an input field resulting in a `<p>` output of the user’s input. These types of state are managed internally within a single component.

### Cross-Component State

This type of state effects more than one component. An action like a button press opening an overlay would be Cross-Component state. When more than one component is required to work together to perform an action the process uses Cross-Component state. Anytime you pass a prop to a different component and then use that received data to perform an action you are using Cross-Component state.

### App-Wide State

This is a type of state that changes how an entire application behaves. Something like having a user login to use specific features or having features locked behind the validation of a purchased tier (think MyFitnessPal or Strava features that require validation of purchase).

## React Context

This is reacts built in Context management tool. The benefits of tools that are built in is they require no setup. From the creator of Redux himself,

> If you're only using Redux to avoid passing down props, context could replace Redux - but then you probably didn't need Redux in the first place.

So, for basic passing of data between components inside an application there’s no need to look outside of React Context. It is incredibly efficient at performing tasks in which it needs to read does not write a lot of data. Like when changing from Dark to Light mode or checking if a user is currently authenticated.

As react gets increasingly complex and powerful the use for outside (tools not included when creating the initial app) become less and less necessary. However, given the way the industry is currently and the ease of use some external solutions offer it's a good idea to know them. Below I'll talk a bit about Redux one of if not the most popular alternative.

## Redux State Management.

Depending on the app you are creating you may or may not need to worry about using Redux to manage your applications state. React Context and Redux can be used together to manage your applications state. For large scale applications state management becomes an exceedingly challenging task and using React Context can create overly nested state structures or require messy Context management files.

As projects get larger, efficiency becomes more important. While scale should definitely be a consideration when making claims about the efficiency of Redux. For applications in which states are expected to require deep levels of nesting or excessively large React Context providers. As well as applications that require extremely high frequency state changes Redux is a preferred method of state management.

Redux however deserves its own write-up so I have linked it [here](redux)
