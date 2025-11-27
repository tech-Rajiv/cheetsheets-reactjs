
## 📌 Why This Repo Exists
> To keep short, clear notes that help me revise fast.  
> No long explanations — just the important things.

# cheetsheets-reactjs

## useScrollRestoration()
- Whenever you clicked a link and came back, The page **always scrolled to the top**, Even if you were far down the page.
React Router v7 introduced a new built-in hook: useScrollRestoration()
```jsx
function RootLayout() {
  useScrollRestoration();
  return <Outlet />;
}


