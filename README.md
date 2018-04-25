## Datacoper - Redmine Plugin - Anexos do Progress

Este plugin permite listar os arquivos das pastas do Servidor.

## Funcionalidades

1. Apresentar
    - Nome do Arquivo
    - Usuário que criou o arquivo
    - Data de ultima alteração
    - Tamanho
    - Extensão

2. Filtros
   - Por data
   - Por usuário
   - Por extensão
   - Por nome

## Installation notes

1. Baixe a ultima versão do plugin [ultima versão](https://carlosjustino.github.io/redmine-fntprogress/releases/latest).
2. Extraia dentro da pasta `<redmine_path>/plugins`. O resultado deve ser `<redmine_path>/plugins/fntprogress`.
3. Executar a migração do banco.
   
   `bundle exec rake redmine:plugins:migrate`
   
4. Reinicie o Redmine.

Agora você conseguira ver o plugin na lista no caminho _Administration -> Plugins_ e poderá configura-lo.

Informações sobre Instalar e Desinstalar plugins no Redmine pore ser encontrado em [Redmine Plugins page](http://www.redmine.org/projects/redmine/wiki/Plugins).

### Compatibility ###

- Redmine 3.0
