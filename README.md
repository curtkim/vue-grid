# vue-grid-static
> A flexible grid component for Vue.js

## Usage

```js
<grid
  :data="data"
></grid>
```

```js
export default {
  data() {
    return {
      data: {
        "columns": [
          { "name": "col1" },
          { "name": "col2" },
          { "name": "col3" }
        ],
        "rows": [
          {
            "col1": "Column 1 Row 1",
            "col2": "Column 2 Row 1",
            "col3": "Column 3 Row 1"
          },{
            "col1": "Column 1 Row 2",
            "col2": "Column 2 Row 2",
            "col3": "Column 3 Row 2"
          },{
            "col1": "Column 1 Row 3",
            "col2": "Column 2 Row 3",
            "col3": "Column 3 Row 3"
          }
        ],
        "total_count": 1000
      }
    }
  }
}
```