### Instalando MySQL no Windows

1. Acesse o site oficial do MySQL: [https://www.mysql.com/](https://www.mysql.com/).

2. Vá até a seção **Downloads**.

3. Baixe a **versão gratuita**:

   - **MySQL Community Edition (GPL)**
   - **MySQL Community Server (GPL)**

4. Baixe o **MySQL Installer for Windows**. Escolha a versão **Offline** (arquivo maior) para garantir que todos os pacotes necessários sejam baixados durante a instalação.

5. Ignore a opção de cadastro clicando em:  
   **No thanks, just start my download**.

6. Durante a instalação, escolha o tipo de instalação:

   - **Setup type**: **Server only**.

7. Na seção de **Configuração**:

   - **Type and Networking**:
     - Selecione **Development Machine**.
     - **Port Number**: 3306 (padrão).

8. Na seção **Account and Roles**:

   - **MySQL Root Password**: defina uma senha para o usuário `root`.

9. Após a instalação, localize o diretório `bin` do MySQL no seu disco local. O caminho geralmente será algo como `C:\Program Files\MySQL\MySQL Server X.X\bin`.

10. Copie o caminho (path) dessa pasta.

11. Clique com o botão direito em **Este PC** (ou **Meu Computador**) e selecione **Propriedades**.

12. Em seguida, clique em **Configurações avançadas do sistema**.

13. Selecione a opção **Variáveis de Ambiente**.

14. Na seção **Variáveis do sistema**, localize e selecione **Path**, depois clique em **Editar**.

15. Clique em **Novo** e cole o caminho do diretório `bin` que você copiou.

16. Clique em **OK**, depois clique em **OK** novamente para finalizar.

Agora, o MySQL estará configurado corretamente no seu sistema e o `bin` estará acessível a partir do terminal.
