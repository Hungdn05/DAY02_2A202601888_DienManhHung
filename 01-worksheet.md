# Day 02 Lab — Worksheet

> File này là hướng dẫn chính cho toàn bộ lab 4 tiếng. Bộ gợi ý, hướng dẫn công cụ, prompt mẫu và checklist tự kiểm đã được đặt trực tiếp vào từng phase để bạn không phải nhảy qua nhiều file.

## Nguyên tắc

1. **Problem first, not AI first.** Đừng bắt đầu bằng chatbot/agent. Bắt đầu bằng actor, workflow, bottleneck, metric.
2. **Cá nhân scan rộng, nhóm hội tụ.** Mỗi người chuẩn bị nhiều candidate problems; nhóm chọn một candidate đáng đào sâu.
3. **Vẽ workflow trước khi chọn AI.** Nếu chưa thấy bước nào nghẽn, chưa được chọn Rule / Workflow / Agent.
4. **Không cần AI vẫn là kết luận tốt.** Điểm nằm ở chất lượng lập luận, không nằm ở độ "ngầu" của solution.
5. **AI hỗ trợ, không thay quyết định.** Dùng AI để hỏi ngược, phản biện, vẽ lại, research. Người học tự kiểm và tự chốt.
6. **Tự làm trước, AI sau.** Những phần thể hiện suy nghĩ cá nhân như pitch, challenge và reflection không được để AI viết thay.

## Repo nộp bài

Mỗi học viên nộp một repo cá nhân:

```text
Day02-MãHọcViên-HọVàTên/
├── README.md
├── 01-individual-problem-scan/
├── 02-group-problem-statement/
└── 03-individual-reflection/
```

File phụ như ảnh workflow, Mermaid, survey screenshot, research notes đặt cùng prefix:

```text
01-individual-problem-scan-workflow-card-1.png
02-group-problem-statement-workflow.pdf
02-group-problem-statement-research-notes.md
```

Lưu ý: `02-group-problem-statement/` là **bản nộp nhóm**. Nhóm 3-4 người làm chung một bản cuối, sau đó mỗi học viên copy bản này vào repo cá nhân của mình.

## Output cuối cùng

| Phần | Ai làm | Cần có gì |
|---|---|---|
| `01-individual-problem-scan/` | Cá nhân | 5+ problems, top 3 Problem Cards, draft workflow trước/sau cho top 3 |
| `02-group-problem-statement/` | Nhóm | Nhật ký hội tụ, kiểm chứng nhanh, research giải pháp, workflow trước/sau, Problem Statement v0/v1, Rule / Workflow / Agent, quyết định cuối |
| `03-individual-reflection/` | Cá nhân | Vai trò trong nhóm, cách dùng AI, học được gì, nếu làm lại sẽ đổi gì |

## Tiêu chí đánh giá nhanh

Chi tiết rubric nằm trong `README.md`. Bảng dưới đây giúp bạn biết phần nào đang ảnh hưởng tới điểm khi làm worksheet.

| Nhóm / cá nhân | Thành phần | Điểm |
|---|---|---:|
| Nhóm | Workflow trước/sau | 15 |
| Nhóm | Problem Statement + metric + boundary | 20 |
| Nhóm | Độ phù hợp với AI + phương án thay thế | 15 |
| Nhóm | Chất lượng quyết định Go / Not Yet / No-Go | 10 |
| Cá nhân | Scan problem + top 3 Problem Cards | 12 |
| Cá nhân | Tham gia pitch + challenge | 12 |
| Cá nhân | Reflection cá nhân | 10 |
| Cá nhân | Kiểm tra hiểu bài cá nhân | 6 |

Bonus tối đa +10 điểm:

- +3 nếu scan rộng hơn yêu cầu và vẫn cụ thể.
- +3 nếu tương tác tích cực trên Discord hoặc trong nhóm.
- +4 nếu kiểm chứng/research vượt yêu cầu và giúp nhóm sửa lại problem, metric hoặc quyết định cuối.

## Quy ước dùng AI trong lab

| Phần | Có thể dùng AI không? | Cách dùng đúng |
|---|---|---|
| Scan cá nhân | Có, sau khi tự scan trước | Hỏi thêm góc nhìn, rồi tự chọn ý nào là pain thật. |
| Problem Card | Có | Dùng AI để phản biện, không để AI tự bịa problem thay mình. |
| Pitch + challenge | Không dùng để nói/thay mình | Trình bày và phản biện bằng hiểu biết của bản thân. |
| Research | Có | Dùng AI/search để tìm nguồn, nhưng phải kiểm link và ghi rõ giả định chưa chắc. |
| Workflow | Có | Có thể dùng AI/Mermaid để vẽ lại flow, nhưng phải tự kiểm từng bước. |
| Reflection | Không dùng để viết thay | Có thể dùng AI để gợi ý câu hỏi tự soi, nhưng câu trả lời phải là trải nghiệm thật của mình. |

## Gợi ý công cụ nhanh

| Phase | Tool có thể dùng | Dùng để làm gì | Lưu ý |
|---|---|---|---|
| Phase 1 | ChatGPT / Claude / Gemini, Google, review app/forum | Gợi ý thêm problem nếu bí | Tự scan trước; bỏ ý không có trải nghiệm thật. |
| Phase 2 | ChatGPT / Claude | Phản biện Problem Card | Prompt rõ: "chỉ ra điểm yếu, đừng khen". |
| Phase 4 | Google, Perplexity, tài liệu chính thức, survey/interview nhanh | Kiểm chứng pain, tìm giải pháp đã có | Không dùng số liệu nếu không kiểm được nguồn. |
| Phase 5 | Giấy/bảng, Mermaid, Excalidraw, FigJam | Vẽ workflow trước/sau | Vẽ tay cho rõ tư duy trước, số hóa sau nếu cần nộp đẹp hơn. |
| Phase 6 | ChatGPT / Claude | Hỏi phản biện Rule / Workflow / Agent | Không để AI chốt thay. Nhóm phải tự quyết định. |
| Phase 7 | Không bắt buộc | Chỉ dùng để gợi ý câu hỏi tự soi | Không copy reflection do AI viết. |

---

# Phase 0 — Worked Example (15')

Mở `02-deliverable-example.md` để xem một bài hoàn chỉnh. Khi đọc, chú ý:

- cá nhân scan rộng như thế nào,
- top 3 Problem Cards cụ thể ra sao,
- nhóm hội tụ từ nhiều candidates về một bài như thế nào,
- research giải pháp giúp nhóm tránh nghĩ trong chân không ra sao,
- workflow trước/sau thể hiện bottleneck, boundary và phương án quay về nếu AI sai như thế nào,
- Problem Statement v0/v1 khác nhau ở đâu.

Self-check:

- [x] Tôi hiểu nhóm chỉ chọn **candidate problem**, không chọn ngay Problem Statement.
- [x] Tôi hiểu deep-dive gồm validation, research, workflow, metric, PS và AI decision.

---

# Phase 1 — Individual Scan: tìm 5+ problems (25')

## Mục tiêu

Mỗi người scan rộng ít nhất 5 problems từ trải nghiệm thật. Đây là phần phân kỳ cá nhân.

