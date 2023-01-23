# FlexboxGrid Styled Component

Grid layout system base on [styled-components](https://github.com/styled-components/styled-components) and inspired by [Flexbox Grid](http://flexboxgrid.com/).
The library name is `styled-components-flexboxgrid`.

`styled-components-flexboxgrid` uses [styled-components](https://github.com/styled-components/styled-components) as peer dependency. Please confirm that you have styled-components installed in your project.

## Install

```
npm install styled-components-flexboxgrid --save
```

## Basic Usage

```javascript
import React, { Component } from 'react';
import { Col, Row } from 'styled-components-flexboxgrid'

class App extends Component {
  render() {
    return (
      <Row>
        <Col xs={1} md={6} lg={12}>666</Col>
        <Col xs={1} md={6} lg={12}>777</Col>
      </Row>
    )
  }
}
```
