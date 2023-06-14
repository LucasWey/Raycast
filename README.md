Dupla: Lucas Wey e Lucas Yuji
conforme realizamos o projeto utilizamos como base um estande de tiro com arco e flecha, onde tentamos desenvolver uma cena simples para apenas a visualização e aplicar o conceito do Raycast,
assim fizemos um pequeno mapa com bonecos de tiro ao alvo tirados da assetstore, e fizemos um código para ignorar o mapa ao acertar o raio para não destruir os mesmos, foram aplicados também
o conceito de movimentação para mover câmera e personagem como mostrado na imagem a seguir:
![image](https://github.com/LucasWey/Raycast/assets/101645516/ffcec44a-eedc-4490-b375-87e9c404c6cc)
então aplicamos o código do Raycast para gerar um raio que ao colidir com um objeto ele destroi, e ignora todos os objetos que estão com o código para ignorar os raios, assim evitando possíveis problemas com o mapa.
![image](https://github.com/LucasWey/Raycast/assets/101645516/fdb35fff-b482-4b92-b7cf-eb67f22b2503)
a iluminação que utilizamos foi a directional light para simular a luz solar na cena e não gerar sombras, por isso o elemento está tão próximo.