Bonus:

- 8+ problems: bonus nếu vẫn cụ thể.
- 10+ problems: bonus tốt nếu đa dạng lăng kính và có dấu hiệu thật.
- Không bonus cho list dài nhưng toàn ý chung chung.

## 4 lăng kính để scan

Một problem có thể rơi vào nhiều lăng kính. Không cần phân loại hoàn hảo ở bước này. Dùng lăng kính để mở rộng quan sát, rồi bước sau mới filter.

| Lăng kính | Câu hỏi gợi mở | Ví dụ |
|---|---|---|
| **Lặp lại** | Việc gì cứ xuất hiện đều đặn mỗi ngày/tuần/tháng?<br>Nếu phải làm thêm 10 lần nữa, phần nào tôi muốn chuẩn hóa hoặc tự động hóa?<br>Người mới vào có phải hỏi lại cùng một quy trình không? | Báo cáo tuần, nhập liệu, tổng hợp câu hỏi |
| **Tốn thời gian** | Việc gì mỗi lần làm đều nặng, dù không nhất thiết xảy ra thường xuyên?<br>Thời gian mất ở đâu: tìm thông tin, đọc hiểu, tổng hợp, chờ người khác, format, hay sửa lại?<br>Nếu giảm 50% thời gian thì có đáng kể không? | Đọc tài liệu dài, tìm quyết định cũ, review PRD |
| **AI có thể tốt hơn** | Việc gì cần hiểu ngữ cảnh, đọc/viết ngôn ngữ, phân loại, so sánh, tổng hợp hoặc gợi ý đúng lúc?<br>Nếu AI chỉ hỗ trợ một bước trong workflow, bước nào đáng hỗ trợ nhất?<br>Nếu AI sai ở bước đó thì hậu quả là gì? | Search tài liệu, gợi ý next step, tóm tắt nhiều nguồn |
| **Pain từ người khác** | Ai ngoài tôi đang bị kẹt hoặc phàn nàn lặp lại?<br>Họ thường nói câu gì, hỏi lại điều gì, hoặc bỏ sót bước nào?<br>Có dấu hiệu thật không: ticket, Slack/Discord, comment, survey, phản hồi trực tiếp? | Hỏi lại deadline, không hiểu task, support ticket lặp lại |

Cách phân biệt nhanh:

- `Lặp lại` bắt đầu từ câu hỏi: việc này xảy ra bao nhiêu lần?
- `Tốn thời gian` bắt đầu từ câu hỏi: mỗi lần làm tốn bao nhiêu công?
- Một problem vừa lặp lại vừa tốn thời gian thì càng đáng đưa vào danh sách scan.

Nếu bí, tự hỏi:

- Tuần trước tôi mất nhiều thời gian nhất vào việc gì?
- Việc gì tôi hay trì hoãn vì nhàm chán hoặc rối?
- Người khác hay hỏi tôi câu gì lặp lại?
- Có workflow nào ở trường/công ty ai cũng biết là chậm?
- Có app nào tôi dùng và thường nghĩ "giá như nó hiểu mình hơn"?

Một số điểm bắt đầu dễ quan sát:

| Bối cảnh | Có thể nhìn vào đâu? | Câu hỏi gợi mở |
|---|---|---|
| Học tập | Bài tập, tài liệu, deadline, câu hỏi lặp lại trong lớp | Phần nào làm tôi mất thời gian vì phải đọc, tổng hợp, hỏi lại hoặc đoán ý? |
| Công việc / thực tập | Báo cáo, họp, handoff, ticket, review, nhập liệu | Việc nào lặp lại đủ nhiều nhưng vẫn cần hiểu ngữ cảnh trước khi xử lý? |
| Nhóm / CLB / dự án | Phân công, theo dõi tiến độ, feedback, tổng hợp quyết định | Chỗ nào mọi người hay hiểu khác nhau hoặc bỏ sót việc cần làm? |
| Sản phẩm đang dùng | Search, onboarding, support, form, notification | Điểm nào user phải tự nối nhiều thông tin rời rạc để hoàn thành việc? |

## Ngân hàng gợi ý problem

Nếu vẫn bí ý tưởng, đọc nhanh các gợi ý dưới đây rồi quay lại trải nghiệm thật của bạn. Không copy nguyên văn; hãy viết lại theo người dùng, workflow và dấu hiệu thật mà bạn quan sát được.

| Bối cảnh | Gợi ý problem để suy nghĩ |
|---|---|
| Học tập | Tìm lại quyết định/câu trả lời cũ trong Discord; đọc tài liệu dài trước deadline; không biết bài nộp thiếu field nào; ôn tập từ nhiều nguồn rời rạc. |
| Đời sống cá nhân | Theo dõi chi tiêu rải rác nhiều app; lên kế hoạch đi lại/ăn uống cho nhóm; tổng hợp giấy tờ cá nhân; nhắc việc định kỳ nhưng hay quên context. |
| Thực tập / công việc mới | Hỏi lại quy trình onboarding; tìm người phụ trách đúng việc; viết update hằng tuần; hiểu task từ nhiều Slack/thread/tài liệu. |
| Người đi làm | Tổng hợp báo cáo tuần; chuẩn bị meeting recap; review tài liệu dài; phân loại ticket/support; tìm quyết định cũ trước khi làm tiếp. |
| Cải thiện sản phẩm đang dùng | Search kém; onboarding khó hiểu; notification không đúng lúc; form dài và dễ nhập sai; support phải hỏi lại cùng một thông tin nhiều lần. |

## Bảng scan

