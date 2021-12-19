
<h1>Weather App</h1>

<form on:submit|preventDefault={getWeather}>
    <label for="location">Location:</label>
    <input id="location" bind:value={location} type="text" />
    <button type="submit">Check</button>
</form>