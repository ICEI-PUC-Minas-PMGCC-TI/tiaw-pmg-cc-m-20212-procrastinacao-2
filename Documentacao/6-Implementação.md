# Projeto da Solução

<span style="color:red">Pré-requisitos: <a href="4-Gestão-Configuração.md"> Ambiente e Ferramentas de Trabalho</a></span>

## Tecnologias Utilizadas

> O template do site, o login, a edição do perfil do usuário, a agenda, o cadastro e a apresentação do contato de psicólogos e o quiz 
> foram desenvolvidos utilizando as linguagens HTML, CSS e JavaScript e a framework Bootstrap.
> 
>
> E além dessas tecnologias, os artefatos relacionados ao login do usuário, à agenda e ao contato dos psicólogos, foram desenvolvidos utilizando o local storage. 
> 
> 
> O desenvolvimento do código foi feito no Visual Studio Code e consolidado no Replit, onde também foi hospedado.
> Projeto disponível em https://up.joaovlmelo.repl.co/
> 
> ![image](https://user-images.githubusercontent.com/91549016/145920516-c17e55b1-e8fa-4516-bf1b-a5edd5872299.png)
>
>
> Template do Site
> ![image](https://user-images.githubusercontent.com/91549016/145921909-dd06060e-8a99-49a2-8a10-8b8db5f66c56.png)
>
> 
## Arquitetura da solução

![image](https://user-images.githubusercontent.com/91549016/145923414-fab0343f-c469-42f2-a403-b366812476d4.png)


A imagem acima ilustra a o fluxo do usuário da nossa solução. Assim
que o usuário acessa o site, ele é presentado a tela de login. Caso não haja um cadastro no site ainda, ele pode criar uma nova conta que terá as informações de acesso
armazenadas no local storage. Caso haja conta cadastrada, ao preencher os campos com informações válidas, ele será redirecionado para a página principal da plataforma, 
de onde é possível acessar todas as outras páginas que também têm acesso livre entre si em razão do menu.


Caso ele escolha a opção Agenda, ele será redirecionado para uma página em que ao fazer o cadastro de tarefas, elas são armazenadas no local storage e há o registro desses 
eventos em uma agenda semanal. E ao final da página há a opção de preencher um quiz para auxiliar os desenvolvedores da plataforma a melhorar o site.


Na página de contatos de psicólogos é possível cadastrar o contato do seu psicólogo que é armazenado no local storage e é apresentado formando uma agenda.


Na página de edição de perfil de usuário é possível realizar modificações no perfil, alterando o local storage.


Vale ressaltar que todas as páginas conectadas pelo menu possuem um botão de compartilhamento do site em redes sociais.



