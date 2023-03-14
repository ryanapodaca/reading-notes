# React LifeCycle

React is catalyzed through temporal activation of its components.

The first phase is mounting. Constructors and statics derived from props are rendered here. Updating and unmounting are the other phases.  

Rendering occurs in both the mount and update phases.  Hence rendering occurs before componenetDidMount. 

componentDidMount() method is used after a component is mounted.  You can load content through this method at its component, so it is common for websites to include subscriptions here.

Order:

1. Constructor
2. React Updates
3. Render
4. ComponentDidMount
5. componentWillUnmount

## States vs. Props

Props act similaly to function parameters. Hence props contents are arguments that are initialized and sometimes modulated by higher order components. 

Props can be modified by overriding component content. States cannot.  A state is just the predefined architectural, aesthetic functional content through which dynamic props content is displayed. States are defined from within the component.  

We rerender the state of a component within the application when the user has meaningfully interacted with the component.  For example, if a component includes a minigame, if the user interacts and scores, the state of the component should rerender and add to the score counter.  

Other examples of state variables include information to be collected from a form, tabular data, and other types of counters(temporal, backend functionality).
