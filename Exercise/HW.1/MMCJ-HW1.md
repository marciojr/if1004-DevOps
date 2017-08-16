## Homework 1 - DevOps

### Slack Profile

link: https://github.com/marciojr/if1004-DevOps/blob/master/Exercise/HW.1/Slack_Perfil.jpeg

![](ttps://github.com/marciojr/if1004-DevOps/blob/master/Exercise/HW.1/Slack_Perfil.jpeg)

### Git Tutorial Screenshot

link: https://github.com/marciojr/if1004-DevOps/blob/master/Exercise/HW.1/Screenshot_GitTutorial.jpeg

![](https://github.com/marciojr/if1004-DevOps/blob/master/Exercise/HW.1/Screenshot_GitTutorial.jpeg)

### Hooks and Gif ScreenCast

link ScreenShot: https://github.com/marciojr/if1004-DevOps/blob/master/Exercise/HW.1/post-commit_screenshot.PNG

![](https://github.com/marciojr/if1004-DevOps/blob/master/Exercise/HW.1/post-commit_screenshot.PNG)

link ScreenCast: https://github.com/marciojr/if1004-DevOps/blob/master/Exercise/HW.1/post-commit_screencast.gif

### Concepts

* In your own words, explain the difference between continuous integration,continuous delivery, and continuous deployment.
 
> - Continuous Integration - A ideia de integração contínua diz respeito ao modelo de desenvolvimento onde é importante se ter integração rápida e testes, onde no caso da integração contínua são os testes unitários, acelerando o processo de teste sobre as implatações todos, garantindo o funcionamento, possibilitando a descoberta de erros mais cedo e permitindo atualizações mais rápidas do produto.
 - Continuous Delivery - São algumas práticas ligadas ao processo, onde através delas é possível testar o comportamento das funções desenvolvidas(utilizando BDD), garantindo,através dessas, que o que foi implementado possa ser adicionado no ambiente de produção.
 - Continuous Deployment - Esse método faz uso de processos automatizados para a publicação da implementação no ambiente de produção, dando um ganho na velocidade, isso, se os testes feitos nos outros processos, assim o permitirem.

* How does DevOps team model (e.g., site reliability engineer) differ than a a NoOps team model (e.g. Netflix team)? What differences in architecture allow for a NoOps model?

>No DevOps a barreira entre Devs e Ops é quebrada, sendo necessário que o Dev e o Ops pensem juntos e participem juntos de toda a integração, de todo o ciclo de formação do projeto ou da atualização. Com o Noops, a barreira minima que ainda sobra no metódo DevOps, é derrubado possibilitando que cada persona do projeto, seja responsável parcialmente pelas etapas necessárias, seja desenvolvimento, monitoramento, teste. A arquitetura Noops faz uso de mais automatização durante todo o processo, abrindo um lack pra que todos estejam cientes de cada fase do projeto e trabalhe neles.

* Explain the principle of Every Feature is an Expertiment.

>Utiliza a opção de feedback do usuário para determinada feature, recebendo informações e tirando delas, a decisão sobre se persiste aquela feature na implantação da release, ou se retira ela do processo. Evitando um gasto desnecessário de tempo sobre essa feature.

* Explain the principle of Be Fast to Deploy, Slow(er) to Release.

>Trás uma ideia de teste e garantia sobre a feature, pensando em não afetar de nenhuma forma o usuário, a forma como ele receberá a atualização ou a criação da nova feature. Possibilitando que ele continue tendo uma boa experiência dentro do processo de uso da aplicação.