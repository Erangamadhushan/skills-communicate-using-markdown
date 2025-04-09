# Week of April 1 - April 7, 2025

## What I Learned This Week

- Learned how to use GitHub Actions for automated testing
- Explored CSS Grid for responsive layouts(tailwindcss)
- Understood the basics of React hooks(useState)

## Challenges Faced

- Struggled with setting up proper Jest testing environment
  - Solution: Found a tutorial that explained the configuration steps clearly
- Had issues with CSS Grid item alignment
  - Solution: Used the Firefox DevTools Grid inspector to debug layout issues

  ## Resources Discovered

- [CSS Grid Guide](https://css-tricks.com/snippets/css/complete-guide-grid/) - Comprehensive visual guide to CSS Grid
- [React Hooks Tutorial](https://legacy.reactjs.org/docs/hooks-reference.html#usestate) - Official documentation that clarified useState concepts


## Code Snippets
```javascript
function Counter({initialCount}) {
  const [count, setCount] = useState(initialCount);
  return (
    <>
      Count: {count}
      <button onClick={() => setCount(initialCount)}>Reset</button>
      <button onClick={() => setCount(prevCount => prevCount - 1)}>-</button>
      <button onClick={() => setCount(prevCount => prevCount + 1)}>+</button>
    </>
  );
}
```