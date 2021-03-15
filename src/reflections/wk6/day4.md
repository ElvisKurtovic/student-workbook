What is a nested route?
<!-- enter you answer in the space below -->
```
const router = new VueRouter({
  routes: [
    { path: '/user/:id', component: User }
  ]
})
```

When might you use a nested route? (other than the provided example)
<!-- enter you answer in the space below -->
```
 We need nested routes to organize routes where components are nested multiple levels deep, into one coherent place.
```

Can you pass parameters through nested routes? When might you use them?
<!-- enter you answer in the space below -->
```
Yes
When you have children within them such as comments to a blog post by a specific userId or blogId
```

https://github.com/ElvisKurtovic/pokedexg.git