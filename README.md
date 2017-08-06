# React VK Login Button

```sh
react-vk-login
```

```js
import React from 'react'
import VKLogin from 'react-vk-login'
import styles from './styles.css'

export default class LoginWithVK extends React.Component {

  static propTypes = {

  }

  callbackVK = ({code, redirectUri}) => {
    // Login with vk
  }

  render () {
    return (
      <VKLogin
        clientId='xxx'
        callback={this.callbackVK}
        className={styles.vk}
        text='VK'
      />
    )
  }

}

```
