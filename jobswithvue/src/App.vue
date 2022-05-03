<template>
    <div>
      <div class="container-fluid p-5 bg-primary text-white text-center">
        <h1>Lista zadań</h1>
        <p>Niech Twój dzień będzie lepszy</p> 
      </div>

      <div class="container">
        <div class="col-sm-5">
          <form>
          <div class="mb-3 mt-3">
            <label for="title" class="form-label">Tytuł</label>
            <input type="text" class="form-control" id="title" placeholder="Wpisz tytuł" name="title">
          </div>
          <div class="mb-3">
            <label for="city" class="form-label">Miasto</label>
            <input type="text" class="form-control" id="city" placeholder="Wpisz miasto" name="city">
          </div>
          <div class="mb-3">
            <label for="salary" class="form-label">Zarobki</label>
            <input type="text" class="form-control" id="salary" placeholder="Wpisz zarobki" name="salary">
          </div>
          <div class="mb-3">
            <label for="description">Opis</label>
            <textarea class="form-control" rows="3" id="description" name="text"></textarea>
          </div>
          <button type="submit" class="btn btn-primary">Dodaj</button>
        </form>
        </div>
        <div class="col-sm-7">

        </div>
        
      </div>

    </div>
      
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import HelloWorld from './components/HelloWorld.vue';

export default defineComponent({
  name: 'App',
  components: {}
});
</script>

<style>
</style>
