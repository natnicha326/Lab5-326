<template>
  <div id="app">
    <h1>เกมเป่ายิ้งฉุบ</h1>
    <GameComponent />
  </div>
</template>

<script>
import GameComponent from './components/game.vue';

export default {
  components: {
    GameComponent,
  },
};
</script>

<style>
#app {
  background-image: url('./assets/3.jpg');
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center ;
  text-align: center;
  color: #000000;
  font-size: 30px;
  text-shadow: 5px 3px 5px rgb(255, 60, 177);
  margin-top: 0px;
  width: 70%; 
  height: 110vh; 
  display: flex;
  flex-direction: column;
}

h1 {
  font-size: 4em;
}
h3{
  margin:15px;
}
.player1-name {
  color: #0feae6; 
  text-shadow: 2px 2px 2px rgb(18, 80, 226);
  font-size: 40px;
}

.player2-name {
  color: #f4e13b; 
  text-shadow: 2px 2px 2px rgb(235, 130, 18);
  font-size: 40px;
}


.player-container {
  display: flex;
  justify-content: space-between;
  align-items: center;
  
}

.reset-button {
  margin-left: 70px; 
  background-color: #0dc66d; 
  color: #ffffff; 
  font-size: 25px;
  border-radius: 30px;
  border: 5px solid #ffffff;  
}

.reset-button:hover {
  background-color: #00793c; 
}
.round-button:hover {
  background-color: #9a0000ee; 
}

.round-button {
  
  background-color: #fb0101; 
  color: #fff;
  font-size: 25px;
  border-radius: 30px;
  border: 5px solid #ffffff;  
}

.score-container {
  background-color: #f7f6f6; 
  color: #a300a3; 
  font-size: 30px;
  padding: 3px; 
  margin-top: 15px; 
  text-align: center; 
  border-radius: 30px; 
  border: 2px solid #efe52c; 
  border-width: 10px;
  max-width: 400px; 
  margin: 20px auto;
}
.score-text {
  margin: 0; 
}
</style>


