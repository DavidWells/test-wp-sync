---
ID: 65
post_title: newnewnew
author: David Wells
post_date: 2016-01-24 06:37:40
post_excerpt: ""
layout: post
permalink: http://testbox.wpengine.com/?p=65
published: true
---

This is the newestes fix it plx. again

```js
var test = "newnewnew"
```

```js
import React, { PropTypes, Component } from 'react'
import styles from './Card.css'
import externalCSS from '../Card/Card.css'

const Card = ({children, className, ...other}) => {
  const classProp = (className) ? className : ""
  const classes = `${styles.card} anypoint-card ${classProp}`

  return (
    <span className={classes} {...other}>
      {children}
    </span>
  )
}

Card.propTypes = {
  children: PropTypes.any,
  className: PropTypes.string,
}

export default Card
```

# Nice!

Update the post please