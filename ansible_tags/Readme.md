Neste exemplo iremos taggear nossas tasks, para que quando necessitarmos, rodaremos somente algumas específicas de nossas roles.

Para chamar somente uma task taggeada:

ansible-playbook -i inventory --tags *nomedasuatag meu-playbook.yml 