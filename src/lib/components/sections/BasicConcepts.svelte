<script>
  import DualHeader from '$lib/components/common/DualHeader.svelte';
</script>

<section class="flex flex-col justify-center w-full py-5 sm:py-9 gap-14 xl:gap-20">
  <DualHeader title="basic concepts">
    <p slot="subtitle">Anki supports complex workflows, but getting started is easy.</p>
  </DualHeader>
  <div class="flex flex-col items-center gap-6 md:gap-20 md:flex-row">
    <img
      src="/graphics/deck-graphic.svg"
      alt="deck-graphic"
      class="aspect-[16/10] grow max-w-[90%] md:max-w-[40%]"
    />
    <div class="flex flex-col gap-2 md:gap-6 md:w-[60%]">
      <h2 class="text-2xl lg:text-4xl font-medium uppercase tracking-[1.08px]">Decks</h2>
      <p class="lg:text-2xl text-neutral">
        Decks are groups of flashcards that allow you to study specific parts of your collection
        instead of everything all at once. Create a new deck and add some flashcards to get started.
      </p>
    </div>
  </div>
  <div class="flex flex-col items-center gap-6 md:gap-20 md:flex-row-reverse">
    <img
      src="/graphics/review-graphic.svg"
      alt="deck-graphic"
      class="aspect-[16/10] grow max-w-[90%] md:max-w-[40%]"
    />
    <div class="flex flex-col gap-2 md:gap-6 md:w-[60%]">
      <h2 class="text-2xl lg:text-4xl font-medium uppercase tracking-[1.08px]">Reviews</h2>
      <p class="lg:text-2xl text-neutral">
        When you're ready, start reviewing your flashcards. Rate your recall with the most suitable
        option and Anki will schedule the next review for when you're most likely to forget the
        information.
      </p>
    </div>
  </div>
</section>
