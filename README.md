# React

###### Rules of State
- Only usable with class components
- 'State' is a JS **object** that contains data relevant to a component
- Updating 'state' on a component causes the component to (almost) instanly rerender
- State must be initialized when a component is created
- State can **only** be updated using the function 'setState'
###### ComponentDidMount
Good place to do data-loading
###### ComponentDidUpdate
Good place to do more data-loading when state/props change
###### ComponentWillUnmount
Good place to do cleanup (especially for non-React stuff)