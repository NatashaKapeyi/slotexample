<template>
  <div class="container-fluid">
    <div class="row">
      <Card>
        <template #cardHeader>
          <p class="lead">Title 1</p>
        </template>
        <template #cardBody>
          <div class="d-flex justify-content-between">
            <img class="img-fluid w-50" src="https://picsum.photos/id/7/4728/3168.jpg" alt="image 1" loading="lazy" />
            <p class="lead">Image description 1</p>
          </div>
        </template>
        <template #default>
          <div class="d-flex justify-content-between">
            <button class="btn btn-primary">View Detail</button>
            <button class="btn btn-primary">Cart</button>
          </div>
        </template>
      </Card>
      <Card>
        <template>
          <p class="lead">Title 1</p>
        </template>
        <template> 
          <div class="d-flex justify-content-between">
            <img class="img-fluid w-50" src="https://picsum.photos/id/7/4728/3168.jpg" alt="image 1" loading="lazy" />
            <p class="lead">Image description 1</p>
          </div>
        </template>
        <template>
          <div class="d-flex justify-content-between">
            <button class="btn btn-primary">View Detail</button>
            <button class="btn btn-primary">Cart</button>
          </div>
        </template>
      </Card>
      <Button>
        <template #Btn>
           Hello
        </template>
        <template #Click>
          click <img class="img-fluid" src="https://picsum.photos/id/7/4728/3168.jpg" alt="image 1" loading="lazy" />
        </template>
      </Button>
    </div>
  </div>
</template>

<script>
import Button from "./components/Button.vue";
import Card from "./components/Card.vue";


export default {
  name: "App",
  components: {
    Card, 
    Button,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
img{
  width: 30px;
}
</style>
