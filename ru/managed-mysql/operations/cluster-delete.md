# Удаление кластера

{% include [backups-stored](../../_includes/mdb/backups-stored.md) %}

{% list tabs %}

- Консоль управления
  
  1. Откройте страницу каталога в консоли управления.
  1. Выберите сервис **{{ mmy-name }}**.
  1. Нажмите значок ![image](../../_assets/options.svg) для нужного кластера и выберите пункт **Удалить**.

- CLI
  
  {% include [cli-install](../../_includes/cli-install.md) %}
  
  {% include [default-catalogue](../../_includes/default-catalogue.md) %}
  
  Чтобы удалить кластер, выполните команду:
  
  ```
  $ yc managed-mysql cluster delete <имя или идентификатор кластера>
  ```
  
  Идентификатор и имя кластера можно запросить со [списком кластеров в каталоге](#list-clusters).
  
{% endlist %}


