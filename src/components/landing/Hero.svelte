<script>
	import ColorfulBackground from './ColorfulBackground.svelte';
	import arrowdown from 'feather-icons/dist/icons/arrow-down.svg';
  </script>
  <section class="w-full relative overflow-hidden">
	<div class="absolute top-0 left-0 mix-blend-multiply w-full h-full">
	  <ColorfulBackground />
	</div>
	<h1 class="text-4xl md:text-6xl font-bold text-center z-10 absolute top-0 left-0 w-full h-full flex items-center">
	  Learning to create services that will change lives.
	</h1>
  </section>
  <div 
  class="absolute bottom-0 left-0 w-full text-center mb-8">
	<img src={arrowdown} alt="Arrow Down" class="animate-bounce h-8 w-8 mx-auto text-white">
  </div>
  
  <style>
	h1 {
	  background-color: white;
	  color: black;
	  mix-blend-mode: screen;
	}
  
	section {
	  min-height: 85vh;
	}
  </style>
  
  