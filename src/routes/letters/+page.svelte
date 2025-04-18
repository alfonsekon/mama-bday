<script lang='ts'>
    import dem1 from '$lib/assets/d-e-m.jpg';
    import mamadaddy from '$lib/assets/mamadaddy.jpg';
    import helloKitty from '$lib/assets/hello-kitty-main-removebg-preview.png';
    import helloKittySide from '$lib/assets/hello-kitty-side.png';
    import mamaEnzoCoffeebean from '$lib/assets/mama-enzo-coffeebean.jpg';
    import mamaBag from '$lib/assets/mama-bag.jpg';
    import mamaIceCream from '$lib/assets/mama-icecream.jpeg';
    let count = 0;
    function counter() {
        count += 1;
    }
</script>


<div class="hello-container" style="background-color: transparent;">
    <div class="hello-container" style="background-color: transparent;">
        <div class="curve-text">
            <svg width="300" height="130">
                <path id="curve" d="M 0 130 C 0 120, 146 30, 300 120"></path>
                <text class="text" text-anchor="middle">
                    <textPath class="text__path" href="#curve" startOffset="50%">
                        Hello Mommy
                    </textPath>
                </text>
            </svg>
        </div>

        <div style="background-color: transparent; position: relative; top: -70px;" class="div">
                <img style="scale: 60%;" src={helloKitty} alt="Hello Kitty"/>
        </div>
    </div>
</div>

<div class="grid">
    <div class="top-left">Left Top</div>
    <div class="bottom-left">Left Bottom</div>
    
    <div class="middle">Middle (Tall)</div>
    
    <div class="top-right">Right Top</div>
    <div class="bottom-right">Right Bottom</div>
</div>