<script>
  import Logo from './Logo.svelte';
</script>

<nav class="fixed top-0 left-0 right-0 z-50 bg-white/90 backdrop-blur-sm transition-all duration-300 border-b border-gray-100/50">
  <!-- Announcement Bar -->
  <div class="w-full py-2 text-center bg-white border-b border-gray-100 hidden md:block">
    <a href="#" class="text-[11px] font-medium text-gray-500 hover:text-gray-900 underline underline-offset-2 transition-colors">
      Read "You Are The Product" — AI-native product leadership insights
    </a>
  </div>

  <div class="max-w-[1400px] mx-auto px-6 h-20 flex items-center justify-between">
    <!-- Logo -->
    <div class="flex-shrink-0">
      <a href="/" class="flex items-center gap-3 text-primary-600">
        <Logo className="w-7 h-7" />
        <span class="text-xl tracking-tight font-semibold text-gray-900">Mirza Besirovic</span>
      </a>
    </div>

    <!-- Navigation -->
    <div class="hidden md:flex items-center gap-8 text-sm font-medium text-gray-600">
      <a href="#work" class="hover:text-gray-900 transition-colors">Work</a>
      <a href="#expertise" class="hover:text-gray-900 transition-colors">Expertise</a>
      <a href="#speaking" class="hover:text-gray-900 transition-colors">Speaking</a>
      <a href="#writing" class="hover:text-gray-900 transition-colors">Writing</a>
    </div>

    <!-- Actions -->
    <div class="flex items-center gap-6 text-sm font-medium">
      <a href="https://www.linkedin.com/in/mirzabesirovic/" target="_blank" class="text-gray-600 hover:text-gray-900 transition-colors">LinkedIn</a>
      <a href="#contact" class="bg-primary-600 hover:bg-primary-700 text-white px-5 py-2.5 rounded-full transition-colors">
        Get in touch
      </a>
    </div>
  </div>
</nav>
