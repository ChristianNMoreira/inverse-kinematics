# Cinemática Inversa

O problema da cinemática inversa consiste em encontrar ângulos de juntas robóticas que correspondem à certa posição desejada do braço robótico no espaço. Ou seja, encontrar valores de θ que satisfaçam f(θ)=x, f(θ₁,θ₂)=(x,y) e f(θ₁,θ₂,θ₃)=(x,y,z).

Portanto, esse processo é o inverso da cinemática direta, na qual os parâmetros utilizados são diretamente os ângulos. Nela, um sistema receberia um argumento θᵢ e com isso moveria o braço robótico nesse ângulo. Já na inversa, o sistema recebe o valor desejado no espaço, e o sistema, a partir dessa informação, descobre o ângulo referente.

<div align="center">

  <br>
        <img src="https://res.cloudinary.com/dev63c7l0/image/upload/v1629517659/Untitled_rcyy6l.png" width="400" height="auto">
        <figcaption><a href="https://repositorio.ufscar.br/bitstream/handle/ufscar/13588/TCC%20-%20Victor%20Abreu%20Nunes%20%28Rev%20Victor%2020.12%29.pdf?sequence=1&isAllowed=y">Fonte: Repositório UFSCAR</a></figcaption>
  <br>

</div>

Esse problema pode ser visto como uma busca de raízes, o que permite usar alguns métodos numéricos, de forma que se deseja encontrar um ou mais θᵢ tal que xᵢ - f(θᵢ) = 0.