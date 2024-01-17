# Statistic_A-B_testing

## Описание проекта
Данный проект осуществляет анализ результатов A/B теста, проведенного в крупном дейтинговом приложении. В рамках теста была изменена стоимость премиум-подписки для новых пользователей из нескольких стран при покупке через две новые платежные системы. Целью исследования является определение успешности эксперимента в целом.

## Библиотеки
Для выполнения проекта были использованы следующие библиотеки Python:
- pandas
- numpy
- matplotlib
- seaborn
- scipy.stats
- pingouin

## Выводы
На основании проведенного анализа результатов A/B теста в дейтинговом приложении можно сделать следующие выводы:
- Конверсия в покупку новых пользователей тестовой группы снизилась в среднем на 15% по сравнению с контрольными группами. Вероятность того, что конверсия в тестовой группе будет хуже, чем в контрольных группах, составляет 93.5%. Тест Хи-квадрат не показал значимых различий в конверсии между тестовой и контрольными группами.
- В тестовой группе наблюдается увеличение среднего дохода на одного платящего пользователя (ARPPU) в среднем на 41.5%. Вероятность того, что ARPPU в тестовой группе будет хуже, чем в контрольных группах составляет 11.4%. Также в тестовой группе наблюдается увеличение среднего дохода на пользователя в целом (ARPU) в среднем на 20.6%. Вероятность того, что ARPU в тестовой группе будет хуже, чем в контрольных группах, составляет 28%. Результаты бутстрепа показали, что значения p-value для ARPPU, ARPU превышают уровень значимости 0.05, значит нет статистически значимых различий между тестовой и контрольными группами.
- Изменение стоимости премиум-подписки не оказало статистически значимого влияния на конверсию, однако привело к увеличению среднего дохода на пользователя. Эксперимент можно считать частично успешным, так как удалось увеличить доход, но не удалось улучшить конверсию.
На основе проведенного анализа можно предложить следующие рекомендации для бизнеса:
- Проанализировать причины снижения конверсии в тестовой группе и идентифицировать возможные проблемы или барьеры, которые могут отталкивать новых пользователей от покупки премиум-подписки. Рекомендуется провести дополнительное исследование пользовательского опыта и провести A/B тестирование с различными вариантами предложений и маркетинговых стратегий, чтобы определить наиболее эффективные способы увеличения конверсии.
- Продолжить мониторинг и анализ ARPPU и ARPU в долгосрочной перспективе, чтобы убедиться, что увеличение дохода является стабильным и не является временным эффектом. Также можно рассмотреть возможности для дальнейшего увеличения ARPPU и ARPU, например, путем предложения дополнительных премиум-функций или улучшения пользовательского опыта.
- Проанализировать результаты эксперимента с новыми платежными системами и оценить их эффективность и удобство для пользователей. Если новые платежные системы не привели к значимым изменениям в метриках, можно рассмотреть возможность внедрения других платежных систем или улучшения существующих, чтобы обеспечить удобство и безопасность для пользователей.  

