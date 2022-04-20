<template>
    <div class="Container">
        <div class="Container_image">
            <img class="Container_image_image" src="@/assets/Yaroslavle.jpg">
        </div>
        <div class="Container_Name">
            <p>Имя:<input type="text"></p>
        </div>
        <div class="Container_Comments">
            <input class="Container_Comments_Input" type="text" >
        </div>
            <form method="post" action="#" id ="input_capcha">
	        <div class="g-recaptcha" data-sitekey="6Ld5o4MfAAAAANNtby9nVSloxKd0R42rqg8JnnXY"></div>
	            <button type="submit">Отправить</button>
            </form>
        <div class="Buttons">
            <button class="Buttons_Add">Добавить</button>
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
.Container{
    display: grid;
    grid-auto-rows: 325px 50px 30px 1fr 1fr;
    width: 500px;
    height: 700px;
    border: 1px solid black;
}
.Container_image_image{
    max-width: 100%;
    padding: 0px;
    margin: 0px;
}
.Container_Name{
    display: grid;
    justify-content: center;
    align-content: center;
    padding-top: 15px;
    margin: 20px;

}
.Container_Comments_Input{
    width: 300px;
}
.Buttons{
    display: grid;
    padding-top: 15px;
}

#input_capcha{
    display: grid;
    justify-content: center;
    padding-top: 15px;
}
</style>