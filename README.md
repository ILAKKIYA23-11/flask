@import url('https://fonts.googleapis.com/css2?family=Lato&display=swap');
body {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    background-color:#f5f6e2;
    font-family: "lato", sans-serif;
  }
  .signupForm {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
  }
  .signinForm {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
  }
  .form {
    background-color: white;
    width: 400px;
    border-radius: 8px;
    padding: 70px 150px;
    box-shadow: 0 10px 25px rgba(188, 193, 198, 0.2);
  }

  .title {
    font-size: 50px;
    margin-bottom: 50px;
  }
  .inputContainer {
    position: relative;
    height: 45px;
    width: 90%;
    margin-bottom: 17px;
  }
  .Container {
    position: relative;
    height: 45px;
    width: 90%;
    margin-bottom: 17px;
  }
  .input {
    position: absolute;
    top: 0px;
    left: 0px;
    height: 100%;
    width: 100%;
    border: 1px solid #DADCE0;
    border-radius: 7px;
    font-size: 16px;
    padding: 0 20px;
    outline: none;
    background: none;
    z-index: 1;
  }
  ::placeholder {
    color: transparent;
  }
  .label {
    position: absolute;
    top: 15px;
    left: 15px;
    padding: 0 4px;
    background-color: white;
    color: #DADCE0;
    font-size: 16px;
    transition: 0.5s;
    z-index: 0;
  }
  .submitBtn {
    display: block;
    margin-left: auto;
    padding: 15px 30px;
    border: none;
    background-color: green;
    color: white;
    border-radius: 6px;
    cursor: pointer;
    font-size: 16px;
    margin-top: 30px;
  }
  .pl{
    display: flex;
    justify-content: center;
    align-items: center;
    font-family:sans-seriff;
    font-size: 25px;
  }
  .img{
    display: flex;
    justify-content: center;
    align-items: center;

  }
