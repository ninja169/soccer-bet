<template>
    <div id="app">
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="">
                <span class="logo">
                    <svg style="color: white;width:50px" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 256 256"><rect width="56" height="56" fill="none"></rect><path d="M231.8,134.8a4.8,4.8,0,0,0,0-1.2c.1-1.9.2-3.7.2-5.6a103.2,103.2,0,0,0-23-65.1,5.5,5.5,0,0,0-1.4-1.7,103.9,103.9,0,0,0-41.1-29.8l-1.1-.4a103.4,103.4,0,0,0-74.8,0l-1.1.4A103.9,103.9,0,0,0,48.4,61.2,5.5,5.5,0,0,0,47,62.9,103.2,103.2,0,0,0,24,128c0,1.9.1,3.7.2,5.6a4.8,4.8,0,0,0,0,1.2,104.2,104.2,0,0,0,15.7,48.4,9.9,9.9,0,0,0,1.1,1.7,104.3,104.3,0,0,0,60.3,43.6h.3a104.2,104.2,0,0,0,52.8,0h.3A104.3,104.3,0,0,0,215,184.9a9.9,9.9,0,0,0,1.1-1.7A104.2,104.2,0,0,0,231.8,134.8ZM68.5,117.1l13.2,4.3,12.7,39.2-8.1,11.2H51.7a86.2,86.2,0,0,1-11.2-34.3Zm119,0,28,20.4a86.2,86.2,0,0,1-11.2,34.3H169.7l-8.1-11.2,12.7-39.2ZM193.2,69l-10.7,32.9-13.2,4.3L136,81.9V68.1l28-20.4A87,87,0,0,1,193.2,69ZM92,47.7l28,20.4V81.9L86.7,106.2l-13.2-4.3L62.8,69A87,87,0,0,1,92,47.7Zm18,166.4L99.3,181.2l8.1-11.2h41.2l8.1,11.2L146,214.1a86.2,86.2,0,0,1-36,0Z" fill="white"></path></svg>
                </span>
                SoccerBet
            </a>
            <button
            class="navbar-toggler"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#navbarTogglerDemo02"
            aria-controls="navbarTogglerDemo02"
            aria-expanded="false"
            aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarTogglerDemo02">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="">Matches</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="">Bets</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="">Help</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
</div>
</template>

<script>
export default {
  name: 'NavBar',
  props: {
  },
};
</script>
