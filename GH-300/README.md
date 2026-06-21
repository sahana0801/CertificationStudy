# 📚 GH-300 GitHub Copilot Certification — Study Guide & Practice Exam

> **Mục tiêu:** Học 1 buổi tối, mai đi thi pass.
> **Tổng:** 70 câu hỏi trắc nghiệm (7 domains × 10 câu)
> **Thời gian thi thực tế:** ~65 phút | **Điểm đạt:** 700/1000

---

## 📊 Tổng quan 7 Domains

| # | Domain | Tỷ lệ | Số câu |
|---|--------|-------|--------|
| 1 | Responsible AI | 7% | 5 |
| 2 | GitHub Copilot Plans & Features | 31% | 22 |
| 3 | How Copilot Works & Handles Data | 15% | 10 |
| 4 | Prompt Crafting & Prompt Engineering | 9% | 7 |
| 5 | Developer Use Cases for AI | 14% | 10 |
| 6 | Testing with GitHub Copilot | 9% | 7 |
| 7 | Privacy Fundamentals & Context Exclusions | 15% | 10 |

---

## Domain 1: Responsible AI (7%)

### Câu 1
**Q:** GitHub Copilot được phát triển theo nguyên tắc Responsible AI nào?
- A) Fairness, Privacy, Accountability, Transparency
- B) Speed, Accuracy, Scalability, Security
- C) Cost, Performance, Reliability, Usability
- D) Openness, Freedom, Equality, Justice

**✅ A)** — GitHub cam kết với Responsible AI principles: fairness (công bằng), privacy (quyền riêng tư), accountability (trách nhiệm giải trình), transparency (minh bạch).

### Câu 2
**Q:** Tính năng nào trong GitHub Copilot giúp chặn nội dung độc hại (toxic) được tạo ra?
- A) Code review filter
- B) Toxicity filter
- C) Content exclusion
- D) Duplication detection

**✅ B)** — Toxicity filter lọc và chặn các nội dung độc hại, phân biệt chủng tộc, giới tính không phù hợp.

### Câu 3
**Q:** Khi GitHub Copilot tạo code giống public code, điều gì xảy ra nếu bật duplication detection filter?
- A) Code bị block hoặc cảnh báo
- B) Code tự động được include
- C) Code được lưu vào cache
- D) Code được gửi về GitHub để kiểm tra

**✅ A)** — Duplication detection filter phát hiện và chặn/block suggestions trùng với public code trên GitHub.

### Câu 4
**Q:** Nguyên tắc nào yêu cầu developer phải review code do Copilot tạo ra trước khi sử dụng?
- A) Code first
- B) Responsible AI — con người phải giám sát AI output
- C) Trust the AI
- D) Auto-accept

**✅ B)** — Responsible AI đòi hỏi con người luôn review và chịu trách nhiệm với code output từ AI.

### Câu 5
**Q:** Đâu là mục tiêu chính của Responsible AI trong GitHub Copilot?
- A) Tạo code nhanh nhất có thể
- B) Đảm bảo AI an toàn, đáng tin cậy, và có đạo đức
- C) Thay thế hoàn toàn developer
- D) Tối ưu performance code

**✅ B)** — Mục tiêu là đảm bảo AI systems are safe, trustworthy, and ethical.

---

## Domain 2: GitHub Copilot Plans & Features (31% — NẶNG NHẤT)

### Câu 6
**Q:** Plan nào cho phép content exclusions và audit logs?
- A) Copilot Free
- B) Copilot Individual
- C) Copilot Business hoặc Enterprise
- D) Tất cả các plan

**✅ C)** — Content exclusions và audit logs là org-level governance features, chỉ có trong Business/Enterprise.

### Câu 7
**Q:** GitHub Copilot Enterprise bao gồm những gì?
- A) Chỉ có Copilot Chat
- B) Mọi thứ trong Copilot Business + codebase personalization
- C) Chỉ có code completion
- D) Chỉ có CLI agent

**✅ B)** — Enterprise bao gồm toàn bộ Business features + khả năng personalize bằng codebase của tổ chức.

### Câu 8
**Q:** Agent Mode trong GitHub Copilot cho phép điều gì?
- A) Chỉ gợi ý code
- B) Tự động thực hiện multi-step tasks, delegate sub-agents, sử dụng MCP
- C) Chỉ chat
- D) Chỉ review PR

