#### linaresl1836.github.io
GitHub Pages site


Here are a list of projects I'm working on:
<ul>
  
  <li><strong><a href="https://github.com/GothicLolita229/Story-Co-Writing">Website Project</a> - a website where you can co-write stories with amateur authors</strong></li>

  <li><a href="https://github.com/GothicLolita229/CTS285-Dataman">Dataman Project</a>- a remake of the 80s math game</li>
  
  <li><a href="https://github.com/GothicLolita229/CSC-253-Mortuus" target="_blank">Mortuus project</a> - a simple text adventure game</li>

</ul>

## Useful Links

- A list of [Jekyll themes](https://pages.github.com/themes/)
- [GitHub Pages Quickstart](https://pages.github.com)
- [Dev Blog](https://linaresl1836.github.io/dev-blog)
- This Website's URL: https://gothiclolita229.github.io/linaresl1836.github.io/

## Description
My Main project is the Co-Writers Website and it's a website that showcases young amateur author's work. This site gives users the opportunity to create stories even if they lack the skills to write great detail and have their words flow eloquently.
Amamteur authors will take the user input and create a story with the guidelines from the form's input.

## User Stories
[Co-Writers Website Kanban Board](https://github.com/users/GothicLolita229/projects/5)

## Code Snippets

Here my open Preview button JavaScript Code Snippet
```
openPreviewButtons.forEach(button => {
    button.addEventListener("click", () => {
        formSubmit();
        const preview = document.querySelector(button.dataset.previewTarget);
        openPreview(preview);
    });
});
overlay.addEventListener("click", () => {
    const previews = document.querySelectorAll(".preview.active")
    previews.forEach(preview => 
        {
            closePreview(preview)
    });
});
```

## Diagrams

![M5T1-ContextDiagram_Linaresl1836](https://user-images.githubusercontent.com/90853197/205704427-895e08f7-0159-4684-8da7-d9aef27b8dec.png)
