# Pulse Rules

A comprehensive collection of coding standards, patterns, and guidelines for the **Pulse Framework** - a Ruby on Rails-based framework designed for building modern web applications with consistent patterns and best practices.

## 🎯 Overview

The Pulse framework provides a structured approach to Rails development with pre-defined patterns for controllers, views, and UI components. These rules ensure consistency, maintainability, and developer productivity across Pulse-based projects.

## 📁 Rule Categories

### Backend & Controllers
- **[`pulse-backend-rules.mdc`](rules/pulse-backend-rules.mdc)** - Guidelines for using the `Pulse::Backend` concern in Rails controllers, including fields management, filters, breadcrumbs, and turbo frame integration

### UI Components & Patterns
- **[`pulse-section-general.mdc`](rules/pulse-section-general.mdc)** - Standards for implementing Pulse section templates with inline editing and turbo frame functionality
- **[`pulse-filters-form-partial.mdc`](rules/pulse-filters-form-partial.mdc)** - Patterns for building consistent filter forms and search interfaces
- **[`pulse-has-many-section.mdc`](rules/pulse-has-many-section.mdc)** - Guidelines for implementing has_many relationship sections

### Page Templates
- **[`pulse-index-page.mdc`](rules/pulse-index-page.mdc)** - Standards for building consistent index/listing pages
- **[`pulse-show-page.mdc`](rules/pulse-show-page.mdc)** - Patterns for detail/show page implementations

### Framework Foundation
- **[`ruby-on-rails.mdc`](rules/ruby-on-rails.mdc)** - Core Ruby on Rails conventions and best practices that form the foundation of Pulse development

## 🚀 Key Features

The Pulse framework emphasizes:

- **🔄 Turbo Frame Integration** - Seamless SPA-like interactions with server-rendered content
- **🎨 Consistent UI Patterns** - Reusable components and layouts for rapid development
- **📊 Smart Data Management** - Built-in filtering, pagination, and field management
- **🍞 Navigation Support** - Automatic breadcrumb generation and navigation handling
- **⚡ Performance Optimized** - Follows Rails best practices for database queries and caching

## 🛠 Usage

These rules are designed to be used with AI coding assistants and development tools that support the `.mdc` (Markdown with metadata) format. Each rule file contains:

- **Metadata** - File globs, descriptions, and applicability rules
- **Patterns** - Code examples and implementation guidelines  
- **Best Practices** - Performance, security, and maintainability considerations

### For Developers

1. **Reference** - Use these rules as a reference when building Pulse-based applications
2. **Code Review** - Apply these standards during code review processes
3. **AI Integration** - Load these rules into AI coding assistants for automated guidance

### For AI Assistants

These rules provide context-aware coding assistance by:
- Suggesting appropriate patterns based on file paths and extensions
- Enforcing consistent code structure across the application
- Providing detailed examples for complex implementations

## 🏗 Framework Architecture

Pulse builds upon Ruby on Rails with:

- **Concerns** - `Pulse::Backend` for controller functionality
- **View Patterns** - Standardized ERB templates with Turbo integration
- **Styling** - Tailwind CSS with consistent component classes
- **Interactions** - Hotwire (Turbo + Stimulus) for dynamic behavior

## 🤝 Contributing

When adding new rules or updating existing ones:

1. Follow the established `.mdc` format with proper frontmatter
2. Include practical code examples
3. Document the reasoning behind patterns
4. Test rules with real-world scenarios

## 📝 License

These rules are part of the Pulse framework development guidelines.

---

*Built with ❤️ for consistent, maintainable Rails development*
