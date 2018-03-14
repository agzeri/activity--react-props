# Gmail

## General

Time to keep practicing with `React.props`. We are going to build a basic Gmail view.

## Steps

1. You’ll need to fork this [pen](https://codepen.io/agzeri/pen/WzraQG)

2. Read carefully, you have almost everything you need to create the view.
  2.1 The data object
  ```js
  ```
  2.2 The JSX objects
  ```js
  ```

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
4.1 Create a `prop` for the author name, message and time. And, to display which `Email` was read or not you could use a prop and validate in the component using a `if` statement.

## Deliverable

+ A pen with code solved.

**Happy Coding**
