<script setup></script>

<template>
  <div
    class="bg-white sm:rounded-none rounded-t-3xl rounded-b-3xl sm:mx-0 md:mx-40"
  >
    <div class="container">
      <div class="recipe-img sm:p-0 md:p-10">
        <img
          src="../assets/images/image-omelette.jpeg"
          alt="omelette"
          class="sm:w-full h-auto object-cover sm:rounded-none md:rounded-xl"
        />
      </div>

      <div class="recipe-info sm:px-5 md:px-10">
        <h1 class="text-3xl sm:pt-4 font-bold font-Outfit text-[#302d2c]">
          Simple Omelette Recipe
        </h1>
        <p class="pt-3 pb-3 text-[#5f574e]">
          An easy and quick dish, perfect for any meal. This classic omelette
          combines beaten eggs <br />
          cooked to perfection, optionally filled with your choice of cheese,
          vegetables, or meats.
        </p>
        <div class="bg-[#fff5fa] rounded-lg my-5">
          <div class="p-5">
            <p class="text-xl font-bold text-[#7b284f]">Preparation time</p>
            <ul class="p-2 pl-7 list-disc text-[#7b284f]">
              <li>
                <span class="font-bold sm:pl-1 lg:pl-6 text-[#5f574e]"
                  >Total</span
                ><span class="text-[#5f574e]">: Approximately 10 minutes</span>
              </li>
              <li>
                <span class="font-bold sm:pl-1 lg:pl-6 text-[#5f574e]"
                  >Preparation</span
                ><span class="text-[#5f574e]">: 5 minutes</span>
              </li>
              <li>
                <span class="font-bold lg:pl-6 sm:pl-1 text-[#5f574e]"
                  >Cooking</span
                ><span class="text-[#5f574e]">: 5 minutes</span>
              </li>
            </ul>
          </div>
        </div>
        <h2 class="text-3xl pt-3 text-[#854632]">Ingredients</h2>
        <ul class="list-disc py-5 pl-5 text-[#854632]">
          <li class="pl-4">
            <span class="text-[#5f574e]">2-3 large eggs</span>
          </li>
          <li class="pl-4">
            <span class="text-[#5f574e]">Salt, to taste</span>
          </li>
          <li class="pl-4">
            <span class="text-[#5f574e]">Pepper, to taste</span>
          </li>
          <li class="pl-4">
            <span class="text-[#5f574e]">1 tablespoon of butter or oil</span>
          </li>
          <li class="pl-4">
            <span class="text-[#5f574e]">
              Optional fillings: cheese, diced vegetables, cooked meats, herbs
            </span>
          </li>
        </ul>

        <hr />
        <h2 class="my-8 text-3xl text-[#854632]">Instructions</h2>
        <ol class="list-decimal text-[#854632] font-bold pl-6 pb-5">
          <li class="pl-4 lg:pb-4 sm:py-4">
            <span class="text-[#5f574e]">Beat the eggs</span
            ><span class="font-normal text-[#5f574e]"
              >: In a bowl, beat the eggs with a pinch of salt and pepper until
              they are well mixed. You can add a tablespoon of water or milk for
              a fluffier texture.</span
            >
          </li>
          <li class="pl-4 lg:pb-4 sm:py-4">
            <span class="text-[#5f574e]">Heat the pan</span
            ><span class="font-normal text-[#5f574e]"
              >: Place a non-stick frying pan over medium heat and add butter or
              oil.</span
            >
          </li>
          <li class="pl-4 lg:pb-4 sm:py-4">
            <span class="text-[#5f574e]">Cook the omelette</span
            ><span class="font-normal text-[#5f574e]"
              >: Once the butter is melted and bubbling, pour in the eggs. Tilt
              the pan to ensure the eggs evenly coat the surface.</span
            >
          </li>
          <li class="pl-4 lg:pb-4 sm:py-4">
            <span class="text-[#5f574e]">Add fillings (optional)</span
            ><span class="font-normal text-[#5f574e]"
              >: When the eggs begin to set at the edges but are still slightly
              runny in the middle, sprinkle your chosen fillings over one half
              of the omelette.</span
            >
          </li>
          <li class="pl-4 lg:pb-4 sm:py-4">
            <span class="text-[#5f574e]">Fold and serve</span
            ><span class="font-normal text-[#5f574e]"
              >: As the omelette continues to cook, carefully lift one edge and
              fold it over the fillings. Let it cook for another minute, then
              slide it onto a plate.</span
            >
          </li>
          <li class="pl-4 lg:pb-4 sm:py-4">
            <span class="text-[#5f574e]">Enjoy</span
            ><span class="font-normal text-[#5f574e]"
              >: Serve hot, with additional salt and pepper if needed. Nutrition
              The table below shows nutritional values per serving without the
              additional fillings.</span
            >
          </li>
        </ol>
        <hr />
        <h2 class="my-5 text-3xl text-[#854632]">Nutrition</h2>
        <p class="text-[#5f574e] pb-5">
          The table below shows nutritional values per serving without the
          additional fillings.
        </p>
        <div class="grid grid-cols-2 gap-4 pt-5 pb-5 pl-8">
          <div class="text-[#5f574e]">Calories</div>
          <div class="font-semibold text-[#854632]">277kcal</div>
        </div>
        <hr />
        <div class="grid grid-cols-2 gap-4 py-5 pl-8">
          <div class="text-[#5f574e]">Carb</div>
          <div class="font-semibold text-[#854632]">0g</div>
        </div>
        <hr />
        <div class="grid grid-cols-2 gap-4 py-5 pl-8">
          <div class="text-[#5f574e]">Protein</div>
          <div class="font-semibold text-[#854632]">20g</div>
        </div>
        <hr />
        <div class="grid grid-cols-2 gap-4 py-5 pl-8">
          <div class="text-[#5f574e]">Fat</div>
          <div class="font-semibold text-[#854632]">22g</div>
        </div>
        <hr class="pb-10" />
      </div>
    </div>
  </div>
  <div class="flex justify-center sm:text-xs sm:py-5 md:py-10">
    Challenge by &nbsp;
    <NuxtLink to="https://www.frontendmentor.io/"
      ><span class="text-[#854632] underline"> Frontend Mentor.</span>
      &nbsp;</NuxtLink
    >
    Coded by &nbsp;
    <NuxtLink to="https://github.com/Preeyapornn"
      ><span class="text-[#854632] underline">
        Preeyapornn Petc..
      </span></NuxtLink
    >
  </div>
</template>

<style scoped></style>
