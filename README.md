# ML модель для имитации дэйттрейдинга акциями Газпром в реальном времени

gazprom_file_v1 - код для создания обучающего набора данных через парсинг стоимости акций.
gazprom_pred_30s_v1 - код обучения модели ML.

## Результаты
Работающая автоматическая парсинговая система.
ML модель, стабильно выходящая в плюс совершая около 60 сделок за день. В зависимости от вероятности повышения или понижения стоимости акции, сумма сделки менялась. К сожалению, комиссия за сделки почти полностью перекрывала полученный профит, однако небольшой "плюс" все ещё оставался, так что проект был успешен.
