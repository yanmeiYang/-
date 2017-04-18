-- $state
- $state.go('contact.detail') will go to the 'contact.detail' state
- $state.go('^') will go to a parent state.
- $state.go('^.sibling') will go to a sibling state.
- $state.go('.child') will go to a child state.
- $state.go('.child.grandchild') will go to a grandchild state.

