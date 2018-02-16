# iesAnchor v0.1
Anchor any element on scroll with javascript

## Usage
Include iesAnchor.js in your webpage and then call this function ***after*** your target element is loaded
```javascript
_iesAnchor({target:document.getElementById("element-to-anchor")})  
```
  
### Usage with jQuery selector  
```javascript
_iesAnchor({target:"#element-to-anchor"})  
```

### Parameters 
```javascript
_iesAnchor({  
	position:100, //int (Default: 0), distance from top of page to start the anchoring onscroll, and the position of the anchored element   
	invert:false,//boolean (Default: false) when true, the anchoring is disable if the user scroll from bottom to top  
	timeout:0,  //int (Default: 0 (disabled)) in milliseconds, after this timeout the anchoring is disabled  
	jQuerySelector:true,  //boolean (Default: false) - when true, you are allowed to pass a jQuery selector in the target parameter  
	target:document.getElementById("element-to-anchor"), //REQUIRED - DOM element to anchor  
	mobile:true //boolean (Default:false) - when true, the anchoring is active also on mobile  
})
```
