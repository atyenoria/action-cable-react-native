# Depreciated!!(use https://github.com/cpunion/react-native-actioncable.git)
Action Cable for react native node module. This is React native polyfill for https://github.com/tomchinery/action-cable-node. Action-cable-node use native js which cause "Can't find variable ..." pointed by https://github.com/facebook/react-native/issues/1495. This issue has no activity as of now(20160910). That's why react native polyfill is required

## Install

```
npm install action-cable-react-native --save
```

## Usage

It has all the same methods as ActionCable and usage is exactly the same.

```
import ActionCable from 'action-cable-node'

const App = {}

App.cable = ActionCable.createConsumer()

App.cable.subscriptions.create({ channel: "ChatChannel", room: "Best room!"})

etc...
```

See the ActionCable [documentation](http://edgeguides.rubyonrails.org/action_cable_overview.html) for more.