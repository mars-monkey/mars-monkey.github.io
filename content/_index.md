+++
title = ""
description = ""
template = "index.html"
+++

<div class="text-center my-12">
  <h1 class="text-5xl font-bold mb-4">Mars Monkey</h1>
  <p class="text-xl text-gray-600 dark:text-gray-400 max-w-md mx-auto">
    Here are my two main projects
  </p>
</div>

<div class="grid grid-cols-1 md:grid-cols-2 gap-8 max-w-4xl mx-auto">
  
  <!-- Project 1 Card -->
  <a href="/projects/project-one/" class="block group">
    <div class="border border-gray-200 dark:border-gray-700 rounded-2xl overflow-hidden hover:shadow-xl transition-all duration-300">
      <img src="/images/project-one.jpg" 
           alt="Project One" 
           class="w-full h-56 object-cover">
      <div class="p-6">
        <h2 class="text-2xl font-semibold mb-2 group-hover:text-blue-600 dark:group-hover:text-blue-400">
          Project One
        </h2>
        <p class="text-gray-600 dark:text-gray-400 mb-4">
          Short description of what this project does and why it's cool.
        </p>
        <span class="inline-block text-blue-600 dark:text-blue-400 font-medium group-hover:underline">
          View Project →
        </span>
      </div>
    </div>
  </a>

  <!-- Project 2 Card -->
  <a href="/projects/project-two/" class="block group">
    <div class="border border-gray-200 dark:border-gray-700 rounded-2xl overflow-hidden hover:shadow-xl transition-all duration-300">
      <img src="/images/project-two.jpg" 
           alt="Project Two" 
           class="w-full h-56 object-cover">
      <div class="p-6">
        <h2 class="text-2xl font-semibold mb-2 group-hover:text-blue-600 dark:group-hover:text-blue-400">
          Project Two
        </h2>
        <p class="text-gray-600 dark:text-gray-400 mb-4">
          Short description of the second project.
        </p>
        <span class="inline-block text-blue-600 dark:text-blue-400 font-medium group-hover:underline">
          View Project →
        </span>
      </div>
    </div>
  </a>

</div>
