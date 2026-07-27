# Group Report — Day 02

> Candidate nhóm chọn: **Hướng dẫn lab dài, hai nguồn không đồng bộ**  
> Nguồn đầu vào chính: Problem Card của Trần Minh Hiển — AI in Action Labs.

## Thành viên nhóm

| STT | Họ và tên | Mã học viên | Vai trò trong nhóm |
|-----|-----------|-------------|--------------------|
| 1 | Trương Minh Tâm | 2A202602005 | Tổng hợp group report, chuẩn hóa workflow và Problem Statement |
| 2 | Trần Minh Hiển | 2A202601812 | Đưa candidate problem chính, mô tả case thực tế và pain point |
| 3 |  Phạm Hải Yến  | 2A202601152 | Thành viên / Phân tích / Phản biện / Nhà đầu tư |
| 4 | Trần Hoàng Khôi| 2A202601778 | Thành viên / Phân tích / Nghiên cứu giải pháp / Thuyết trình |


# Phase 3 — Group Convergence

## Bước 3.1 — Trình bày candidate problems

Nhóm không chọn solution ngay. Mỗi candidate được nhìn qua các câu hỏi: actor là ai, workflow hiện tại nghẽn ở đâu, impact đo được không, và có thể so sánh Rule / Workflow / Agent không.

| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh |
|---|---|---|---|---|---|
| 1 | Trần Minh Hiển | Học viên phải đọc hướng dẫn lab dài trên web và README GitHub, hai nguồn cùng ý nhưng diễn đạt khác nhau | Học viên AI in Action Labs | Tự ghép hai nguồn trong đầu, không chắc nên theo cách hiểu nào | Rất phù hợp để đào sâu vì actor, workflow và metric rõ |
| 2 | Trương Minh Tâm | Theo dõi yêu cầu nhất quán khi nhiều tài liệu dài chỉ khớp nhau khoảng 90% | Học viên làm lab cá nhân | Đối chiếu README, worksheet/example và rubric | Trùng pattern với candidate #1 |
| 3 | Trương Minh Tâm | Tạo checklist có trích nguồn từ tài liệu lab dài | Học viên mới bắt đầu làm bài | Tự rút checklist nhưng không biết mỗi item đến từ nguồn nào | Hẹp hơn, có thể là một phần của solution |
| 4 | Trương Minh Tâm | Tìm lại quyết định/context trong nhóm trước deadline | Thành viên nhóm làm bài nộp chung | Note, file nhóm và tin nhắn rời rạc | Có pain thật nhưng lệch khỏi problem tài liệu lab |
| 5 | Phạm Hải Yến  | Học viên không hiểu mục đích từng phase nên làm cho có | Học viên mới học 1-2 buổi | Biết phải làm gì nhưng không hiểu vì sao làm bước đó | Gắn chặt với candidate #1 |
| 6 | Phạm Hải Yến  | Lab coach phải trả lời lặp lại câu hỏi “em cần nộp gì?” | Lab coach, học viên | Câu hỏi đọc hiểu hướng dẫn lặp 2-3 lần/lab | Impact rõ cho coach |
| 7 |  Trần Hoàng Khôi | Trước khi nộp, học viên không tự tin “đã đủ chưa?” | Học viên nộp bài | Không có pre-submit checklist có nguồn | Có thể là feature trong future workflow |
| 8 |  Trần Hoàng Khôi | README thay đổi nhưng web lab hoặc nội dung tóm tắt chưa cập nhật kịp | Học viên, lab operator | Không biết nguồn nào mới nhất | Rủi ro vận hành cần xử lý |
| 9 |  Trần Hoàng Khôi | FAQ cố định không cover hết cách hỏi của học viên | Học viên, lab coach | Câu hỏi theo ngữ cảnh riêng không có trong FAQ | Gợi ý vì sao AI Q&A có thể hữu ích |

## Bước 3.2 — Gom trùng / cluster

| Cluster | Candidates included | Pattern chung | Ghi chú |
|---|---|---|---|
| A — Hiểu hướng dẫn lab nhiều nguồn | #1, #2, #5, #8 | Học viên phải ghép web lab, README và ví dụ để hiểu yêu cầu cuối | Đây là cluster mạnh nhất |
| B — Checklist trước khi làm/nộp | #3, #7 | Cần checklist ngắn, có nguồn, giúp biết làm gì và còn thiếu gì | Có thể trở thành intervention trong solution |
| C — Hỏi đáp lặp lại với lab coach | #6, #9 | Câu hỏi đọc hiểu hướng dẫn lặp lại, coach bị kéo vào việc giải thích tài liệu | Cho thấy impact vận hành |
| D — Context nhóm | #4 | Thông tin nhóm rời rạc trước deadline | Có pain nhưng khác domain chính |

