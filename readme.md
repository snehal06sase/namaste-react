React.createElement --> It actually creates the react element. Its basically the object. Its not the html tag.

Render -> this method takes this react element and creates html tag of an element. and put into DOM.

--> If an parent as siblings then pass both of them in an array format.
e.g. <div id="parent">
        <h1>H1 tag</h1>
        <h2>H2 tag</h2>
</div>

React.createElement('div',{id: "parent"}, [React.createElement('h1',{},"H1 tag"), React.createElement('h2',{},"H2 tag")])

