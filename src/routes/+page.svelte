<script lang="ts">

    let selectedMode:string;

    const changeMode = (button:any) => {
    selectedMode = button;
  };

</script>

<div class="hero min-h-screen bg-base-200">
  <div class="hero-content text-center">
    <div class="max-w-md">
      <h1 class="text-5xl font-bold">Welcome to the Makefile generator</h1>
      <p class="py-6">This web app creates a basic Makefile for your C projects. They are not perfect but definetly a great beginning.</p>
      <button class="btn btn-primary">Start creating</button>
    </div>
  </div>
</div>

<div class="flex justify-center gap-24 bg-base-200">
    <button class="btn btn-primary">42 Project</button>
    <button class="btn-primary btn">Own Project</button>
</div>
