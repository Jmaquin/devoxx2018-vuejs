<template>
  <div id="app">
    <header>
      <h1>SuperCook</h1>
    </header>

    <!-- TODO afficher la recette -->
  </div>
</template>

<script>
  // TODO importer le service
  // TODO import le composant Recipe

  // TODO définir le composant
</script>

<style lang="scss">
  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;

    header {
      text-align: center;

      h1 {
        font-family: 'Cookie', cursive;
        font-size: 5em;
        text-shadow: 2px 8px 2px #aca2a2;
        margin: 30px 0;
      }

      .menu {
        display: inline-block;

        ul {
          display: flex;
          margin: 0;
          padding: 0;

          li {
            list-style-type: none;

            margin: 0 8px;
            border-bottom: 1px solid;
            border-radius: 11px;

            a {
              text-decoration: none;
              color: rgb(108, 108, 108);
              padding: 7px 30px;
              display: inline-block;
            }

            &:hover {
              background: #f6f6f6;
            }
          }
        }
      }
    }

    main {
      .content {
        width: 90%;
        margin: auto;

        .title {
          box-shadow: 0 8px 13px 0 #aeadad;
          padding: 0 11px;
          border-radius: 0 0 8px 8px;
          display: flex;
          justify-content: space-between;
          align-items: center;
          height: 30px;
          margin-bottom: 10px;
          margin-top: 10px;
        }
      }
    }

    footer {
      height: 20px;
    }
  }
</style>
