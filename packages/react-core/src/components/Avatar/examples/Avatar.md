---
id: Avatar
section: components
cssPrefix: pf-c-avatar
propComponents: ['Avatar']
---

import avatarImg from './avatarImg.svg';

## Examples
### Basic
```js
import React from 'react';
import { Avatar } from '@patternfly/react-core';
import avatarImg from './examples/avatarImg.svg';

class AvatarExample extends React.Component {
  render() {
    return (
      <Avatar src={avatarImg} alt="avatar"></Avatar>
    );
  }
}
```
