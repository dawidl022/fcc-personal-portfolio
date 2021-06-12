# FCC: Personal Portfolio Webpage

Fifth and final project in FreeCodeCamp Responsive Web Design course.

What I learnt:
- How to add a simple animation using @keyframes
- Where utilising CSS grid is useful
- Flexbox does some magic when it contains images, whilst being a grid-item:
    ```css
    .outer-div {
      display: grid;
      grid-auto-rows: 1fr;
    }

    .inner-div {
      display: flex;
    }

    .inner-dix > img {
      width: 100%;
      height: 100%;
      object-fit: cover;
    }
    ```
    This makes the height of all images in the grid the same, where an
    additional element (i.e some text) can also be present


What I had difficulties with:
- Understanding how the code in the snipped above works. Figuring a universal
way to make photos of a certain container the same size (without specifying
the explicit height and width in px) and have the same aspect ratio (i.e. 1:1).
- Getting the translation animations to work, flex `baseline` brakes when using translate functions.
