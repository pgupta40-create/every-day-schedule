# Copilot Instructions for Every Day Schedule

## Project Overview
Every Day Schedule is a web-based personal scheduling and time management application. The project aims to provide users with a simple yet effective tool for organizing daily tasks and maintaining work-life balance.

## Project Structure
- `index.html`: Main entry point containing both the UI structure and embedded styles
- Core styling approach uses embedded CSS with a focus on:
  - Clean, minimalist design
  - Mobile-responsive layout
  - Consistent color palette (purples, grays, white backgrounds)

## Design Patterns & Conventions
### CSS Conventions
- Base colors:
  - Primary text: `#4a5568` (dark gray)
  - Headings: `#718096` (medium gray)
  - Highlights: `#805ad5` (purple)
  - Background: `#f0f4f8` (light blue-gray)
  - Container: `#fff5f5` (light pink)
- Container styling uses:
  - Rounded corners (`border-radius: 15px`)
  - Subtle shadows (`box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1)`)
  - Centered content layout
  - Responsive padding and margins

### HTML Structure
- Semantic HTML5 structure
- Mobile-first viewport configuration
- UTF-8 character encoding
- Content uses container-based layout for centered positioning

## Development Workflow
1. Make changes to `index.html` to update both structure and styles
2. Test changes across different viewport sizes (mobile, tablet, desktop)
3. Ensure accessibility standards are maintained

## Best Practices
- Keep styles embedded in `index.html` until complexity requires separation
- Maintain the established color scheme for consistency
- Follow mobile-first responsive design principles
- Use semantic HTML elements for better accessibility

## Future Considerations
As the project grows, consider:
- Separating CSS into external stylesheet
- Adding JavaScript for interactive features
- Implementing a task management system
- Adding persistent storage for user data