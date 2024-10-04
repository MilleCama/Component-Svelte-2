<script>
    let selectedOption = 'Option 1'; 
</script>


<div class="flex justify-center items-center">
 
	<!-- Option 1 -->
  <label class="cursor-pointer flex">
    <input
      type="radio"
      value="Option 1"
      bind:group={selectedOption}
      class="sr-only"
    />
    <div
      class="px-4 py-2 border border-gray-300 text-sm font-medium transition-all
             bg-gray-200 hover:bg-gray-300 focus:bg-gray-300 focus:outline-none
             rounded-md
             {selectedOption === 'Option 1' ? 'bg-gray-300 text-white' : 'text-gray-700'}">
      Segment 1
    </div>
  </label>

  <!-- Option 2 -->
  <label class="cursor-pointer flex">
    <input
      type="radio"
      value="Option 2"
      bind:group={selectedOption}
      class="sr-only"
    />
    <div
      class="px-4 py-2 border border-gray-300 text-sm font-medium transition-all
             bg-gray-200 hover:bg-gray-300 focus:bg-gray-300 focus:outline-none
             rounded-md
             {selectedOption === 'Option 2' ? 'bg-gray-300 text-white' : 'text-gray-700'}">
      Segment 2
    </div>
  </label>

  <!-- Option 3 -->
  <label class="cursor-pointer flex">
    <input
      type="radio"
      value="Option 3"
      bind:group={selectedOption}
      class="sr-only"
    />
    <div
      class="px-4 py-2 border border-gray-300 text-sm font-medium transition-all
             bg-gray-200 hover:bg-gray-300 focus:bg-gray-300 focus:outline-none
             rounded-md
             {selectedOption === 'Option 3' ? 'bg-gray-300 text-white' : 'text-gray-700'}">
      Segment 3
    </div>
  </label>
</div>

<p class="mt-4 text-center">Selected Segment: {selectedOption}</p>