## Bước 3.3 — Shortlist

| Candidate | Vì sao vào shortlist | Rủi ro / điều chưa rõ |
|---|---|---|
| Hướng dẫn lab dài, web và README không đồng bộ hoàn toàn | Actor rõ; pain lặp mỗi lab; workflow hiện tại vẽ được; có baseline 30-60 phút đọc và 2-3 lần hỏi coach/lab | Cần xác nhận thêm bằng quick interview/survey ngoài nhóm |
| Checklist có trích nguồn từ tài liệu lab dài | Scope nhỏ, dễ pilot; có thể đo thời gian tạo checklist và số lỗi miss field | Có thể chỉ là solution component, chưa phải problem đủ rộng |
| Tìm lại quyết định/context nhóm trước deadline | Pain thật trong làm việc nhóm; có thể đo số lần hỏi lại và thời gian tìm context | Không trực tiếp giải quyết pain web vs README của lab |

## Bước 3.4 — Score để đồng thuận

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| Hướng dẫn lab dài, web và README không đồng bộ hoàn toàn | 5 | 5 | 4 | 5 | 5 | 5 | 5 | 34 |
| Checklist có trích nguồn từ tài liệu lab dài | 5 | 4 | 3 | 4 | 5 | 4 | 5 | 30 |
| Tìm lại quyết định/context nhóm trước deadline | 4 | 4 | 3 | 4 | 4 | 4 | 4 | 27 |

Candidate nhóm chọn:

```text
Hướng dẫn lab dài, hai nguồn web lab và README GitHub không đồng bộ hoàn toàn.
```

Vì sao chọn:

```text
Candidate này có actor cụ thể là học viên AI in Action Labs, có workflow hiện tại rõ, có baseline thời gian 30-60 phút và số lần hỏi coach 2-3 lần/lab. Vấn đề không chỉ là “tài liệu dài”, mà là học viên phải tự ghép hai nguồn cùng ý nhưng diễn đạt khác nhau, dẫn đến hiểu lệch, thiếu field hoặc không chắc trước khi nộp.
```

Vì sao không chọn các candidate còn lại:

```text
Checklist có trích nguồn là một phần quan trọng của solution, nhưng nếu chỉ chọn nó làm problem thì chưa chạm hết pain “hai nguồn không đồng bộ”.

Tìm lại context nhóm trước deadline có pain thật, nhưng domain khác hơn: nó nằm ở coordination trong nhóm, không phải đọc hiểu hướng dẫn lab.
```

Nếu có disagreement, nhóm xử lý thế nào:

```text
Nhóm thống nhất không chọn “AI Q&A” ngay từ đầu. Trước tiên nhóm chốt candidate problem là “học viên khó theo dõi yêu cầu nhất quán từ web lab và README”. Sau đó mới so sánh non-AI checklist/source of truth với workflow có AI.
```

---

# Phase 4 — Quick Validation + Research giải pháp

## Bước 4.1 — Quick validation

Validation hiện tại là tín hiệu ban đầu từ Problem Card và thảo luận nhóm. Nhóm chưa xem đây là bằng chứng tuyệt đối; cần phỏng vấn/survey thêm nếu triển khai thật.

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác | Nhóm sửa problem thế nào |
|---|---:|---|---|---|
| Problem Card / quan sát nội bộ | 1 case chi tiết | Học viên mất 30-60 phút đọc web + README; hỏi coach 2-3 lần/lab vì không chắc yêu cầu | Chưa có số liệu từ toàn cohort | Ghi rõ đây là baseline ban đầu, cần đo thêm |
| Thảo luận nhóm | Nhóm lab | Nhiều người đồng ý pain nằm ở việc phải ghép nhiều tài liệu, không phải folder/file lộn xộn | Có thể non-AI checklist giải được phần lớn miss field | Thêm non-AI alternative: source of truth + checklist 1 trang |
| Coach/support pattern | Quan sát từ lab | Câu hỏi “em cần nộp gì?”, “bước này để làm gì?”, “đủ chưa?” lặp lại | Chưa có log Discord/coach chính thức | Nếu pilot, cần đo số câu hỏi coach trước/sau |

