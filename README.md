# Automatizar_Emissao_de_Nota_Fiscal

💡 Automação de Emissão de Notas Fiscais com Selenium e Python
Este projeto utiliza Python com Selenium WebDriver para automatizar o preenchimento e emissão de notas fiscais a partir de uma planilha Excel.

📌 Funcionalidades
Acesso automático a uma página de login local
Preenchimento de formulário baseado em dados de um Excel
Emissão automatizada de notas fiscais para vários clientes
Configuração de download direto de arquivos
Controle e interação com o navegador Google Chrome
🛠️ Tecnologias Utilizadas
Python 3.x
Selenium WebDriver
WebDriver Manager
Pandas
Google Chrome + ChromeDriver
⚙️ Como Funciona
O navegador é configurado para baixar arquivos automaticamente;
O sistema acessa uma página de login local (login.html);
Preenche login e senha automaticamente;
Lê uma planilha (NotasEmitir.xlsx) com os dados dos clientes;
Para cada linha da planilha, preenche o formulário HTML da nota fiscal;
Clica no botão "Emitir" e recarrega a página para o próximo registro;
Ao fim do processo, o navegador é encerrado automaticamente.
📘 Principais Comandos e Funções
Comando	Descrição
from ... import ...	Importa partes específicas de bibliotecas
webdriver.Chrome()	Inicia uma instância do navegador Chrome
send_keys()	Simula a digitação de um texto em campos de formulário
find_element(By.X, valor)	Localiza um elemento da página (por XPATH, NAME, etc.)
click()	Simula um clique em um botão
pd.read_excel()	Lê uma planilha Excel usando Pandas
for linha in tabela.index:	Loop que percorre todas as linhas da planilha
navegador.refresh()	Atualiza a página atual
quit()	Encerra e fecha o navegador totalmente
🧾 Exemplo de uso
Verifique se os arquivos login.html e NotasEmitir.xlsx estão na mesma pasta do script
Execute o script com python script.py
Acompanhe o navegador automatizando o preenchimento das notas fiscais
🧑‍💻 Desenvolvido por Rogério (rogeriothelast)
📍 São Paulo - SP | 🌐 Apaixonado por automações e soluções inteligentes
📫 E-mail: rogeriothelast@gmail.com
📱 WhatsApp: (11) 95215-0048
🔗 GitHub: github.com/Rogeriosil