| # | Lăng kính | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật |
|---|---|---|---|---|
| 1 | Tốn thời gian / AI có thể tốt hơn | Khó tìm bộ câu hỏi phỏng vấn sát vị trí và JD mục tiêu. | Sinh viên năm cuối / mới tốt nghiệp | Tôi phải tìm từ nhiều nguồn và vẫn không biết câu hỏi có phủ đúng competency của JD hay không. Chưa đo thời gian baseline. |
| 2 | AI có thể tốt hơn | Tự luyện một mình nên không có câu hỏi follow-up dựa trên câu trả lời. | Sinh viên chuẩn bị vòng phỏng vấn đầu tiên | Khi tự luyện, tôi thường dừng ở một câu trả lời; không có người đào sâu evidence hoặc mâu thuẫn. |
| 3 | Pain từ người khác / AI có thể tốt hơn | Feedback từ bạn bè hoặc các lần luyện không dùng cùng rubric nên khó so sánh tiến bộ. | Sinh viên ít kinh nghiệm phỏng vấn | Cùng một câu trả lời có thể nhận nhận xét khác nhau; chưa có scorecard hoặc error log cố định. |
| 4 | AI có thể tốt hơn | Không biết câu trả lời hành vi đã đủ STAR và bằng chứng hay chưa. | Sinh viên mới ra trường | Câu trả lời thường thiên về kể việc đã làm, thiếu Result hoặc số liệu; đây là tự quan sát, cần benchmark đo lại. |
| 5 | Lặp lại | Mỗi JD lại phải tìm câu hỏi từ đầu vì chưa có bản đồ JD → competency → câu hỏi. | Người ứng tuyển nhiều vị trí | Quy trình tìm và chọn câu hỏi lặp lại theo từng JD nhưng không được lưu thành bộ competency có thể tái dùng. |
| 6 | Tốn thời gian / AI có thể tốt hơn | Không biết chỉnh CV theo JD mà vẫn trung thực với kinh nghiệm thật. | Sinh viên / fresh graduate | Khó nhận ra yêu cầu quan trọng và thiếu gì trong CV; có nguy cơ nhồi từ khóa hoặc phóng đại kinh nghiệm. |
| 7 | AI có thể tốt hơn | Khó chuyển trải nghiệm học tập / dự án thành bullet CV có evidence. | Sinh viên thiếu kinh nghiệm thực tế | Bullet thường mô tả nhiệm vụ, thiếu hành động, kết quả và phạm vi đóng góp. |
| 8 | AI có thể tốt hơn | Biết mình thiếu kỹ năng nhưng không biết biến gap thành dự án portfolio nhỏ. | Sinh viên mới ra trường | Danh sách skill gap không tạo ra next step cụ thể, nên dễ trì hoãn hoặc học lan man. |
| 9 | Lặp lại / tốn thời gian | Workflow tìm việc bị phân mảnh giữa JD, CV, ghi chú phỏng vấn và lịch ứng tuyển. | Sinh viên đang nộp nhiều công ty | Thông tin nằm ở nhiều file/tab; khó theo dõi phiên bản CV, lỗi lặp lại và tiến bộ theo vị trí. |
| 10 | AI có thể tốt hơn | Chưa biết dùng và kiểm chứng AI an toàn trong quá trình chuẩn bị ứng tuyển. | Sinh viên mới bắt đầu dùng AI | Có xu hướng chấp nhận câu trả lời nghe hợp lý dù AI có thể bịa kinh nghiệm, chấm thiếu nhất quán hoặc làm lộ dữ liệu CV. |

Gợi ý cho `Dấu hiệu thật`: mất bao lâu, xảy ra mấy lần/tuần, bao nhiêu người gặp, có log/ticket/review/comment không, nếu không sửa thì hậu quả là gì.

## Nếu dùng AI ở phase này

Tự scan trước rồi mới hỏi AI.

Prompt gợi ý:

```text
Tôi là [vai trò] trong [bối cảnh].
Công việc hằng tuần gồm: [...]

Tôi đã nghĩ ra các vấn đề sau:
1. [...]
2. [...]
3. [...]

Hãy gợi ý thêm problem theo 4 lăng kính: lặp lại, tốn thời gian, AI có thể tốt hơn, pain từ người khác.
Với mỗi gợi ý, ghi actor, workflow sơ bộ và cách đo.
Đừng đưa ý tưởng quá rộng kiểu "xây trợ lý AI toàn năng".
```

Ghi vào reflection: AI gợi ý gì dùng được, ý nào bị bỏ vì không phải pain thật.

---

# Phase 2 — Top 3 Problem Cards + draft workflow (35')

## Mục tiêu

Từ 5+ problems, mỗi người chọn top 3 để chuẩn bị share với nhóm. Mỗi top problem cần có:

- Problem Card.
- Draft current workflow.
- Draft future workflow.
- Lý do vì sao bài này có impact.

## Chọn top 3

Tiêu chí chọn:

- Actor rõ.
- Workflow hiện tại có thể vẽ được.
- Bottleneck cụ thể.
- Impact có thể đo hoặc ước lượng.
- Có thể so sánh No AI / Rule / Workflow / Agent.
- Không quá rộng cho một buổi lab.

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Luyện phỏng vấn sát vị trí và nhận feedback nhất quán | Pain gần với vòng tuyển dụng thật; current/future workflow rõ; có thể luyện lặp lại cùng competency và đo STAR/evidence/confidence. | Baseline chưa đo; cần xác nhận với 2–3 sinh viên và một cố vấn tuyển dụng. |
| 2 | CV–JD Alignment trung thực | Nhu cầu phổ biến, dễ thấy output trước/sau và có thể benchmark bằng checklist/rule. | Chưa biết alignment score có dự báo CV qua vòng hồ sơ hay không. |
| 3 | Skill Gap → Project portfolio | Giúp sinh viên thiếu kinh nghiệm tạo evidence thay vì chỉ học lý thuyết. | Phạm vi dễ quá rộng; hiệu quả cần nhiều tuần mới quan sát được. |

## Problem Card template

Lặp lại template này cho top 3.

Nếu cần một bản nhìn nhanh để pitch với nhóm, dùng dạng card này:

```text
┌──────────────────────────────────────────────┐
│ PROBLEM CARD #___                            │
│                                              │
│ Problem 1 câu: ___________________________   │
│                                              │
│ Ai chịu ảnh hưởng? ______________________   │
│                                              │
│ Workflow hiện tại:                           │
│ 1. ______ → 2. ______ → 3. ______ → 4. ___   │
│                                              │
│ Bước nghẽn nhất: ________  (___ phút/lần)    │
│                                              │
│ Đo thành công bằng gì? ___________________   │
│ Ví dụ: giảm 90 phút → dưới 30 phút           │
│                                              │
│ Quick gut: □ No AI □ Rule □ Workflow         │
│            □ Agent □ Chưa biết               │
└──────────────────────────────────────────────┘
```

Phần nộp chi tiết vẫn dùng template bên dưới để không thiếu field.

```text
Problem 1 câu:

Actor:

Thời điểm / bối cảnh:

Current workflow 3-7 bước:
1.
2.
3.
4.
5.

Bottleneck:

Impact:

Success metric:

Non-AI alternative:

AI hypothesis:

Quick gut:
[ ] No AI / process fix
[ ] Rule
[ ] Workflow
[ ] Agent
[ ] Chưa biết
```

### Bài làm đã điền — Problem Card #1