### Câu hỏi validation bổ sung

Nếu có thêm thời gian, nhóm sẽ hỏi nhanh 5-10 học viên bằng các câu hỏi sau để biến tín hiệu ban đầu thành bằng chứng rõ hơn:

| Câu hỏi | Dùng để kiểm gì? | Cách đo |
|---|---|---|
| Lần gần nhất bạn làm lab, bạn mất bao lâu để đọc web lab + README trước khi bắt đầu làm? | Kiểm baseline thời gian 30-60 phút | Ghi số phút tự báo cáo |
| Bạn có phải hỏi lab coach vì không chắc yêu cầu không? Bao nhiêu lần/lab? | Kiểm metric 2-3 lần hỏi coach/lab | Đếm số lần hỏi |
| Chỗ nào làm bạn bối rối nhất: nộp gì, thứ tự bước, mục đích phase, hay format bài? | Xác định bottleneck cụ thể hơn | Chọn nhóm pain phổ biến |
| Khi web lab và README diễn đạt khác nhau, bạn thường làm gì? | Kiểm root cause “hai nguồn không đồng bộ hoàn toàn” | Chọn: tự đoán / hỏi bạn / hỏi coach / bỏ qua |
| Nếu có Q&A có trích nguồn ngay trên web lab, bạn có dùng trước khi hỏi coach không? | Kiểm nhu cầu solution | Thang 1-5 |

Insight sau validation:

```text
Pain thật không nằm ở việc học viên không tìm thấy file. File/folder khá rõ. Pain nằm ở việc học viên phải đọc hai nguồn dài, web lab và README GitHub, rồi tự ghép thành một cách hiểu nhất quán. Khi hai nguồn cùng ý nhưng diễn đạt khác nhau, học viên dễ miss thông tin, làm sai mục đích bước hoặc phải hỏi coach nhiều lần.
```

## Bước 4.2 — Research giải pháp đã có

Nhóm tìm pattern tương tự ở các công cụ tài liệu/Q&A có AI. Mục tiêu không phải copy tool, mà rút ra nguyên tắc: trả lời phải dựa trên nguồn, có cite, có fallback khi tài liệu chưa rõ.

| Nguồn / tool / case | Link | Họ giải quyết phần nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| GitBook AI Search | https://gitbook.com/docs/publishing-documentation/ai-search | Cho người đọc hỏi trực tiếp trong published docs; câu trả lời có phần sources liên quan | Pattern gần với Q&A trên web lab; trả lời ngay trong trải nghiệm đọc docs | Theo docs, AI search chủ yếu dựa trên content của docs site; nếu README GitHub là nguồn ngoài site thì cần sync/index riêng | Q&A hữu ích nhưng phải thiết kế pipeline đồng bộ README |
| GitBook AI internal content search | https://gitbook.com/docs/creating-content/searching-your-content/gitbook-ai | Tìm và tóm tắt câu trả lời trong knowledge base nội bộ | Có semantic search và trả lời nhanh từ tài liệu | Index update có thể mất thời gian; nếu tài liệu mơ hồ thì AI vẫn có thể trả lời sai | Cần hiển thị “knowledge last updated” và yêu cầu cite nguồn |
| NotebookLM | https://support.google.com/notebooklm/answer/16179559 và https://support.google.com/notebooklm/answer/16215270 | Cho thêm nhiều source như URL, Markdown, PDF, Google Docs; hỏi đáp dựa trên nguồn đã chọn và có citation | Phù hợp pattern “nhiều nguồn → hỏi theo ngữ cảnh → trả lời dựa trên sources” | Không phải widget trực tiếp trên web lab; cần học viên tự thêm nguồn nếu không tích hợp | Bài học: câu trả lời phải bám nguồn và người dùng cần thấy nguồn nào đang được dùng |
| Non-AI: source of truth + checklist 1 trang | Không cần tool riêng | Gộp yêu cầu thành một bản official, giảm miss field | Rẻ, dễ hiểu, ít rủi ro hallucination | Cần người duy trì; không trả lời tốt câu hỏi theo ngữ cảnh riêng của từng học viên | Nên làm trước hoặc song song với AI Q&A |

