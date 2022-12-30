# Projeto Empregados - Capítulo: Enumerações e composição
## Desafio proposto
Você deve fazer um programa para ler os dados de um departamento, que inclui seu endereço e seus empregados. Em seguida você deverá mostrar na tela um relatório de
folha de pagamento, conforme exemplos.

Para resolver este problema, você deverá implementar as entidades conforme projeto abaixo. O método payroll() da classe Department é responsável por retornar o
valor total da folha de pagamento do departamento.

![image](https://user-images.githubusercontent.com/88738577/210092813-d4689eab-7751-46d7-b371-249d07ef9833.png)

ATENÇÃO:

Seu programa principal deve manter uma variável para um objeto do tipo Department. Crie um método estático showReport para receber como argumento este objeto 
Department e, a partir dele, exibir todo relatório na tela.

    package application;
    import java.util.Locale;
    import java.util.Scanner;
    import entities.Department;
    
    public class Program {
      public static void main(String[] args) {
          Locale.setDefault(Locale.US);
          Scanner sc = new Scanner(System.in);
          Department dept = new ...
          ...
          showReport(dept);
          sc.close();
      }

      private static void showReport(Department dept) {
        // MOSTRAR NA TELA OS DADOS DO RELATÓRIO
      }
    }

ATENÇÃO:

Para o exemplo dado abaixo, esta é a estrutura de objetos que você deverá criar na memória:

![image](https://user-images.githubusercontent.com/88738577/210093499-bc044336-4c04-4ee5-9ba7-08eb23b5e5a6.png)

---
EXEMPLO: <br>
Nome do departamento: Vendas <br>
Dia do pagamento: 10 <br>
Email: vendas@lojatop.com <br>
Telefone: 99883355 <br>
Quantos funcionários tem o departamento? 2 <br>
Dados do funcionário 1: <br>
Nome: João Silva <br>
Salário: 8000.00 <br>
Dados do funcionário 2: <br>
Nome: Maria Torres <br>
Salário: 10000.00 <br>

*Resultado esperado:* 

FOLHA DE PAGAMENTO: <br>
Departamento Vendas = R$ 18000.00 <br>
Pagamento realizado no dia 10 <br>
Funcionários: <br>
João Silva <br>
Maria Torres <br>
Para dúvidas favor entrar em contato: vendas@lojatop.com <br>

---
## *Realizando teste do código localmente* 
O Windows 10 já possui um programa padrão para visualizar arquivos compactados.

Caso seu sistema operacional seja anterior ao Windos 10, realize o passo abaixo:

Para visualizar o projeto você precisará extrair os arquivos através de um programa para arquivos compactados.

Recomendo Winrar, baixe a versão 32x ou 64x, de acordo com seu sistema.

Link para download:
https://www.win-rar.com/download.html

---
## 📦️ *Como Testar o Código*
Para executar este passo, você tera que ter uma IDE instalada em sua máquina. Utilizei o Eclipse.


Siga o passo a passo abaixo:
```bash
  # Clone o repositório
  ❯ Clique no botão Code, depois em Download ZIP e salve o arquivo.

  # Extrair arquivos sem Winrar
  > Abra a pasta onde o arquivo foi salvo.
  >> Clique com o botão direito sobre o arquivo e selecione
  Extrair Tudo.
  As informações foram extraídas para a pasta Mod4_DesafioOO-4_Composicoes-main.

  # Extrair arquivos com Winrar
  > Abra a pasta onde o arquivo foi salvo.
  >> Clique com o botão direito sobre o arquivo e selecione Extrair Aqui (Extract Here).
  As informações foram extraídas para a pasta Mod4_DesafioOO-4_Composicoes-main.
  
  # Abrir o projeto
  > No Eclipse, clique em *File* e após em *Open Projects from File System...*
  >> Selecione a pasta do projeto e depois clique em *Finish*
  Aguarde a IDE carregar os arquivos e então visualize o código fonte.
  
```

---
## ⚠️ *Erros comuns* ⚠️

No passo *Como Testar o Código*, se não houver a opção *Extrair Tudo*, significa que não há programa instalado para manipulação de arquivos compactados.
Neste cado, seguir com o passo *Realizando teste do código localmente*.

No passo *Abrir o projeto*, após os arquivos serem carregados, pode acontecer de aparecer um X ou um ! vermelho. Caso isso ocorra, tente as soluções deste
tutorial: https://www.youtube.com/watch?v=Je4JWWJcyo0

---
## *Contribuidores* 🔥👊
Este projeto foi desenvolvido durante o curso [Formação Desenvolvedor Moderno](https://devsuperior.com.br/formacao-desenvolvedor-moderno),
sobe orientação do tutor [Nelio Alves](https://www.linkedin.com/in/nelio-alves/?originalSubdomain=br).



