<template>
  <div id="nav">
    <router-link to="/">PersonalInfo</router-link> |
    <router-link to="/formation">Formations</router-link> |
    <router-link to="/experience">Experiences</router-link>|
    <router-link to="/langues">Langues</router-link> |
    <router-link to="/loisers">Loisers</router-link> |
    <router-link to="/curriculum_Vitae">CV</router-link> 
  </div>
  <router-view/>
</template>

<style>
body{
  background-color: #859aff;
}
div{
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
form{
  
  width: 80%;
 

}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
  text-decoration: none;
}

#nav a.router-link-exact-active {
  color: #42b983;
}

#CV{
    width: 80%;
    height: auto;
    margin-bottom: 20px;
    /* margin-left: 25%; */
  border: 1px solid white;
}

#infoPersonnel{
    float: left;
    text-align: left;
    /* padding-left: 3%; */
    padding-top: 3%;
        line-height: 0.7;
}
#title{
    float: left;
    /* padding-left: 25%; */
    width: 72%; 
}
#pics{

    /* padding-left: 77%; */
}
img{
      width: 10%;
}
.formation{
    width: 71%;
    margin-top: 1%;
    color: blue;
    float: left;
    /* margin-left: 14%; */
    border: 1px solid;
}
table{
  float: left;
    /* margin-left: 4%; */
    margin-top: 3%;
}
td{
  width: 20%;
  color: blue;
}
th{
  width: 80%;

}
</style>
