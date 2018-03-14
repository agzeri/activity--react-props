# Gmail

## General

Time to keep practicing with `React.props`. We are going to build a basic Gmail view.

## Steps

1. You’ll need to fork this [pen](https://codepen.io/agzeri/pen/WzraQG)

2. Read carefully, you have almost everything you need to create the view.

2.1 The data object
```js
const data = [{
  author: 'Josh Matos',
  message: 'Accepted: Mentors Call',
  time: '10:48pm',
  isRead: true
}, {
  author: 'The Bloc Team',
  message: 'Design portfolios galore!',
  time: '8:14am',
  isRead: false
}, {
  author: 'Slack',
  message: 'New login from Slack in Chrome on Mac',
  time: 'Mar 13',
  isRead: false
}, {
  author: 'Trello',
  message: 'Maribel Navia commented on the card',
  time: 'Mar 11',
  isRead: true
}, {
  author: 'Balsamiq Cloud',
  message: 'Your Balsamiq Cloud Trial is about to expire',
  time: 'Mar 11',
  isRead: true
}, {
  author: 'CSA Consultores',
  message: 'Estado de Cuenta Febrero',
  time: 'Mar 11',
  isRead: false
}, {
  author: 'code@nytimes.com',
  message: 'Your New York Times API Key',
  time: 'Mar 10',
  isRead: true
}, {
  author: 'Dropbox (2)',
  message: 'We noticed a new sign into your Dropbox',
  time: 'Mar 8',
  isRead: false
}, {
  author: 'The Bloc Team',
  message: 'Let’s celebrate: It’s International Women’s Day!',
  time: 'Mar 8',
  isRead: false
}, {
  author: 'enrique@muktek.com',
  message: 'Monthly Team Meeting',
  time: 'Mar 7',
  isRead: false
}, {
  author: 'CodePen',
  message: 'The CodePen Spark: Chameleons, Challenges and Celeste',
  time: 'Mar 6',
  isRead: false
}, {
  author: 'Digital Ocean',
  message: 'Save up to 55% with new Droplet plans',
  time: 'Mar 4',
  isRead: true
}, {
  author: 'Trello',
  message: 'Arturo Ortega mentioned in you on the card Day 2 - Tuesday',
  time: 'Mar 1',
  isRead: false
}, {
  author: 'Trello',
  message: 'Damian Allende mentioned in you on the card Day 2 - Tuesday',
  time: 'Mar 1',
  isRead: false
}, {
  author: 'DigitalOcean',
  message: '[DigitalOcean] Your February 2018 invoice is available',
  time: 'Mar 1',
  isRead: true
}, {
  author: 'Slack',
  message: 'New login from Slack in Safari on Mac',
  time: 'Feb 27',
  isRead: false
}, {
  author: 'Joel Ponce',
  message: 'Bookgrade.xlsx - Request for access',
  time: 'Feb 22',
  isRead: true
}];
```

2.2 The JSX objects
+ `App` Component
+ `EmailContainer` Component
+ `Actions` Component

## What is left?

1. We don’t have created the `Email` Component to render a single email.

##

#### 1. Create an `Email` component using `class ComponentName extends React.Component` syntax
#### 2. The markup for each component is the next (dont’t worry for the styles):
```html
<div>
  <div class='email read'>
    <div class='email__actions'>
      <input type='checkbox' />
      <i class='fa fa-star-o'></i>
    </div>
    <p class='email__author'>Josue Matos</p>
    <p class='email__message'>Accepted: Mentors Call</p>
    <p class='email__time'>10:48pm</p>
  </div>
</div>
```
##### Notes
1. Put attention on `class` attributes and rememeber how to change it when you are writing React.
2. Add another component and change the class `read` to `no-read`.

#### 3. Visually you’ll see two different `Email` components, to indicate which email was open and which it wasn’t.

#### 4. The data object is the next, you’ll need to iterate (using a `.map`) over the list and render each component.

Create a `prop` for the author name, message and time. And, to display which `Email` was read or not you could use a prop and validate in the component using a `if` statement.

## Deliverable

+ A pen with code solved.


**Happy Coding**
