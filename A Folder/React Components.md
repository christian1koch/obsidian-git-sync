- They are functions that return react elements
- Use PascalCase instead of camelCase
- Are the building blocks for React
- Example of a component:
- ```JavaScript
function TemporaryName() {
	return (
		<div>
			<h1>This is a React Component</h1>
		</div>
	)
}
ReactDOM.render(<TemporaryName />, document.getElementById("root"));
	- 
- Components in their own files can be exporting using "export default"
	- Then they can be imported as "import *ComponentName* from *./ComponentName*