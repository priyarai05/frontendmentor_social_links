# frontendmentor_social_links

## Favicon implementation
<link rel="icon" href="favicon-32x32.png">

## put container in the center of the page
.container {
    height: calc(100vh - 40px);
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

## Styling Link <a> elements within List <li> elements
a {
    display: block;
    text-decoration: none;
    color: hsl(0, 0%, 100%);
    font-size: 0.85rem;
    width: inherit;
    padding: 0.8rem;
    background-color: hsl(0, 0%, 20%);
    margin: 0.7rem 0;
    border-radius: 0.3rem;
}

a:hover {
    background: hsl(75, 94%, 57%);
    color: hsl(0, 0%, 8%);
}

## image styling
made image-avatar in circular shape
