# mle-template-case-sprint2

Добро пожаловать в репозиторий-шаблон Практикума для проекта 2 спринта. Ваша цель — улучшить ключевые метрики модели для предсказания стоимости квартир Яндекс Недвижимости.

Полное описание проекта хранится в уроке «Проект. Улучшение baseline-модели» на учебной платформе.

Здесь укажите имя вашего бакета:
student-mle-20250130-582c662a4e 

## Инструкция по поднятию MLFlow-сервисов и регистрации модели.
1. MLFlow и все сервисы поднимаются командой - ./mlflow_server/run_mlflow_server.sh
   Сам sh-файл лежит в папке mlflow_server.
2. Ноутбук с регистрацией модели, а также pickle-файл самой модели лежат в папке .mlflow_server/  estate_prediction_model_artifacts

## Ссылки на артефакты в MLFlow
EXPERIMENT_NAME = 'logging_base_model_mmakarov'
RUN_NAME = 'stage_1'
REGISTRY_MODEL_NAME = 'price_prediction'
Run ID = 1285f129b1f5463f8a57bf0db5e4f442

## Этап 2
EXPERIMENT_NAME = 'EDA_mmakarov_2_sprint'
RUN_NAME = 'EDA_run'
REGISTRY_MODEL_NAME = 'price_prediction'
Run ID = f0607b7bb0254a90863a3e9a5cee2d80

## Этап 3
EXPERIMENT_NAME = 'feature_engineering_mmakarov_2_sprint'
RUN_NAME = "feature_engineering_run"
REGISTRY_MODEL_NAME = 'price_prediction'
Run ID = d46b77b4850a4d6392ba72e33029b8dc

## Этап 4
EXPERIMENT_NAME = 'feature_selection_mmakarov_2_sprint'
RUN_NAME = 'feature_selection_run'
REGISTRY_MODEL_NAME = 'price_prediction'
Run ID = b74f9b4f5e074b13aadffdb8dba1c7e9

## Этап 5
EXPERIMENT_NAME = 'find_params_price_prediction'
RUN_NAME = 'model_bayesian_search'
REGISTRY_MODEL_NAME = 'price_prediction'
Run ID = a90519a1eb93449f94559cbaa12ecae4

EXPERIMENT_NAME = 'find_params_RS'
RUN_NAME = 'find_params_RS'
REGISTRY_MODEL_NAME = 'price_prediction'
Run ID = 305554937c8b4c0aba4c5a8879e61357