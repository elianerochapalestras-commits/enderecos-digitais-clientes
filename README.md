# Endereços Digitais - Clientes

Pasta única que reúne os mini-sites individuais de clientes do produto Endereço Digital (Eliane Rocha).

Cada cliente fica em sua própria subpasta (ex: /aline). O arquivo vercel.json faz o domínio de cada cliente apontar para a subpasta correta, sem precisar de um projeto Vercel separado por cliente.

Para adicionar um novo cliente:
1. Criar uma nova subpasta com o nome do cliente (ex: /roberta) contendo o index.html do site dele.
2. Adicionar duas novas entradas no vercel.json (domínio e www), apontando para essa subpasta.
3. Adicionar o domínio do cliente nas configurações do projeto na Vercel.
