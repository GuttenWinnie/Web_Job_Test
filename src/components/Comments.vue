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
        <div>
            <p id="Capcha"><input type="text"></p>
        </div>
        <div class="Buttons">
            <button id="input_capcha">Ввести</button>
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
    grid-auto-rows: 325px 50px 1fr 50px 1fr;
    width: 500px;
    height: 600px;
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
    padding: 10px;

}
#Input_Comments{
    padding: 10px;
    width: 400px;
    height: 100px;
}
.Buttons{
    display: grid;
    grid-template-areas: "input_capcha Add";
}
#input_capcha{
}
</style>