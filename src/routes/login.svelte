<script lang="ts">
  import {goto} from '$app/navigation';
</script>

<div class="w-full h-full flex justify-center items-center bg-neutral">
  <div class="bg-base-100 w-full h-full p-4 md:h-auto md:w-1/2 md:card md:shadow-2xl xl:w-1/4 flex flex-col">
    <div class="flex flex-row-reverse">
      <div class="badge badge-outline">ALPHA</div>
    </div>
    <h1 class="text-center text-3xl font-bold mt-2">Poly</h1>
    <h2 class="text-center text-2xl font-light mb-4">Anmeldung</h2>
    <label class="label">
      <span class="label-text">E-Mail</span>
    </label> 
    <input type="text" placeholder="yourmom@example.com" class="input input-bordered">
    <label class="label mt-2">
      <span class="label-text">Passwort</span>
    </label> 
    <input type="password" placeholder="12345" class="input input-bordered">
    <button class="btn btn-primary mt-6" on:click={() => goto('/')}>Login</button>
  </div>
</div>