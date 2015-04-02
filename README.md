# getValuesFromPanel
Classe que pega os valores do Campos de um JPanel e insere automaticamente nos atributos de uma classe pelos metodos "Setters" facilitando e agilizando o desenvolvimento de aplicações Swing

# Utilizando
<code>
//Instancia a Classe getValuesFromPanel
getValuesFromPanel p = new getValuesFromPanel();
//esta é a classe de modelo que receberá os valores dos campos
MyClasse mc = new MyClasse();
//Passa como parâmetro o JPanel que contem os componentes, e o nome da Classe que instanciada acima, 
//no nosso caso MyClasse que contem os metodos getter e setters.
mc = (MyClasse) p.pega(this.myJPanel, "MyClasse");
</code>

OBS.: O ATRIBUTO NAME DE CADA CAMPO(COMPONETE) DEVE ESTAR COM O MESMO NOME DO ATRIBUTO DA CLASSE.

# Projeto
Esta classe ainda pode ser melhorada, trata apenas de 3 Components diferentes, JTextField, JTextArea e JRadioButton, em breve será atualizada para novos componentes.

obs.: Esta classe ja esta sendo desenvolvida para Android, posteriormente estarem disponibilizando a classe em meu repositório.

Dúvidas ou críticas são aceitas.
email: contato@aldairnatan.com
