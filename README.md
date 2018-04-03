# iesAnchor v0.1
Fix any element on scroll with javascript
![example](https://github.com/tritone11/iesAnchor/blob/master/example.gif?raw=true)

## Usage
Include iesAnchor.js in your webpage and then call this function ***after*** your target element is loaded
```javascript
_iesAnchor({target:document.getElementById("element-to-anchor")})  
```
  
### Usage with jQuery selector  
```javascript
_iesAnchor({target:"#element-to-fix"})  
```

### Parameters 
```javascript
_iesAnchor({  
	position:100, //int (Default: 0), distance from top of page to start the anchoring onscroll, and the position of the fixed element   
	invert:false,//boolean (Default: false) when true, the anchoring is disabled if the user scroll from bottom to top  
	timeout:0,  //int (Default: 0 (disabled)) in milliseconds, after this timeout the anchoring is disabled  
	jQuerySelector:true,  //boolean (Default: false) - when true, you are allowed to pass a jQuery selector in the target parameter  
	target:document.getElementById("element-to-fix"), //REQUIRED - DOM element to fix  
	mobile:true //boolean (Default:false) - when true, the anchoring is active also on mobile  
})
```
