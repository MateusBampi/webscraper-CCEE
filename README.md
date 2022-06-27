# Webscraper para dados de segurança de mercado da CCEE
#### Criador: [Mateus Furlin Bampi](https://github.com/MateusBampi) & Tiago Sepulveda

---

### Resumo

O projeto foi desenvolvido com a ideia de extrair os dados de segurança de mercado da página da CCEE que utiliza o tableau. É necessário extrair um arquivo por empresa, um por vez (a lista de empresas encontra-se no arquivo .csv ~2000 empresas). Como o tamanho e a posição da janela dos arquivos se altera, utilizamos a biblioteca pyautogui para localizar as imagens na tela e adicionar um percetual de confiança para que o algoritmo fosse capaz de detectar onde deveria clicar na tela.

As imagens que devem ser detectadas estão no arquivo .zip e devem ser descompactadas na mesma pasta do arquivo .py.

Uma vez que o script faça o download de toda a base, o arquivo 'Concatenar Dados.xlsm' concatena todas as informações em um único arquivo e faz o tratamento dos dados.
