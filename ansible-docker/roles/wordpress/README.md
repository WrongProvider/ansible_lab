Role Name
=========

Aqui executaremos o conteiner Wordpress, fazendo uso do `links` para esse fazer uso do container MySQL. Também usaremos o `ports` para que a porta 80 do host se redirecione para o container na porta 80, e assim podemos configurar o Wordpress de qualquer host na rede.

Example Playbook
----------------

    - hosts: servers
      roles:
	- wordpress
License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
