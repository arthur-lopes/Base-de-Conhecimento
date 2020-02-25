<template>
  <footer class="footer">
      <span>Copyright <strong><a href="http://2ois.com.br">Dois</a></strong> - © 2019 - 2020</span>
  </footer>
</template>

<script>
export default {
    name: "Footer"
}
</script>

<style>
    .footer {
        grid-area: footer;
        background-color: #ddd;
        color: #333;

        display: flex;
        align-items: center;
        justify-content: flex-end;
        padding-right: 10px;
    }

    strong a {
        text-decoration: none;
        color: #333;
    }
</style>