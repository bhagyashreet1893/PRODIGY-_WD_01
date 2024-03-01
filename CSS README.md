    margin-bottom: 30px;

    margin-left: 80px;
}
 
.contactMenu {

    display: flex;

    justify-content: space-evenly;
}
 

.input2 {

    margin-top: 10;
}
 

.label1 {

    font-size: 18px;

    margin-top: 8px;

    margin-bottom: 8px;

    font-weight: bolder;
}
 

.contactMenu .input1 input {

    border-radius: 13px;

    padding: 6px;
}
 

.input2 input {

    border-color: rgb(252, 244, 244);

    width: 400px;
}
 
.button {

    margin-top: 12px;

    margin-left: 5px;
}
 
.button button {

    width: 162px;

    height: 35px;

    border-radius: 12px;

    border-color: transparent;
}
 
.button button:hover {

    background-color: #8cc099;
}
 
button {

    width: 162px;

    height: 35px;

    border-radius: 12px;

    border-color: transparent;
}
 
button:hover {

    background-color: #8cc099;
}
 

.rightside1 {

    display: flex;

    flex-direction: column;

    margin-left: 300px;
}
 

.title1 {

    font-size: 18px;

    margin-top: 8px;

    margin-bottom: 5px;

    font-weight: bolder;
}
 

.content1 {

    width: 450px;

    margin-top: 2px;

    color: grey;
}
 
/* Footer */
footer {

    background: var(--primary-color);

    padding: 15px 0;

    text-align: center;

    font-family: "Poppins", sans-serif;
}
 
footer .footer span {

    font-size: 17px;

    font-weight: 400;

    color: var(--white-color);
}
 
footer .footer span a {

    font-weight: 500;

    color: var(--white-color);
}
 
footer .footer span a:hover {

    text-decoration: underline;
}
 

@media screen and (max-width: 1060px) {

    .contactMenu {

        flex-direction: column;

        align-items: center;

    }
 

    .rightside1 {

        display: flex;

        flex-direction: column;

        margin-left: 0px;

    }
 

    .content1 {

        width: 100%;

        margin-top: 2px;

        color: grey;

    }
 

    .side2 img {

        width: 95%;

        height: 90%;

    }
}
 

@media screen and (max-width: 600px) {

    .side2 img {

        width: 100%;

    }
 

    section .topic a {

        font-size: 20px;

    }
 

    section .topic p {

        font-size: 5px;

    }
 

    .about .boxes {

        display: flex;

        flex-direction: column;

        align-items: center;

    }
 

    .about .boxes .box {

        max-width: 70%;

    }
}







