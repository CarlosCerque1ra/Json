## Manipulação de JSON em PHP

1. **`file_get_contents("Dados.json")`**
   - Lê o conteúdo do arquivo JSON.

2. **`json_decode(..., true)`**
   - Converte o JSON para um array em PHP.

3. **`is_array($dados)`**
   - Garante que a variável `$dados` seja um array válido.

4. **`$_POST["nome"]` e `$_POST["Idade"]`**
   - Captura dados do formulário.

5. **`$dados[] = $novo_dado`**
   - Adiciona o novo dado à array existente.

6. **`json_encode($dados, JSON_PRETTY_PRINT)`**
   - Converte o array PHP de volta para o formato JSON, com formatação legível.

7. **`file_put_contents("dados.json", ...)`**
   - Salva o novo JSON no arquivo.

