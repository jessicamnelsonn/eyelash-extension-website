<script>
  const navItems = [
    { name: 'Home', href: '/' },
    { name: 'About Us', href: '/about' },
    { name: 'Pricing', href: '/pricing' },
    { name: 'Contact', href: '/contact' },
  ];
</script>

<header class="relative">
  <nav class="py-4 flex items-center justify-between">
    <div>
      <h1 class="text-2xl px-8">Lash Lux</h1>
    </div>
    <ul class="flex space-x-2 md:space-x-5 lg:space-x-8">
      {#each navItems as { name, href }}
        <li>
          <a href={href} class="text-base md:text-lg lg:text-xl text-[#241528] hover:text-[#54315E] hover:underline transition-colors duration-300 px-2 md:px-3 py-2 focus:outline-none focus:shadow-outline">
            {name}
          </a>
        </li>
      {/each}
    </ul>
  </nav>
</header>


