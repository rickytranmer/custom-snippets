# Custom Snippets
## for [Sublime](https://github.com/rickytranmer/custom-snippets##sublime) and [VS Code](https://github.com/rickytranmer/custom-snippets#vs%20code)

<br>

## SUBLIME
### &nbsp;-Installation-
Sublime Text -> Preferences -> Browse Packages

Place any custom snippets in the `User` folder.


### &nbsp;-Snippets-
**cN** -> `className=""`<br />
**comL** -> `/*  */`<br />
**comR** -> `{/*  */}`<br />
**comB** -> 
```
/**
 * 
 *
 * 
**/
```
**deb** -> `debugger;`<br />
**dcN** -> `<div className=""></div>`<br />
**dgt** -> `new Date().getTime()`<br />
**for** -> 
```
for(i = 0; i <loop.length}; i++) {
	console.log(loop[i]); 
}
```
**gid** -> `document.getElementById('')`<br />
**gcn** -> `document.getElementsByClassName('')`<br />
**interval** -> `setInterval(()=> { }, 100);`<br />
**log** -> `console.log();`<br />
**passT** -> `val={this.val}`<br />
**passP** -> `val={this.props.val}`<br />
**passS** -> `val={this.state.val}`<br />
**qs** -> `document.querySelector('')`<br />
**qsa** -> `document.querySelectorAll('')`<br />
**rie** -> `{ bool ? () : () }`<br />
**rng** -> `Math.floor(Math.random() * (max - min + 1)) + min`<br />
**routeM** -> 
```
{array.map((path)=> 
  <Route key={path} exact path={path} render={
    (props)=> <Element  /> } />
)}
```
**routeP** -> `<Route path='/' render={ (props)=> <Element  /> } />`<br />
**timeout** -> `setTimeout(()=> { }, 100);`

<br>

## VS CODE
### &nbsp;-Installation-
Paste .json in Code -> User -> Snippets

### &nbsp;-Snippets-
[javascript](https://github.com/rickytranmer/custom-snippets/blob/master/vscode/javascript.json)

[react](https://github.com/rickytranmer/custom-snippets/blob/master/vscode/javascriptreact.json)