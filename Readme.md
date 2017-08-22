# Vue-beer

Build your first VueJs App!

## Result

![result](./result.png)

The final result is composed of a paginated list of beers fetched with an HTTP request with a filter input, and a selected beer details area.

## Step 1: HTTP Request and list rendering

**Specs:**

- HTTP Request to https://api.punkapi.com/v2/beers (GET) in the home component
- Create a BeerList component that render a list of beers with the data from "home" component

**Hints:**

- v-for: https://vuejs.org/v2/guide/list.html#v-for
- vue-axios: https://www.npmjs.com/package/vue-axios (already installed)
- "mounted" hook
- Dynamic props: https://vuejs.org/v2/guide/components.html#Props

## Step 2: Details panel and passing data between components

**Specs:**

- Create a BeerDetails component with the selected beer infos
- Add a "selected" state on the selected beer in "BeerList" component

**Hints:**

- Custom event "$emit input" and v-model: https://vuejs.org/v2/guide/components.html#Form-Input-Components-using-Custom-Events
- Class Binding / Object Syntax: https://vuejs.org/v2/guide/class-and-style.html#Object-Syntax
- Dynamic props: https://vuejs.org/v2/guide/components.html#Props

## Step 3: Filter by name and beer list paginate

**Specs:**

- add a filter input above the beer list in BeerList component
- add paginate buttons under the beer list in BeerList component

**Hints:**

- Computed properties