**✅ B)** — Agent Mode cho phép Copilot tự động hoàn thành nhiều bước, delegate sub-agents, và kết nối MCP servers.

### Câu 9
**Q:** Đây là câu hỏi về Edit Mode. Edit Mode trong Copilot cho phép gì?
- A) Chỉ xem code
- B) Chỉnh sửa file trực tiếp với multi-file edits qua natural language
- C) Chỉ tạo file mới
- D) Chỉ xóa code

**✅ B)** — Edit Mode cho phép chỉnh sửa nhiều file cùng lúc thông qua natural language instructions.

### Câu 10
**Q:** Copilot CLI hỗ trợ tính năng nào sau đây?
- A) Chỉ code completion
- B) Plan mode, Autopilot mode, parallel sub-agents (Explore, Task, Code Review, Plan)
- C) Chỉ chat
- D) Chỉ tạo tests

**✅ B)** — Copilot CLI mới (2026) hỗ trợ Plan mode, Autopilot mode, và parallel specialized sub-agents.

### Câu 11
**Q:** Để delegate task từ CLI, lệnh nào được sử dụng?
- A) `/run`
- B) `/delegate` hoặc prefix `&`
- C) `/send`
- D) `/task`

**✅ B)** — Dùng `/delegate TASK-DESCRIPTION` hoặc prefix `&` để delegate task cho Copilot CLI agent.

### Câu 12
**Q:** MCP (Model Context Protocol) trong Copilot cho phép:
- A) Chỉ dùng local context
- B) Kết nối Copilot với external data sources và tools
- C) Chỉ dùng GitHub data
- D) Không có tính năng này

**✅ B)** — MCP servers cho phép Copilot truy cập external resources mà không cần chuyển context.

### Câu 13
**Q:** GitHub Copilot có thể tương tác với những issue tracking nào?
- A) Chỉ GitHub Issues
- B) GitHub Issues, Azure Boards, Jira, Raycast, Linear
- C) Chỉ Jira
- D) Không tích hợp issue tracking

**✅ B)** — Copilot agents có thể nhận tasks từ nhiều issue tracking platforms.

### Câu 14
**Q:** Copilot for Pull Requests hỗ trợ điều gì?
- A) Chỉ tạo PR title
- B) Tạo PR description, review code, suggest changes
- C) Chỉ merge PR
- D) Chỉ tạo PR từ template

**✅ B)** — Copilot hỗ trợ tạo PR description, code review, và suggest changes.

### Câu 15
**Q:** Sự khác biệt chính giữa Copilot Individual và Copilot Business là gì?
- A) Individual nhanh hơn
- B) Business có org-level governance, content exclusions, audit logs
- C) Individual có nhiều tính năng hơn
- D) Không có khác biệt

**✅ B)** — Business thêm org-level governance features như content exclusions, audit logs.

### Câu 16
**Q:** GitHub Copilot Pro+ plan mới (2026) bao gồm:
- A) Chỉ có code completion
- B) Premium requests, models từ Anthropic/Google/OpenAI, next edit suggestions
- C) Chỉ có chat
- D) Chỉ có CLI

**✅ B)** — Pro+ bao gồm premium requests, models từ nhiều providers, next edit suggestions.

### Câu 17
**Q:** Copilot code review agent có khả năng:
- A) Chỉ format code
- B) Review code, identify security vulnerabilities, suggest improvements
- C) Chỉ check syntax
- D) Chỉ rename variables

**✅ B)** — Copilot code review agent giúp review code, phát hiện lỗi bảo mật, đề xuất cải thiện.

### Câu 18
**Q:** Để tắt telemetry data trong Copilot, ta cần:
- A) Không thể tắt
- B) Cấu hình trong settings (Copilot settings → telemetry)
- C) Xóa Copilot
- D) Dùng CLI flag

**✅ B)** — Có thể cấu hình telemetry trong Copilot settings.

### Câu 19
**Q:** Copilot Chat hoạt động trong những môi trường nào?
- A) Chỉ VS Code
- B) VS Code, JetBrains IDEs, Visual Studio, CLI, GitHub Mobile
- C) Chỉ CLI
- D) Chỉ web browser

**✅ B)** — Copilot Chat hoạt động trong nhiều IDEs và CLI.

