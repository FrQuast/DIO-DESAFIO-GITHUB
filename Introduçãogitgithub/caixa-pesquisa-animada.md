###  caixa de pesquisa animada html/css

###### html

<div class="busca">
                <input type="text" class="transformar" placeholder="Titulos, gente e gêneros">
            </div>

###### css

.transformar{

  background: url('../img/lupa.png') no-repeat center left;

  background-size: 20px;

  border: none;

  padding-top: 8px;

  padding-bottom: 8px;

  padding-left: 2px;

  width: 25px;

  z-index: 0;

  transition: all .5s ease, opacity 0s;



}

.transformar:focus{

  width: 250px;

  border: 1px solid white;

  background-color: var(--preto);

}



.transformar::-webkit-input-placeholder{

  padding-left: 30px;

  font-size: 14px;

}