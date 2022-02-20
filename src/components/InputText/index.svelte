<script>
    export let value;
    export let placeholder;
    export let icon;
  </script>
  
  <div>
    <span>{icon}</span>
    <input bind:value {placeholder} />
  </div>