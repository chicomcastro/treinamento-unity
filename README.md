# treinamento-unity
Arquivos das aulas para os treinamentos dos bixos em unity

##Conteudo

### Aula0: Projeto Follow 
1. Objeto Player
  - Criar um sprite no paint
  - Adicionar um sprite no objeto vazio
  - Adicionar um novo script (PlayerController)
2. Player Controller Basico
  - Update
  - Input.GetKey    (LEMBRAR DE FAZER O PROXIMO PROJETO COM GET KEY DOWN E MOUSE)
  - transform.position (s = s0 + vt) (v é constante)
  - speed -> variavel publica (editar variavel publica no Unity, dentro e fora do jogo)
  - Opcional: Fazer os transforms usando GetAxis();
 3. Objeto Enemy
  - Aproveitar Codigo do Player Basico (s = s0 + vt)
  - Pegar a posicao do player e usar como vetor direcao
  - Passar um GameObject público como parametro para poder 'arrastar' no Unity
  - v = direction * speed
 4. Opcionais (Viram desafios caso não dê tempo dedar na aula)
  - Botar um sprite bonitinho da internet
  - Botar o inimigo para spawnar a uma distancia (em posicao aleatoria)
 5. Desafios (com conhecimentos futuros)
  - Fazer alguma condiçao de Game Over
  - Fazer aparecerem novos inimigos a cada intervalo de tempo
 6. TODO
  - Fazer a colisao do inimigo com o player;
### Aula 1: Projeto Defender:
  1. Objeto Player
    - Adicionar um "canhão"
    - Adicionar o ponto de onde os tiros vao sair
    - Criar um novo script (PlayerController)
  2. Player Controller
    - Codigo de olhar para a posicao do mouse
    - Codigo de atirar (criar campo public GameObject Bullet)
  3. Objeto Bullet
    - Adicionar um novo script (Bullet)
    - Script faz a bullet ir para o lado (s += vt)
    - Colocar no player e mostrar que sao criados novas Bullet
  4. Prefab Bullet
    - Explicar prefab, criando prefab do bullet
    - Arrastar o prefab no player e mostar que sao criados novas Bullets
  5. Objeto Enemy
    - Copiar o script do enemy do _Projeto Follow_
    - Criar nova tag buller e colocar na bullet
    - Adicionar logica de colisao com a bullet
  6. Objeto Enemy Spawner
    - Criar um novo script Enemy Spawner
    - Criar uma funcao Spawn()
    - Colocar no start um InvokeRepeating e explicar o funcionamento
    - Usar com prefab do enemy vai dar pau por desconhecimento do player
    - Pegar player com FindObjectsWithTag()
    
  

    
    
