# 1. Thông tin cá nhân và nhóm

- MHV: 2A202602358
- Họ tên: Đinh Xuân Quyền
- Tên nhóm:  Prompt Kiếm Tông
- Thành viên: Hoàng Quốc Dũng, Trần Đình Hinh, Đinh Xuân Quyền
- Case đã chọn: Case A — AI Tutor: Diagnostic Refresher



## 2. Problem Hypothesis Brief (Kết quả Chặng 1)

### 2.1. Solution — Gỡ solution khỏi hình thức cụ thể

- **Solution directive (Nguyên văn Case A):** Thêm nút “Tôi vẫn chưa hiểu” vào bài học. Khi học viên bấm nút, AI Tutor sử dụng nội dung bài hiện tại, các câu trả lời gần đây và lịch sử học tập để: 1. Đặt 2–3 câu hỏi chẩn đoán ngắn. 2. Chọn một khái niệm nền để học viên ôn lại. 3. Tạo một phần giải thích ngắn. 4. Đưa học viên trở về bài đang học.
- **Capability trung tính:** Cung cấp sự hỗ trợ tức thời để chẩn đoán và khắc phục lỗ hổng kiến thức nền tảng ngay tại điểm người học gặp khó khăn, giúp họ tiếp tục tiến độ học tập.

### 2.2. Change — Chuỗi thay đổi được kỳ vọng

`Solution (Chẩn đoán & ôn kiến thức nền tại chỗ) → Người học phát hiện được gốc rễ phần kiến thức bị hổng và hiểu bài ngay → Không bị gián đoạn mạch học, không nản chí → Outcome (Tăng tỉ lệ hoàn thành bài học, hiểu bài sâu sắc và tự tin hơn)`

- **Các thay đổi được kỳ vọng:**
  1. Người học nhận diện được chính xác khái niệm tiên quyết (prerequisite) mà mình đang thiếu thay vì đoán mò.
  2. Thời gian loay hoay tìm kiếm tài liệu giải thích giảm từ hàng chục phút xuống chỉ còn vài phút.
  3. Người học giảm cảm giác hoang mang, sợ tụt hậu và không bỏ cuộc giữa chừng.

### 2.3. Actor — Xác định các nhóm người liên quan

| Actor                                                 | Họ đang làm gì?                           | Pain hoặc hậu quả có thể có                                                           | Họ hưởng lợi thế nào?                                      |
| :---------------------------------------------------- | :-------------------------------------------- | :------------------------------------------------------------------------------------------ | :--------------------------------------------------------------- |
| **Learner (Học viên)** *(Chọn điều tra)* | Tự học hoặc nghe giảng, làm bài tập    | Kẹt bài, không biết mình hổng chỗ nào, sợ tụt lùi, nản chí                     | Được gỡ rối tức thì, theo kịp bài học                  |
| **Instructor / Giảng viên**                   | Soạn bài, giảng bài, trả lời thắc mắc | Bị quá tải khi nhiều học viên hỏi cùng câu hỏi cơ bản, ngắt quãng giờ giảng | Giảm tải việc giải đáp lặp đi lặp lại kiến thức nền |
| **Course Designer / Platform**                  | Tối ưu nội dung khóa học                 | Tỷ lệ drop-off cao ở các bài tập/khái niệm khó                                     | Tăng retention rate và mức độ hài lòng của người học  |

- **Actor nhóm chọn để điều tra trước:** Learner (Người học trực tiếp).
- **Vì sao chọn nhánh này:** Learner là người trực tiếp trải nghiệm sự bế tắc và chịu hậu quả trực tiếp (mất động lực, tụt hậu, bỏ học). Nếu không hiểu rõ hành vi tự xoay xở của learner thì mọi giải pháp hỗ trợ đều vô nghĩa.

### 2.4. Situation & Job

- **Mô tả Situation & Job:** Khi đang học bài mới và gặp một khái niệm hoặc bài tập khó hiểu, người học đang cố gắng tự hiểu và vượt qua điểm nghẽn bằng cách đọc lại tài liệu, tra cứu mạng hoặc hỏi người khác.
- **JTBD Hypothesis:** Khi gặp một khái niệm hoặc bài tập không hiểu trong lúc học, tôi muốn nhanh chóng gỡ rối và nắm được bản chất vấn đề, để có thể tiếp tục mạch học mà không bị nản chí hay tụt lùi so với tiến độ.

