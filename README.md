# React VK Login Button

```sh
react-vk-login
```

```js
import React from 'react'
import VK from 'react-vk-login'
import styles from './styles.css'
import autobind from 'autobind-decorator'

export default class LoginWithVK extends React.Component {

  static propTypes = {

  }

  @autobind
  callbackVK ({code, redirectUri}) {
    // Login with vk
  }

  render () {
    return (
      <VK
        clientId='xxx'
        callback={this.callbackVK}
        className={styles.vk}
        text='VK' />
    )
  }

}

```
