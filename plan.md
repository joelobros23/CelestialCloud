# Project Plan: CelestialCloud

**Description:** A simplified web hosting platform built with Ruby on Rails, focusing on ease of use and essential features.


## Development Goals

- [ ] Install and configure tailwindcss-rails, customizing application.tailwind.css with a basic theme.
- [ ] Implement Domain model validations (name presence, plan inclusion in a predefined list ['basic', 'premium', 'enterprise']).
- [ ] Enhance the Domain scaffold views (index, show, new, edit) with Tailwind CSS classes for a responsive and modern UI.
- [ ] Modify the Domains controller to automatically associate newly created domains with the currently logged-in user (before_action :authenticate_user!). Ensure only associated domains are displayed.
- [ ] Implement domain status transitions (e.g., 'pending', 'active', 'suspended', 'cancelled') using an enum or a state machine gem (e.g., AASM), and reflect these states in the UI.
- [ ] Add a user profile page where users can view their domains and update their account information.
- [ ] Implement basic plan selection during domain creation, allowing users to choose a plan ('basic', 'premium', 'enterprise').
- [ ] Secure the platform by using strong parameters in the Domains controller to prevent mass assignment vulnerabilities.
- [ ] Add a flash message system using Tailwind CSS to provide feedback to users on actions (e.g., domain created, updated, deleted).
- [ ] Create seed data for initial user and some initial domains for testing