### Câu 20
**Q:** Tính năng "next edit suggestions" trong Copilot là gì?
- A) Gợi ý code tiếp theo dựa trên context hiện tại
- B) Gợi ý chỉnh sửa tiếp theo sau khi bạn edit code
- C) Gợi ý refactor
- D) Gợi ý tạo file mới

**✅ B)** — Next edit suggestions dựa trên edit hiện tại để gợi ý các chỉnh sửa tiếp theo.

### Câu 21
**Q:** Custom instructions trong Copilot cho phép:
- A) Chỉ thay đổi màu theme
- B) Cung cấp project-specific guidelines để Copilot tuân theo khi generate code
- C) Chỉ rename variables
- D) Chỉ format code

**✅ B)** — Custom instructions cho phép định nghĩa project-specific coding guidelines.

### Câu 22
**Q:** GitHub Copilot cloud agent có thể:
- A) Chỉ chạy local
- B) Tự động nhận GitHub Issues, thực hiện tasks, tạo PR
- C) Chỉ chat
- D) Chỉ review code

**✅ B)** — Cloud agent có thể nhận issues, tự động implement và tạo PR.

---

## Domain 3: How Copilot Works & Handles Data (15%)

### Câu 23
**Q:** GitHub Copilot sử dụng phương pháp nào để tạo code suggestions?
- A) Chỉ zero-shot learning
- B) Zero-shot, one-shot, và few-shot learning
- C) Chỉ deep learning
- D) Chỉ rule-based

**✅ B)** — Copilot sử dụng zero-shot, one-shot, và few-shot learning approaches.

### Câu 24
**Q:** Context window của Copilot được xử lý như thế nào?
- A) Chỉ dùng file hiện tại
- B) Thu thập context từ file hiện tại, project structure, imports, và open files
- C) Chỉ dùng clipboard
- D) Không cần context

**✅ B)** — Copilot thu thập context từ nhiều nguồn: active file, project structure, imports, open files.

### Câu 25
**Q:** Khi bạn gõ code, Copilot xử lý prompt như thế nào?
- A) Gửi toàn bộ codebase lên server
- B) Xây dựng prompt từ context hiện tại, gửi lên model, nhận suggestion
- C) Chỉ dùng local cache
- D) Không xử lý gì

**✅ B)** — Copilot xây dựng prompt từ context, gửi lên model API, nhận về code suggestion.

### Câu 26
**Q:** Dữ liệu telemetry của Copilot được dùng để làm gì?
- A) Train model công khai
- B) Cải thiện sản phẩm, không để train public model
- Bán cho bên thứ ba
- D) Không thu thập telemetry

**✅ B)** — Telemetry được dùng để cải thiện sản phẩm, KHÔNG để train public models.

### Câu 27
**Q:** Suggestion matching public code filter được bật/tắt ở đâu?
- A) Không thể thay đổi
- B) Copilot settings → "Suggestions matching public code"
- C) Chỉ trong config file
- D) Chỉ admin có thể

**✅ B)** — Có thể bật/tắt trong Copilot settings.

### Câu 28
**Q:** Copilot xử lý dữ liệu như thế nào khi bật public code filter?
- A) Gửi tất cả code lên GitHub
- B) So sánh suggestions với public code, block nếu trùng
- C) Không làm gì
- D) Chỉ log lại

**✅ B)** — Filter so sánh suggestions với public code database, block suggestions trùng.

### Câu 29
**Q:** Giới hạn context của Copilot có ảnh hưởng thế nào đến chất lượng suggestions?
- A) Không ảnh hưởng
- B) Context ít → suggestions kém chính xác hơn; nhiều context → tốt hơn
- C) Context nhiều luôn tốt
- D) Chỉ phụ thuộc vào model

**✅ B)** — Context nhiều giúp Copilot hiểu rõ hơn → suggestions chính xác hơn.

### Câu 30
**Q:** Copilot sử dụng model nào để tạo code?
- A) Chỉ GPT-4
- B) Nhiều models khác nhau (OpenAI, Anthropic, Google) tùy plan và cấu hình
- C) Chỉ Claude
- D) Chỉ Gemini

**✅ B)** — Copilot hỗ trợ nhiều models từ nhiều providers (OpenAI, Anthropic, Google).

