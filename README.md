# DAY 6 - State
- if th setState is called with an object argument, it will perform a shallow merge of the data into the object available via this.state and then will rerender the component
- shallow merge: not nested
- keep values in our state that we will use in the render() function
- its preferred to use props instead of state (performance, test)
 