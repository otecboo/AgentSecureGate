# AgentSecureGate — рабочие заметки

## Тема диплома (промежуточная)
Разработка интеллектуального модуля обнаружения аномальных цепочек вызовов инструментов
в agent-gateway для защиты от нештатного поведения ИИ-агентов.

## Репозитории
- Форк: https://github.com/otecboo/AgentSecureGate
- Upstream: https://github.com/agentgateway/agentgateway

## Датасеты (кандидаты)
- StepShield — траектории кодовых агентов с метками rogue/not rogue (Apache 2.0)
- GAP Benchmark — 17 420 взаимодействий, случаи "сказал нет, но сделал"
- MCP-SafetyBench — атаки на MCP-серверы
- AgentDojo — бенчмарк prompt injection (для переразметки)

## Ветки
- main — чистая копия upstream
- dev — интеграционная ветка
- feature/* — задачи
- experiment/* — эксперименты

## Полезные ссылки
- OWASP Agentic Top 10 (ASI10 Rogue Agents)
- OWASP MAESTRO
- agentgateway.dev/docs
