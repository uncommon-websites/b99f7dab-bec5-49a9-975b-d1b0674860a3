<script>
  import { onMount } from 'svelte';
  
  let isScrolled = false;

  onMount(() => {
    const handleScroll = () => {
      isScrolled = window.scrollY > 10;
    };
    window.addEventListener('scroll', handleScroll);
    return () => window.removeEventListener('scroll', handleScroll);
  });
</script>

<nav class="fixed top-0 left-0 right-0 z-50 transition-all duration-300 {isScrolled ? 'bg-white/90 backdrop-blur-md border-b border-gray-100 py-3' : 'bg-transparent py-5'}">
  <div class="container-custom flex items-center justify-between">
    <div class="flex items-center gap-8">
      <a href="/" class="flex items-center gap-2 text-xl font-bold tracking-tight text-gray-900">
        <!-- Logo Icon -->
        <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="text-plain-green">
          <path d="M12 22C17.5228 22 22 17.5228 22 12C22 6.47715 17.5228 2 12 2C6.47715 2 2 6.47715 2 12C2 17.5228 6.47715 22 12 22Z" fill="currentColor"/>
          <path d="M15 9L10 16L8 13" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
        </svg>
        Plain
      </a>
      
      <div class="hidden md:flex items-center gap-6 text-sm font-medium text-gray-600">
        <a href="#" class="hover:text-gray-900 transition-colors">Channels <span class="text-xs ml-0.5">▼</span></a>
        <a href="#" class="hover:text-gray-900 transition-colors">Customers <span class="text-xs ml-0.5">▼</span></a>
        <a href="#" class="hover:text-gray-900 transition-colors">Resources <span class="text-xs ml-0.5">▼</span></a>
        <a href="#" class="hover:text-gray-900 transition-colors">Pricing</a>
        <a href="#" class="hover:text-gray-900 transition-colors">Support</a>
      </div>
    </div>

    <div class="flex items-center gap-3">
      <a href="#" class="px-3 py-1.5 text-xs font-semibold border border-gray-200 rounded text-gray-700 hover:border-gray-400 transition-colors uppercase tracking-wide">
        Sign In
      </a>
      <a href="#" class="px-3 py-1.5 text-xs font-semibold bg-plain-green text-white rounded hover:bg-green-400 transition-colors uppercase tracking-wide">
        Book a Demo
      </a>
    </div>
  </div>
</nav>
