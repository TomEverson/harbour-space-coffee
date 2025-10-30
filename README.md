# Harbour Space Coffee - REST API Assignment

Welcome to your first REST API project! In this assignment, you'll build a simple REST API for a virtual coffee shop menu.

## Goal

Create a RESTful API to manage coffee shop menu items. This is a free-form assignment - you decide what properties your menu items should have!

## Requirements

### API Endpoints

Your API should support the following operations:

1. **Get all menu items** - Retrieve a list of all items
   - Bonus: Add optional filtering (e.g., by category, price range, etc.)

2. **Get menu item details** - Retrieve a specific item by ID

3. **Add a new menu item** - Create a new item in the menu

4. **Update a menu item** - Modify an existing item

5. **Delete a menu item** - Remove an item from the menu

### Technical Requirements

- Create a `MenuItemController` (or similar name of your choice)
- The logic can live directly in the controller OR you can extract it to a service - your choice!
- **No repositories or database persistence required** - you can store items in memory (e.g., using a mutable list)

### Menu Item Model

**You decide!** Think about what information a coffee shop menu item should have. Some ideas:
- Name
- Price
- Description
- Category (coffee, tea, pastry, etc.)
- Size options
- Availability
- ...or anything else you think makes sense!

## Getting Started

This is a Spring Boot application using Kotlin. To run it:

```bash
./gradlew bootRun
```

The application will start on `http://localhost:8080`

## Testing Your API

You can test your API using:
- Browser (for GET requests)
- Postman
- curl
- IntelliJ HTTP Client
- Any other REST client you prefer

## Tips

- Think about appropriate HTTP methods (GET, POST, PUT/PATCH, DELETE)
- Consider HTTP status codes (200, 201, 404, etc.)
- Remember to use `@RestController` and request mapping annotations
- Don't forget to handle edge cases (what if an item doesn't exist?)

Good luck and have fun! ☕