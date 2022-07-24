<template>
  <main>
    <div class="container">
        <div id="content">
            <h2> CONTENT GOES HERE </h2>
        </div>
    </div>
  </main>
</template>

<script>
export default {
    name: 'TheMain',
}
</script>

<style>
    main {
        background-color: #1c1c1c;
        height: 100px;
    }


    .container, #content {
        height: 100%;
    }

    #content {
        color: white;
        display: flex;
        align-items: center;
    }
</style>