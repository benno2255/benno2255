/* Basic reset */
body, html {
    margin: 0;
    padding: 0;
    height: 100%;
    width: 100%;
    box-sizing: border-box;
}

body {
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: #f0f0f0;
    font-family: Arial, sans-serif;
}

.ludo-board {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-template-rows: repeat(3, 1fr);
    gap: 10px;
    width: 500px;
    height: 500px;
    position: relative;
}

.home {
    width: 100%;
    height: 100%;
    position: absolute;
    border: 2px solid #000;
    box-sizing: border-box;
}

.red-home {
    background-color: red;
    grid-column: 1 / 2;
    grid-row: 1 / 2;
}

.green-home {
    background-color: green;
    grid-column: 3 / 4;
    grid-row: 1 / 2;
}

.yellow-home {
    background-color: yellow;
    grid-column: 1 / 2;
    grid-row: 3 / 4;
}

.blue-home {
    background-color: blue;
    grid-column: 3 / 4;
    grid-row: 3 / 4;
}

.board {
    display: grid;
    grid-template-columns: repeat(8, 1fr);
    grid-template-rows: repeat(8, 1fr);
    gap: 1px;
    width: 100%;
    height: 100%;
    position: relative;
}

.center {
    grid-column: 4 / 5;
    grid-row: 4 / 5;
    background-color: #fff;
    border: 2px solid #000;
    position: relative;
    width: 100%;
    height: 100%;
}

.row {
    display: flex;
    width: 100%;
}

.square {
    width: 100%;
    height: 100%;
}

.blue {
    background-color: blue;
}

.green {
    background-color: green;
}

.yellow {
    background-color: yellow;
}

.red {
    background-color: red;
}
