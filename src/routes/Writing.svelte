<main data-animate style="--stagger: 5;">
    <h2>Select writing</h2>
    <a href="/writing/figma-inspired-viewport/" data-info="In this post, I build a viewport component inspired by Figma using the Javascript Canvas API.">
        <span>4/1/23</span>
        Figma/Framer inspired Viewport component
    </a>
</main>

<style>
    main {
        display: flex;
        flex-direction: column;
        gap: 4px;

        margin-top: 8px;
        width: 512px;
    }

    h2 {
        font-family: 'Fakt Pro';
        font-size: 14px;
        font-weight: normal;

        color: #666;
        user-select: none;
        margin-bottom: 2px;
    }

    a {
        width: fit-content;
        text-decoration: none;

        font-family: 'Fakt Pro';
        font-size: 14px;
        font-weight: normal;

        color: black;
        cursor: pointer;
        user-select: none;
    }

    span {
        font-family: 'IBM Plex Serif';
        font-size: 14px;
        font-weight: normal;
        
        color: #666;
        margin-right: 4px;
    }

    @media only screen and (max-width: 600px) {
        main {
            width: 100%;
        }
    }
</style>