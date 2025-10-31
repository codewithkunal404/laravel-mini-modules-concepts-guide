# 🧩 Laravel Concepts — Mini Modules List
### 🔰 1. Laravel Basics

- Installation & Folder Structure

- Laravel Request Lifecycle

- Routing Basics (web.php, api.php)

- Controllers & Methods

- Views (Blade Templates)

- Passing Data to Views

- Environment Config (.env)

### 🧱 2. Core Foundation

- Service Providers

- Service Container (IoC Container)

- Facades (How Facades Work)

- Contracts / Interfaces

- Dependency Injection (DI)

### 🧑‍💻 3. Routing & Middleware

- Route Parameters & Named Routes

- Route Groups / Prefix / Namespaces

- Middleware Basics

- Custom Middleware Example (e.g., CheckAge)

- Global vs Route Middleware

- CSRF Protection

### 🧭 4. Controllers & Requests

- Resource Controllers

- Form Requests (Validation Class)

- Route Model Binding

- Custom Responses (JSON, Redirect, etc.)

### 🗃️ 5. Database & Eloquent ORM

- Database Configuration

- Migrations

- Seeders & Factories

- Eloquent Models

- CRUD Operations

##### Relationships:

- One to One

- One to Many

- Many to Many

- Has Many Through

- Polymorphic Relations

- Query Builder

- Soft Deletes

- Accessors / Mutators

- Eager Loading

### 🚀 6. Database Optimization

- Eager Loading vs Lazy Loading

- Query Caching

- Indexing & DB Query Optimization

- Using Redis for Caching

- Pagination Optimization

- Chunking & Lazy Collections

### 🔄 7. Caching Systems

- Cache Drivers (File, Redis, Database, Array)

- Store / Retrieve / Forget Cache

- Tagged Cache

- Cache Invalidation

- Redis Setup + Example CRUD

### ⚙️ 8. Service Container & Binding

- Basic Binding

- Interface Binding

- Contextual Binding

- Automatic Injection

- Real-World Example (Payment Gateway / Power Plug analogy)

### 📦 9. Service Providers

- How Service Providers Boot Laravel

- Register vs Boot Methods

- Creating Custom Service Providers

- Binding Services inside Provider

### 🔐 10. Authentication & Authorization

- Laravel Breeze / Jetstream / Fortify

- Login / Registration / Logout

- Guards & Providers

- Middleware auth and guest

- Policies & Gates (Role Based Access Control)

- Password Reset Flow

### 📨 11. Notifications & Mails

- Sending Emails (Markdown Mails)

- Mailables

- Mail Queues

- Notifications (Mail, SMS, Slack)

- Custom Channels

### ⏱️ 12. Queues & Jobs

- Queue Concept & Setup

- Queue Drivers (Database / Redis)

- Creating Jobs

- Dispatching Jobs

- Retrying / Failed Jobs

- Laravel Horizon (Monitor Queues)

### 🧩 13. Events & Listeners

- Event Basics

- Listener Handling

- Broadcasting Events

- Real-Time Example (Chat / Notifications)

- Queueing Listeners

- Event Subscribers

### 🌐 14. API Development

- API Routes & Controllers

- API Resources (Transformers)

- Request Validation

- Authentication (Sanctum / Passport)

- Rate Limiting

- API Versioning

- Error Handling

### 💾 15. File Handling

- File Uploads

- Storage Facade

- Public vs Private Storage

- File Download & Delete

- S3 / Cloud Storage

### 🔔 16. Real-Time Apps (Broadcasting)

- Laravel Echo + Pusher Setup

- WebSockets (BeyondCode WebSockets)

- Broadcasting Channels (Public / Private)

- Authentication for Private Channels

- Real-time Notifications or Chat Example

### 🔁 17. Task Scheduling

- php artisan schedule:run

- Kernel Schedule Setup

- Automating Jobs (Clean Logs, Send Reports)

### 🧰 18. Artisan & CLI

- Custom Artisan Commands

- Console Kernel

- Using Artisan in Code (Artisan::call())

### 🧩 19. Testing

- PHPUnit Basics

- Feature vs Unit Tests

- HTTP Test Methods (get, post, assertStatus)

- Mocking / Fakes / Factories

- Dusk (Browser Testing)

### 🧠 20. Advanced Topics

- Repositories Pattern

- Service Pattern

- Observer Pattern

- DTOs (Data Transfer Objects)

- Pipelines

- Macros

- Custom Blade Directives

### ☁️ 21. Deployment & DevOps

- Environment Setup

- Configuration Caching

- Queue Workers (Supervisor setup)

- Horizon Deployment

- Laravel Forge / Vapor / Docker Setup

### 🔄 22. Performance & Security

- Query Optimization

- Route Caching

- Config Caching

- Minifying Assets

- CSRF / XSS / SQL Injection Protection

- Logging & Error Handling

### 🧩 23. Redis & Broadcasting

- Redis Setup

- Redis Pub/Sub

- Broadcasting Notifications

- Using Redis as Queue Driver

### 🧩 24. Laravel with Frontend

- Laravel + Vue

- Laravel + React (Vite)

- Laravel Livewire

- Inertia.js

- Alpine.js

### 🧭 25. Architecture Concepts

- MVC Architecture

- Dependency Inversion

- SOLID Principles

- Domain-Driven Design (DDD) Basics

- Hexagonal Architecture (Optional Advanced)