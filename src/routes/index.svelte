<svelte:head>
    <title>home</title>
</svelte:head>
<div id="container">
    <form>
        <!-- Username -->
        <label for="name">Username:</label>
        <input type="name">
        <!-- Password -->
        <label  class="bg-yellow-600" for="username">Password:</label>
        <input type="pass">
            
        <p><a href=".">Forgot your password?</a></p>
        <input type="password">
        <div id="lower">
            <input type="checkbox"><label class="check" for="checkbox">Soy profesor</label>
            <!-- Submit Button -->
            <button class="text-red-700">login</button>
        </div>
    </form>       
</div>