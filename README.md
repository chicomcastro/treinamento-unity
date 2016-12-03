# treinamento-unity
Arquivos das aulas para os treinamentos dos bixos em unity

##Conteudo

Primeira aula:
- Projeto Follow:
  1. Criar objeto vazio para colocar script (player)
    - Criar um sprite no paint
    - Adicionar um sprite no objeto vazio
    - Adicionar um script em branco (PlayerController)
  2. Player Controller Basico
    - Update
    - Input.GetKey    (LEMBRAR DE FAZER O PROXIMO PROJETO COM GET KEY DOWN E MOUSE)
    - transform.position (s = s0 + vt) (v é constante)
    - speed -> variavel publica (editar variavel publica no Unity, dentro e fora do jogo)
    - Opcional: Fazer os transforms usando GetAxis();
   3. Enemy Controller Basico
    - Aproveitar Codigo do Player Basico (s = s0 + vt)
    - Pegar a posicao do player e usar como vetor direcao
    - Passar um GameObject público como parametro para poder 'arrastar' no Unity
    - v = direction * speed
   4. Opcionais: (Viram desafios caso não dê tempo dedar na aula)
    - Botar um sprite bonitinho da internet
    - Botar o inimigo para spawnar a uma distancia (em posicao aleatoria)
   5. Desafios: (com conhecimentos futuros)
    - Fazer alguma condiçao de Game Over
    - Fazer aparecerem novos inimigos a cada intervalo de tempo
-
    
    
