# Trying to solve surround
Реализация атари игры surround. Две змейки пытаются друг друга запереть.   
Для запуска игры: working_game.py  

В этом проекте я пытался сделать сильного агента для игры. Для этого использовался алгоритм Qlearning.  
Для тренировки агента: agent.py  
Для игры с агентом: AIgame.py  

Агент не обучился играть на хорошем уровне с помощью этого метода.   

Далее я попробовал реализовать метод из статьи AlphaZero.  
Ноутбук с реализацией: Small surround. MCTS testing.ipynb  
Однако тренировки этой модели шли слишком долго.  
Агент получился лучше, чем в первом методе, но все равно проигрывает человеку.   

