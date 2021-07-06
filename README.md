# master.github.io
Este repositório é parte do meu projeto de mestrado e inclui a aplicação de modelos preditivos para cinética enzimática. 

O meu projeto de mestrado foi o desenvolvimento de um integrador de tempo e temperatura (TTI) biológico para avaliar processos térmicos de alimentos líquidos. Nele, a enzima fosfatase alcalina em tampão carbonato (alimento modelo), submetida a processamento em um reator de micro-ondas focalizadas, foi utilizada como sensor térmico biológico. Este sensor pode ser utilizado como indicador de segurança - e também de qualidade - alimentar dentro da faixa de temperatura utilizada (abaixo de 100 °C) e desde que em alimentos líquidos com propriedades termo-físicas similares às da solução modelo de carbonato.

Resumidamente, pode-se utilizar este sensor após certificar-se que a termorresistência dele é maior do que a do microrganismo patogênico mais termorresistente do alimento que se deseja submeter a um processo térmico. 

Contudo, testes experimentais estão se tornando cada vez menos frequentes por causa da aplicação de modelos matemáticos. Estes modelos proporcionam menos uso de reagentes, menor tempo de laboratório (e consequentemente menor surgimento de erros) e eficiência preditiva. Por isso, eu utilizei modelos matemáticos presentes na literatura e também desenvolvi alguns modelos utilizando equações diferenciais e redes neurais.

Caso haja interesse, disponibilizo o link de acesso para a minha dissertação: [Dissertação - Lucas Quemelli.](https://www.teses.usp.br/teses/disponiveis/3/3137/tde-10122020-095647/pt-br.php)

# Modelagem preditiva da curva padrão de indofenol

![image](https://user-images.githubusercontent.com/81119854/124672398-5b647f80-de8d-11eb-83ce-02e91de0e7f5.png)

# Dados experimentais do indicador 

![image](https://user-images.githubusercontent.com/81119854/124673528-56083480-de8f-11eb-9d7d-1b9991dfd63b.png)

# Modelagem preditiva utilizando modelo de duas frações (encontrado na literatura)

![image](https://user-images.githubusercontent.com/81119854/124674029-5523d280-de90-11eb-974e-83fe6f072c89.png)

R² = 0.97. A margem de erro utilizada no gráfico de paridade foi de 10 %.

# Dados experimentais do indicador com sacarose

Com intuito de aumentar a resistência térmica do indicador e aumentar a faixa de temperatura para a sua utilização, sacarose foi adicionada à solução modelo.

![image](https://user-images.githubusercontent.com/81119854/124673724-c911ab00-de8f-11eb-973e-cf85c1c9b6ab.png)
![image](https://user-images.githubusercontent.com/81119854/124673940-31608c80-de90-11eb-92b4-ad229f1d8350.png)

# Modelagem preditiva do indicador com sacarose utilizando modelo de duas frações

![image](https://user-images.githubusercontent.com/81119854/124674195-a8962080-de90-11eb-976e-b068613a7052.png)

R² = 0.99. A margem de erro utilizada no gráfico de paridade foi de 10 %.