### Câu 31
**Q:** Khi Copilot không thể tạo suggestion, nguyên nhân có thể là:
- A) Context quá nhiều
- B) Không đủ context, code quá phức tạp, hoặc filter đã block
- C) Luôn luôn có suggestion
- D) Chỉ lỗi mạng

**✅ B)** — Nhiều nguyên nhân: thiếu context, code phức tạp, hoặc filter chặn.

### Câu 32
**Q:** Dữ liệu code của bạn có được dùng để train Copilot model không?
- A) Luôn luôn
- B) Không, code không được dùng để train public models (với Business/Enterprise)
- C) Chỉ khi bật telemetry
- D) Chỉ free plan

**✅ B)** — Với Business/Enterprise, code KHÔNG được dùng để train public models.

---

## Domain 4: Prompt Crafting & Prompt Engineering (9%)

### Câu 33
**Q:** Prompt engineering trong Copilot là gì?
- A) Viết code bằng tiếng Anh
- B) Viết clear, contextual prompts để hướng dẫn Copilot tạo code tốt hơn
- C) Chỉ gõ tên function
- D) Không cần prompt

**✅ B)** — Prompt engineering là nghệ thuật viết prompts rõ ràng, có context để Copilot hiểu đúng ý đồ.

### Câu 34
**Q:** Cách nào sau đây là best practice cho prompt engineering với Copilot?
- A) Gõ "viết code" và chờ
- B) Cung cấp context cụ thể: tên function, parameters, expected behavior, ví dụ
- C) Gõ càng ngắn càng tốt
- D) Không cần mô tả gì

**✅ B)** — Prompt càng cụ thể với context rõ ràng → Copilot hiểu càng đúng.

### Câu 35
**Q:** Khi Copilot tạo code không đúng ý, bạn nên làm gì?
- A) Chấp nhận và sử dụng
- B) Refine prompt: thêm context, ví dụ, rõ ràng hơn
- C) Tắt Copilot
- D) Viết tay luôn

**✅ B)** — Iterative refinement: thêm context, ví dụ, làm rõ prompt cho đến khi đúng.

### Câu 36
**Q:** Comment trong code giúp Copilot như thế nào?
- A) Không có tác dụng
- B) Comment cung cấp context giúp Copilot hiểu intent → suggestions tốt hơn
- C) Chỉ làm code dài hơn
- D) Chỉ dễ đọc cho con người

**✅ B)** — Comments = natural language context → Copilot dễ hiểu intent hơn.

### Câu 37
**Q:** Để Copilot tạo một Python function hoàn chỉnh, prompt tốt nhất là:
- A) "viết function"
- B) "Write a Python function called `calculate_average` that takes a list of numbers and returns the average. Handle empty list edge case."
- C) "code please"
- D) "function"

**✅ B)** — Prompt cụ thể với tên function, parameters, behavior, và edge cases → kết quả tốt nhất.

### Câu 38
**Q:** File structure và imports giúp Copilot như thế nào?
- A) Không ảnh hưởng
- B) Giúp Copilot hiểu dependencies và context → suggestions phù hợp hơn
- C) Chỉ ảnh hưởng performance
- D) Chỉ dùng cho TypeScript

**✅ B)** — Imports và file structure cung cấn context về dependencies → Copilot suggest đúng libraries.

### Câu 39
**Q:** Khi dùng Copilot Chat, cách đặt câu hỏi nào hiệu quả nhất?
- A) "làm cho code chạy được"
- B) "Tôi cần function X với input Y, output Z. Đây là code hiện tại: [code]. Hãy suggest cách cải thiện."
- C) "sửa hết bugs"
- D) "viết lại hết"

**✅ B)** — Cung cấn context cụ thể, input/output, code hiện tại → Copilot đưa ra suggestion chính xác.

---

## Domain 5: Developer Use Cases for AI (14%)

### Câu 40
**Q:** Copilot phù hợp nhất cho use case nào sau đây?
- A) Chỉ viết documentation
- B) Code generation, refactoring, testing, documentation, debugging
- C) Chỉ debug
- D) Chỉ format code

**✅ B)** — Copilot hỗ trợ nhiều use cases: generate code, refactor, test, docs, debug.