Research takeaway:

```text
Không nên build agent tự quyết toàn bộ bài lab. Hướng hợp lý hơn là Workflow: sync/index web lab + README, retrieve đoạn liên quan, AI trả lời ngắn có cite, học viên mở nguồn để xác nhận, và coach chỉ xử lý case ngoài tài liệu hoặc tài liệu thật sự chưa thống nhất.
```

---

# Phase 5 — Workflow + Problem Statement

## Bước 5.1 — Current workflow bản nhóm

Workflow hiện tại:

```text
CURRENT STATE — ~30-60 phút đọc + 2-3 lần hỏi coach / lab

[1 Mở trang web lab: 15-25']
→ [2 Click sang README GitHub: 15-25']
→ [3 Tự ghép hai nguồn trong đầu: 5-10']  <-- bottleneck
→ [4 Bắt đầu làm theo cách hiểu hiện tại]
→ [5 Gặp chỗ mơ hồ → hỏi lab coach: 2-3 lần/lab]  <-- bottleneck
→ [6 Gần deadline đọc lại toàn bộ]
→ [7 Sửa gấp hoặc nộp trong trạng thái chưa chắc]
```

| Bước | Actor | Input | Output | Thời gian/tần suất | Ghi chú |
|---|---|---|---|---|---|
| 1 | Học viên | Trang web lab | Hiểu sơ mô tả, deadline, cách nộp | 15-25 phút/lab | Dễ đọc lướt vì nhiều chữ |
| 2 | Học viên | README GitHub | Hiểu cấu trúc repo, file/folder, chi tiết kỹ thuật | 15-25 phút/lab | Mở tab riêng, giọng văn khác web |
| 3 | Học viên | Web + README | Cách hiểu tạm thời về yêu cầu | 5-10 phút/lab | Bottleneck: tự ghép hai nguồn |
| 4 | Học viên | Cách hiểu hiện tại | Bắt đầu làm bài | Lặp trong mỗi lab | Có thể miss field hoặc hiểu sai mục đích |
| 5 | Học viên → lab coach | Câu hỏi mơ hồ | Coach giải thích | 2-3 lần/lab | Bottleneck vận hành, không scale |
| 6 | Học viên | Web + README + bài đang làm | Kiểm lại trước deadline | 10-20 phút gần deadline | Dễ sửa gấp |
| 7 | Học viên | Bài đã chỉnh | Nộp bài | Mỗi lab | Vẫn không chắc “đã đủ chưa” |

Bottleneck chính:

```text
Bottleneck không nằm ở việc thiếu tài liệu, mà ở bước tự ghép hai nguồn dài và không đồng bộ hoàn toàn. Học viên cần biết phải làm gì, vì sao làm bước đó, và đã đủ yêu cầu chưa, nhưng hiện phải tự đoán hoặc hỏi coach.
```

## Bước 5.2 — Future workflow bản nhóm

Workflow sau tối ưu:

```text
FUTURE STATE — đọc ít hơn, hiểu nhanh hơn, ít hỏi coach hơn

[1 Mở trang web lab]
→ [2 Panel “Hỏi về lab này” xuất hiện cạnh hướng dẫn]
→ [3 Hỏi AI bằng ngôn ngữ tự nhiên]
→ [4 AI retrieve từ web lab + README đã sync/index]
→ [5 AI trả lời ngắn + bullet + cite nguồn]
→ [6 Học viên mở nguồn để xác nhận]  <-- human boundary
→ [7 Làm bài / pre-submit check “em còn thiếu gì không?”]
→ [8 Chỉ hỏi coach khi AI không chắc hoặc tài liệu thật sự lệch]

Fallback:
AI không chắc hoặc hai nguồn mâu thuẫn thật
→ không trả lời dứt khoát
→ hiện cả hai trích dẫn lệch nhau
→ gợi ý hỏi lab coach và log câu hỏi để sửa tài liệu/FAQ.
```

