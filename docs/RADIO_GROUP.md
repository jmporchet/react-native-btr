# RadioButton

###### Note: Please bear with the current documentation. Docs will be updated soon.

Selects only one value out of multiple RadioButtons.

### Props
Key | Type | Default
----|----|----
labelStyle | object | {}
radioButtons | array | []
onPress | function | () => null

### Usage
```
import { RadioGroup } from 'react-native-btr';

state = {
    radioButtons: [
      {
        label: 'In Progress',
        value: 'stage-1',
        checked: true,
        color: '#484',
        disabled: true,
        flexDirection: 'column',
        size: 14
      },
      {
        label: 'Completed',
      }
    ]
}

<RadioGroup 
  labelStyle={{fontSize: 14}}
  radioButtons={this.state.radioButtons}
  onPress={radioButtons => this.setState({radioButtons})}
/>

``` 