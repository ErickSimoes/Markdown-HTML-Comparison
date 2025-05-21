# WeatherCLI

Um utilitário de linha de comando escrito em Python que exibe a previsão do tempo para qualquer cidade em poucos segundos.

## Características

- Consulta rápida à API OpenWeatherMap  
- Suporte a unidades métricas e imperiais  
- Cache local para reduzir requisições repetidas  
- Saída colorida para melhor leitura no terminal  

## Instalação

```bash
git clone https://github.com/usuario/weathercli.git
cd weathercli
pip install -r requirements.txt
```

## Uso

```bash
python weather.py Recife --dias 3 --unidade metric
```

Argumento|Descrição
---------|----------
`cidade` | Nome da cidade (ex.: **Recife**)
`--dias` | Número de dias de previsão (padrão: 1)
`--unidade` | `metric` para °C ou `imperial` para °F

## Contribuindo

1. Abra um _fork_ do projeto  
2. Crie uma _branch_: `git checkout -b feature/nova-funcionalidade`  
3. Faça _commit_ das mudanças: `git commit -m 'Add nova funcionalidade'`  
4. Faça _push_: `git push origin feature/nova-funcionalidade`  
5. Envie um _pull request_

## Licença

Distribuído sob a licença MIT. Veja `LICENSE` para mais informações.
