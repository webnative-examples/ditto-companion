<script lang="ts">
  import { createEventDispatcher } from 'svelte'
  const dispatch = createEventDispatcher()
</script>

<div class="flex items-center gap-2 cursor-pointer">
  <svg xmlns="http://www.w3.org/2000/svg" width="28" height="29" fill="none">
    <rect
      width="26"
      height="26"
      x="1"
      y="1"
      stroke="currentColor"
      stroke-width="2"
      rx="5"
    />
    <path
      fill="currentColor"
      d="M19.228 9.49c-.18.76-.37 1.58-.57 2.46-.2.88-.38 1.74-.54 2.58-.16.84-.29 1.61-.39 2.31h-2.85l-.21-.33c.18-.7.41-1.45.69-2.25.28-.82.59-1.64.93-2.46.34-.82.67-1.59.99-2.31h1.95Zm-5.55 0c-.18.76-.37 1.58-.57 2.46-.2.88-.38 1.74-.54 2.58-.16.84-.29 1.61-.39 2.31h-2.82l-.18-.33c.18-.7.41-1.45.69-2.25.28-.82.58-1.64.9-2.46.34-.82.67-1.59.99-2.31h1.92Z"
    />
  </svg>
  <h2 class="text-lg font-mono cursor-pointer">Ditto Companion</h2>
</div>
