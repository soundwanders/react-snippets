## JavaScript React Snippets


### Import React
```javascript
import React from 'react';
```

### Import React, Component
```javascript
import React, { Component } from 'react';
```

### Import React, useState
```javascript
import React, { useState } from 'react';
```

### Import React, useState, useEffect
```javascript
import React, { useState, useEffect } from 'react';
```

### Import PropTypes
```javascript
import PropTypes from 'prop-types';
```

### Import PureComponent
```javascript
import React, { PureComponent } from 'react';
```

### Class Component
```javascript
class | extends Component {
  state = { | },
  render() {
    return ( | );
  }
}
export default |;
```

### Class Component With Constructor
```javascript
class | extends Component {
  constructor(props) {
    super(props);
    this.state = { | };
  }
  render() {
    return ( | );
  }
}
export default |;
```

### Class Component With Constructor
```javascript
class | extends PureComponent {
  state = { | },
  render() {
    return ( | );
  }
}
export default |;
```

### Stateless Function Component
```javascript
const | = props => {
  return ( | );
};
export default |;
```

### componentDidMount
```javascript
componentDidMount() {
  |
}
```

### useEffect Hook
```javascript
useEffect(() => {
  |
}, []);
```

### componentWillMount
```javascript
componentWillMount()
}
```

### componentWillReceiveProps
```javascript
static getDerivedStateFromProps(props, state)
}
```

### getDerivedStateFromProps
```javascript
static getDerivedStateFromProps(nextProps, prevState) {
  //
}
```

### ShouldComponentUpdate
```javascript
shouldComponentUpdate(nextProps, nextState) {
  //
}
```

### componentDidUpdate
```javascript
componentDidUpdate(prevProps, prevState) {
  //
}
```

### componentWillUnmount
```javascript
componentWillUnmount() {
  //
}
```

### componentDidCatch
```javascript
componentDidCatch(error, info) {
  //
}
```

### getSnapshotBeforeUpdate
```javascript
getSnapshotBeforeUpdate(prevProps, prevState) {
  //
}
```

### setState
```javascript
this.setState({ | : | });
```

### Functional setState
```javascript
this.setState(prevState => {
  return { | : prevState. | }
});
```

### Declare a new state variable using State Hook
	`const [|, set |] = useState();`
	Tab key applies CamelCase to function [count, setCount]

### Render
```javascript
render() {
  return (
    //
  );
}
```

### Render Prop
```javascript
class | extends Component {
  state = { | },
  render() {
    return this.props.render({
      |: this.state.|
    });
  }
}
export default |;
```

### Higher Order Component
```javascript
function | (|) {
  return class extends Component {
    constructor(props) {
      super(props);
    }
	
    render() {
      return < | {...this.props} />;
    }
  };
}
```
