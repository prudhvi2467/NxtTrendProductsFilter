In this project, let's build a **Nxt Trendz - Products Filters Group** app by applying the concepts we have learned till now.

### Refer to the images below:

<br/>
<div style="text-align: center;">
    <img src="https://assets.ccbp.in/frontend/content/react-js/nxt-trendz-products-filter-group-output-v0.gif" alt="products filters group output" style="max-width:70%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12)">
</div>
<br/>

**Failure View**

<br/>
<div style="text-align: center;">
    <img src="https://assets.ccbp.in/frontend/content/react-js/nxt-trendz-products-filter-group-failure-view-output.gif" alt="products filters group failure output" style="max-width:70%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12)">
</div>
<br/>

### Design Files

<details>
<summary>Click to view</summary>

- [Extra Small (Size < 576px) and Small (Size >= 576px) - Products](https://assets.ccbp.in/frontend/content/react-js/nxt-trendz-products-filter-group-sm-output-v2.png)
- [Extra Small (Size < 576px) and Small (Size >= 576px) - No Products](https://assets.ccbp.in/frontend/content/react-js/nxt-trendz-products-filter-group-sm-no-products-output-v0.png)
- [Extra Small (Size < 576px) and Small (Size >= 576px) - Failure View](https://assets.ccbp.in/frontend/content/react-js/nxt-trendz-products-filter-group-sm-failure-view-output.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - Products](https://assets.ccbp.in/frontend/content/react-js/nxt-trendz-products-filter-group-lg-output-v2.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - No Products](https://assets.ccbp.in/frontend/content/react-js/nxt-trendz-products-filter-group-lg-no-products-output.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - Failure View](https://assets.ccbp.in/frontend/content/react-js/nxt-trendz-products-filter-group-lg-failure-view.png)

</details>

### Set Up Instructions

<details>
<summary>Click to view</summary>

- Download dependencies by running `npm install`
- Start up the app using `npm start`
</details>

### Completion Instructions

<details>

<summary>API Requests & Responses</summary>
<br/>

**productsApiUrl**

#### API: `https://apis.ccbp.in/products`

#### Example: `https://apis.ccbp.in/products?sort_by=PRICE_HIGH&category=4&title_search=machine&rating=4`

#### Method: `GET`

#### Description:

Returns a response containing the list of Products

#### Success Response

```json
{
  "products": [
    {
      "title": "Front Load Machine",
      "brand": "Samsung",
      "price": 22490,
      "id": 24,
      "image_url": "https://assets.ccbp.in/frontend/react-js/ecommerce/appliances-washing-machine.png",
      "rating": 4.5,
    },
      ....
  ]
}
```

</details>

<details>
<summary>Components Structure</summary>

<br/>
<div style="text-align: center;">
    <img src="https://assets.ccbp.in/frontend/content/react-js/nxt-trendz-products-filter-group-component-structure-breakdown.png" alt="component-breakdown-structure" style="max-width:100%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12)">
</div>
<br/>

</details>

### Important Note

<details>
<summary>Click to view</summary>

<br/>

**The following instructions are required for the tests to pass**

- `Home` Route should consist of `/` in the URL path
- `Login` Route should consist of `/login` in the URL path
- `Products` Route should consist of `/products` in the URL path
- `Cart` Route should consist of `/cart` in the URL path
- No need to use the `BrowserRouter` in `App.js` as we have already included in `index.js`

- User credentials

  ```text
   username: raja
   password: raja@2021
  ```

- The rating stars images in the route should have the alt attribute value as **rating {ratingId}**

</details>

### Resources

<details>
<summary>Image URLs</summary>

- [https://assets.ccbp.in/frontend/react-js/nxt-trendz/nxt-trendz-no-products-view.png](https://assets.ccbp.in/frontend/react-js/nxt-trendz/nxt-trendz-no-products-view.png) alt should be **no products**
- [https://assets.ccbp.in/frontend/react-js/nxt-trendz/nxt-trendz-products-error-view.png](https://assets.ccbp.in/frontend/react-js/nxt-trendz/nxt-trendz-products-error-view.png) alt should be **products failure**

</details>

<details>
<summary>Colors</summary>

<br/>

<div style="background-color: #f1f5f9; width: 150px; padding: 10px; color: black">Hex: #f1f5f9</div>
<div style="background-color: #0f172a; width: 150px; padding: 10px; color: white">Hex: #0f172a</div>
<div style="background-color: #12022f; width: 150px; padding: 10px; color: white">Hex: #12022f</div>
<div style="background-color: #64748b; width: 150px; padding: 10px; color: white">Hex: #64748b</div>
<div style="background-color: #475569; width: 150px; padding: 10px; color: white">Hex: #475569</div>
<div style="background-color: #0967d2; width: 150px; padding: 10px; color: white">Hex: #0967d2</div>
<div style="background-color: #ffffff; width: 150px; padding: 10px; color: black">Hex: #ffffff</div>

</details>

<details>
<summary>Font-families</summary>

- Roboto

</details>

> ### _Things to Keep in Mind_
>
> - All components you implement should go in the `src/components` directory.
