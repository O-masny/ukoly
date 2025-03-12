<script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.2/gsap.min.js"></script>


gsap.to("#box", { x: 200, duration: 1 });


let tl = gsap.timeline();
tl.to("#box", { x: 200, duration: 1 })
  .to("#box", { y: 100, duration: 1 })
  .to("#box", { rotation: 360, duration: 1 });

CSS
 body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f4f4f4;
        }
        .wrapper {
            display: flex;
            flex-direction: column;
            gap: 20px;
        }
        .item {
            opacity: 0;
            background: #3498db;
            color: white;
            padding: 20px;
            text-align: center;
            border-radius: 8px;
            font-size: 18px;
        }

        
 <script>
        gsap.fromTo(".item", 
            { opacity: 0, y: 50 },  // Výchozí stav (prvky neviditelné a posunuté dolů)
            { opacity: 1, y: 0, duration: 1, stagger: 0.3, ease: "power2.out" } // Animace
        );
    </script>