# Store Product Listing React App - Project Overview

<h3>Visit: https://store-product-listing-react-app.netlify.app/</h3>
<img alt="alt_text" src="./shop.gif"/>

## Description:

In this project, a product listing application is developed using React. The app fetches data from the "Fake Store API" to display a list of products available in a fake online store. The main components used in this project are: 

## Components:

### Home Component 
- The Home component serves as the main entry point of the application.
- It fetches the product data from the "Fake Store API" using the `fetch` function and `useState` hook.
- The fetched product data is stored in the `shop` state.
- The Home component also holds the `Header` component and the `ProductCard` component.
- The `Header` component is passed the `setShop` function and the `news` state to handle product filtering.
- The `ProductCard` component is passed the `shop` state to display the list of products.

### Header Component
- The Header component displays the title "Products List" at the top of the page.
- It fetches product categories from the "Fake Store API" using the `fetch` function and `useState` hook.
- The fetched categories are stored in the `buttons` state.
- Users can filter products by category by clicking on the category buttons.
- The `btnFilter` function is used to filter the products based on the selected category.

### ProductCard Component
- The ProductCard component receives the `shop` state containing the list of products as props.
- It maps through the product data and renders each product as a card.
- Each card displays the product title, price, and an image.
- The product image is initially displayed, but upon clicking the "Info" button, the product description is revealed in a tooltip-like manner using CSS transitions.

## Styling
- The application's styling is done using CSS.
- The page has a light background with cards for each product.
- Hover effects and transitions are applied to cards and buttons for better user experience.

## Summary
The Fake Store Product Listing application built with React allows users to view a list of products from the "Fake Store API" and filter products by category. The project demonstrates fetching data from an API, managing state with `useState` hook, and creating reusable components to display product information. It can serve as a foundation for building more complex e-commerce applications with features like product details, shopping cart functionality, and user authentication.

