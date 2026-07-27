# Phase 7 — Individual Reflection

## Tôi đã tham gia vào phần nào?

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng |
|---|---|---|
| Scan cá nhân | Tôi scan 10 problems từ trải nghiệm học tập, làm bài lab và làm việc nhóm. Tôi cố gắng không bắt đầu bằng “làm AI”, mà bắt đầu từ actor, workflow, bottleneck và dấu hiệu thật. | Có danh sách problem đủ rộng để chọn top 3. Các problem tập trung vào pain thật: tài liệu dài, yêu cầu chưa hoàn toàn thống nhất, khó rút checklist và khó tìm lại context nhóm. |
| Pitch Problem Card | Tôi chọn pitch Problem Card #1: hợp nhất yêu cầu từ nhiều tài liệu dài không khớp hoàn toàn. | Card này có actor rõ là sinh viên làm lab, workflow rõ, bottleneck cụ thể ở bước đối chiếu web lab và README GitHub, và có metric thời gian 30-45 phút xuống dưới 15 phút. |
| Challenge bài của bạn khác | Tôi chuẩn bị câu hỏi challenge: bài này chỉ cần một checklist/source of truth cố định, hay thật sự cần AI đọc nhiều nguồn và phát hiện điểm không thống nhất? | Câu hỏi này giúp tránh nhảy sang AI quá sớm và buộc nhóm so sánh giữa process fix, rule/checklist và workflow có AI. |
| Gom trùng / cluster | Tôi đề xuất gom các problem liên quan đến “đọc hiểu tài liệu dài”, “rút checklist”, và “theo dõi yêu cầu không thống nhất” vào cùng một cluster. | Cluster giúp thấy pattern chung: pain không nằm ở folder/file lộn xộn, mà ở việc nhiều tài liệu dài chỉ khớp nhau phần lớn. |
| Chọn candidate problem | Tôi ưu tiên candidate “theo dõi yêu cầu nhất quán khi nhiều tài liệu dài không khớp hoàn toàn” vì có workflow rõ và dễ đo. | Candidate này đủ hẹp cho lab, có thể vẽ before/after workflow và có thể so sánh Rule / Workflow / Agent. |
| Validation / research | Tôi ghi lại validation ban đầu từ Problem Card/thảo luận nhóm và bổ sung kế hoạch hỏi nhanh 5-10 học viên. Tôi cũng đưa vào research các pattern như GitBook AI Search, GitBook AI internal search, NotebookLM và phương án non-AI source of truth. | Nhóm có cơ sở để không nghĩ trong chân không: pain đã có tín hiệu ban đầu, nhưng vẫn cần đo thêm trước khi launch rộng. |
| Workflow nhóm | Tôi chuẩn hóa current/future workflow nhóm: web lab → README → tự ghép hai nguồn → hỏi coach; future là sync/index → retrieve → AI Q&A có citation → học viên xác nhận. | Workflow nhóm thể hiện rõ bottleneck, điểm AI hỗ trợ, human boundary và fallback khi AI không chắc. |
| Problem Statement | Tôi hoàn thiện Problem Statement v0/v1 với actor, workflow, bottleneck, impact, success metric, boundary, AI intervention point và rủi ro. | Problem Statement cuối rõ hơn bản ban đầu vì đã thêm metric, boundary và người thật kiểm tra. |
| Rule / Workflow / Agent | Tôi lập luận chọn Workflow: AI hỗ trợ đọc nhiều nguồn, tạo checklist có trích nguồn và đánh dấu điểm không thống nhất; con người vẫn chốt cách hiểu cuối. | Nhóm không chọn Agent quá sớm. Rule/checklist được giữ làm nền, nhưng workflow có AI phù hợp hơn cho câu hỏi theo ngữ cảnh. |
| Decision | Tôi cùng nhóm chốt “Go với pilot nhỏ, chưa launch rộng”. | Decision có điều kiện rõ: pilot 1 lab, đo thời gian đọc, số lần hỏi coach, lỗi miss field và độ tự tin trước khi nộp. |

