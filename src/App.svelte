<script>
</script>

<div class="calculator">
  <div class="display" />
  <div class="buttons">
    <button>7</button>
    <button>8</button>
    <button>9</button>
    <button class="operator">+</button>
    <button>4</button>
    <button>5</button>
    <button>6</button>
    <button class="operator">-</button>
    <button>1</button>
    <button>2</button>
    <button>3</button>
    <button class="operator">*</button>
    <button>0</button>
    <button>.</button>
    <button class="clear">C</button>
    <button class="operator">/</button>
    <button class="equals">=</button>
  </div>
</div>

<style>
  .calculator {
    display: inline-block;
    border: 1px solid #ccc;
    padding: 10px;
    border-radius: 5px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
  }

  .display {
    font-size: 24px;
    border: 1px solid #ccc;
    height: 24px;
    padding: 10px;
    margin-bottom: 10px;
    width: 300px;
    text-align: right;
  }
  .buttons {
    display: grid;
    grid-template-columns: repeat(4, 75px);
    gap: 5px;
  }

  button {
    padding: 10px;
    font-size: 18px;
    border: none;
    cursor: pointer;
    border-radius: 5px;
    font-family: Arial, sans-serif;
    text-align: center;
  }
  .operator {
    border: 0px solid #a46d19;
    background: #f90;
  }
  .clear {
    border: 0px solid #000;
    background: red;
  }
  .equals {
    border: 0px solid #000;
    background: #245be9;
    width: 320px;
  }
  .operator:hover {
    background: #ffd700;
  }
  .clear:hover {
    background: #ffc0cb;
  }
  .equals:hover {
    background: #add8e6;
  }
</style>
