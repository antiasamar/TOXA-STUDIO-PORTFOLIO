header {
    display: flex;
    padding: 80px 0;
    row-gap: 80px;
    column-gap: 200px;
    flex-wrap: wrap;
    justify-content: center;
    align-items: center;
}

header > div:first-child {
    display: flex;
    flex-direction: column;
    gap: 28px;
}

header > div:last-child {
    min-width: 380px;
    max-width: 624px;
    border: 1px #6e06f2 solid;
    padding: 40px;
    height: fit-content;
    border-radius: 50%;
    /* overflow: hidden; (mascara de recorte) */
}
}