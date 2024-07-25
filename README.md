# Grid-Sizing
/* Write your CSS code below to make the purple items size, grow and shrink like the green ones.*/

.grid-container {
  display: grid;
 grid-template-columns: auto  400px  minmax(200px, 500px);
  grid-template-rows: auto  auto 100px;
grid-auto-columns:50px;
}
  
  
