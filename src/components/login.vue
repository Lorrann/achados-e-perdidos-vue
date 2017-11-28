<template>
    <div style="padding: 10%;">
        <div class="card">
            <header class="login">Login</header>
            <div>
                <label>User</label>
                <input type="text"  placeholder="Ex: user@xpto.com" autofocus/>
            </div>
            <div>
                <label>Password</label>
                <input type="password" placeholder="Ex: ******">
            </div>
            <div>
                <button type="submit">Login</button>
            </div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'login',
}
</script>

<style>
    .login{
        text-align: center;
    }
</style>
