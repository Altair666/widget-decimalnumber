# HANDOFF — widget-decimalnumber

## История версий

| Версия | Дата | Изменения |
|--------|------|-----------|
| v0.71 | 2026-07-03 | Возвращены картинки в строки классов: img тег в cls-row через image_file_id → fileAPI URL. fetchAllImagesInBackground теперь вызывает renderBrowse() вместо renderBrowseSummary(). |
| v0.70 | 2026-07-03 | Fix conn bubble: убраны setConn из loadClassifier успешных путей. Диагностические логи для картинок. Fallback через fetch+blob. |
| v0.69 | 2026-07 | Hotfix: guard grist.getUserProfile. |
| v0.68 | 2026-07 | Sidebar «Последние» из S.components. Conn bubble слева внизу. Картинки через image_file_id. |