### Câu 41
**Q:** Khi dùng Copilot để học ngôn ngữ mới, cách hiệu quả nhất là:
- A) Copy code từ StackOverflow
- B) Dùng Copilot Chat để giải thích code, hỏi về syntax, và thử nghiệm
- C) Không dùng Copilot
- D) Chỉ đọc docs

**✅ B)** — Copilot Chat giúp giải thích code, hỏi syntax, thử nghiệm → học nhanh hơn.

### Câu 42
**Q:** Copilot hỗ trợ code review như thế nào?
- A) Chỉ format code
- B) Identify security vulnerabilities, suggest improvements, detect bugs
- C) Chỉ rename variables
- D) Chỉ check indentation

**✅ B)** — Copilot code review giúp phát hiện lỗi bảo mật, đề xuất cải thiện, detect bugs.

### Câu 43
**Q:** Boilerplate code generation với Copilot là:
- A) Không khả thi
- B) Viết mô tả ngắn → Copilot tạo repetitive code patterns
- C) Chỉ dễ với JavaScript
- D) Cần viết tay hoàn toàn

**✅ B)** — Copilot rất giỏi tạo boilerplate code từ mô tả ngắn.

### Câu 44
**Q:** Khi refactor legacy code với Copilot, nên làm gì?
- A) Refactor toàn bộ cùng lúc
- B) Refactor từng phần nhỏ, dùng Copilot Chat để giải thích và suggest
- C) Không refactor
- D) Viết lại từ đầu

**✅ B)** — Refactor incremental, dùng Copilot Chat để hiển code cũ và suggest improvements.

### Câu 45
**Q:** Copilot hỗ trợ data science tasks như thế nào?
- A) Không hỗ trợ
- B) Tạo SQL queries, data visualization code, pandas operations
- C) Chỉ tạo charts
- D) Chỉ tạo CSV files

**✅ B)** — Copilot giúp viết SQL, pandas code, data visualization.

### Câu 46
**Q:** Khi dùng Copilot để tạo documentation:
- A) Không thể
- B) Mô tả function/class → Copilot tạo docstrings, README, comments
- C) Chỉ tạo inline comments
- D) Chỉ format markdown

**✅ B)** — Copilot có thể tạo docstrings, README, và comments từ mô tả.

### Câu 47
**Q:** Translation giữa các ngôn ngữ lập trình với Copilot:
- A) Không hỗ trợ
- B) Dùng Copilot Chat để explain code in language A → generate equivalent in language B
- C) Chỉ hỗ trợ Python ↔ JavaScript
- D) Cần extension riêng

**✅ B)** — Copilot Chat giúp translate code giữa các ngôn ngữ.

### Câu 48
**Q:** Edge cases khi dùng Copilot bao gồm:
- A) Không có edge cases
- B) Suggestions có thể sai logic, cần review kỹ, đặc biệt với complex business logic
- C) Chỉ sai syntax
- D) Chỉ sai khi code dài

**✅ B)** — Copilot có thể sai logic, đặc biệt với complex business logic → luôn review.

### Câu 49
**Q:** Copilot giúp debugging như thế nào?
- A) Tự động fix bugs
- B) Paste error message + code → Copilot giải thích nguyên nhân và suggest fix
- C) Chỉ highlight lỗi
- D) Không hỗ trợ debug

**✅ B)** — Paste error + context → Copilot explain root cause và suggest solutions.

### Câu 50
**Q:** Khi cần tạo database query, Copilot:
- A) Không biết SQL
- B) Mô tả table structure + yêu cầu → Copilot tạo SQL query phù hợp
- C) Chỉ tạo SELECT *
- D) Cần extension

**✅ B)** — Mô tả schema + requirements → Copilot generate correct SQL.

---

## Domain 6: Testing with GitHub Copilot (9%)

### Câu 51
**Q:** Copilot hỗ trợ test generation như thế nào?
- A) Chỉ tạo test file trống
- B) Đọc source code → tạo unit tests, integration tests, edge cases
- C) Chỉ tạo test names
- D) Không hỗ trợ testing

**✅ B)** — Copilot đọc code → generate comprehensive tests bao gồm edge cases.

### Câu 52
**Q:** Khi tạo unit test với Copilot, nên cung cấn gì?
- A) Chỉ tên function
- B) Source code của function + context về expected behavior + edge cases cần test
- C) Chỉ file name
- D) Không cần gì

**✅ B)** — Cung cấp source code + expected behavior → Copilot tạo tests chính xác.