### 2.5. Pain — Hai cách giải thích cạnh tranh

- **Pain Hypothesis A (Giả thuyết kiến thức nền - Nhóm chọn):** Khi gặp một khái niệm/bài tập khó, người học gặp khó khăn trong việc hoàn thành bài học vì **không tự xác định được lỗ hổng kiến thức nền tảng của mình** (không biết những gì mình không biết), dẫn đến việc tra cứu mông lung, mất nhiều thời gian và dễ nản chí bỏ cuộc.
- **Pain Hypothesis B (Giả thuyết cách diễn đạt/tài liệu - Cạnh tranh):** Khi gặp khái niệm khó, người học không hiểu bài là vì **cách diễn đạt của giảng viên/tài liệu quá trừu tượng hoặc thiếu trực quan**, chứ không phải do thiếu kiến thức nền; chỉ cần một ví dụ minh họa trực quan hoặc một góc nhìn giải thích khác là hiểu ngay.
- **Giả thuyết nhóm chọn để điều tra trước:** Hypothesis A.
- **Lý do chọn:** Hypothesis A phản ánh giả định cốt lõi của tính năng "Diagnostic Refresher" (cần chẩn đoán kiến thức nền). Cần kiểm tra xem người học thực sự kẹt do kiến thức nền hay do nguyên nhân khác.

### 2.6. Evidence — Xác định điều cần tìm trước khi viết câu hỏi

| Cần kiểm tra                  | Evidence làm nhóm tin hơn                                                                                       | Evidence làm nhóm nghi ngờ hoặc bác bỏ                                                                               |
| :------------------------------ | :----------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------- |
| **Situation có thật**   | User nhớ rõ tình huống gần đây (môn học cụ thể, slide/bài tập cụ thể) bị tắc nghẽn kiến thức.  | User nói chung chung: "Lúc nào khó thì mình hỏi bạn", không nhớ được sự kiện cụ thể nào trong tuần qua. |
| **Pain có ý nghĩa**    | Bị kẹt thật sự, cảm thấy bối rối, sợ tụt hậu, tốn nhiều thời gian xoay xở hoặc bỏ dở bài học.  | Thấy bình thường, lướt qua luôn không cần hiểu, không ảnh hưởng gì tới việc học.                         |
| **Workaround tồn tại**  | Đã chủ động thử nhiều cách: đọc lại slide, tra cứu từ khóa, hỏi AI, hỏi bạn bè, xem YouTube...   | Ngồi đợi hoặc không làm gì cả; có gia sư/người kèm 1-1 giải đáp ngay lập tức.                            |
| **Consequence tồn tại** | Mất nhiều thời gian, lo lắng, hoang mang, mất mạch bài giảng phía sau.                                    | Không có hậu quả gì, bài thi vẫn qua bình thường dù bỏ qua đoạn đó.                                        |
| **Pattern có lặp**      | Tình trạng này xảy ra định kỳ mỗi khi gặp kiến thức mới hoặc học môn có tính logic/kế thừa cao. | Chỉ là sự cố hãn hữu một lần duy nhất do lỗi mạng hoặc tài liệu in mờ.                                      |

- **Điều gì phải đúng để giả thuyết đứng vững:** Người học thực sự có nỗ lực tự xoay xở khi kẹt bài, và việc không nhận diện được căn nguyên lỗ hổng kiến thức là rào cản chính khiến họ mất thời gian.
- **Điều gì có thể khiến nhóm sửa/bác bỏ giả thuyết:** Nếu người học thực tế biết rõ mình thiếu gì và chỉ cần ví dụ minh họa (ủng hộ Pain B); hoặc người học bị cản trở bởi rào cản xã hội/tâm lý (ngại làm phiền người khác) hơn là thiếu khả năng tự chẩn đoán.

### 2.7. Solution Parking Lot

