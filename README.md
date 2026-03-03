# SPARK - All-in-one Academic Platform 📚

Laravel-based academic support platform for students, tutors, teachers, and school administrators. Utilizes database for meeting sessions and assignments.

## Key Features
1. **Role-Based Access Control**
   - Student, Tutor, Admin, Super Admin roles
   - Custom middleware:
     - AdminMiddleware
     - TutorMiddleware
     - StudentMiddleware
     - SuperAdminMiddleware
2. **Tutor System**
   - Tutor application flow
   - Session scheduling
   - Pending session approval logic
   - Archiving system
3. **Course & Assessment Management**
   - Course tracking
   - Assessment submission/monitoring
   - Individual course linking
4. **Admin Controls**
   - Oversight of tutor sessions
   - User management

---

## Tech Stack
- **Laravel (PHP)**
- **Blade Templates**
- **MySQL / SQL-based database**
- **Docker**
- **Git / GitHub**

--- 

## Project Structure 

```text
app/
├── Http/
│   ├── Controllers/
│   ├── Middleware/
├── Models/
├── Console/Commands/
├── helpers/
```

## Impact
SPARK was awarded Best Education Project at YRHacks 2025.

## Lessons Learned
- Designing backend systems using MVC principles
- Implementing role-based auth
- Databases
- Full-stack collaboration in a competitive environment

## License
MIT