### Câu 53
**Q:** Test-driven development (TDD) với Copilot:
- A) Không phù hợp
- B) Viết test trước → Copilot generate code để pass tests
- C) Chỉ viết code trước
- D) Chỉ dùng cho integration tests

**✅ B)** — TDD + Copilot: viết tests trước, Copilot generate implementation code.

### Câu 54
**Q:** Copilot có thể tạo những loại test nào?
- A) Chỉ unit tests
- B) Unit tests, integration tests, edge case tests
- C) Chỉ end-to-end tests
- D) Chỉ mock tests

**✅ B)** — Copilot hỗ trợ nhiều loại test: unit, integration, edge cases.

### Câu 55
**Q:** Khi Copilot tạo test, điều gì cần lưu ý?
- A) Luôn đúng 100%
- B) Cần review tests vì Copilot có thể bỏ sót edge cases hoặc tạo tests sai logic
- C) Không cần review
- D) Chỉ test happy path

**✅ B)** — Luôn review generated tests, Copilot có thể miss edge cases.

### Câu 56
**Q:** Để Copilot tạo test cho function có external dependencies:
- A) Không thể
- B) Cung cấp mock setup hoặc yêu cầu Copilot tạo mocks
- C) Chỉ test không dependencies
- D) Cần cài đặt thêm

**✅ B)** — Có thể yêu cầu Copilot tạo mocks hoặc cung cấp mock setup.

### Câu 57
**Q:** Copilot code review trong testing context:
- A) Chỉ check syntax
- B) Identify security vulnerabilities, suggest performance optimizations, check test coverage
- C) Chỉ rename test functions
- D) Không hỗ trợ

**✅ B)** — Copilot review code cho security, performance, và test coverage.

---

## Domain 7: Privacy Fundamentals & Context Exclusions (15%)

### Câu 58
**Q:** Content exclusions trong Copilot cho phép:
- A) Chặn mọi suggestions
- B) Loại bỏ specific files/folders khỏi context mà Copilot sử dụng
- C) Chỉ exclude test files
- D) Không có tính năng này

**✅ B)** — Content exclusions cho phép exclude specific files/folders khỏi Copilot context.

### Câu 59
**Q:** File nào được dùng để cấu hình context exclusions trong repository?
- A) `.gitignore`
- B) `.copilotignore`
- C) `.copilotexclude`
- D) `copilot.config`

**✅ B)** — `.copilotignore` tương tự `.gitignore` nhưng cho Copilot context.

### Câu 60
**Q:** Content exclusions có hoạt động ở cấp nào?
- A) Chỉ repository level
- B) Repository level và organization level
- C) Chỉ user level
- D) Chỉ enterprise level

**✅ B)** — Content exclusions hoạt động ở cả repo level và org level.

### Câu 61
**Q:** Khi content exclusion được bật, điều gì xảy ra?
- A) Copilot ngừng hoạt động
- B) Files bị excluded không được dùng làm context cho suggestions
- C) Files bị xóa
- D) Copilot chỉ dùng excluded files

**✅ B)** — Excluded files không contribute context → suggestions không dựa trên code đó.

### Câu 62
**Q:** Telemetry data trong Copilot bao gồm:
- A) Nội dung code của bạn
- B) Usage patterns, suggestions accepted/rejected, performance metrics
- C) Personal files
- D) Passwords

**✅ B)** — Telemetry bao gồm usage data, không phải nội dung code.

### Câu 63
**Q:** Ai có thể cấu hình content exclusions ở organization level?
- A) Bất kỳ ai
- B) Organization owners/admins
- C) Chỉ GitHub support
- D) Không ai

**✅ B)** — Chỉ org owners/admins có quyền cấu hình org-level content exclusions.

### Câu 64
**Q:** Khi làm việc với private/proprietary code, nên làm gì?
- A) Không cần làm gì
- B) Bật content exclusions, đảm bảo plan hỗ trợ privacy (Business/Enterprise)
- C) Chỉ dùng free plan
- D) Không dùng Copilot

**✅ B)** — Bật content exclusions + dùng Business/Enterprise plan để bảo vệ private code.

### Câu 65
**Q:** Contractual protections trong Copilot Business/Enterprise đảm bảo:
- A) Code của bạn được dùng để train models
- B) Code của bạn KHÔNG được dùng để train public models
- C) Code được share công khai
- D) Không có bảo vệ