1. **[AI]** Diagnostic Refresher: Đặt câu hỏi chẩn đoán và tóm tắt kiến thức nền tự động (theo directive gốc).
2. **[AI]** Multi-perspective Explainer: Tự động diễn giải lại đoạn văn bản/slide khó hiểu theo 3 cấp độ (cho người mới bắt đầu, ví dụ đời thực, ẩn dụ so sánh).
3. **[Không dùng AI]** Prerequisite Map & Glossary: Sơ đồ tri thức đính kèm cuối mỗi slide/bài học, gắn link nhảy thẳng về khái niệm nền tiên quyết cần nhớ.
4. **[Không dùng AI]** Anonymous Question Box: Nút bấm gửi câu hỏi ẩn danh tức thời đến giảng viên/trợ giảng trong lớp để tránh ngại ngùng làm phiền lớp học.
5. **[AI]** In-lecture Silent Buddy: AI bot trực tiếp giải nghĩa từ khóa/slide ngay trên giao diện học tập theo thời gian thực mà không ngắt quãng bài giảng.

---

## 3. Conversation Guide phiên bản cuối (Đã sửa sau khi luyện - Chặng 2 & 4)

### 3.1. Big 3 Điều quan trọng nhất cần học

| Điều cần học                                    | Evidence cần tìm                                                                                  | Điều gì khiến nhóm xem lại giả thuyết?                                                               |
| :-------------------------------------------------- | :-------------------------------------------------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------- |
| **1. Hành vi xoay xở đầu tiên**          | Hành động tức thời khi gặp chỗ khó (tự đọc lại, search, hỏi ai...).                    | Bỏ qua luôn hoặc có sẵn người kèm giải đáp ngay mà không cần tự mày mò.                     |
| **2. Quá trình & Rào cản tự tìm hiểu** | Cách họ tra cứu, vì sao chọn công cụ đó thay vì hỏi người khác; rào cản gặp phải. | Dễ dàng tìm ra lời giải đáp trong vài giây mà không gặp bất kỳ khó khăn hay nhầm lẫn nào. |
| **3. Cảm xúc & Hậu quả thực tế**        | Cảm giác bế tắc, áp lực tâm lý, thời gian tiêu tốn, mức độ hiểu bài cuối cùng.    | Coi việc không hiểu là chuyện nhỏ, không ảnh hưởng gì đến tiến độ hay tâm lý.              |

### 3.2. Nội dung Conversation Guide

- **Tiêu chí tuyển người:** Cần nói chuyện với người đang đi học/tự học đã có lúc không hiểu một phần bài học và phải tìm cách xử lý trong vòng 7 ngày gần đây.
- **Recruitment check:** "Trong tuần qua, bạn có lúc nào đang học (trên trường, tự học online...) mà đọc/xem tài liệu nhưng bị khựng lại vì không hiểu một phần nội dung không?"
- **Lời mở đầu:**
  > "Chào bạn, nhóm mình đang làm một bài thực hành nghiên cứu về hành vi học tập. Mình muốn lắng nghe một câu chuyện thực tế gần đây của bạn về cách bạn xử lý khi gặp khó khăn lúc học. Cuộc trò chuyện rất thoải mái, không có đúng sai và chỉ mất tầm 10-15 phút thôi. Bạn cho mình xin phép ghi âm lại để về nhóm nghe lại nhé?"
  > *(TUYỆT ĐỐI KHÔNG NÓI: Nhóm mình đang làm AI chẩn đoán kiến thức, bạn thấy tính năng này thế nào).*
  >
- **Story opener (Neo vào sự kiện cụ thể gần nhất):**
  > "Kể mình nghe về lần gần nhất bạn đang học mà tự nhiên thấy mình không hiểu bài đi. Lúc đó bạn đang học môn gì, ở hoàn cảnh nào (tự học hay đang ngồi trên lớp)?"
  >
