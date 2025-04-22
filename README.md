
# Project Title

A brief description of what this project does and who it's for


## Installation

Install my-project with npm

```bash
  npm install my-project
  cd my-project
```
    
## License

[MIT](https://choosealicense.com/licenses/mit/)


## Usage/Examples

```javascript
import Component from 'my-project'

function App() {
  return <Component />
}
```


## Running Tests

To run tests, run the following command

```bash
  npm run test
```


## Optimizations

What optimizations did you make in your code? E.g. refactors, performance improvements, accessibility


## API Reference

#### Get all items

```http
  GET /api/items
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get item

```http
  GET /api/items/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |

#### add(num1, num2)

Takes two numbers and returns the sum.


