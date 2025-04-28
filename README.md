# Key-performance-indicators-of-forecasts-in-RTB-auctions

Это курсовая работа студентки Кузнецовой Виктории НИУ ВШЭ программы "Прикладная математика и информатика".

Тема: Ключевые показатели эффективности прогнозов в RTB-аукционах

Содержимое файлов:

- prepare_data.ipynb, feature_production.ipynb, feature_production_2.ipynb, feature_production_3.ipynb, add_user_tags_to_test.ipynb - подготовка датасета [iPinYou](https://contest.ipinyou.com/) для обучения моделей

- catboost_all_features.ipynb - обучение CatBoost на всех исходных признаках и подсчет значимости признаков для модели
- catboost_selected_features.ipynb -  обучение CatBoost только на самых значимых признаках и подсчет значимости признаков
- mix-features-catboost.ipynb и mix_features_catboost_results.txt - эксперименты по подбору комбинаций признаков для CatBoost с результатами
- course-work-catboost-comb-features-best.ipynb - лучшая версия CatBoost с учетом комбинаций признаков
- hyperparameter_optimization.ipynb и hyperparameters_optimization_results.txt - подбор гиперпараметров для CatBoost с результатами
- папка mix_features_catboost_experiments - эксперименты по подбору комбинаций признаков для повышения качетсва CatBoost

- simple_net_all_features.ipynb - обучение простейшей нейронной сети на всех исходных признаках и подсчет значимости признаков для модели
- simple_net_select_features.ipynb - обучение простейшей нейронной сети на самых значимых признаках для CatBoost и подсчет значимости признаков
- simple_net_mix_features.ipynb - обучение простейшей нейронной сети с учетом лучших комбинаций признаков для CatBoost и подсчет значимости признаков

- dropout_net_all_features.ipynb - обучение нейронной сети с регуляризацией dropout и batchnorm на всех исходных признаках и подсчет значимости признаков для модели
- dropout_net_select_features.ipynb - обучение нейронной сети с регуляризацией dropout и batchnorm на самых значимых признаках для CatBoost и подсчет значимости признаков
- dropout_net_mix_features.ipynb - обучение нейронной сети с регуляризацией dropout и batchnorm с учетом лучших комбинаций признаков для CatBoost и подсчет значимости признаков

- wide_deep_net_all_features.ipynb - обучение нейронной сети Wide&Deep на всех исходных признаках и подсчет значимости признаков для модели
- wide_deep_net_select_features.ipynb - обучение нейронной сети Wide&Deep на самых значимых признаках для CatBoost и подсчет значимости признаков
- wide_deep_net_mix_features.ipynb - обучение нейронной сети Wide&Deep с учетом лучших комбинаций признаков для CatBoost и подсчет значимости признаков
