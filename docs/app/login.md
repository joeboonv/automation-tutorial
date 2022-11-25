---
title: Login
---

<style>
  h1 {
    text-align: center;
  }
  button {
    padding: 10px 40px;
    display: table-cell;
  }
  .middle {
    text-align: center;
  }
  form {
    display: table;
  }
  p {
    display: table-row;
  }
  label {
    display: table-cell;
  }
  input {
    display: table-cell;
  }
</style>

<br/><br/><br/>

<div class="middle">
  <form action="signin.html">
    <p>
      <label for="username">User name</label>
      <input type="text" id="username"/>
    </p>
    <p>
      <label for="password">Password</label>
      <input type="password" id="password"/>
    </p>
    <p>
      <button type="submit" id="Signin">Sign in</button>
    </p>
  </form>
</div>
