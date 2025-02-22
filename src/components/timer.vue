<script setup>

</script>

<template>
    
    <main class="timer_card">
        <div class="div_buttons">
            <button class="buttons_pressed"> Pomodoro </button>
            <button class="buttons"> Short Break </button>
            <button class="buttons"> Long Break </button>
        </div>
        <div class="timer">
            <p>
                25:00
            </p>
        </div>
        <div class="button_start_position">
            <button class="button_start"> START </button>
        </div>
    </main>    

</template>

<style scoped>
    .timer_card{
        background-color: #FFFFFF1A;
        padding-top: 15px;
        border-radius: 5px;
    }

    .div_buttons{
        display: flex;
        justify-content: center;
        padding-bottom: 20px;
    }

    .buttons{
        background-color: transparent;
        border: none; 
        color: #FFF;
        padding: 9px;
        font-size: 18px;
    }

    .buttons_pressed{
        background-color: #00000026;
        border: none; 
        color: #FFF;
        padding: 9px;
        border-radius: 6px;
        font-weight: bold;
        font-size: 18px;
    }


    .timer{
        display: flex;
        justify-content: center;
        color: #FFF;
        font-size: 100px;
        font-weight: bold;
    }

    .button_start_position{
        display: flex;
        justify-content: center;
        padding: 18px 20px 30px;
    }

    .button_start{
        font-size: 25px;
        background-color: #FFF;
        border: none;
        padding: 7px 40px;
        box-shadow: rgb(235, 235, 235) 0px 6px 0px;
        color: #BA4949;
        font-weight: bold;
        border-radius: 6px;
        width: 48vw;
        height: 8vh;
    }


    main{
        margin: 10% 5% 5% 5%;
    }

=======
    </main>
    

</template>

<style scoped>
    .timer_card{
        background-color: #FFFFFF1A;
        padding-top: 15px;
        border-radius: 5px;
    }

    .div_buttons{
        display: flex;
        justify-content: center;
        padding-bottom: 20px;
    }

    .buttons{
        background-color: transparent;
        border: none; 
        color: #FFF;
        padding: 9px;
        font-size: 18px;
    }

    .buttons_pressed{
        background-color: #00000026;
        border: none; 
        color: #FFF;
        padding: 9px;
        border-radius: 6px;
        font-weight: bold;
        font-size: 18px;
    }


    .timer{
        display: flex;
        justify-content: center;
        color: #FFF;
        font-size: 100px;
        font-weight: bold;
    }

    .button_start_position{
        display: flex;
        justify-content: center;
        padding: 18px 20px 30px;
    }

    .button_start{
        font-size: 25px;
        background-color: #FFF;
        border: none;
        padding: 7px 40px;
        box-shadow: rgb(235, 235, 235) 0px 6px 0px;
        color: #BA4949;
        font-weight: bold;
        border-radius: 6px;
        width: 48vw;
        height: 8vh;
    }


  

    main{
        margin: 10% 5% 5% 5%;
    }

</style>