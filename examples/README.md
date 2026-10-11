# 示例：给别的 AI / 别的 harness 用的独立角色卡

这个目录是**参考材料**，不是安装产物。

- `cordis.patch.example.yml` —— 一份渲染好的完整声明，用的是占位名字。看它比看模板直观：能一眼看出「渲染完之后长什么样」、`persona` 那一行在整份声明里的位置、以及插件行的排列。**不要直接拿它去装**，用你自己的名字重新生成。
- `AI-INSTALL-PROMPT.md` —— 一段可以直接复制给任何 AI 的安装提示词。

真正要装的东西由生成器产出在仓库根的 `out/` 目录里：

```bash
python generate.py --interactive
```
