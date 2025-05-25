# Agendamento de tarefas

## Importação de agendamentos

Na importação de agendamentos o sistema sobrescreve os dados de PDVs selecionados. Então se quiser apenas incluir novos PDVs no agendamento, e manter os que já estão selecionados, deve enviar todos os PDVs no arquivo importado, até mesmo os que já estão selecionados no agendamento.

## Processo de Agendamento Mobile: Funcionamento e Análise de Situações.

Prezados,

Em anexo, envio o documento elaborado em conjunto com o time Encore, detalhando o funcionamento do processo de agendamento mobile (SIM).

Nele, descrevemos um procedimento para analisar as situações reportadas pelos clientes.

[\[Encore+\] Como funciona o agendamento mobile](https://drive.google.com/file/d/15wsIHU3nmIEQZeVLbpRNciE_94DmlOlB/view?usp=sharing)

## Execução de agendamentos

A apresentação abaixo demonstra como realizar uma auditoria no processo de execução de agendamentos web.

* [Logs de criação de Tarefas](https://docs.google.com/presentation/u/0/d/1J0YBG0CorzneFPIAXQeJilm0qECW_HHgusvt8edxSfY/edit)

Atenção em agendamentos com mix de produtos:\
Em casos de divergência no disparo das tarefas do agendamento, onde o disparo não respeita a segmentação do mix, é importante verificar se algum PDV presente no mix foi deletado recentemente. A deleção de um PDV pode causar um disparo desordenado das tarefas, fazendo com que a segmentação não seja respeitada. Para solucionar o problema, é necessário ajustar o template do mix, removendo os PDVs deletados, e reimportá-lo no sistema.
