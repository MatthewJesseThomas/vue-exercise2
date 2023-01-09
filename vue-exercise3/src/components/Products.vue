<template>
    <div class="myCards">
        <div class="card" style="width: 18rem;">
            <img src="../assets/love-story-9781451687613_hr.jpg" class="card-img-top" id="image-size" alt="Love">
            <div class="card-body">
              <h5 class="card-title">Romance</h5>
              <p class="card-text">From #1 New York Times bestselling author Karen Kingsbury comes a new romantic story featuring everyone's favorite family--the Baxters--which tells the story of how John and Elizabeth first fell in love. From the day they met, John and Elizabeth were destined to fall in love.</p>
              <button v-on:click="purchaseAlert" class="btn btn-primary">Purchase Item</button>
              <!-- <a href="#" class="btn btn-primary">Purchase Item</a> -->
            </div>
          </div>
        <div class="card" style="width: 18rem;">
            <img src="../assets/Motivational-Book.gif" class="card-img-top" id="image-size" alt="Motivation">
            <div class="card-body">
              <h5 class="card-title">Motivational</h5>
              <p class="card-text">Powerful Lessons in Personal Change
                Stephen R. Covey's book, The 7 Habits of Highly Effective People, continues to be a bestseller for the simple reason that it ignores trends and pop psychology and focuses on timeless principles of fairness, integrity, honesty, and human dignity.</p>
              <button class="btn btn-primary" v-on:click="purchaseAlert">Purchase Item</button>
              <!-- <a href="#" class="btn btn-primary">Purchase Item</a> -->
            </div>
          </div>
        <div class="card" style="width: 18rem;">
            <img src="../assets/The-Nature-Of-Depression.jpg" class="card-img-top" id="image-size" alt="Depressed">
            <div class="card-body">
              <h5 class="card-title">Depression</h5>
              <p class="card-text">
              What is nature of depression?
              Depression is a common mental disorder. Globally, it is estimated that 5% of adults suffer from the disorder. It is characterized by persistent sadness and a lack of interest or pleasure in previously rewarding or enjoyable activities. It can also disturb sleep and appetite.First, Depression and anxiety, among other unpleasant experiences, are a normal part of the human condition.</p>
            <button class="btn btn-primary" v-on:click="purchaseAlert">Purchase Item</button>
              <!-- <a href="#" class="btn btn-primary">Purchase Item</a> -->
            </div>
          </div>
        <div class="card" style="width: 18rem;">
            <img src="../assets/Art-Of-Happiness.jpg" class="card-img-top" id="image-size" alt="Happy">
            <div class="card-body">
              <h5 class="card-title">Joyous</h5>
              <p class="card-text">The Art Of Happiness is the result of a psychiatrist interviewing the Dalai Lama on how he personally achieved inner peace, calmness, and happiness. This book covers all facets of the human experience, including how to solve everyday problems so that you can live a happy life. Plus, how you can remain peaceful during highly stressful and challenging times</p>
            <button class="btn btn-primary" v-on:click="purchaseAlert">Purchase Item</button>
              <!-- <a href="#" class="btn btn-primary">Purchase Item</a> -->
            </div>
          </div>
    </div>
</template>
<script>
export default {
    methods: {
      purchaseAlert(){
        alert('Purchase Successful')
      }
    },
};

</script>
<style>
    .myCards{
        display: flex;
        margin: auto;
        margin-top: 2rem;
        margin-bottom: 8rem;
        padding-left: 1rem;
        padding-right: 1rem;
        align-content: center;
        justify-content: space-between;
    }  
    #image-size{
        height: 20rem;
        width: 17.8rem;
    }  
</style>