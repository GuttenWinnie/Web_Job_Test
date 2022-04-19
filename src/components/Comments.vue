<template>
    <div class="Conteiner">
        <div>
            <img class="image" src="@/assets/Yaroslavle.jpg">
        </div>
        <div class="Name">
            <p>Имя:<input type="text"></p>
        </div>
        <div class="Comments">
            <input id="Input_Comments" type="text" >
        </div>
            <form method="post" action="#" id ="input_capcha">
	        <div class="g-recaptcha" data-sitekey="6Ld5o4MfAAAAANNtby9nVSloxKd0R42rqg8JnnXY"></div>
	            <button type="submit">Отправить</button>
            </form>
        <div class="Buttons">
            <button id="add">Добавить</button>
        </div>
    </div>
</template>

<style>
body{
    display: grid;
    justify-content: center;
    padding: 0px;
    margin: 0px;
}
.Conteiner{
    display: grid;
    grid-auto-rows: 325px 50px 30px 1fr 1fr;
    width: 500px;
    height: 700px;
    border: 1px solid black;
}
.image{
    max-width: 100%;
    padding: 0px;
    margin: 0px;
}
.Name{
    display: grid;
    justify-content: left;
    align-content: center;
    padding: 15px;
    margin: 20px;

}
#Input_Comments{
    width: 300px;
}
.Buttons{
    display: grid;
    grid-template-areas: "AddComments";
}
#input_capcha{
    display: grid;
    justify-content: center;
}
</style>