<template>
    <button id="btn-ir-arriba" >
        <svg viewBox="0 0 24 24">
          <path d="m4 16 8-8 8 8"></path>
        </svg>
    </button>
</template>


<script>

export default {
      name: 'BtnArriba',
    }

// Evento de boton ir a arriba

document.addEventListener("DOMContentLoaded", () => {

const scrollToBottomButtom = document.getElementById('btn-ir-arriba');

window.addEventListener("scroll", () => {
  if (window.scrollY > 100) {
    scrollToBottomButtom.style.display = 'block';
  } else {
    scrollToBottomButtom.style.display = 'none';
  }
});

scrollToBottomButtom.addEventListener('click', () => {
  window.scrollTo({
    top: 0,
    behavior: 'smooth'
  });
});

});
</script>


<style>
#btn-ir-arriba {
    display: none;
    cursor: pointer;
    
    position: fixed;
    bottom: 20px;
    right: 20px;
    
    background: var(--base-color);
    height: 50px;
    width: 50px;
    border-radius: 25px;
    border: none;
    
    box-shadow: 0px 12px 7px rgba(0, 0, 0, .1);
    transition: 300ms ease;
    }

    #btn-ir-arriba {
        color: var(--accent-color);
    }
    
    #btn-ir-arriba:hover {
      transform: scale(1.1);
    }
    
    #btn-ir-arriba svg {
    width: 25px;
    fill: none;
    stroke: var(--accent-color);
    stroke-width: 3px;
    }
</style>
  