# 第三方组件与数据说明

本项目自定义许可仅覆盖权利人原创部分，不修改上游组件、字体、数据与公共领域素材的独立权利。

软件包保留：

- 根目录 `LICENSE.electron.txt` 与 `LICENSES.chromium.html`：Electron、Chromium 及其组件说明。
- `resources/notices/THIRD_PARTY_LICENSES.md`：桌面依赖概览。
- `resources/notices/frontend-licenses/`：按版本收集的前端依赖许可、声明及补充上游文本。
- `resources/backend/_internal/` 中各包的许可与 Python 许可：Python、RDKit、NumPy、FastAPI 等运行时。
- `resources/notices/THIRD_PARTY_DATA_NOTICES.md` 与 `AUTHORITY_DATA_SOURCES.md`：数据库记录、公开学术署名与来源条款。

晶胞库中 170 条真实 CIF 来源于 COD，另有 4 个本地理想母结构；6 个候选仍待确认。COD 数据说明为 CC0；ChEBI 数据采用 CC BY 4.0，PubChem 和 PDB 记录应结合随包来源与上游条款使用。保留原作者、论文、数据库标识与来源，并不意味着其作者认可本软件的教学结论。

补充上游文本的来源和内容哈希随软件包记录。本文件是导航，不替代上游完整条款，也不是法律合规认证。

本次公开桌面构建不带入 `element-closest-polyfill` 与 `intersection-observer` 的旧浏览器兼容实现，改用内置 Chromium 原生 API。依赖清单中的对应条目明确标记为未打入公开构建，不能据 npm 元数据推断它们已随本包分发。
