cliente (id_cliente, nome, cpf)
 |
 |
/|\
consulta (id_consulta, horario, data, realizada, FK(id_profissional), FK(id_cliente))
\|/
 |
 |
profissional (id_profissional, nome, numero, cpf)