| Bước | Actor / hệ thống | Input | Output | Mức xử lý | Boundary / ghi chú |
|---|---|---|---|---|---|
| 1 | Học viên | Trang web lab | Mở đúng lab cần làm | Người dùng | Không thay đổi hành vi chính |
| 2 | Rule / pipeline | README GitHub + nội dung web lab | Knowledge base đã sync/index | Rule | Cần hiển thị lần cập nhật gần nhất |
| 3 | Học viên | Câu hỏi tự nhiên | Query cụ thể theo ngữ cảnh | Người dùng | Ví dụ: “Lab này em phải nộp gì?” |
| 4 | Retrieval workflow | Query + knowledge base | Các đoạn web/README liên quan | Workflow | Không dùng nguồn ngoài nếu chưa được phép |
| 5 | AI Q&A | Đoạn retrieve được | Câu trả lời ngắn + bullet + citation | Workflow có AI | Không bịa yêu cầu nếu nguồn không nói |
| 6 | Học viên | Câu trả lời + citation | Xác nhận cách hiểu cuối | Human boundary | Học viên vẫn mở nguồn gốc để kiểm |
| 7 | Học viên | Checklist / answer đã xác nhận | Làm bài hoặc check trước nộp | Người dùng | AI không viết thay reflection/problem card |
| 8 | Lab coach | Câu hỏi AI không chắc hoặc nguồn lệch thật | Quyết định/chỉnh tài liệu/FAQ | Human fallback | Coach xử lý ngoại lệ và cập nhật source of truth |

Before/after impact:

| Metric | Trước | Sau kỳ vọng | Ghi chú |
|---|---:|---:|---|
| Thời gian đọc để bắt đầu làm được việc | 30-60 phút | Dưới 20 phút | Target chính |
| Số lần hỏi lab coach vì không chắc yêu cầu | 2-3 lần/lab | ≤ 1 lần/lab | Chỉ hỏi case đặc biệt hoặc tài liệu thật sự lệch |
| Số nguồn học viên phải tự ghép thủ công | 2 nguồn dài | 1 câu trả lời có cite từ 2 nguồn | Học viên vẫn mở nguồn để kiểm |
| Tỷ lệ nộp thiếu field / hiểu sai bước | Chưa đo chính thức | ≤ 1 lỗi miss / 3 lab | Cần đo trong pilot |
| Độ tự tin trước khi nộp | 2-3/5 | ≥ 4/5 | Self-report sau lab |
| Risk mới | Không có hallucination AI | Có risk AI trích sai hoặc trả lời quá tự tin | Giảm bằng cite, confidence và fallback |

## Bước 5.3 — Problem Statement v0

| Field | Nội dung |
|---|---|
| **Actor** | Học viên AI in Action Labs đang làm bài lab cá nhân hoặc trong nhóm mới thành lập. |
| **Workflow** | Mỗi lab, học viên đọc trang web lab, mở README GitHub, tự ghép hai nguồn, bắt đầu làm, gặp mơ hồ thì hỏi lab coach, gần deadline đọc lại toàn bộ để kiểm thiếu. |
| **Bottleneck** | Bước tự ghép web lab và README vì hai nguồn dài, cùng ý nhưng diễn đạt khác nhau; học viên không chắc yêu cầu nào bắt buộc, mục đích từng bước là gì, và nộp đủ chưa. |
| **Impact** | Mất 30-60 phút đọc hiểu trước khi làm; hỏi lab coach 2-3 lần/lab; dễ miss field, sai format hoặc hiểu lệch mục tiêu bước học. |
| **Success Metric** | Giảm thời gian đọc để bắt đầu làm từ 30-60 phút xuống dưới 20 phút; giảm số lần hỏi coach vì không chắc yêu cầu xuống ≤ 1 lần/lab; tăng độ tự tin trước khi nộp lên ≥ 4/5. |
| **Boundary** | Không thay học viên làm bài; không tự bịa yêu cầu; không tự quyết source of truth nếu hai nguồn mâu thuẫn thật; lab coach vẫn xử lý ngoại lệ. |

---

# Phase 6 — Rule / Workflow / Agent + Decision

## Bước 6.0 — Ma trận độ phù hợp với AI

Bài toán của nhóm nằm ở ô:

```text
Độ mơ hồ cao + độ phức tạp trung bình/cao.
```

Vì sao:

```text
Độ mơ hồ cao vì web lab và README thường cùng ý nhưng diễn đạt khác nhau; học viên hỏi bằng ngôn ngữ tự nhiên và cần giải thích theo ngữ cảnh. Độ phức tạp trung bình/cao vì workflow cần sync/index hai nguồn, retrieve đoạn liên quan, trả lời có cite, pre-submit checklist, fallback khi không chắc. Tuy vậy, luồng xử lý vẫn tuyến tính nên chưa cần Agent tự lập kế hoạch động.
```