```text
Problem 1 câu:
Sinh viên năm cuối / mới tốt nghiệp ít có cơ hội luyện phỏng vấn sát với vị trí
và không nhận được feedback nhất quán, nên khó biết câu trả lời đã đủ evidence,
đúng cấu trúc STAR và phù hợp với competency hay chưa.

Actor:
Sinh viên năm cuối / mới tốt nghiệp đã chọn một vị trí và JD mục tiêu,
đang chuẩn bị cho những vòng phỏng vấn đầu tiên.

Thời điểm / bối cảnh:
Trước khi phỏng vấn thật; đặc biệt khi không có mentor hoặc interviewer giàu kinh nghiệm
sẵn sàng luyện cùng nhiều lần.

Current workflow 7 bước:
1. Chọn JD/vị trí mục tiêu.
2. Tìm câu hỏi mẫu chung trên nhiều nguồn.
3. Tự chọn câu hỏi nhưng chưa map với competency của JD.
4. Tự trả lời hoặc ghi âm một mình.
5. Không có follow-up dựa trên câu trả lời.
6. Xin feedback rời rạc, không dùng cùng rubric và không có error log.
7. Đi phỏng vấn thật hoặc tiếp tục luyện mà không biết mình tiến bộ ở đâu.

Bottleneck:
Thiếu một vòng lặp ổn định gồm câu hỏi theo competency → follow-up theo câu trả lời
→ transcript/evidence → feedback theo cùng rubric → luyện lại.

Impact:
Người học khó nhận ra câu trả lời thiếu Situation/Task/Action/Result hoặc thiếu bằng chứng;
confidence thấp và dễ lặp lại cùng lỗi ở phỏng vấn thật.

Success metric:
Sau 3 buổi cùng competency và rubric: điểm STAR tăng ≥20%; ≥80% câu trả lời hành vi
có evidence cụ thể; confidence tự đánh giá tăng ≥1/5; CSAT feedback ≥4/5.
Baseline cần đo trong pilot, không giả định số hiện tại.

Non-AI alternative:
Bộ câu hỏi cố định theo competency + checklist STAR + tự ghi âm + peer/cố vấn review.

AI hypothesis:
Workflow có AI hỗ trợ map JD → competency, chọn câu hỏi, hỏi tối đa 1–2 follow-up,
tạo transcript/evidence và draft feedback theo rubric. Sinh viên xác nhận nội dung;
cố vấn review mẫu và sửa khi AI sai.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

### Hai Problem Cards còn lại — bản tóm tắt

| Card | Actor & bottleneck | Success metric dự kiến | Non-AI benchmark | Quick gut |
|---|---|---|---|---|
| #2 — CV–JD Alignment trung thực | Sinh viên mới ra trường; không biết yêu cầu nào của JD đã/ chưa có evidence trong CV. | Giảm thời gian review; tăng tỷ lệ requirement có evidence; không có claim bịa. | Checklist requirement–evidence và cố vấn review. | Workflow |
| #3 — Skill Gap → Project portfolio | Sinh viên thiếu kinh nghiệm; biết gap nhưng không chuyển thành project nhỏ có output và tiêu chí hoàn thành. | Hoàn thành một project scope nhỏ đúng hạn và tạo được artifact/bullet CV kiểm chứng được. | Template project brief + weekly peer review. | Workflow |

## Draft workflow cho mỗi top problem

Workflow có thể là ảnh, ASCII hoặc Mermaid. Không cần đẹp, nhưng phải đọc được.

Ví dụ ASCII:

```text
CURRENT STATE — 90 phút

