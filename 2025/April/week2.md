# Week of April 8 - April 14, 2025

## What I Learned This Week

- Explored CSS Grid for responsive layouts(tailwindcss)
- Understood the basics of React hooks(useEffect)

## Challenges Faced

- Struggled with setting up proper Jest testing environment
  - Solution: Found a tutorial that explained the configuration steps clearly
- Had issues with CSS Grid item alignment
  - Solution: Used the Firefox DevTools Grid inspector to debug layout issues

  ## Resources Discovered

- [CSS Grid Guide](https://css-tricks.com/snippets/css/complete-guide-grid/) - Comprehensive visual guide to CSS Grid
- [React Hooks Tutorial](https://legacy.reactjs.org/docs/hooks-reference.html#useEffect) - Official documentation that clarified useEffect concepts


## Code Snippets
```javascript
useEffect(() => {
  const subscription = props.source.subscribe();
  return () => {
    // Clean up the subscription
    subscription.unsubscribe();
  };
});
```