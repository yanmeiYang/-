-- $state
- $state.go('contact.detail') will go to the 'contact.detail' state
- $state.go('^') will go to a parent state.
- $state.go('^.sibling') will go to a sibling state.
- $state.go('.child') will go to a child state.
- $state.go('.child.grandchild') will go to a grandchild state.

### window.top.postMessage 引发的思考
  - window.top 是否在所有浏览器中否存在
  - window.top.postMessage 浏览器的支持情况
  	 [postMessage 浏览器的支持](https://developer.mozilla.org/en-US/docs/Web/API/Window/postMessage "postMessage 浏览器的支持")
