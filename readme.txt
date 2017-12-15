
Descrição:
    Conjunto de script bash no intuito de facilitar alguns resultados não
    encontrados diretamente no conjunto de comando bash padrão.
 
    sbenv      Contém informações básica do ambiente de trabalho do grupo de
               scripts, assim como funções básicas de uso comum neste pacote.
    fe         Verifica a existêncio do arquivo solicitado.
               Este script resolve problemas nativos gerados por 'ls'.
    fls        O mesmo que 'ls', mas sem reconhecer diretórios.
               Evita o erro de quando não há arquivos no diretório.
    scutup     Retorna a string contida após a última incidência do
               delimitador.
    scuttail   Tem ação inversa a 'scutup'.
    ssube      Verifica se existe a sub-string indicada.
    schsub     Substitui uma sub-string por outra.
    sbackslash Acrescenta uma contra-barra antes de caracteres extendidos.
 	
Obs.: Para mais detalhes usar o argumento '-h' ou '--help' junto a qualquer
      script.
 
Versões:
 
06/08/2016
 
- O script 'installscript' agora proporciona a instalação de todos os scripts
  do pacote, para isto basta que estejam listados no arquivo 'scripslist'.
- Foram feitos ajustes no texto de ajuda.
- Foi incluido o script 'sbenv', o qual retorna os caminhos dos quais o
  conjunto de script dependem.