## Bước 6.1 — So sánh Rule / Workflow / Agent

| Mức | Phương án cho bài toán nhóm | Khi nào đủ | Rủi ro | Chọn? |
|---|---|---|---|---|
| **Rule** | Một nguồn official duy nhất, checklist 1 trang, FAQ cố định, sync README định kỳ | Đủ nếu pain chính chỉ là miss field hoặc không biết nộp gì | Cần maintain thủ công; không trả lời tốt câu hỏi “bước này để làm gì?” theo ngữ cảnh | Dùng làm nền, chưa chọn làm toàn bộ |
| **Workflow** | Sync/index web + README → retrieve đoạn liên quan → AI trả lời có cite → học viên xác nhận nguồn → pre-submit check | Phù hợp khi cần hỏi nhanh theo ngữ cảnh và đối chiếu hai nguồn dài | AI có thể trả lời sai nếu index cũ hoặc tài liệu mơ hồ; cần cite và fallback | **Chọn** |
| **Agent** | Agent tự đọc repo học viên, tự đánh giá bài, tự sửa hoặc tự quyết nộp | Chỉ cần nếu workflow có nhiều nhánh phức tạp và cần tự gọi nhiều công cụ/ra quyết định | Scope rộng, rủi ro cao, dễ thay học viên hoặc coach | Chưa chọn |

Mức chọn:

```text
Workflow.
```

Vì sao chọn:

```text
- Input có sẵn: web lab + README GitHub.
- Workflow khá rõ: sync/index → retrieve → answer with citation → human verify.
- AI hữu ích ở phần đọc hiểu ngôn ngữ tự nhiên, tóm tắt, đối chiếu cách diễn đạt và trả lời theo context.
- Human boundary rõ: học viên/coach vẫn xác nhận nguồn và quyết định cuối.
```

Vì sao không chọn mức đơn giản hơn:

```text
Rule/checklist có thể giảm miss field, nhưng chưa đủ cho câu hỏi theo ngữ cảnh như “bước này để làm gì?”, “Problem Card khác Problem Statement ở đâu?”, hoặc “web nói thế này README nói thế kia thì em nên hiểu thế nào?”.
```

Vì sao không chọn Agent:

```text
Chưa cần Agent vì bài toán chưa yêu cầu AI tự lập kế hoạch, tự sửa bài hoặc tự nộp. Agent còn tăng rủi ro thay học viên làm bài, bịa yêu cầu hoặc vượt boundary của lab coach.
```

## Bước 6.2 — Problem Statement v1

| Field | Nội dung |
|---|---|
| **Actor** | Học viên AI in Action Labs đang đọc hướng dẫn và làm bài lab. |
| **Workflow** | Mở web lab → đọc mô tả/deadline/rubric → mở README GitHub → đọc cấu trúc repo/chi tiết kỹ thuật → tự ghép hai nguồn → làm bài → hỏi coach khi mơ hồ → kiểm lại trước khi nộp. |
| **Bottleneck** | Tự ghép web lab và README khi hai nguồn dài, cùng ý nhưng diễn đạt khác nhau; học viên không có nơi xác nhận nhanh “phải làm gì, vì sao làm, đã đủ chưa”. |
| **Impact** | 30-60 phút đọc hiểu trước khi làm; 2-3 lần hỏi coach/lab; dễ miss field, sai format hoặc hiểu lệch mục tiêu bước học. |
| **Success Metric** | Thời gian đọc để bắt đầu làm dưới 20 phút; số lần hỏi coach vì không chắc yêu cầu ≤ 1 lần/lab; lỗi miss field ≤ 1 lỗi / 3 lab; độ tự tin trước nộp ≥ 4/5. |
| **Boundary** | AI chỉ trả lời dựa trên web + README đã index; phải cite nguồn; không tự bịa yêu cầu, không viết bài thay học viên, không approve ngoại lệ hoặc deadline. |
| **AI intervention point** | Sau khi học viên mở web lab và có câu hỏi cụ thể; trước khi hỏi lab coach hoặc đọc lại toàn bộ tài liệu. |
| **Mức chọn** | Workflow: sync/index tài liệu → retrieve → Q&A có cite → pre-submit check → human verify. |
| **Rủi ro & người thật kiểm tra** | Risk: index trễ, AI trích sai, hai nguồn mâu thuẫn thật. Người kiểm tra: học viên mở citation để xác nhận; lab coach xử lý câu hỏi không chắc và cập nhật FAQ/tài liệu. |

