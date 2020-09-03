<template>
    
<div>

<form @submit.prevent>
    <input type="email" placeholder="Email">
    <input type="password" placeholder="Password">
    <button type="submit">Sign in</button>
</form>

<NuxtLink to="/sign-in/reset-password">I forgot my password</NuxtLink>

</div>

</template>