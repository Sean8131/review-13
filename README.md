# Review 13

## 1

- This is an array: `[1, 2, 3]`. Map over it to create another array containing: `[2, 4, 6]`

```jsx
[1, 2, 3].map((number, index) => {
    return (
      number * 2
    )
}

);
```

## 2

- This is a React component rendering a list of ice cream flavors. There are 6 bugs. Can you
  find and fix them?

```jsx
function IceCreamShowcase() {
  const iceCreamFlavors [
    {name: "Rockmelon and Lime"}, 
    {name: "Cookies & Cream"}, 
    {name: "Strawberry Cookies & Cream"},
    {name: "Hokey Pokey"}, 
    {name: 'Vanilla'}, 
    {name: 'Lime and Coconut'};
  ];

  return (
    <div>
      <h1>Ice Cream!</h1>

      <ul>
      iceCreamFlavors.map(() => {
        <li>flavor<li>
      });
      </ul>
    </div>
  )
}
```

## 3

- Name something you took away from Dan Walker's chat this morning

Blueprint - There will be redundancies in the tech industry. Prepare for that and accept it. Don't take a redundancy personally.
