This is my attempt to learn `Litestart` by building an e-book store.

**Toolkit:**
- [Litestar](https://litestar.dev/)
- SQLite for dev with [aiosqlite](https://aiosqlite.omnilib.dev/)
- [Postgres](https://www.postgresql.org/) without ORM
- [Asyncpg](https://github.com/MagicStack/asyncpg)
- Self-made migrations (it will be hard 😅)
- DB diagrams in [dbdiagram.io](https://dbdiagram.io/)
- [Msgspec](https://github.com/jcrist/msgspec) instead of [pydantic](https://github.com/pydantic/pydantic)
- [Jinja](https://jinja.palletsprojects.com/)

[**App DB diagram**](https://dbdiagram.io/d/Ebook-Store-67177fe297a66db9a3d8aa15)

**Core Features**:
- **User Management**:
  - Registration
  - Login
  - Profile management
- **Store Flow**:
  - Search and Advance search
  - Find by category
  - Sort & filter
  - View book details
  - Recommendation Engine
- **Purchase Flow**:
  - Add to cart
  - Checkout
  - Purchase history
- **Book Management**:
  - Download
  - Send to device
  - Sort, filter, find
- **Admin Panel**:
  - Manage books
  - Users
  - Orders