- **Big 3 Questions (Hỏi đào sâu hành vi quá khứ):**
  1. *Hành vi xoay xở:* "Lúc tự nhiên thấy không hiểu đoạn đó, phản xạ đầu tiên của bạn là làm gì tiếp theo?"
  2. *Chi tiết quá trình:* "Tại sao bạn lại ưu tiên xử lý theo hướng đó thay vì các phương án khác (như hỏi thầy cô, hỏi bạn bè)?"
  3. *Hậu quả & Cảm xúc:* "Sau khi làm cách đó, bạn có hiểu được trọn vẹn phần đó không? Cảm giác của bạn lúc bị kẹt và sau khi giải quyết xong như thế nào?"
- **Probe bank (Đào sâu khi user trả lời ngắn):**
  - "Lúc đó chuyện gì xảy ra tiếp theo?"
  - "Bạn đã làm điều đó như thế nào?"
  - "Việc đó làm mất của bạn bao nhiêu thời gian?"
  - "Nếu bỏ qua đoạn đó thì sẽ ảnh hưởng gì đến đoạn sau?"
- **3 Phản xạ khi dữ liệu bắt đầu lệch chuẩn The Mom Test:**
  - *Khi user khen ngợi:* **Deflect** — Cảm ơn ngắn gọn rồi kéo về hành vi thực tế ("Cảm ơn bạn, mà ở lần gần nhất học bài đó thì bạn đã làm thế nào?").
  - *Khi user nói chung chung / tương lai:* **Anchor** — Kéo về quá khứ ("Lần gần nhất chuyện đó xảy ra cụ thể là hôm nào?").
  - *Khi user hiến kế / feature request:* **Dig** — Tìm hiểu gốc rễ nỗi đau ("Ý tưởng đó sẽ giúp bạn làm được gì mà hiện tại bạn chưa làm được?").

# 4. Practice Reflection (Chặng 4)

1. Câu hỏi nào đã giúp user kể một tình huống cụ thể?
   -> Câu hỏi mở đầu (Story opener): "Anh có thể chia sẻ về lần gần nhất mà anh đang học mà tự nhiên cảm thấy mình không hiểu bài thì lúc đó anh đang học môn gì và trong hoàn cảnh như thế nào ạ?" đã giúp user nhanh chóng nhớ lại tình huống thực tế (học Track 1 trên Vlearn, giáo viên giảng nhanh).
2. Chỗ nào mình cần làm tốt hơn ở lần phỏng vấn thật?
   -> Cần tránh hỏi trực tiếp người dùng về giải pháp (ví dụ câu hỏi trong buổi tập: "Theo góc nhìn của anh thì anh muốn cải thiện điều gì để xử lý việc tìm kiếm tài liệu đấy ạ?"). Thay vào đó, nên đào sâu hơn vào nỗi đau và hậu quả của việc mất 5-10 phút tìm slide (cảm xúc lúc đó ra sao, có bị tụt hậu so với video không).
3. Sau khi luyện, nhóm đã sửa Conversation Guide ở đâu và vì sao?
   -> Nhóm đã bổ sung thêm các câu hỏi vào Probe bank để đào sâu về cảm xúc/sự bực bội khi người dùng phải tốn thời gian "mò slide", đồng thời tự nhắc nhở nhau (phần "Phản xạ khi data lệch") phải tránh hỏi xin ý tưởng/giải pháp từ người dùng mà chỉ tập trung vào "nỗi đau" (pain) của họ.

# 5. AI Support Log

- **AI đã giúp gì:**
  - Định hướng framework và rà soát logic reverse từ Solution về Problem Hypothesis (Chặng 1 & Chặng 2).
  - Xử lý dữ liệu thô từ transcript phỏng vấn (Chặng 4): tự động phân tích và trích xuất user profile, pain points, workarounds và các exact quotes đắt giá.
- **Điểm sai/hời hợt của AI (nếu có):** AI đôi khi phân tích các câu trả lời thô có xu hướng sa đà vào việc đề xuất giải pháp (tính năng mới) thay vì tập trung đào sâu vào nỗi đau (pain point) và cảm xúc thực sự của người dùng.
- **Cách tự sửa:** Đã rà soát và review lại các bản tóm tắt của AI, đối chiếu với transcript/file ghi âm gốc để điều chỉnh lại góc nhìn, đảm bảo chỉ giữ lại những insight tập trung vào hành vi và khó khăn thực tế của user.
