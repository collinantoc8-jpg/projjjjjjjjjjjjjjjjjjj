# TODO: Add Authentication and Account Management

## Backend Changes
- [x] Update backend/db.js: Add users table and seed admin user
- [x] Update backend/package.json: Add express-session dependency
- [x] Update backend/server.js: Add session middleware, auth routes (login, logout, check auth, add user)

## Frontend Changes
- [x] Create frontend/login.html: Login page with form
- [x] Update frontend/index.html: Add "Add Account" menu item in sidebar
- [x] Create frontend/add-account.html: Form to add new accounts
- [x] Update frontend/app.js: Add auth checks, redirect to login if not authenticated, handle login/logout
- [x] Update frontend/styles.css: Styles for login and add-account pages

## Testing
- [ ] Install dependencies (npm install)
- [ ] Start server (npm start)
- [ ] Test login with admin/admin123
- [ ] Test adding new accounts
- [ ] Test logout and auth protection
