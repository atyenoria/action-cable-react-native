# Action Cable Node
Action Cable for react native node module.

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