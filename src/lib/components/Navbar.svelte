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
          <path
            d="M17.2235 12.5566C17.2235 15.0114 15.2335 17.0015 12.7787 17.0015C10.3239 17.0015 8.33384 15.0114 8.33384 12.5566H4.77795C4.77795 16.9753 8.36002 20.5574 12.7787 20.5574C17.1974 20.5574 20.7794 16.9753 20.7794 12.5566C20.7794 8.13797 17.1974 4.55591 12.7787 4.55591V8.11179C15.2335 8.11179 17.2235 10.1018 17.2235 12.5566Z"
            fill="currentColor"
          />
          <path
            opacity="0.5"
            d="M7.44485 2.77795C7.44485 5.23278 5.45483 7.22281 3 7.22281V10.7787C7.41869 10.7787 11.0007 7.19663 11.0007 2.77795H7.44485Z"
            fill="currentColor"
          />
        </svg>
        Claimable
      </a>
      
      <div class="hidden md:flex items-center gap-6 text-sm font-medium text-gray-600">
        <a href="#" class="hover:text-gray-900 transition-colors">Features</a>
        <a href="#" class="hover:text-gray-900 transition-colors">Pricing</a>
        <a href="#" class="hover:text-gray-900 transition-colors">Integrations</a>
        <a href="#" class="hover:text-gray-900 transition-colors">Resources <span class="text-xs ml-0.5">▼</span></a>
      </div>
    </div>

    <div class="flex items-center gap-3">
      <a href="#" class="px-3 py-1.5 text-xs font-semibold border border-gray-200 rounded text-gray-700 hover:border-gray-400 transition-colors uppercase tracking-wide">
        Sign In
      </a>
      <a href="#" class="px-3 py-1.5 text-xs font-semibold bg-plain-green text-white rounded hover:opacity-90 transition-opacity uppercase tracking-wide">
        Start Free Trial
      </a>
    </div>
  </div>
</nav>
