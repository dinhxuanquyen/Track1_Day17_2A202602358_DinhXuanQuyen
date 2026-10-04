# 1. Thông tin cá nhân và nhóm

- MHV: 2A202602358
- Họ tên: Đinh Xuân Quyền
- Tên nhóm:  Prompt Kiếm Tông
- Thành viên: Hoàng Quốc Dũng, Trần Đình Hinh, Đinh Xuân Quyền
- Case đã chọn: Case A — AI Tutor: Diagnostic Refresher

# 2. Problem Hypothesis Brief (Kết quả Chặng 1)

- **Solution directive:** Thêm nút “Tôi vẫn chưa hiểu” vào bài học. Khi học viên bấm nút, AI Tutor sử dụng nội dung bài hiện tại, các câu trả lời gần đây và lịch sử học tập để chẩn đoán, chọn một khái niệm nền và tạo phần giải thích ôn lại ngắn trước khi đưa học viên về bài đang học.
- **Capability trung tính:** Khả năng chẩn đoán lỗ hổng kiến thức nền của người học khi họ đang gặp khó khăn và cung cấp ngay nội dung bổ trợ phù hợp.
- **Các thay đổi được kỳ vọng (Change):**
  1. Học viên nhận biết được việc mình không hiểu bài là do hổng kiến thức cũ.
  2. Học viên chấp nhận dừng lại một nhịp để ôn lại kiến thức nền thay vì bỏ cuộc hoặc học vẹt.
  3. Học viên lấp được lỗ hổng và tiếp tục hoàn thành bài học hiện tại.
- **Actor:** Learner (Học viên) - Lý do: Họ là người trực tiếp trải nghiệm sự "không hiểu bài" và chịu hậu quả trực tiếp là sự nản chí hoặc bỏ cuộc.
- **Situation & Job:** Khi đang bị mắc kẹt (không hiểu) ở một nội dung bài học mới, học viên đang cố gắng tìm cách hiểu bài bằng cách tự đọc lại nhiều lần, lật tìm bài cũ, lên Google hoặc hỏi bạn bè.
- **JTBD Hypothesis:** Khi bị kẹt lại ở một khái niệm khó, tôi muốn nhanh chóng tìm ra phần kiến thức nền mình đang thiếu, để có thể hiểu bài và đi tiếp mà không bị nản chí.
- **Problem Hypothesis (Giả thuyết chốt):** Khi không hiểu một phần bài học, học viên gặp khó khăn trong việc tự gỡ rối vì họ không biết chính xác mình đang bị hổng kiến thức nền nào, dẫn đến tốn thời gian lật tìm tài liệu một cách vô định hoặc nản chí bỏ cuộc.
- **Điều kiện để giả thuyết đứng vững:** Học viên thực sự có nhận thức được mình "không hiểu", có ý thức muốn tìm cách giải quyết (không skip bài ngay) nhưng bị bế tắc do không biết bắt đầu ôn lại từ đâu.
- **Điều gì có thể khiến nhóm sửa hoặc bác bỏ giả thuyết:** Khi phỏng vấn, học viên nói rằng khi không hiểu họ thường skip (bỏ qua) luôn, không quan tâm việc ôn lại; hoặc họ đã có cách dùng ChatGPT/Google tự gỡ rối rất nhanh và không hề thấy đó là khó khăn.

# 3. Conversation Guide phiên bản cuối (Đã sửa sau khi luyện - Chặng 4)

- **Tiêu chí tuyển người:** Chúng tôi cần nói chuyện với người đã không hiểu một phần bài học và phải tìm cách xử lý trong vòng 7 ngày gần đây.
- **Recruitment check:** Trong 1 tuần qua, có lúc nào bạn đang học mà bị kẹt lại vì không hiểu một phần nội dung bài không?
- **Lời mở đầu:** Chào bạn, nhóm mình đang làm một bài tập nghiên cứu về trải nghiệm học tập. Mình muốn nghe về cách bạn xử lý khi gặp khó khăn trong lúc học. Buổi phỏng vấn không có câu trả lời đúng sai, mình chỉ muốn lắng nghe câu chuyện thực tế của bạn thôi.
- **Story opener:** Kể mình nghe về lần gần nhất bạn đang học mà thấy mình không hiểu bài. Lúc đó bạn đang học môn gì, ở hoàn cảnh nào?
- **Big 3 Questions:**
  1. Lúc phát hiện ra mình không hiểu bài, bạn đã thực sự làm gì tiếp theo?
  2. Việc tìm cách hiểu lại phần đó mất của bạn bao lâu? Điều gì cản trở bạn nhiều nhất trong lúc đó?
  3. Sau khi thử các cách đó (hoặc bỏ cuộc), chuyện gì đã xảy ra tiếp theo với tiến độ học của bạn?
- **Probe bank:**
  - “Lúc đó chuyện gì xảy ra tiếp theo?”
  - “Vì sao bạn lại chọn cách Google/hỏi bạn bè... thay vì cách khác?”
  - “Kết quả của việc đó là gì?”
  - “Nếu không tìm được câu trả lời thì sao?”

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
