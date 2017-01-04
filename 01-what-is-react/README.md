# React
- view layer for web applications
- component: 
	- self contained modul that renders some output
    - component might include one or more other components
- React operates **not directly on DOM**, but on a **virtual DOM**
- rather than manipulating the document in browser after changes to our data, it resolves changes in its vitual DOM. AFter the virtual DOM has been updateted, React detects intelligently what changes to make to the actual DOM
- React Virtual DOM exsists in-memory
