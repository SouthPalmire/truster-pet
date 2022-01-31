<template>
  <div>
    <div>
      <h1>registration</h1>

      <form>
        <label>Firstname<br>
          <input
            type="text"
            name="firstname"
          />
        </label><br><br>

        <label>Lastname<br>
          <input
            type="text"
            name="lastname"
          />
        </label><br><br>

        <label>password<br>
          <input
            type="password"
          />
        </label><br><br>

        <label>confirm password<br>
          <input
            type="password"
          />
        </label><br><br>

        <label>e-mail<br>
          <input
            name="email"
            type="email"
          />
        </label><br><br>

        <label>date of birth<br>
          <input
            type="date"
          />
        </label><br><br>

        <button class="btn">
          register
        </button>
      </form>

    </div>
  </div>
</template>

<script>
export default {
  name: 'Register',
};
</script>

<style scoped>

</style>
