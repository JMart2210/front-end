# Front-end - Summary of projects in this repo

## Admin-dashboard

**Live version**: https://jmart2210.github.io/top-admin-dashboard/

Created an admin dashboard, using Grid to layout the site. To facilitate the expanding project cards, I used a grid-template-column property, utilizing repeat, auto-fit, and min-max with a defined size as well as fractional units. This maintained a consistent visual appearance while also letting the projects expand and contract with the screen width.

<img src="/img/grid_Dashboard.gif" alt="expanding grid layout"/>

## Sign-up Form
**Live version here**: https://jmart2210.github.io/sign-up-form/

**Tech used:** HTML, CSS, & JavaScript

This signup page is laid out using flexbox. The signup form utilizes HTML5 form validation attributes, as well as Javascript custom validation rules and error messages to provide robust client-side validation. 

The form utilizes CSS pseudo-classes to visually update the elements as the user fills out the form. This provides immediate visual feedback, highlighting the field in red if invalid, and a brand-matching green to indicate acceptance. 

Additionally, when the input is invalid, the user is presented with an error message positioned below the form field, making it clear to the user which field has an error and what the error is. This was accomplished with the 'data-help' attribute in combination with the :after pseudo-class. 

<img src="sign-up-form/img/formExample.gif">