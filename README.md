# React

### Rules of State
- Only usable with class components
- 'State' is a JS **object** that contains data relevant to a component
- Updating 'state' on a component causes the component to (almost) instanly rerender
- State must be initialized when a component is created
- State can **only** be updated using the function 'setState'
### Rules of Class Components
- Must be a Javascript Class
- Must extend (subclass) React.Component
- Must define a 'render' method that returns some amount of JSX


# React Lifecycle (most use)
### ComponentDidMount
Good place to do data-loading
### ComponentDidUpdate
Good place to do more data-loading when state/props change
### ComponentWillUnmount
Good place to do cleanup (especially for non-React stuff)

**Example**
[Chat](https://github.com/khuongtran19/ReactMiniProj1) - This project create simple show for chat app.
[Season](https://github.com/khuongtran19/ReactMiniProj2) - This project show your current location weather
[List Cars](https://github.com/khuongtran19/ReactMiniProj3) - This project return images through searching words with using API from Unsplash
[Youtube](https://github.com/khuongtran19/ReactMiniProj4) - This project re-create youtube page show the videos and next suggestion using Google API