# Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

> 💡 These are just the design sizes. Ensure content is responsive and meets WCAG requirements by testing the full range of screen sizes from 320px to large screens.

## Colors

### Primary

- Navy 950 (main background): hsl(233, 47%, 7%)
- Blue 950 (card background): hsl(244, 37%, 16%)
- Purple 500 (accent): hsl(277, 64%, 61%)

### Neutral

- White (main heading, stats): hsl(0, 0%, 100%)             main-heading-stats
- White (main paragraph): hsla(0, 0%, 100%, 0.75)
- White (stat headings): hsla(0, 0%, 100%, 0.6)

## Typography

### Body Copy

- Font size: 15px

### Font

- Family: [Inter](https://fonts.google.com/specimen/Inter)
- Weights: 400, 700

- Family: [Lexend Deca](https://fonts.google.com/specimen/Lexend+Deca)
- Weights: 400

> 💎 [Upgrade to Pro](https://www.frontendmentor.io/pro?ref=style-guide) for design file access to see all design details and get hands-on experience using a professional workflow with tools like Figma.



.text-section {
    display: grid;

    grid-template-columns: repeat(auto-fit, minmax(375px, 1fr));

    background-color: var(--clr-primary-teal-500);

    flex-wrap: wrap;
    color: var(--clr-neutral-white-900);

    width: 100%;
}

<div class="text-section">
        <h1> Get insights that help your business grow.</h1>

        <p> Discover the benefits of date analytics and make better decisions regarding revenue, customer experience,
          and
          overall efficiency</p>

        <div class="stats">
          <div class="stats-content">
            <h2>10k+</h2>
            <p>COMPANIES</p>
          </div>

          <div class="stats-content">
            <h2>314</h2>
            <p>TEMPLATES</p>
          </div>

          <div class="stats-content">
            <h2>12M+</h2>
            <p>QUERIES</p>
          </div>

        </div>

      </div>

      <div class="image-section">

      </div>


.text-section {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: flex-start;
    background-color: var(--clr-neutral-teal-200);

    height: 100%;
    width: 50%;
    max-width: 375px;
    min-width: 100%;

    padding: var(--spacing-md);
    gap: var(--spacing-md);


    h1 {
        font-weight: 900;
    }

    p {
        font-weight: 700;
    }
}


.image-section {
    background-image: url("/images/image-header-desktop.jpg");
}


.attribution {
    font-family: inherit;
    font-size: inherit;

    a {
        display: inline;
        padding: 0;
    }

    padding: var(--spacing-lg);
}



.btn-CTA{
  display:inline-block;
  padding:1rem 2.5rem;
  text-decoration:none;
}

.btn-capsule{
  border-radius:3rem;
}

.btn-round-edge{
  border-radius:0.5rem;
}

.btn-square-edge{
  border-radius:0;
}

.btn-CTA{
  background-color:orangered;
  color: white;
}


.card{
  display:flex;
  flex-direction:column;
  justify-content:center;
  align-items:center;
  
  width:400px;
  height:300px;
  
  padding:2rem;
  
  box-sizing:border-box;
}

.card-round-edge{
    border-radius:1rem;
}

.card-left{
  display:flex;
  flex-direction:column;
  justify-content:center;
  align-items:flex-start;
  text-align:left;
}

.card-right{
  display:flex;
  flex-direction:column;
  justify-content:center;
  align-items:flex-end;
  text-align:right;
}

.card-center{
  display:flex;
  flex-direction:column;
  justify-content:center;
  align-items:center;
  text-align:center;
}

.card{
  background-color:#cccccc;
  border:2px solid #aaaaaa;
}

.btn-sect{
  display:flex;
  flex-direction:row;
  justify-content:flex-start;
  align-items:center;
  
  width:100%;
  height:auto;
}

.btn-sect-center{
  display:flex;
  flex-direction:row;
  justify-content:center;
  align-items:center;
  
  width:100%;
  height:auto;
}

.btn-sect-right{
  display:flex;
  flex-direction:row;
  justify-content:flex-end;
  align-items:center;
  
  width:100%;
  height:auto;
}
