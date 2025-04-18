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

<div class="scrolling-text" style="background-color: transparent;">
    <svg width="100%" height="100">
        <text class="text" text-anchor="middle" x="50%" y="50%">
            Happy Birthday! We Love You!
        </text>
    </svg>
</div>

<div class='grid'>
    <!-- <div class='item1' style="background-color: pink;"> -->
        <!-- <div class="curve-text top-left birthday-curve" style="background-color: green;">
            <svg width="300" height="130">
                <path id="curve" d="M 0 130 C 0 130, 146 30, 300 130"></path>
                <text class="text" text-anchor="middle">
                    <textPath class="text__path" href="#curve" startOffset="50%">
                        Happy Birthday
                    </textPath>
                </text>
            </svg>
        </div> -->
        <img src={helloKittySide} alt="daddy, enzo, mama 1" class="grid-image-left bottom-left" />
    <!-- </div> -->

    <!-- <div class="item1" style="background-color: blue;"> -->
        <img src={mamaIceCream} alt='mama eating ice cream in texas roadhouse' class="grid-image-center-portrait middle"/>
    <!-- </div> -->

    <!-- <div class='item1' style="background-color: pink;"> -->
        <img src={helloKittySide} alt="daddy, enzo, mama 1" class="bottom-right grid-image-right"/>
    <!-- </div> -->
</div>

<div class="div">
    <h1 class='title'>You are the <font color=#FFD2A0>best mom</font> in the world!</h1>
</div>

<div>
    <div>you are mommymazing!</div>
</div>

<table style="border=2; width=50%; height=50%; bordercolor=white;">
</table>


<div class="box-model">
    hello
</div>

<div style="background-color=green;">
    <svg width="300" height="200" viewBox="0 0 300 200">
      <defs>
        <path id="curve" d="M 50 100 A 100 100 0 0 0 250 100" />
      </defs>
    
      <text font-size="18" fill="black">
        <textPath href="#curve" startOffset="50%" text-anchor="middle">
          Happy Birthday Mama!
        </textPath>
      </text>
    </svg>
</div>