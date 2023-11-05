# Provide / Inject

Usually, when we need to pass data from the parent to a child component, we use props. However, imagine the case where we have a large component tree, and a deeply nested component needs something from a distant ancestor component. With only props, we would have to pass the same prop across the entire parent chain. We can solve props drilling with `provide` and `inject`.

Visit the following resources to learn more:

- [Provide / Inject in Vue.js](https://vuejs.org/guide/components/provide-inject.html)
