
<template>
  <main>

    <div class="container">
      <header>
        <h1>Notes</h1>
        <button>+</button>
      </header>
        <div class="card-continer">
          <div class="card">
            <p>text</p>
            <p class="date">date</p>
          </div>
        </div>
      
    </div>
  </main>
</template>
<style scoped>
main {

  width: 100vw;
  height: 100vh;
}

.container {
  padding: 10px;
  max-width: 1000px;
  margin: 0 auto;

}
.date{
  font-size: 12.5px;
  font-weight: bold;
}

header {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.card-continer{
  margin:25px;
display: flex;
flex-wrap: wrap;
}

.card{
  height: 26vh;
  width: 10vw;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  margin-left: 25px;
  margin-bottom: 25px;
  padding: 10px;
  border-radius:10px;
  background-color: aqua;
}
header button {
  /* margin-left:45vw; */
    border: none;
    padding: 10px;
    width: 50px;
    height: 50px;
    cursor: pointer;
    background-color: rgb(21,20,20);
    border-radius: 100%;
    color: white;
    font-size: 20px;
  }
</style>