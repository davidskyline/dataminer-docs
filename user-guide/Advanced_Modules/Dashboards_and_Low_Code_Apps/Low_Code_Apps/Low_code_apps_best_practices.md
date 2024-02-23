---
uid: Low_code_apps_best_practices
---

# Best practices for creating a visually appealing and user-friendly low-code app

- [Best practices for creating a visually appealing and user-friendly low-code app](#best-practices-for-creating-a-visually-appealing-and-user-friendly-low-code-app)
  - [Styling Guidelines](#styling-guidelines)
    - [Colors and Themes](#colors-and-themes)
    - [Layouting](#layouting)
  - [Usability Guidelines](#usability-guidelines)
    - [Navigation](#navigation)
    - [Forms](#forms)
    - [Messaging](#messaging)

> [!TIP]
> See also: [Kata #19: Transform Low-Code Apps into visual delights](https://community.dataminer.services/courses/kata-19/) on DataMiner Dojo ![Video](~/user-guide/images/video_Duo.png)

## Styling Guidelines

### Colors and Themes

- For interface colors in light mode, the darker you make elements, the more important they are. For dark mode, it is the opposite
- Use background colors (and borders) on components with data. But don’t make the contrast between your app’s background color and component background color too big. It helps your user divide your interface into pieces, but keep it subtle.
- Use the same colors for the same states throughout your app (e.g. colors for states in table and in charts).

### Layouting

- Space for navigation, actions and titles should take up as little space as possible in terms of height. This way you will have more space left for the essence of your page.
- Be consistent in width of pop-ups and panels.
- Be consistent in the lay-out of components on pages or panels.
- Try out your app on different desktop sizes and make sure your templates are responsive.

## Usability Guidelines

### Navigation

- Avoid using buttons for navigation.
- Try to avoid nesting pages (Pages in sidebar > Panels on page > Nested pages > Panels on nested pages).

### Forms

- Use pop-ups when there is user input and panels for additional information.
- Make sure labels are above inputs in forms, this ensures better readability. This can be done by limiting the width of the form.

### Messaging

- Personalize the informative empty result message for components and template information.
- If the content of your component is based on a selection in another component you should make this clear in the title.