<template>
  <div class="login-body">
    <div class="login">
      <h1>login</h1>

      <form>
        <label>e-mail<br>
          <input
            type="email"
            name="email"
            placeholder="enter your email"
          />
        </label><br><br>

        <label>password<br>
          <input
            type="password"
            placeholder="enter your password"
          />
        </label><br><br>

        <button
          class="btn"
          @click.prevent="$router.push('Main')"
        >
          login
        </button>

        <button
          class="btn"
          @click.prevent="$router.push('Register')"
        >
          registration
        </button>
      </form>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Login',
  data() {
    return {
    };
  },
};
</script>

<style scoped>
/*.login-body {*/
/*  background-color: rgb(196, 194, 194);*/
/*  width: 100%;*/
/*  height: 100%;*/
/*  position: absolute;*/
/*  top: 0;*/
/*  left: 0;*/
/*  overflow: auto;*/
/*}*/
/*.login {*/
/*  text-align: center;*/
/*  width: 40em;*/
/*  height: 35em;*/
/*  background-color: grey;*/
/*  position: absolute;*/
/*  top: 0;*/
/*  right: 0;*/
/*  bottom: 0;*/
/*  left: 0;*/
/*  margin: auto;*/
/*}*/
</style>
