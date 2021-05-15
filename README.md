# react-native

clone the module and add on any react-native or expo project, and test it. 
### Linking Screen - Linking
### Fully Customize header component - AppHeader

Header usage:
```
<AppHeader
    title={"Home"}
    headerBg={"#60c5a8"}
    iconColor={"black"}
    menu //or back
    optionalBadge={5}
    navigation={props.navigation}
    right="more-vertical"
    rightFunction={() => console.log('right')}
    optionalIcon="bell"
    optionalFunc={() => console.log('optional')}
/>
```

#### AppHeader Screenshot
<div display="inline-block">
  <img src="/screenshots/header1.jpg" width="300" height="100" />
  <img src="/screenshots/header2.jpg" width="300" height="100" />
  <img src="/screenshots/header3.jpg" width="300" height="100" />
</div>
