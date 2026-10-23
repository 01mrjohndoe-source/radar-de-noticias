
# Web Monitor Robot

Automação de monitoramento de páginas web com Robot Framework
e Browser Library (Playwright).

## Funcionalidades

- Lista configurável de URLs
- Validação de elementos e textos
- Timeout por elemento
- Registro de falhas por página
- Execução contínua em ciclos
- Fechamento do navegador ao final de cada ciclo

## Executar

Ative o ambiente virtual e execute:

python -m robot --outputdir results tests/monitor.robot

Interrompa com Ctrl+C.

rodar o dashboard
python -m streamlit run dashboard.py