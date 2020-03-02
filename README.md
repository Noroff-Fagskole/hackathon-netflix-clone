# Hackathon - Netflix Clone

> Lets Build a netflix clone 🚀 using the [TVMAZE API](http://www.tvmaze.com/api).

## API

[TVMAZE Docs](http://www.tvmaze.com/api)

## Rules of the hackathon

1. Work in pairs
2. minimal assistance will be provided from tutors as it's a hackathon
3. be creative
4. have fun

# episode 1

### :TODO

Fork Repo first, then clone it and get going !

1. create a mockups first (20min) 
2. Homepage:
    - Header, content container and footer.
    - Layout should have cards on the homepage in a grid format.
    - each card should have a picture, title, clickable button taking the user to a character detail page.
    - create search input, this input should filter the character cards, this should only be triggerd on a click pf a button.
3. Tv Show Detail Page:
    - The page should have a Title, Picture, Summary, Language, Genres, schedule.
    - The schedule must be in an accordion menu, when the user clicks an arrow it should show more info, when user clicks the arrow again it should close. 
4. Contact Page:
    - Name, Email, Telephone number
    - Validate the form, show the user error messages.
    - use regex.
    
### Endpoints

You will make use of these endpoints.

Request | End point | 
---------|----------|
 Schedule | [SCHEDULE](http://api.tvmaze.com/schedule) |
 One tv show | [One show](http://api.tvmaze.com/shows/1) |

# episode 2

### :TODO

1. Build/Update the interactive TV Show details page. It must follow this wireframe `Netflix-clone-tv-show-page-wireframes.xd` available in repository.
2. Update homepage styles to look more polished than it was when you finished episode 1.
3. deploy your site using github pages: [https://pages.github.com/](https://pages.github.com/)

### Endpoints

You will make use of these endpoints.

Request | End point | 
---------|----------|
 Episodes | [api.tvmaze.com/shows/1/episodes](http://api.tvmaze.com/shows/1/episodes) |
Seasons | [api.tvmaze.com/shows/1/seasons](http://api.tvmaze.com/shows/1/seasons) |
 Cast | [api.tvmaze.com/shows/1/cast](http://api.tvmaze.com/shows/1/cast) |

You may use vanilla CSS or CSS Framework of your choosing. You are not allowed to use any JavaScript from these frameworks.

1. [Vanilla CSS](https://www.w3.org/Style/CSS/specs.en.html)
2. [Bulma](https://bulma.io/)
3. [Tailwind](https://tailwindcss.com/)
4. [Bootstrap](https://getbootstrap.com/)
5. [Zurb Foundation](https://get.foundation/)
6. [Semantic UI](https://semantic-ui.com/)

You decide.