## Bước 6.3 — Final decision

| Câu hỏi | Yes / Not Yet / No | Ghi chú |
|---|---|---|
| Actor và workflow đã rõ chưa? | Yes | Actor là học viên lab; workflow đọc web → README → tự ghép → hỏi coach rõ. |
| Baseline và success metric đã đo được chưa? | Not Yet | Có baseline ban đầu 30-60 phút và 2-3 lần hỏi coach/lab, nhưng cần đo thêm trên 5-10 học viên. |
| Có data/input đủ dùng chưa? | Yes | Web lab và README GitHub là text có sẵn. |
| Nếu AI sai, hậu quả có chấp nhận được không? | Yes, nếu có boundary | AI không tự chốt; phải cite nguồn, báo không chắc và fallback về coach. |
| Có người review/owner vận hành không? | Not Yet | Cần lab team/mentor làm owner sync README và xử lý câu hỏi log. |
| Có cách non-AI đơn giản hơn không? | Yes | Checklist/source of truth giải được một phần, nên nên làm song song. |

Decision:

```text
Go với pilot nhỏ, chưa launch rộng.
```

Lý do:

```text
Problem rõ, workflow rõ, input có sẵn và metric có thể đo. Tuy nhiên validation còn là tín hiệu ban đầu, nên chỉ nên Go với pilot 1 lab để kiểm chứng pain và rủi ro trước khi mở rộng.
```

Pilot nhỏ nhất là:

```text
1 lab, ví dụ Day 02:
1. Index nội dung web lab + README GitHub.
2. Tạo widget/panel hỏi đáp hoặc prototype Q&A đơn giản.
3. Chuẩn bị 5-10 câu hỏi mẫu: “Lab này nộp gì?”, “Reflection có bắt buộc không?”, “Problem Card khác Problem Statement ở đâu?”.
4. Cho 5-10 học viên dùng thử trong 1 tuần.
5. Đo thời gian đọc để bắt đầu làm, số lần hỏi coach, số lỗi miss field và độ tự tin trước nộp.
```

Exit / rollback:

```text
- Nếu AI trả lời không có citation hoặc citation sai, không dùng để trả lời chính thức.
- Nếu index README trễ hoặc không ổn định, hạ xuống checklist/source of truth thủ công.
- Nếu học viên vẫn hỏi coach 2-3 lần/lab sau pilot, cần xem lại chất lượng tài liệu hoặc scope câu hỏi.
- Nếu AI bị dùng để viết bài thay học viên, tắt pre-submit answer dạng sinh nội dung và chỉ giữ checklist/citation.
```

Nếu Not Yet, cần validate gì trước:

```text
- Hỏi 5-10 học viên: mất bao lâu để đọc web + README trước khi làm?
- Log 1-2 lab: mỗi lab coach nhận bao nhiêu câu hỏi liên quan đến “nộp gì / làm bước này để làm gì / đủ chưa?”.
- Kiểm tra 3 bài nộp gần nhất: lỗi thiếu field hay hiểu sai yêu cầu xuất hiện ở đâu.
```

Nếu No-Go, nên làm gì thay AI:

```text
Tạo một source of truth chính thức cho mỗi lab: checklist 1 trang, phần “nộp gì”, phần “mỗi bước để làm gì”, FAQ cố định và changelog khi README/web thay đổi.
```

## Tự kiểm phần nhóm

- [x] Nhóm có nhật ký hội tụ từ nhiều candidates về 1 candidate problem.
- [x] Nhóm có quick validation ban đầu và kế hoạch validation bổ sung.
- [x] Nhóm có research giải pháp đã có với hyperlink.
- [x] Nhóm có current workflow và future workflow, kèm bottleneck, boundary và fallback.
- [x] Nhóm có Problem Statement v0 và Problem Statement v1.
- [x] Nhóm có so sánh Rule / Workflow / Agent và giải thích vì sao chọn Workflow.
- [x] Nhóm có final decision, pilot nhỏ nhất, rollback và các điểm cần validate thêm.

---

*Group Report — Day 02 Lab*
