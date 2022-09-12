* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: "Poppins", sans-serif;
}

body {
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: #4e4cff;
}

.calculator {
    margin-top: 7rem;
    display: flex;
    flex-direction: column;
    background-color: white;
    border-radius: 15px;
    height: 30rem;
    width: 20rem;
    padding: 20px 30px;
}

#totalBill {
    margin: 10px 0;
    height: 38px;
    border: none;
    background: #f1f1f1;
    padding: 0 10px;
    border-radius: 5px;
}

#totalBill:focus {
    outline: 2px solid #4b49f1;
}

input[type='range'] {
    accent-color: #4b49f1;
    margin: 10px 0;
}

.result {
    width: 100%;
    min-height: 100px;
    margin-top: 20px;
    padding: 20px;
    background-color: #4b49f1;
    border-radius: 15px;
    font-size: 1.2rem;
    color: white;
}
