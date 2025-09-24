📚 Bookstore Web Application Using Spring Boot & Thymeleaf

This Bookstore project is a full-stack web application designed to manage books, customers, and orders efficiently. Built with Spring Boot on the backend and Thymeleaf on the frontend, it offers a clean architecture, fast performance, and a user-friendly interface.

🛠️ Backend: Spring Boot

- RESTful Architecture: Controllers handle HTTP requests for book listings, user actions, and order processing using @RestController and @RequestMapping.
- JPA Integration: Entities like Book, Customer, and Order are mapped to database tables using Spring Data JPA, enabling seamless CRUD operations.
- Service Layer: Business logic is encapsulated in service classes, promoting modularity and testability.
- Validation & Security: Input validation via annotations (@Valid, @NotBlank) and optional Spring Security for user authentication and role-based access.

🎨 Frontend: Thymeleaf

- Dynamic Templates: HTML pages use Thymeleaf expressions (${book.title}, th:each, th:if) to render dynamic content directly from the model.
- Form Binding: Supports user registration, book search, and checkout forms with automatic binding to backend models.
- Reusable Layouts: Common UI components like headers, footers, and navigation bars are defined as fragments (th:fragment) for consistent design.
- Live Feedback: Error messages and success notifications are displayed using conditional rendering (th:if, th:unless).

⚡ Efficiency & Scalability

- Minimal Configuration: Spring Boot’s auto-configuration and embedded server reduce setup time and deployment complexity.
- Responsive UI: Thymeleaf templates are lightweight and integrate easily with Bootstrap or Tailwind CSS for mobile-friendly design.
- Pagination & Filtering: Efficient book browsing with server-side pagination and category-based filtering.
- Admin Dashboard: Role-based access to manage inventory, view orders, and track customer activity.


