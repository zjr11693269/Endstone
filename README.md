# Endstone
This is endstone plugin
这是一个Minecraft基岩版反作弊插件
ZJRAnticheat
中文
ZJRAnticheat 是面向 Minecraft 基岩版 Endstone 服务端的反作弊与管理插件，当前版本 1.0.45。项目以“减少误判、保留可调查性”为核心：所有检测都可以独立开关、调整阈值和配置违规动作，并提供完整的中文游戏内控制面板。

管理员执行 /ac 即可打开面板，无需记忆子命令。面板支持玩家档案、封禁与解封、检测项开关、违规拉回或踢出、单玩家豁免、在线与离线物品栏打包、日志查询和性能查看。

插件包含移动、战斗、方块交互和协议层检测，并针对基岩版常见行为做了兼容处理，包括创造模式、死亡与重生、船与矿车、鞘翅与激流、重锤范围攻击、荆棘反伤、击退与爆炸位移、上岸与贴墙、传送门切换和中键选取方块。阈值支持按延迟和 TPS 自适应，但保留硬上限。

审计日志、方块记录和玩家攻击/交互记录使用中国标准时间，支持分页、按玩家与时段搜索，以及本地或 DeepSeek、OpenAI、Claude、Gemini、Ollama 等 AI 服务的自然语言查询。方块和实体名称提供中文目录，未知 ID 不会直接显示英文命名空间。

项目包含 154 项自动化测试，使用 Python 3.11+、Endstone 0.11 和 Apache-2.0 许可证。

English
ZJRAnticheat is an anti-cheat and administration plugin for Minecraft Bedrock servers running Endstone, currently at version 1.0.45. The project is built around reducing false positives while keeping every decision auditable: checks can be enabled independently, thresholds are configurable, and violation actions can be selected per check. A complete Chinese in-game control panel is included.

Administrators can open the panel with /ac without memorizing subcommands. The panel covers player profiles, bans and unbans, per-check toggles, setback or kick actions, single-player exemptions, online and offline inventory packaging, log search, and performance monitoring.

The plugin provides movement, combat, block-interaction, and protocol-level checks, with compatibility handling for common Bedrock behavior: creative mode, death and respawn, boats and minecarts, elytra and riptide, mace area attacks, thorns reflection, knockback and explosion movement, shorelines and walls, portal transitions, and middle-click block picking. Thresholds adapt to latency and server TPS within bounded limits.

Audit logs, block records, and player attack/interaction records use China Standard Time and support pagination, player and time-range filtering, and natural-language search through a local parser or optional AI providers such as DeepSeek, OpenAI, Claude, Gemini, and Ollama. Chinese catalogs are bundled for blocks and entities; unknown IDs are not exposed as raw English namespaces.

The project includes 154 automated tests and targets Python 3.11+, Endstone 0.11, and the Apache-2.0 license.
