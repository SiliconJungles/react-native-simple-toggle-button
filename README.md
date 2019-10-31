# React Native Simple Toggle Button

Adapted from https://github.com/ashishpandey001/react-native-flip-toggle-button

## Usage
- `yarn add @siliconjungles/react-native-simple-toggle-button` 
or 
- `npm install @siliconjungles/react-native-simple-toggle-button --save`
```
<ToggleButtonComponent
  value={useQr}
  leftText="Left"
  rightText="Right"
  buttonWidth={250}
  buttonHeight={50}
  buttonRadius={50}
  sliderWidth={125}
  onToggle={(newState) => this.setState({ useQr: newState })}
/>
```
<img src="images/1.png" /> <img src="images/2.png">