[Export Jira: 10']
→ [Lấy metrics: 10']
→ [Đọc Slack: 15']
→ [Tổng hợp: 15']
→ [Viết narrative: 25']  <-- bottleneck
→ [Review: 10']
→ [Gửi: 5']

FUTURE STATE — 21 phút

[Auto-pull: 2']
→ [AI cấu trúc dữ liệu: 1']
→ [AI draft narrative: 1']
→ [PM review + edit: 15']  <-- human boundary
→ [PM gửi: 2']

Fallback: AI draft tệ → PM tự viết lại
```

Nếu nộp file riêng, đặt tên như:

```text
01-individual-problem-scan-workflow-card-1.png
```

## Chọn card muốn pitch nhất

Card tôi muốn pitch nhất:

```text
Problem Card #1 — Luyện phỏng vấn sát vị trí và nhận feedback nhất quán.
```

Vì sao:

```text
Đây là pain gần nhất với áp lực tìm việc hiện tại. Workflow có điểm nghẽn cụ thể,
có non-AI benchmark để so sánh và có thể kiểm chứng bằng pilot 3 buổi thay vì hứa hẹn chung chung.
```

Câu hỏi tôi muốn nhóm challenge:

```text
1. Bộ câu hỏi + rubric cố định đã giải được phần lớn pain chưa?
2. Feedback của AI có đủ nhất quán và hữu ích so với cố vấn người thật không?
3. Metric STAR/evidence có phản ánh khả năng phỏng vấn thật hay chỉ phản ánh cách chấm rubric?
```

## Nếu dùng AI ở phase này

Prompt phản biện:

```text
Đây là Problem Card của tôi:
[dán card]

Hãy đóng vai skeptical product manager và phản biện:
1. Actor có đủ cụ thể không?
2. Workflow có thật không?
3. Bottleneck có rõ chưa?
4. Metric có đo được không?
5. Rule/process fix đã đủ chưa?
6. Tôi có đang nhảy sang Agent quá sớm không?

Trả lời ngắn, tập trung vào điểm yếu.
```

---

# Break (10')

---

# Phase 3 — Group Convergence: từ 9-12 candidates về 1 (30')

## Mục tiêu

Nhóm 3-4 người sẽ có khoảng 9-12 candidate problems. Không vote ngay. Đi qua 4 bước hội tụ:

```text
Trình bày top 3
→ gom trùng / cluster
→ shortlist
→ chấm nhanh + đồng thuận chọn 1 candidate problem
```

Nhóm lúc này **chỉ chọn candidate problem**, chưa viết Problem Statement hoàn chỉnh.

Đây là phase **tự pitch và tự challenge**. Không dùng AI để viết lời pitch, đặt câu hỏi thay mình, hoặc quyết định thay nhóm. Nếu muốn dùng AI để tóm tắt notes, chỉ làm sau khi nhóm đã thảo luận xong phần chính.

## Bước 3.1 — Trình bày top 3

Mỗi người trình bày 3 candidates, mỗi candidate 1-2 phút:

- problem là gì,
- người gặp vấn đề là ai,
- workflow hiện tại nghẽn ở đâu,
- draft workflow tương lai thay đổi gì,
- vì sao bài này có tác động đáng kể.

| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh |
|---|---|---|---|---|---|
| 1 | Hùng | Mock Interview sát vị trí + feedback nhất quán | Sinh viên năm cuối / mới tốt nghiệp | Không có vòng competency → follow-up → evidence → cùng rubric → luyện lại | Cao; chọn deep-dive |
| 2 | Hùng | CV–JD Alignment trung thực | Sinh viên / fresh graduate | Không map được requirement của JD với evidence thật trong CV | Cao; benchmark Rule rõ |
| 3 | Hùng | Skill Gap → Project portfolio | Sinh viên thiếu kinh nghiệm | Gap không chuyển thành project scope nhỏ có output đo được | Khá; phạm vi dễ rộng |
| 4 | Chờ thành viên nhóm bổ sung | — | — | — | Chưa có dữ liệu |
| 5 | Chờ thành viên nhóm bổ sung | — | — | — | Chưa có dữ liệu |
| 6 | Chờ thành viên nhóm bổ sung | — | — | — | Chưa có dữ liệu |
| 7 | Chờ thành viên nhóm bổ sung | — | — | — | Chưa có dữ liệu |
| 8 | Chờ thành viên nhóm bổ sung | — | — | — | Chưa có dữ liệu |
| 9 | Chờ thành viên nhóm bổ sung | — | — | — | Chưa có dữ liệu |
| 10 | Chờ thành viên nhóm bổ sung | — | — | — | Chưa có dữ liệu |
| 11 | Chờ thành viên nhóm bổ sung | — | — | — | Chưa có dữ liệu |
| 12 | Chờ thành viên nhóm bổ sung | — | — | — | Chưa có dữ liệu |

## Bước 3.2 — Gom trùng / cluster

| Cluster | Candidates included | Pattern chung | Ghi chú |
|---|---|---|---|
| A — Interview practice | Mock Interview, follow-up, STAR rubric | Luyện sát vị trí và nhận feedback có thể so sánh qua nhiều lần | Candidate ưu tiên |
| B — Application documents | CV–JD Alignment, viết bullet CV | Biến JD và trải nghiệm thật thành hồ sơ có evidence | Candidate dự phòng |
| C — Skill & evidence | Skill Gap → Project | Biến thiếu hụt kỹ năng thành project/portfolio kiểm chứng được | Cần scope dài hơn buổi lab |
| D — Planning & progress | Theo dõi ứng tuyển, error log, motivation | Giảm phân mảnh và giúp nhìn thấy next step/tiến bộ | Chưa đủ evidence để chọn |

## Bước 3.3 — Shortlist

Hỏi:

- Có ai trong nhóm hiểu workflow thật đủ sâu không?
- Actor có cụ thể không?
- Bottleneck có phải một bước cụ thể không?
- Impact có thể đo không?
- Có thể vẽ before/after workflow không?
- Có thể so sánh Rule / Workflow / Agent không?
- Có quá rộng cho lab hôm nay không?

| Candidate | Vì sao vào shortlist | Rủi ro / điều chưa rõ |
|---|---|---|
| Mock Interview sát vị trí + feedback nhất quán | Workflow và bottleneck cụ thể; có thể pilot trong ba buổi; đo được STAR/evidence/CSAT. | Baseline và peer validation chưa hoàn tất; AI feedback có thể bias hoặc thiếu căn cứ. |
| CV–JD Alignment trung thực | Actor rõ; output trước/sau dễ so sánh; Rule benchmark mạnh. | Tỷ lệ qua hồ sơ chịu nhiều yếu tố ngoài CV; dễ tối ưu từ khóa quá mức. |
| Skill Gap → Project portfolio | Tạo evidence thật cho sinh viên thiếu kinh nghiệm. | Cần nhiều tuần; khó cô lập impact trong phạm vi lab. |

## Bước 3.4 — Score để đồng thuận

Chấm 1-5. Điểm không cần tuyệt đối; mục tiêu là ép nhóm nói rõ lý do.

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| Mock Interview sát vị trí + feedback nhất quán | 5 | 5 | 3 | 5 | 4 | 5 | 4 | 31 |
| CV–JD Alignment trung thực | 5 | 5 | 3 | 4 | 5 | 4 | 4 | 30 |
| Skill Gap → Project portfolio | 4 | 4 | 3 | 4 | 3 | 3 | 3 | 24 |

> Điểm trên là self-score tạm thời của Hùng để tạo giả thuyết thảo luận, chưa phải điểm đồng thuận của cả nhóm.

Candidate nhóm chọn:

```text
Mock Interview sát vị trí + feedback nhất quán.
```

Vì sao chọn:

```text
Pain gần với vòng tuyển dụng thật; có một bottleneck rõ là thiếu vòng luyện tương tác
và feedback cùng rubric. Có thể chạy pilot nhỏ, so sánh với non-AI benchmark và đặt boundary rõ.
```

Vì sao không chọn các candidate còn lại:

```text
CV–JD Alignment: Rule/checklist có thể đã giải phần lớn; outcome qua vòng hồ sơ khó quy trực tiếp cho tool.
Skill Gap → Project: có impact nhưng cần thời gian dài hơn và scope lớn hơn một buổi lab.
```

Nếu có disagreement, nhóm xử lý thế nào:

```text
Hiện mới có self-score của Hùng. Nhóm cần để từng thành viên nêu bằng chứng và rủi ro,
sau đó xác nhận hoặc sửa shortlist/điểm; không dùng AI hoặc vote nhanh để thay thảo luận.
```

---

# Phase 4 — Quick Validation + Research giải pháp (30')

## Mục tiêu

Sau khi chọn candidate problem, nhóm cần kiểm tra nhanh:

- pain có thật không,
- người khác có gặp không,
- đã có giải pháp nào tương tự chưa,
- bài toán có nên giải bằng AI không.

## Bước 4.1 — Quick validation

Chọn ít nhất một cách.

### Option A — Quick interviews

Hỏi 2-3 người:

- Lần gần nhất bạn gặp vấn đề này là khi nào?
- Bạn đang xử lý bằng workflow nào?
- Bước nào mất thời gian hoặc khó chịu nhất?
- Bạn mất khoảng bao lâu?
- Nếu tốt hơn, bạn muốn điều gì thay đổi?

### Option B — Micro survey / Discord poll

Hỏi 5-10 người:

- Bạn có gặp vấn đề này không?
- Tần suất?
- Bước nào đau nhất?
- Hiện bạn workaround thế nào?
- Mức độ đáng giải quyết: 1-5?

Kết quả:

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác | Nhóm sửa problem thế nào |
|---|---:|---|---|---|
| Interview | 0 / mục tiêu 2–3 | Chưa thực hiện | Chưa có | Hỏi về lần luyện gần nhất, workflow, pain và willingness to retry; cập nhật PS sau phỏng vấn. |
| Survey / poll | 0 / mục tiêu 5–10 | Chưa thực hiện | Chưa có | Chỉ chạy nếu không đủ người phỏng vấn; không coi self-report là bằng chứng outcome. |
| Log / review / ticket | 1 self-observation của Hùng / mục tiêu 1 mock baseline | Tự luyện thiếu follow-up và cùng rubric | Có thể chỉ là pain cá nhân | Ghi âm một buổi baseline, chấm bằng rubric cố định và để cố vấn audit mẫu. |

## Bước 4.2 — Research giải pháp đã có

Tìm ít nhất:

- 2-3 existing solutions/tools/patterns.
- 1-2 nguồn tham khảo có hyperlink.
- Nhận xét: họ xử lý bước nào trong workflow, chưa xử lý bước nào.
- Bài học kéo về bài toán nhóm mình.

| Nguồn / tool / case | Link | Họ giải quyết phần nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| Google Interview Warmup | https://grow.google/certificates/interview-warmup/ | Luyện trả lời và xem insight từ câu trả lời | Self-practice dễ tiếp cận | Không thay interviewer/cố vấn; cần kiểm chứng độ sát từng JD và tính nhất quán của feedback | Tận dụng self-practice nhưng không hứa dự đoán tuyển dụng. |
| Yoodli Interview Preparation | https://e.yoodli.ai/use-cases/interview-preparation | Mock interview và feedback luyện nói | Có vòng practice/feedback gần với use case | Feedback AI có thể làm người dùng quá tin; cần transcript, rubric và quyền sửa | Human review và evidence phải hiện rõ trong workflow. |
| U.S. OPM — Structured Interviews | https://www.opm.gov/policy-data-oversight/assessment-and-selection/structured-interviews | Mẫu tư duy phỏng vấn có cấu trúc, câu hỏi/đánh giá nhất quán | Hỗ trợ nguyên tắc dùng competency và tiêu chí chấm nhất quán | Không phải sản phẩm mock interview cho sinh viên | Dùng question bank + rubric cố định làm baseline và guardrail. |

Nếu dùng AI research, dùng prompt:

```text
Nhóm tôi đang phân tích bài toán:
[mô tả ngắn]

Hãy tìm:
1. 2-3 tool/case/pattern đã giải bài toán tương tự
2. Họ giải quyết bước nào trong workflow
3. Rủi ro hoặc khoảng trống còn lại

Yêu cầu: ghi link nguồn cho claim quan trọng. Nếu không chắc, nói rõ không chắc.
```

Không dùng số liệu AI đưa ra nếu không verify được.

---

# Phase 5 — Workflow + Problem Statement (45')

## Bước 5.1 — Current workflow bản nhóm

Vẽ workflow hiện tại kỹ hơn bản cá nhân. Mỗi bước nên có:

- actor,
- input,
- output,
- thời gian/tần suất,
- handoff,
- bottleneck.

Dán workflow hoặc link file:

```text
Xem: 02-group-problem-statement/02-group-problem-statement-workflow.md
```

[Mở sơ đồ workflow riêng](02-group-problem-statement/02-group-problem-statement-workflow.md)

| Bước | Actor | Input | Output | Thời gian/tần suất | Ghi chú |
|---|---|---|---|---|---|
| 1 | Sinh viên | Danh sách vị trí/JD | Một JD mục tiêu | Mỗi vị trí; chưa đo | Chưa có tiêu chí chọn competency. |
| 2 | Sinh viên | JD/vị trí | Danh sách câu hỏi từ nhiều nguồn | Mỗi lần luyện; chưa đo | Câu hỏi thường phổ biến/chung. |
| 3 | Sinh viên | JD + danh sách câu hỏi | Một số câu tự chọn | Mỗi buổi; chưa đo | Chưa map câu hỏi với competency. |
| 4 | Sinh viên | Câu hỏi | Câu trả lời/ghi âm | Mỗi buổi; chưa đo | Bottleneck bắt đầu: luyện một mình. |
| 5 | Không có interviewer ổn định | Câu trả lời | Ít hoặc không có follow-up | Gần như 0 | Không đào sâu evidence/mâu thuẫn. |
| 6 | Bạn bè/cố vấn nếu sẵn sàng | Câu trả lời rời rạc | Feedback ad-hoc | Không đều | Không cùng rubric giữa các lần. |
| 7 | Sinh viên | Feedback rời rạc | Không có error log/progress view | Sau buổi luyện | Không biết lỗi lặp hoặc mức tiến bộ. |
| 8 | Sinh viên + nhà tuyển dụng | Chuẩn bị hiện có | Phỏng vấn thật | Theo lịch tuyển dụng | Rủi ro lặp lỗi ở tình huống thật. |

Bottleneck chính:

```text
Thiếu vòng luyện nhất quán: câu hỏi theo competency → follow-up theo câu trả lời
→ transcript/evidence → cùng rubric → error log → luyện lại. Mentor thật không luôn sẵn sàng.
```

## Bước 5.2 — Future workflow bản nhóm

Vẽ workflow sau tối ưu. Cần thể hiện:

- bước nào Rule xử lý,
- bước nào AI/Workflow hỗ trợ,
- bước nào con người vẫn làm,
- boundary ở đâu,
- phương án quay về nếu AI sai.

Dán workflow hoặc link file:

```text
Xem: 02-group-problem-statement/02-group-problem-statement-workflow.md
```

Before/after impact:

| Metric | Trước | Sau kỳ vọng | Ghi chú |
|---|---:|---:|---|
| Số bước | 8 | 10 | Số bước tăng vì bổ sung control/review; mục tiêu là chất lượng vòng luyện, không phải chỉ giảm bước. |
| Tổng thời gian | Chưa đo | Đo trong pilot | Không đặt số giả; ghi thời gian từng bước ở buổi baseline và buổi 3. |
| Số bước thủ công | Phần lớn 8/8 | Sinh viên trả lời/xác nhận/luyện lại; cố vấn audit | Rule/AI chỉ hỗ trợ phần có input/output rõ. |
| Bottleneck chính | Tự luyện, ít follow-up và feedback ad-hoc | Review transcript/feedback | Bottleneck mới là human quality gate được chủ động giữ lại. |
| Risk mới | Lỗi lặp mà không biết | Bias, transcript sai, privacy, overconfidence | Consent, quyền sửa/xóa, rubric, advisor audit và fallback. |

## Bước 5.3 — Problem Statement v0

| Field | Nội dung |
|---|---|
| **Actor** | Sinh viên năm cuối / mới tốt nghiệp đã chọn vị trí mục tiêu và chuẩn bị cho một trong những cuộc phỏng vấn đầu tiên. |
| **Workflow** | Chọn JD → tìm câu hỏi → tự luyện → ít follow-up → feedback ad-hoc nếu có → đi phỏng vấn thật. |
| **Bottleneck** | Thiếu vòng luyện tập tương tác có follow-up và feedback có evidence, được chấm bằng cùng rubric qua nhiều lần; mentor thật không luôn sẵn sàng. |
| **Impact** | Câu trả lời dễ chung chung/thiếu evidence; không biết lỗi lặp; khó thấy tiến bộ; thiếu tự tin. |
| **Success Metric** | Sau ba buổi cùng competency/rubric: STAR tăng ≥20%; ≥80% câu behavioral có evidence; confidence tăng ≥1/5; CSAT feedback ≥4/5. Baseline chưa đo. |
| **Boundary** | Không dự đoán đậu/rớt; không chấm yếu tố nhạy cảm; feedback chỉ dựa trên transcript; sinh viên có quyền xem/sửa/xóa; cố vấn review case quan trọng. |

Prompt phản biện PS:

```text
Đây là Problem Statement v0 của nhóm tôi:
[dán 6 field]

Hãy chỉ ra field nào còn mơ hồ, metric đã đo được chưa, boundary đã rõ chưa.
Đừng viết lại thay tôi. Chỉ đặt câu hỏi và chỉ ra lỗ hổng.
```

---

# Break (10')

---

# Phase 6 — Rule / Workflow / Agent + Decision (25')

## Bước 6.0 — Ma trận độ phù hợp với AI để suy nghĩ nhanh

Ma trận này chỉ là công cụ phụ để suy nghĩ. Quyết định cuối vẫn phải dựa trên workflow, metric, boundary và rủi ro thật.

| | Độ mơ hồ thấp | Độ mơ hồ cao |
|---|---|---|
| **Độ phức tạp thấp** | Rule hoặc workflow đơn giản thường đủ | Workflow có AI hỗ trợ một bước có thể đủ |
| **Độ phức tạp cao** | Workflow điều phối nhiều bước rõ ràng, chưa chắc cần Agent | Agent có thể phù hợp, nhưng cần boundary, người thật kiểm tra và phương án quay về rất rõ |

Độ mơ hồ là gì?

- Thấp: có đáp án đúng/sai khá rõ, ví dụ phân loại theo 5 nhóm cố định.
- Cao: có nhiều cách trả lời vẫn chấp nhận được, ví dụ viết narrative tổng hợp từ nhiều nguồn.

Độ phức tạp là gì?

- Thấp: 1-2 bước, input/output rõ, ít nguồn dữ liệu.
- Cao: nhiều bước nối tiếp, nhiều nguồn dữ liệu, bước sau phụ thuộc kết quả bước trước.

Tự kiểm nhanh:

| Câu hỏi | Nếu có | Nếu không |
|---|---|---|
| Output có thể khác nhau mỗi lần mà vẫn chấp nhận được không? | Độ mơ hồ cao | Độ mơ hồ thấp |
| Cần phối hợp 3+ bước hoặc 3+ nguồn dữ liệu không? | Độ phức tạp cao | Độ phức tạp thấp |
| AI có cần tự quyết định bước tiếp theo không? | Có thể cần Agent | Rule/Workflow có thể đủ |

Bài toán của nhóm nằm ở ô nào?

```text
Độ mơ hồ cao × độ phức tạp cao vừa phải; phù hợp Workflow có AI hỗ trợ,
chưa đủ lý do cho Agent tự chủ.
```

Vì sao?

```text
Câu trả lời tốt có nhiều dạng nên không thể chỉ dùng rule cứng. Tuy nhiên luồng JD → competency
→ câu hỏi → follow-up → transcript → rubric → review vẫn tuyến tính, input/output rõ và cần human gate.
```

## Bước 6.1 — So sánh Rule / Workflow / Agent

| Mức | Phương án cho bài toán nhóm | Khi nào đủ | Rủi ro | Chọn? |
|---|---|---|---|---|
| **Rule** | Question bank theo role + checklist STAR + form feedback cố định | Đủ nếu không cần follow-up theo ngữ cảnh | Cứng nhắc; không phản hồi theo câu trả lời | Dùng cho câu hỏi gốc và rubric |
| **Workflow** | JD → competency → question bank → AI follow-up → transcript/evidence → rubric → human review | Hợp vì luồng tuyến tính, AI chỉ hỗ trợ vài bước | Feedback sai/bias, transcript sai, privacy | **Chọn cho pilot** |
| **Agent** | Tự chọn chiến lược hỏi, gọi nhiều tool và tự quyết bài luyện tiếp | Chỉ đáng dùng khi nhiều nhánh/tool và tự lập kế hoạch tạo giá trị | Scope rộng, khó dự đoán, chi phí/permission cao | Chưa chọn |

Hỏi kỹ:

- Rule có giải được 70-80% case không?
- Workflow có đủ vì các bước khá rõ không?
- Có thật sự cần Agent tự lập kế hoạch/gọi công cụ/đổi bước tiếp theo không?
- Nếu AI sai, ai phát hiện và sửa?
- Có thể hạ mức từ Agent về Workflow hoặc từ Workflow về Rule không?

Mức chọn:

```text
Workflow có AI hỗ trợ.
```

Vì sao chọn:

```text
Rule giữ các phần cần nhất quán; AI hỗ trợ follow-up, transcript/evidence và draft feedback;
sinh viên/cố vấn vẫn xác nhận trước khi sử dụng feedback.
```

Vì sao không chọn mức đơn giản hơn:

```text
Rule đơn thuần không phản hồi theo nội dung câu trả lời và không tạo được vòng follow-up linh hoạt.
Tuy vậy Rule vẫn là benchmark bắt buộc; nếu pilot không cho thấy lợi ích thêm thì quay về Rule.
```

## Bước 6.2 — Problem Statement v1

| Field | Nội dung |
|---|---|
| **Actor** | Sinh viên năm cuối / mới tốt nghiệp đã chọn một vị trí mục tiêu và thiếu cơ hội luyện phỏng vấn thực tế. |
| **Workflow** | Chọn JD → tìm câu hỏi → tự luyện → ít follow-up → feedback ad-hoc → không có progress log → phỏng vấn thật. |
| **Bottleneck** | Không có vòng practice nhất quán gồm câu hỏi theo competency, follow-up, feedback dựa trên transcript/evidence và cùng một rubric qua nhiều lần. |
| **Impact** | Câu trả lời dễ chung chung/thiếu evidence; lỗi lặp lại không được nhìn thấy; sinh viên khó biết mình tiến bộ và thiếu tự tin. |
| **Success Metric** | Với cùng competency/rubric qua ba buổi: STAR tăng ≥20%; ≥80% câu behavioral có evidence; confidence tăng ≥1/5; CSAT ≥4/5; cố vấn thấy feedback hữu ích. |
| **Boundary** | Không dự đoán tuyển dụng; không chấm yếu tố nhạy cảm; không suy đoán ngoài transcript; sinh viên có quyền xem/sửa/xóa và phản hồi; cố vấn review case quan trọng. |
| **AI intervention point** | Sau khi role/competency được xác nhận: hỗ trợ follow-up, transcript/evidence và draft feedback; trước bước sinh viên/cố vấn review. |
| **Mức chọn** | Workflow: Rule cho question bank/rubric; AI cho follow-up và feedback draft; human review. |
| **Rủi ro & người thật kiểm tra** | Transcript sai, feedback thiếu căn cứ, bias, overconfidence và privacy. Sinh viên xác nhận transcript/evidence; cố vấn hiệu chỉnh rubric và review case bất thường. |

## Bước 6.3 — Final decision

| Câu hỏi | Yes / Not Yet / No | Ghi chú |
|---|---|---|
| Actor và workflow đã rõ chưa? | Yes | Đã khoanh một actor, một JD và luồng trước/sau. |
| Baseline và success metric đã đo được chưa? | Not Yet | Metric đã định nghĩa nhưng buổi baseline chưa chạy. |
| Có data/input đủ dùng chưa? | Not Yet | Cần một JD, question bank, rubric versioned và ba transcript có consent. |
| Nếu AI sai, hậu quả có chấp nhận được không? | Not Yet | Chỉ chấp nhận trong pilot khi có human gate, quyền sửa/xóa và không dùng để dự đoán tuyển dụng. |
| Có người review/owner vận hành không? | Not Yet | Hùng là problem owner; cố vấn/peer review chưa được xác nhận. |
| Có cách non-AI đơn giản hơn không? | Yes | Question bank + checklist STAR + ghi âm + peer/cố vấn review. Đây là benchmark. |

Decision:

```text
Not Yet cho việc build Agent hoặc triển khai rộng.
Go cho pilot validation bán thủ công.
```

Lý do:

```text
Problem/workflow đủ rõ để pilot, nhưng pain ngoài trường hợp cá nhân, baseline,
độ nhất quán của feedback và reviewer vận hành chưa được xác nhận.
```

Nếu Go, pilot nhỏ nhất là:

```text
Một sinh viên (Hùng), một JD/vị trí, 3–5 competency, ba buổi cùng question scope/rubric;
cố vấn/peer có kinh nghiệm audit ít nhất một transcript + feedback; so với Rule benchmark.
```

Nếu Not Yet, cần validate gì trước:

```text
Phỏng vấn nhanh 2–3 sinh viên; chạy một mock baseline; xác nhận cố vấn review;
đo STAR/evidence/CSAT; kiểm tra bias, transcript và privacy trước khi mở rộng.
```

Nếu No-Go, nên làm gì thay AI:

```text
Giữ question bank + checklist STAR + ghi âm + peer/cố vấn review.
Nếu AI scoring thiếu nhất quán, bỏ scoring và chỉ giữ transcript/insight đã được người dùng xác nhận.
```

---

# Phase 7 — Individual Reflection (15')

Reflection không chỉ là "tôi dùng AI thế nào". Bạn cần phản tư về vai trò của mình trong nhóm.

Reflection là phần cá nhân. Không dùng AI để viết thay câu trả lời. Nếu dùng AI, chỉ dùng để gợi ý câu hỏi tự soi hoặc kiểm xem mình còn bỏ sót ý nào.

## Tôi đã tham gia vào phần nào?

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng |
|---|---|---|
| Scan cá nhân | Ghi 10 pain từ trải nghiệm chuẩn bị tìm việc, không chỉ tập trung vào CV. | Nhìn ra pain trọng tâm là chất lượng vòng luyện phỏng vấn, không phải thiếu một chatbot tổng quát. |
| Pitch Problem Card | Chuẩn bị ba candidates và chọn Mock Interview để pitch. | Candidate có actor, workflow, bottleneck, metric và non-AI benchmark rõ. |
| Challenge bài của bạn khác | Chưa có dữ liệu về bài của thành viên khác; tự challenge candidate bằng câu hỏi “Rule đã đủ chưa?”. | Tránh nhảy thẳng sang Agent; cần bổ sung challenge thật khi nhóm họp. |
| Gom trùng / cluster | Tạm nhóm candidates thành Interview, Application documents, Skill/evidence và Planning/progress. | Tạo khung hội tụ; còn chờ nhóm xác nhận. |
| Chọn candidate problem | Dùng scorecard tạm thời và nêu rõ giới hạn của self-score. | Mock Interview xếp đầu 31/35, nhưng chưa coi là đồng thuận nhóm. |
| Validation / research | Ghi rõ self-observation, khoảng trống validation và nghiên cứu ba pattern/tool chính thức. | Quyết định chỉ Go cho pilot validation, không triển khai rộng. |
| Workflow nhóm | Vẽ current/future, đặt human boundary và ba fallback. | AI chỉ đứng ở các bước follow-up, transcript/evidence và draft feedback. |
| Problem Statement | Viết v0, sau đó bổ sung AI intervention point, reviewer và risk thành v1. | PS v1 cụ thể hơn và có thể dùng để thiết kế pilot. |
| Rule / Workflow / Agent | So sánh cả ba mức và giữ Rule làm benchmark. | Chọn Workflow có AI hỗ trợ; chưa chọn Agent. |
| Decision | Đối chiếu baseline, data, reviewer và rủi ro. | Not Yet cho build/rollout; Go cho pilot bán thủ công. |

## Bảng dùng AI trong reflection

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai/hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Mở rộng danh sách pain và phân loại. | Gợi ý nhiều góc nhìn liên quan đến CV, interview và skill gap. | Dễ gom mọi khó khăn thành “AI career coach”. | Chỉ giữ pain gắn với trải nghiệm thật và có workflow cụ thể. |
| Problem Card | Kiểm tra actor, bottleneck, metric và alternative. | Giúp thấy metric cần cùng competency/rubric qua nhiều lần. | Có thể biến target thành “số liệu có vẻ thật” dù chưa đo. | Ghi rõ baseline chưa đo và target là giả thuyết pilot. |
| Workflow | Phản biện bước nào dùng Rule/AI/human. | Hữu ích khi tách follow-up, transcript, rubric và review. | Dễ thêm quá nhiều tính năng hoặc gọi toàn bộ là Agent. | Giữ luồng tuyến tính và đặt human boundary trước khi dùng feedback. |
| Research | Tạo từ khóa và khung so sánh existing solutions. | Giúp tìm pattern self-practice, AI feedback và structured interview. | Có thể bịa claim hoặc nguồn. | Chỉ dùng nguồn có link; không đưa số liệu chưa kiểm chứng. |
| Problem Statement | Soi field còn mơ hồ. | Nhắc bổ sung AI intervention point và quyền sửa/xóa. | Có xu hướng viết solution vào problem statement. | Tách problem v0 khỏi solution; chỉ thêm intervention ở v1. |
| Rule / Workflow / Agent | So sánh mức tự động hóa. | Làm rõ Rule phù hợp với question bank/rubric. | Dễ ưu tiên Agent vì nghe ấn tượng. | Chọn Workflow và giữ Agent ngoài pilot. |
| Decision | Kiểm tra điều kiện Go/Not Yet. | Giúp liệt kê baseline, data, reviewer và rollback. | Có thể kết luận Go khi chưa có evidence. | Chọn Not Yet cho build/rollout, chỉ Go cho validation pilot. |

## Reflection câu hỏi mở

- Tôi học được gì khi nghe top 3 problems của các bạn khác?
- Nhóm có lúc nào bị solution-first không?
- Tôi có thay đổi ý kiến sau khi bị challenge không?
- Tôi đóng góp gì thật sự vào artifact cuối?
- Điều khó nhất khi viết Problem Statement là gì?
- Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?

Reflection:

```text
Tôi nhận ra pain thật không phải “chưa có AI luyện phỏng vấn”, mà là thiếu một vòng luyện
có thể lặp lại và so sánh: câu hỏi đúng competency, follow-up dựa trên câu trả lời,
feedback có evidence và cùng rubric. Điểm khó nhất là không biến áp lực tìm việc của bản thân
thành bằng chứng cho toàn bộ sinh viên. Vì vậy tôi giữ baseline là “chưa đo”, coi scorecard là
self-score tạm thời và chọn Not Yet cho build lớn. Nếu làm lại, tôi sẽ phỏng vấn 2–3 bạn trước,
chạy một buổi mock baseline, rồi challenge mạnh hơn xem question bank + peer review đã đủ chưa.
```

## Tự kiểm cuối bài

- [x] [12đ cá nhân] Cá nhân có 5+ problems và top 3 Problem Cards.
- [ ] [12đ cá nhân] Tôi đã pitch rõ và challenge nhóm đúng trọng tâm. *(Chờ pitch/challenge trực tiếp với nhóm.)*
- [ ] Nhóm có nhật ký hội tụ từ candidates về 1 bài. *(Đã có bản tạm từ Hùng; chờ thành viên nhóm xác nhận.)*
- [x] [15đ nhóm] Nhóm có workflow trước/sau.
- [x] [20đ nhóm] Nhóm có Problem Statement v0/v1 với metric và boundary rõ.
- [x] [15đ nhóm] Nhóm có so sánh No AI / Rule / Workflow / Agent.
- [x] [10đ nhóm] Nhóm có Go / Not Yet / No-Go và lý do rõ.
- [x] [10đ cá nhân] Reflection cá nhân có nói rõ vai trò trong nhóm, cách dùng AI, điều học được và nếu làm lại sẽ đổi gì.
- [x] [6đ cá nhân] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp với AI.

---

*Day 02 Lab — Worksheet*