## Bảng dùng AI trong reflection

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai/hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Dùng AI để gợi ý thêm hướng quan sát problem sau khi đã có bối cảnh học tập/lab. | AI giúp mở rộng danh sách và nhắc tôi ghi actor, workflow, dấu hiệu thật. | Ban đầu AI dễ hiểu sai pain thành “file/folder lộn xộn”. | Tôi sửa lại: file/folder đã rõ, pain thật là nhiều tài liệu dài chỉ khớp nhau khoảng 90% nên khó theo dõi nhất quán. |
| Problem Card | Dùng AI để đưa nội dung vào đúng template Problem Card. | AI giúp viết đủ field: actor, current workflow, bottleneck, impact, metric, non-AI alternative, AI hypothesis. | AI có xu hướng chọn case dễ hơn như “kiểm tra file đủ chưa”, chưa bắt đúng phần khó của bài. | Tôi chỉnh lại card #1 thành “hợp nhất yêu cầu từ nhiều tài liệu dài không khớp hoàn toàn”. |
| Workflow | Dùng AI để chuyển mô tả workflow thành current/future workflow có thời gian ước lượng. | AI giúp tách bottleneck và đặt human boundary ở bước sinh viên/mentor xác nhận cách hiểu cuối. | Một số mốc thời gian ban đầu chưa cộng nhất quán hoặc chưa phản ánh đúng bottleneck. | Tôi sửa mốc thời gian để workflow current/future hợp lý hơn: 42 phút xuống 14 phút. |
| Research | Dùng AI để gợi ý pattern/tool tương tự rồi kiểm lại link nguồn chính thức trước khi đưa vào group report. | AI giúp nhớ các pattern docs Q&A có nguồn như GitBook/NotebookLM và nhắc so sánh với non-AI source of truth. | AI có thể đưa claim quá rộng hoặc không có nguồn kiểm chứng. | Tôi chỉ giữ các ý có hyperlink rõ và không dùng số liệu tiết kiệm thời gian nếu chưa verify. |
| Problem Statement | Dùng AI gián tiếp để kiểm xem các thành phần nền đã đủ chưa. | AI giúp nhắc các field cần có: actor, workflow, bottleneck, impact, success metric, boundary, AI intervention point. | AI có thể viết Problem Statement quá sớm hoặc quá solution-first. | Tôi chỉnh Problem Statement theo workflow và boundary thật: AI trả lời có cite, con người chốt source of truth. |
| Rule / Workflow / Agent | Dùng AI để so sánh nhanh Rule / Workflow / Agent. | AI giúp thấy checklist/source of truth có thể là non-AI alternative tốt. | AI dễ đẩy sang workflow/agent nếu chỉ nhìn thấy “nhiều tài liệu dài”. | Tôi giữ boundary: AI chỉ gợi ý và phát hiện điểm lệch, con người chốt source of truth. |
| Decision | Dùng AI để kiểm xem quyết định Go/Not Yet/No-Go đã có đủ điều kiện và rollback chưa. | AI giúp nhắc cần pilot nhỏ, metric đo và fallback khi AI trả lời sai. | AI có thể khuyến khích Go quá nhanh nếu bỏ qua validation. | Tôi giữ quyết định “Go với pilot nhỏ”, kèm điều kiện cần đo thêm trước khi launch rộng. |

## Reflection câu hỏi mở

Reflection:

```text
Điều tôi học rõ nhất trong phần cá nhân là một problem tốt không nhất thiết phải là problem nghe “AI” nhất. Ban đầu tôi dễ nghĩ theo hướng kiểm tra file, checklist hoặc tự động hóa bài nộp. Nhưng khi nhìn lại case thật, khó khăn không nằm ở việc file/folder sắp xếp lộn xộn. Các file đã khá rõ trong từng folder. Pain thật là người học phải đọc nhiều tài liệu dài, các tài liệu khớp nhau phần lớn nhưng không hoàn toàn giống nhau, nên phải tự hợp nhất yêu cầu để biết nên làm theo cách hiểu nào.

Khi viết Problem Card, tôi thấy workflow giúp bóc đúng bottleneck. Nếu chỉ nói “tài liệu dài” thì problem còn chung. Khi vẽ workflow, điểm nghẽn rõ hơn: đọc README, đọc worksheet, xem example, tự rút yêu cầu chính, rồi đối chiếu những điểm lệch giữa các nguồn. Bước khó nhất là phân biệt đâu là yêu cầu bắt buộc, đâu là ví dụ, đâu là diễn đạt khác nhưng cùng ý, và đâu là điểm thật sự không thống nhất.

Tôi cũng học được rằng không nên nhảy thẳng sang Agent. Với case này, một checklist/source of truth cố định có thể giải quyết nhiều phần nếu được duy trì tốt. AI chỉ hợp lý khi nó hỗ trợ đọc nhiều nguồn, tạo checklist có trích nguồn và đánh dấu điểm không thống nhất để con người xác nhận. Boundary quan trọng là AI không được tự chốt nguồn đúng cuối cùng; sinh viên hoặc mentor vẫn phải quyết định.

Nếu làm lại, tôi sẽ validation sớm hơn bằng cách hỏi vài bạn học: họ mất bao lâu để đọc và đối chiếu tài liệu trước khi làm bài, họ thường bị kẹt ở chỗ nào, và họ có từng hỏi lại vì web lab/README nói hơi khác nhau không. Tôi cũng sẽ challenge nhóm mạnh hơn ở câu hỏi: “Có cần AI không, hay chỉ cần một source of truth tốt hơn?” Câu hỏi đó giúp nhóm không chọn giải pháp vì công nghệ, mà vì đúng bottleneck.
```

## Tự kiểm cuối bài

- [x] [12đ cá nhân] Cá nhân có 5+ problems và top 3 Problem Cards.
- [x] [12đ cá nhân] Tôi đã chuẩn bị pitch rõ và có câu hỏi challenge đúng trọng tâm.
- [x] Nhóm có nhật ký hội tụ từ candidates về 1 bài.
- [x] [15đ nhóm] Nhóm có workflow trước/sau.
- [x] [20đ nhóm] Nhóm có Problem Statement v0/v1 với metric và boundary rõ.
- [x] [15đ nhóm] Nhóm có so sánh No AI / Rule / Workflow / Agent.
- [x] [10đ nhóm] Nhóm có Go / Not Yet / No-Go và lý do rõ.
- [x] [10đ cá nhân] Reflection cá nhân có nói rõ vai trò trong nhóm, cách dùng AI, điều học được và nếu làm lại sẽ đổi gì.
- [x] [6đ cá nhân] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp với AI.