**✅ B)** — Business/Enterprise có contractual protections: code không được dùng train public models.

### Câu 66
**Q:** Giới hạn của content exclusions là gì?
- A) Không có giới hạn
- B) Không thể exclude tất cả files (cần context để hoạt động), và không áp dụng cho Copilot Chat history
- C) Chỉ exclude được 10 files
- D) Chỉ hoạt động với JavaScript

**✅ B)** — Copilot cần context để hoạt động, không thể exclude tất cả.

### Câu 67
**Q:** Khi bạn accept một suggestion từ Copilot, dữ liệu đó:
- A) Được gửi công khai
- B) Có thể được dùng làm telemetry (không phải train public model với Business/Enterprise)
- C) Được xóa ngay
- D) Được lưu vào GitHub repo

**✅ B)** — Accepted suggestions có thể contribute telemetry data.

### Câu 68
**Q:** Để bảo vệ intellectual property khi dùng Copilot, nên:
- A) Không cần làm gì
- B) Bật duplication detection filter, dùng content exclusions, chọn plan phù hợp
- C) Chỉ dùng free plan
- D) Không bao giờ accept suggestions

**✅ B)** — Kết hợp duplication filter + content exclusions + đúng plan = bảo vệ IP.

### Câu 69
**Q:** Audit logs trong Copilot Business/Enterprise cho phép:
- A) Xem code của user
- B) Theo dõi usage, ai đã dùng Copilot, những gì được accept/reject
- C) Chỉ xem errors
- D) Không có audit logs

**✅ B)** — Audit logs theo dõi usage patterns và compliance.

### Câu 70
**Q:** Khi organization muốn đảm bảo không có proprietary code leak qua Copilot, kết hợp nào sau đây là best practice?
- A) Chỉ dùng free plan
- B) Business/Enterprise plan + content exclusions + duplication detection + audit logs
- C) Tắt hoàn toàn Copilot
- D) Chỉ dùng Copilot Chat

**✅ B)** — Kết hợp nhiều layers: đúng plan + exclusions + filter + audit = bảo vệ tốt nhất.

---

## 📋 Quick Reference Cheat Sheet

### Plans Comparison
| Feature | Free | Individual | Business | Enterprise |
|---------|------|------------|----------|------------|
| Code completion | ✅ | ✅ | ✅ | ✅ |
| Copilot Chat | ✅ | ✅ | ✅ | ✅ |
| Content exclusions | ❌ | ❌ | ✅ | ✅ |
| Audit logs | ❌ | ❌ | ✅ | ✅ |
| Codebase personalization | ❌ | ❌ | ❌ | ✅ |
| Org-level governance | ❌ | ❌ | ✅ | ✅ |
| Telemetry opt-out | ❌ | ❌ | ✅ | ✅ |
| Duplication detection | ✅ | ✅ | ✅ | ✅ |

### Key Concepts
- **Responsible AI:** Fairness, Privacy, Accountability, Transparency
- **Agent Mode:** Multi-step tasks, MCP, sub-agents
- **Edit Mode:** Multi-file edits via natural language
- **Context:** File + project structure + imports + open files
- **Prompt Engineering:** Clear, contextual, specific prompts → better suggestions
- **Content Exclusions:** `.copilotignore` file, repo + org level
- **Duplication Detection:** Block suggestions matching public code
- **Privacy:** Business/Enterprise = code NOT used to train public models

### Key CLI Commands
- `/delegate TASK` — Delegate task to Copilot agent
- `& TASK` — Prefix to delegate
- Autopilot mode — Multi-step without approval at each step

### Key Filters
- **Toxicity filter** — Chặn nội dung độc hại
- **Duplication detection** — Chặn code trùng public
- **Content exclusions** — Loại bỏ files/folders khỏi context

---

## 📖 Tài liệu tham khảo
- [Official Study Guide](https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/gh-300)
- [GitHub Copilot Docs](https://docs.github.com/en/copilot)
- [GitHub Copilot Plans](https://github.com/features/copilot/plans)
- [ExamTopics GH-300](https://www.examtopics.com/exams/microsoft/gh-300/)
- [Copilot Cert Prep Repo](https://github.com/timothywarner-org/copilot-cert-prep)
