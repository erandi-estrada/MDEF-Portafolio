# DEBUG - Grid Test

## Test de imágenes individuales:
![Test 1](images/initial-ideas.jpg)
![Test 2](images/bootcamp.jpg)

---

## Test del grid con bordes de colores:

<div class="grid-cards" style="border: 2px solid red; padding: 20px;">

<div class="card" style="border: 2px solid blue;">
    <img src="images/initial-ideas.jpg" alt="Test" style="border: 2px solid green;">
    <div class="card-content">
        <h3>TEST CARD 1</h3>
        <p>This should show as a card with green border around image</p>
        <a href="project/project.md" class="card-button">Test button</a>
    </div>
</div>

<div class="card" style="border: 2px solid blue;">
    <img src="images/bootcamp.jpg" alt="Test" style="border: 2px solid green;">
    <div class="card-content">
        <h3>TEST CARD 2</h3>
        <p>Second test card</p>
        <a href="term1/01-Bootcamp.md" class="card-button">Test button</a>
    </div>
</div>

</div>

---

## Lo que deberíamos ver:
- ✅ **Borde ROJO** alrededor del grid completo
- ✅ **Borde AZUL** alrededor de cada tarjeta  
- ✅ **Borde VERDE** alrededor de cada imagen
- ✅ **Texto y botones** dentro de cada tarjeta