---
layout: app
title: Login
description: Authenticate to use the tutorial app
---

<style>
  .table {
    display: table;
  }
  .row {
    display: table-row;
  }
  .cell {
    display: table-cell;
  }
  label {
    display: table-cell;
    padding: 5px 30px;
  }
  input {
    display: table-cell;
    padding: 5px;
    margin: 5px 0px;
  }
  button {
    margin: 40px 0px;
    padding: 10px 40px;
  }
  .flex-centre {
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .flex-right {
    display: flex;
    justify-content: right;
    align-items: right;
  }
</style>

<br/>

<div class="flex-centre">
 <form action="signin.html">
  <div class="table">
   <div class="row">
    <label for="username">User name</label>
    <input type="text" id="username"/>
   </div>
   <div class="row">
    <label for="password">Password</label>
    <input type="password" id="password"/>
   </div>
  </div>
  <div class="flex-right">
   <button type="submit" id="Signin">Sign in</button>
  </div>
 </form>
</div>
