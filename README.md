# Track1_Day17_2A202602776_NguyenVanAn

## 1. Thông tin cá nhân và nhóm

| Trường                | Nội dung                                                               |
| --------------------- | ---------------------------------------------------------------------- |
| Bài lab               | Track 1 – Day 17: Finding and Validating Pain Points                   |
| Mã học viên           | 2A202602776                                                            |
| Họ tên                | Nguyễn Văn An                                                          |
| Nhóm                  | 3aecaykhe                                                              |
| Thành viên            | Nguyễn Văn An, Lưu Xuân Dũng, Nguyễn Long Khánh                        |
| Case                  | Case B — AI Notes: Personal Learning Notes                             |
| Ngày phỏng vấn        | 04/10/2026, theo xác nhận của Nguyễn Văn An                            |
| Người làm interviewer | Nguyễn Văn An, theo thông tin người học đã thực hiện phỏng vấn         |
| Người tham gia        | P01 — mã ẩn danh trong bài; transcript người học cung cấp ghi tên Oanh |
| Bản ghi               | `interview/recording.m4a` đã có trong thư mục bài làm gốc              |

**Phạm vi bài:** reverse solution directive thành giả thuyết vấn đề và chuẩn bị problem interview theo The Mom Test. Đây là buổi luyện kỹ năng, chưa phải validation hay đặc tả triển khai AI Notes.

**Phân biệt nguồn thông tin:**

- **Yêu cầu lab:** các điều được VLearn quy định.
- **Giả định:** actor, tình huống, barrier, consequence và outcome cần được kiểm chứng. Việc diễn đạt hợp lý không biến chúng thành facts.
- **Thông tin người học xác nhận:** An đã phỏng vấn, có file ghi âm, ngày phỏng vấn 04/10/2026.
- **Đề xuất biên tập:** phần phân tích và guide dưới đây được hoàn thiện sau khi tham khảo tài liệu nhóm và bài của Dũng. Chưa xác nhận nhóm đã thống nhất hoặc dùng phiên bản này trong giờ lab.
- **Evidence hiện có:** transcript do An cung cấp, có mốc 00:01–05:58 và các đoạn `[không rõ]`/`[?]`. Notes và reflection được biên tập từ transcript này, chưa đối chiếu trực tiếp audio. Các phát biểu về hành vi là lời P01 tự thuật, không phải quan sát độc lập. Không sửa các từ chưa rõ thành chi tiết chắc chắn.
- **Giới hạn thực hành:** transcript chưa xác nhận sự kiện ghi chú trong bảy ngày, người ngoài nhóm hay consent; chưa rõ gần sáu phút là toàn bộ lượt hay trích đoạn. Thiếu đoạn consent không đồng nghĩa không có consent. Không xem bước An tự nghe lại là đã hoàn thành.

## 2. Problem Hypothesis Brief

Các phần 2.1–2.6 giữ baseline giả thuyết trước khi đối chiếu transcript, kế thừa tài liệu chung của nhóm và được chỉnh để dễ kiểm chứng. Nhận định về người dùng ở các phần này là **Giả định**. Phần 2.7 bổ sung kết quả đối chiếu lượt P01; không viết lại giả thuyết ban đầu như thể nhóm đã biết trước kết quả phỏng vấn.

### 2.1 Solution — từ directive đến capability trung tính

**Directive từ đề lab:** Trong khi học, học viên có thể highlight một đoạn nội dung, đánh dấu “Chưa hiểu”, hoặc viết một câu hỏi hay ghi chú ngắn. Khi bài học kết thúc, AI Notes kết hợp những dấu vết này với nội dung bài để tạo một bản ghi chú có cấu trúc. Học viên có thể chỉnh sửa và xác nhận trước khi lưu.

| Thành phần   | Nội dung đề bài                                                        |
| ------------ | ---------------------------------------------------------------------- |
| Trigger      | Học viên hoàn thành bài học                                            |
| Input        | Nội dung bài, highlights, điểm “Chưa hiểu”, câu hỏi và ghi chú cá nhân |
| AI action    | Chọn lọc, nhóm và tổ chức thông tin                                    |
| Output       | Bản ghi chú cá nhân có cấu trúc                                        |
| User control | Học viên chỉnh sửa và xác nhận trước khi lưu                           |

**Capability trung tính:** giúp người học giữ lại nội dung có ý nghĩa với mình cùng các điểm còn vướng, tổ chức chúng để có thể tìm và sử dụng lại; người học kiểm tra nội dung trước khi lưu.

Capability này có thể được hỗ trợ bằng nhiều cách. Không mặc định AI, tự động tóm tắt hoặc một kiểu giao diện cụ thể là giải pháp duy nhất. Không suy rằng ghi chú cá nhân được chia sẻ cho giảng viên.

### 2.2 Change — chuỗi thay đổi kỳ vọng

`Có bản ghi chú gắn với dấu vết cá nhân → learner kiểm tra/chỉnh sửa và lưu → learner mở lại khi có việc cần làm → tìm được ý hoặc câu hỏi cần dùng → giảm công sức tái dựng nội dung để ôn tập.`

| Mắt xích    | Thay đổi kỳ vọng — Giả định                                  | Cách kiểm tra trong discovery                                                     |
| ----------- | ------------------------------------------------------------ | --------------------------------------------------------------------------------- |
| Giữ lại     | Learner lưu đúng nội dung mình cần nhớ hoặc còn chưa hiểu    | Một sự kiện thật: đã chọn gì, vì sao, lưu bằng cách nào                           |
| Kiểm tra    | Learner rà soát nội dung và nhận ra chỗ thiếu hoặc chưa đúng | Hỏi việc đã kiểm tra/chỉnh sửa tài liệu thực tế, không hỏi ý định dùng tính năng  |
| Sử dụng lại | Learner tìm và dùng lại nội dung khi ôn hoặc làm bài         | Lần mở lại gần nhất, mục đích, thao tác và kết quả                                |
| Outcome     | Ít mất công tìm/tạo lại nội dung, hỗ trợ hoàn thành việc học | Công sức và hậu quả trong sự kiện; chỉ ghi con số người tham gia thực sự cung cấp |

**Output khác outcome:** có một bản ghi chú chưa chứng minh người học sẽ sử dụng lại, nhớ tốt hơn, tăng điểm hoặc hoàn thành khóa học. Nếu không có nhu cầu mở lại, chuỗi giá trị có thể dừng ở bước lưu. Không đặt mức cải thiện phần trăm khi chưa có baseline.

### 2.3 Actor — xem xét các bên liên quan

| Actor                       | Công việc có thể liên quan                       | Pain/consequence giả định                                  | Lợi ích kỳ vọng                                                         |
| --------------------------- | ------------------------------------------------ | ---------------------------------------------------------- | ----------------------------------------------------------------------- |
| Learner                     | Học, quyết định lưu gì, tìm và dùng lại nội dung | Mất mạch theo bài khi ghi; khó tìm/hiểu lại phần đã lưu    | Giữ được ngữ cảnh, tìm lại nội dung phục vụ công việc học               |
| Instructor/coach            | Giải thích kiến thức, hướng dẫn việc ôn          | Có thể phải giải thích lại nội dung chưa được learner hiểu | Learner chuẩn bị câu hỏi cụ thể hơn; chưa có evidence từ instructor     |
| Platform owner/course admin | Tổ chức trải nghiệm và hỗ trợ học tập            | Có thể có chi phí hỗ trợ ở các điểm vướng                  | Trải nghiệm học thuận lợi hơn; chưa có evidence về retention/completion |

**Chọn learner để điều tra trước:** họ trực tiếp trải nghiệm việc chọn, lưu và dùng lại nội dung. Quan sát chuỗi hành vi này phù hợp Case B hơn việc suy từ chỉ số quản trị khóa học. Instructor và platform owner là stakeholder liên quan; job/pain của họ cần được nghiên cứu riêng, không suy từ ba cuộc luyện phỏng vấn learner.

### 2.4 Situation & Job

**Situation & Job — Giả định:** khi học một bài có nhiều nội dung mới và cần giữ lại phần sẽ dùng sau, learner cố vừa theo dõi nội dung vừa chọn/lưu các ý và câu hỏi, bằng ghi chép, highlight, bookmark hoặc lưu ảnh. Vướng mắc có thể xuất hiện ở việc chọn/lưu ngay lúc học, hoặc ở việc tìm/hiểu lại sau đó. Các công cụ và cách làm này là khả năng cần hỏi, không phải hành vi đã xác nhận của người An phỏng vấn.

**JTBD Hypothesis:** “Khi học nội dung mới mà tôi cần dùng lại, tôi muốn giữ được các ý cần nhớ cùng những điểm còn vướng theo cách dễ tìm và hiểu lại, để tiếp tục ôn tập hoặc hoàn thành việc học mà không phải tái dựng toàn bộ nội dung.”

Job vẫn tồn tại khi bỏ tên AI Notes và công nghệ AI khỏi bối cảnh. Chưa giả định người học thích bản tóm tắt hơn ghi chép tự làm.

### 2.5 Các giả thuyết pain cạnh tranh

| Nhánh                            | Situation, job, barrier và consequence — Giả định                                                                                                                              |
| -------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **A — chọn/lưu trong lúc học**   | Khi theo dõi nội dung mới, learner khó giữ lại các ý cần dùng vì việc chọn và ghi diễn ra cùng lúc với việc theo bài, dẫn đến bỏ sót ý hoặc phải quay lại học liệu để bổ sung. |
| **B — tìm/hiểu lại sau khi học** | Khi ôn hoặc làm bài, learner khó sử dụng nội dung đã lưu vì thiếu ngữ cảnh hoặc khó định vị ý cần tìm, dẫn đến phải mở học liệu gốc hoặc tạo lại phần ghi chú.                 |

**Điều tra A trước:** tài liệu nhóm chọn A vì barrier có thể bắt đầu ngay lúc học. Đây là thứ tự điều tra, chưa phải kết luận A là pain chính hoặc nguyên nhân của B. Guide phải hỏi cả khâu tạo và khâu sử dụng lại để phân biệt hai nhánh.

**Cách giải thích khác cần giữ mở:** người học chưa hiểu khái niệm; tài liệu gốc đã đáp ứng đủ; mục đích lưu là làm bài ngay chứ không để ôn; hoặc người học không gặp khó khăn đáng kể. Không ép các trường hợp này thành pain ghi chú.

### 2.6 Evidence Map

Đây là **kế hoạch tìm evidence**, không phải kết quả phỏng vấn của An.

| Cần kiểm tra        | Evidence làm tin hơn                                                                      | Evidence làm nghi ngờ/sửa/bác bỏ                                                         |
| ------------------- | ----------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- |
| Situation có thật   | Một sự kiện trong 7 ngày: bài nào, khi nào, đã ghi/highlight/lưu gì                       | Không có sự kiện phù hợp: cần tuyển người khác, không kết luận pain không tồn tại        |
| Pain có ý nghĩa     | Khoảnh khắc cụ thể việc lưu làm gián đoạn theo bài, hoặc không tìm/hiểu lại được nội dung | Job hoàn thành thuận lợi; barrier chính là hiểu khái niệm, không phải ghi chú            |
| Workaround tồn tại  | Dừng/xem lại bài, thay cách lưu, bổ sung hoặc tổ chức lại nội dung; user kể trình tự      | Cách hiện tại đủ tốt, không phải làm thêm; thiếu workaround riêng lẻ chưa đủ bác bỏ pain |
| Consequence tồn tại | User mô tả ảnh hưởng tới việc đang làm, công sức phát sinh hoặc nội dung bỏ sót           | Bất tiện nhẹ, không ảnh hưởng đáng kể tới job                                            |
| Pattern có lặp      | Một sự kiện trước đó có hoàn cảnh và hành vi/hậu quả tương tự                             | Chỉ một sự kiện đặc biệt; chưa đủ kết luận về pattern                                    |

**Quy tắc ghi nhận:**

- Tách lời người tham gia kể, hành vi có thể quan sát và diễn giải của người phân tích.
- Recruitment check chỉ xác nhận người phù hợp, không thay thế câu chuyện evidence.
- Exact quote phải đối chiếu bản ghi; chưa nghe rõ thì ghi “chưa rõ”, không làm sạch thành một câu mới.
- Phân biệt “không được hỏi/không có dữ liệu” với “người tham gia xác nhận không có”.
- Workaround không tự chứng minh pain nghiêm trọng; hỏi mục đích và consequence.
- Lời khen, mong muốn tính năng và lời hứa tương lai không chứng minh pain.
- Một vài câu chuyện luyện tập không chứng minh prevalence trên đa số learners, quan hệ nhân quả với điểm số hay retention.

### 2.7 Problem Hypothesis chốt để điều tra

**Giả định:** khi cần giữ lại nội dung mới để dùng sau, learner có thể khó chọn và lưu các ý quan trọng trong lúc vẫn theo bài, vì hai hoạt động cạnh tranh sự chú ý; điều này có thể khiến họ bỏ sót ý hoặc phải quay lại học liệu để bổ sung.

**Điều phải đúng:** learner có một job cần lưu và dùng nội dung; barrier thực sự nằm ở khâu chọn/lưu; có consequence đủ đáng kể; các cách hiện tại chưa đáp ứng tốt trong tình huống đó.

**Điều khiến sửa/bác bỏ:** learner theo bài và lưu thuận lợi; tài liệu có sẵn đã đủ; không có nhu cầu dùng lại; barrier chính là kiến thức nền; hoặc pain chỉ xuất hiện khi tìm lại nội dung — khi đó cần xem xét nhánh B.

### 2.7.1 Sau lượt luyện — evidence làm thay đổi hướng điều tra

| Evidence từ transcript An                                                                                                             | Diễn giải có giới hạn                                                                    | Tác động tới giả thuyết                                                    |
| ------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | -------------------------------------------------------------------------- |
| 01:06: P01 mô tả dùng Notion cho nội dung có hệ thống; Docs cho văn bản dài/chia sẻ. Tên đầy đủ của Docs còn dấu hỏi trong transcript | Có cách chọn công cụ theo mục đích; chưa phải một sự kiện gần nhất đủ chi tiết           | Không chứng minh learner nói chung thiếu cách tổ chức ghi chú              |
| 02:09: P01 trả lời tìm lại ghi chú “Bình thường thì không”, kể search theo từ khóa và đặt tên theo ngày                               | Cách hiện tại nhìn chung đáp ứng việc tìm lại; ví dụ ngày cụ thể chưa rõ                 | Làm yếu B nếu B được hiểu là khó tìm lại trên mọi công cụ                  |
| 03:53: P01 kể ban đầu ghi ở phần note theo slide VLearn, sau chuyển sang chia đôi màn hình slide/Notion                               | Một thay đổi hành vi được tự thuật, với lý do note VLearn phân tán và cần nhiều thao tác | Ủng hộ điều tra B trong ngữ cảnh riêng VLearn; chưa chứng minh A           |
| 04:53–04:59: An diễn giải sẵn vấn đề; P01 đồng ý và nói lại note phân bố theo slide                                                   | Câu hỏi dẫn dắt; lời đồng ý không được tính như bằng chứng độc lập                       | Ưu tiên lời kể trước đó ở 03:53, tránh đếm lặp                             |
| 05:13: P01 đề xuất gom note, có liên kết về slide và mở nhanh                                                                         | Feature request, sau câu hỏi cải tiến của An                                             | Là đầu mối hỏi tiếp job; không chứng minh nhu cầu AI hoặc phương án tối ưu |

**A — khó ghi trong lúc học:** chưa có evidence đủ rõ về bỏ sót ý, không theo kịp vì ghi chép hoặc chi phí bổ sung. Việc chia đôi màn hình là cách làm P01 kể, không tự chứng minh A đúng.

**B — khó dùng lại ghi chú:** có tín hiệu cụ thể ở note VLearn, nhưng không được khái quát thành mọi ghi chú đều khó tìm. P01 kể cách tìm trong hệ thống riêng nhìn chung thuận lợi. Đây là khác biệt theo công cụ và luồng truy cập, có giá trị hơn một kết luận chung rằng người học “ghi quá nhiều”.

**Problem Hypothesis được tinh chỉnh — Giả định cần điều tra tiếp:** khi muốn xem lại nội dung đã ghi trong các bài học VLearn, learner có thể khó tiếp cận phần cần dùng vì note nằm ở từng slide và phải đi qua nhiều bước để mở lại, dẫn đến công sức tìm lại tăng và có thể chuyển sang ghi ở công cụ khác. P01 đã kể sự chuyển công cụ; mức công sức, tần suất, sự kiện gần nhất và ảnh hưởng tới job chưa được đo.

**JTBD được tinh chỉnh — Giả định:** “Khi cần ôn lại kiến thức đã học, tôi muốn tiếp cận nhanh ghi chú liên quan và có thể quay về nội dung gốc khi cần, để hiểu lại phần còn vướng mà không phải dò từng slide.” Liên kết nguồn là hướng cần kiểm tra thêm từ feature request, chưa phải yêu cầu sản phẩm đã xác nhận.

**Hướng tiếp theo:** ưu tiên kiểm tra pain truy cập/tập hợp note VLearn, so sánh với cách P01 tìm trong Notion, đồng thời tuyển thêm learner có sự kiện phù hợp. Nếu truy cập nhanh là job chính, giải pháp không AI có thể đủ. Không dùng lượt này để tuyên bố AI Notes đã được validated.

**Điều có thể làm hypothesis mới yếu đi:** learner mở lại thuận lợi; không cần tổng hợp theo bài; cách tổ chức theo slide giúp họ hiểu ngữ cảnh; chuyển công cụ vì thói quen/chia sẻ thay vì barrier truy cập; hoặc consequence quá nhỏ để cần can thiệp. Xem [Interview Record](interview/notes.md) để kiểm tra evidence và phần chưa khai thác.

### 2.8 Solution Parking Lot

Các hướng dưới đây là **đề xuất**, chưa chọn triển khai hoặc kiểm chứng nhu cầu. Không đưa danh sách này cho interviewee trong problem interview.

| Hướng có thể nghiên cứu sau discovery                                                    | AI / Không AI | Giả định cần kiểm tra trước                                    |
| ---------------------------------------------------------------------------------------- | ------------- | -------------------------------------------------------------- |
| Tổng hợp nội dung gắn với highlights/câu hỏi, có liên kết nguồn và bước learner kiểm tra | AI            | Người học cần tổ chức nội dung cá nhân và sẵn sàng kiểm tra    |
| Tạo câu hỏi ôn từ ghi chú đã được learner xác nhận                                       | AI            | Người học thực sự ôn lại và cần tự kiểm tra hiểu biết          |
| Khung Cornell/Outline bên cạnh nội dung học                                              | Không AI      | Khó khăn có thể giảm nhờ cách chọn và tổ chức ý                |
| Bookmark/highlight gắn với vị trí trong bài                                              | Không AI      | Barrier chính là tìm lại đúng đoạn và ngữ cảnh                 |
| Thời điểm dừng ngắn để learner tự ghi ý chính/câu hỏi                                    | Không AI      | Ghi và theo bài cùng lúc là barrier đáng kể                    |
| Chia sẻ ghi chú tự nguyện trong nhóm học                                                 | Không AI      | Peer learning có ích; người tạo chủ động chọn nội dung chia sẻ |

## 3. Conversation Guide — phiên bản hoàn thiện đề xuất

**Phiên bản v2:** đã chỉnh sau khi đọc transcript lượt An–P01 ngày 04/10/2026. Baseline nhóm chọn A; tín hiệu trong lượt này hướng tới B riêng ở note VLearn. Guide giữ câu hỏi trung tính, không tuyển riêng người bất mãn với VLearn. Đây là bản chỉnh sửa trong tài liệu cá nhân; chưa có xác nhận cả nhóm đã thống nhất hoặc sử dụng v2.

### 3.1 Big 3 — ba điều cần học sau lượt luyện

| Điều cần học                                                                   | Evidence cần tìm                                                                 | Điều khiến xem lại giả thuyết                                                       |
| ------------------------------------------------------------------------------ | -------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------- |
| 1. Ở một lần gần nhất, learner đã tạo và mở lại ghi chú như thế nào?           | Bài/ngày, job, nơi lưu, trình tự tìm và dùng lại; tách VLearn/công cụ riêng      | Cách hiện tại hoàn thành job thuận lợi; không cần gom ghi chú                       |
| 2. Nếu có vướng, barrier nằm ở truy cập, cấu trúc, hiểu nội dung hay khâu tạo? | Khoảnh khắc cụ thể, hành động xử lý, consequence; lịch sử đổi công cụ            | Barrier chính là kiến thức nền; chuyển công cụ vì lý do khác; hậu quả nhỏ           |
| 3. Cách tổ chức hiện tại đã đủ tốt chưa? **Câu hỏi có thể làm nhóm đổi hướng** | Một lần hoàn thành việc ôn thuận lợi; cách search/đặt tên; vai trò của slide gốc | Note theo slide có lợi; cách riêng đã đủ; không cần can thiệp hoặc tổng hợp bằng AI |

### 3.2 Tuyển người và xin phép

**Tiêu chí:** người ngoài nhóm 3aecaykhe, trong bảy ngày trước cuộc phỏng vấn đã ghi chú, highlight hoặc lưu nội dung học để xem sau. Để kiểm tra lượt ngày 04/10/2026, hỏi mốc cụ thể trong khoảng bảy ngày trước đó; không dùng một sự kiện cũ ngoài cửa sổ tuyển.

**Recruitment check:** “Trong bảy ngày vừa rồi, bạn có lần nào ghi chú, highlight hoặc lưu nội dung học để xem sau không? Đó là nội dung gì và vào ngày nào?”

Nếu không phù hợp, đổi người phỏng vấn theo hướng dẫn lab; không mớm một câu chuyện để đạt tiêu chí.

**Lời mở đầu:** “Mình muốn tìm hiểu cách bạn học và giữ lại nội dung để dùng sau. Mình muốn nghe trải nghiệm thực tế; không có đáp án đúng hay sai. Bạn có thể bỏ qua câu hỏi không muốn trả lời.”

**Xin phép ghi âm:** “Mình xin phép ghi âm để nghe lại, ghi notes và phục vụ bài học. Bản ghi chỉ chia sẻ với giảng viên/TA, không công khai. Bạn có đồng ý không?” Chỉ bắt đầu ghi sau khi có đồng ý; không suy consent từ việc có file.

### 3.3 Story opener và Big 3 Questions

**Story opener:** “Kể mình nghe lần gần nhất trong bảy ngày vừa rồi bạn ghi chú, highlight hoặc lưu một phần nội dung học để xem sau. Lúc đó bạn đang học gì?”

| Big 3                     | Câu hỏi chính                                                                                                                                                                                      |
| ------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1. Tạo và sử dụng lại     | “Ở lần đó, bạn đã chọn và lưu những gì?” Sau khi nghe: “Sau đó bạn đã mở lại phần ấy chưa? Kể mình lần gần nhất bạn dùng lại nhé.” Nếu chưa, hỏi job hiện tại thay vì ép user có nhu cầu ôn.       |
| 2. Barrier và consequence | “Trong lần mở lại đó có chỗ nào không diễn ra như bạn muốn không?” Nếu có, hỏi lần lượt: “Bạn đã làm gì tiếp theo?” và “Việc đó ảnh hưởng thế nào tới việc bạn đang làm?”                          |
| 3. Cách hiện tại đủ tốt?  | “Kể mình một lần gần đây bạn dùng lại ghi chú và hoàn thành việc định làm thuận lợi.” Theo câu chuyện để hỏi cách tìm, tài liệu dùng và kết quả; không mặc định user cần AI hoặc muốn đổi công cụ. |

### 3.4 Probe bank — chỉ hỏi khi câu chuyện cần làm rõ

- **Neo sự kiện:** “Đó là bài nào, vào ngày nào? Khi ấy bạn định hoàn thành việc gì?”
- **Hành vi:** “Chuyện gì xảy ra tiếp theo? Bạn đã làm gì?”
- **Lựa chọn:** “Điều gì khiến bạn chọn lưu phần đó hoặc dùng cách đó?”
- **Artifact:** “Nếu tiện, bạn có thể mô tả hoặc cho xem riêng phần liên quan không?” Không yêu cầu mở nội dung cá nhân không cần thiết.
- **Workaround:** “Ở lần đó bạn đã thử cách nào khác? Sau đó chuyện gì xảy ra?”
- **Consequence:** “Việc ấy làm thay đổi điều gì trong việc bạn đang làm? Bạn mất thêm công sức hoặc thời gian thế nào?” Không đặt sẵn số phút.
- **Nhánh B:** “Khi mở lại, bạn tìm phần cần dùng bằng cách nào? Bạn có hiểu ngay nội dung đã lưu không?”
- **VLearn nếu user tự nêu:** “Kể mình lần cuối bạn tìm lại một note ở đó. Bạn bắt đầu ở đâu rồi làm gì tiếp?” Không đặt sẵn số bước hoặc đánh giá khó tìm.
- **Chuyển công cụ nếu user tự nêu:** “Kể mình lần bạn quyết định đổi cách ghi. Chuyện gì xảy ra trước đó? Ở lần dùng cách mới, điều gì thay đổi?” Hỏi cả phần thuận lợi và bất tiện.
- **Feature request:** “Lần nào bạn cần quay lại nội dung gốc? Lúc đó bạn đã xử lý thế nào?” Không hỏi user xác nhận một ý tưởng giao diện.
- **Pattern:** “Lần gần nhất trước đó có chuyện tương tự là khi nào? Có gì giống hoặc khác?”
- **Alternative:** nếu user tự nêu không hiểu thuật ngữ, hỏi thuật ngữ nào, đã xử lý thế nào và kết quả; không tự biến thiếu kiến thức nền thành pain ghi chú.

### 3.5 Deflect – Anchor – Dig

| Khi câu trả lời lệch           | Phản xạ | Câu quay lại evidence                                                              |
| ------------------------------ | ------- | ---------------------------------------------------------------------------------- |
| Lời khen                       | Deflect | “Cảm ơn bạn. Quay lại lần vừa kể, khi đó bạn đã làm gì?”                           |
| Câu chung chung hoặc tương lai | Anchor  | “Lần gần nhất chuyện đó xảy ra là khi nào? Kể mình lần đó nhé.”                    |
| Feature request                | Dig     | “Điều đó giúp bạn hoàn thành việc gì? Trong lần vừa kể, bạn xử lý việc ấy ra sao?” |

### 3.6 Nhịp phỏng vấn 15 phút — kế hoạch đề xuất

| Khoảng thời gian dự kiến | Hoạt động                                                      |
| ------------------------ | -------------------------------------------------------------- |
| 0–2 phút                 | Kiểm tra người phù hợp, mở đầu và consent trước ghi âm         |
| 2–5 phút                 | Story opener, job và trình tự hành vi                          |
| 5–10 phút                | Barrier, workaround và consequence                             |
| 10–13 phút               | Lần dùng lại, tài liệu thay thế, sự kiện trước đó              |
| 13–15 phút               | Tóm tắt để user sửa chỗ hiểu sai, hỏi điều còn thiếu và cảm ơn |

Đây là kế hoạch, không phải thời lượng đã xác nhận của file An. Follow câu chuyện thay vì đọc hết probe bank; chưa có khó khăn thì không ép user kể pain.

### 3.7 Revision log — sửa từ đúng câu hỏi An đã dùng

| Đoạn thực tế trong transcript                                                        | Nhận xét                                                                                   | Cách sửa trong v2                                                               |
| ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------- |
| 00:09–00:26: hỏi “bình thường”, khó hiểu thì “sẽ làm gì”; mở rộng “từ trước đến nay” | Phạm vi rộng, lấy thói quen và nhánh hiểu kiến thức; chưa neo Case B                       | Recruitment 7 ngày rồi hỏi một lần gần nhất đã ghi/highlight/lưu                |
| 02:02: đặt sẵn “ghi note quá nhiều” và “mất thời gian”                               | Có nguy cơ mớm pain. P01 vẫn nói nhìn chung không mất thời gian                            | Hỏi lần tìm lại gần nhất và trình tự; để user tự nêu barrier                    |
| 02:47: hỏi xem note có “tạo ra điều gì mới”                                          | Tiêu chuẩn outcome do interviewer đặt, có thể không khớp job ôn kiến thức                  | Hỏi lúc đó muốn làm gì, dùng note ra sao và kết quả đối với job ấy              |
| 03:46–03:53: hỏi quy trình ghi note VLearn                                           | Mở được lời kể về thay đổi từ note theo slide sang Notion, nhưng vẫn ở mức quy trình chung | Giữ chủ đề, neo lần chuyển cách ghi và một lần mở lại cụ thể                    |
| 04:53–04:59: diễn giải sẵn khó tìm và kết bằng “đúng không?”                         | Câu xác nhận dẫn dắt; không tính lời đồng ý như evidence bổ sung                           | Hỏi “Ở lần đó bạn tìm lại thế nào?”; cuối buổi tóm tắt và mời sửa điều hiểu sai |
| 05:08–05:55: hỏi muốn cải tiến, rồi diễn giải giao diện/link                         | Chuyển từ problem interview sang solution discussion; request chưa chứng minh nhu cầu AI   | Dig: hỏi một lần đã cần gom/mở nhanh/quay về slide và cách hiện tại xử lý       |

**Chưa đủ để đạt trọn gate revision:** v2 đã sửa từ transcript thật, nhưng An còn phải tự đối chiếu bản ghi và xác nhận nội dung với nhóm. Không ghi nhóm đã dùng v2 trong giờ lab.

## 4. Practice Reflection — biên tập từ transcript thật

**Nguồn:** transcript An cung cấp của lượt ngày 04/10/2026. AI hỗ trợ phân tích và diễn đạt; không xác nhận An đã tự nghe lại. Nhận xét sau đây gắn với lời thoại thực tế, để An kiểm tra, sửa và xác nhận trước khi nộp.

### 4.1 Câu hỏi nào giúp user kể một tình huống cụ thể?

Câu hỏi về quy trình ghi note bài VLearn ở **03:46** mở được đoạn có giá trị nhất: ở **03:53**, P01 kể ban đầu dùng note theo slide, sau chuyển sang chia đôi màn hình để ghi trong Notion, đồng thời giải thích nhiều thao tác và sự phân tán khi mở lại. Đây là lời kể về một thay đổi hành vi và lý do lựa chọn; hữu ích hơn các câu hỏi “bình thường” ở đầu cuộc trò chuyện. Tuy nhiên, câu hỏi chưa neo một lần cụ thể: còn thiếu bài nào, ngày nào, mục đích lần mở lại và hậu quả. Ở vòng tiếp theo, cần hỏi một lần gần nhất thay vì dừng ở quy trình chung.

### 4.2 Chỗ nào cần làm tốt hơn ở lần phỏng vấn thật?

Ba điểm cần sửa từ transcript:

1. **Neo vào sự kiện và tuyển đúng người:** đoạn 00:09–00:26 hỏi cách xử lý kiến thức khó hiểu nói chung; chưa kiểm tra có ghi/lưu trong bảy ngày. Cần tuyển đúng tình huống Case B rồi theo một câu chuyện từ đầu đến cuối.
2. **Không mớm pain, biết giữ evidence trái giả thuyết:** câu 02:02 gợi “note quá nhiều” và mất thời gian, nhưng P01 trả lời thường không khó tìm. Phải giữ lời phủ định này, hỏi cách đặt tên/search giúp họ hoàn thành job, thay vì bỏ qua để củng cố B. Câu 04:53 diễn giải và hỏi “đúng không” cũng cần đổi thành hỏi mở về hành động.
3. **Đào consequence trước khi nói solution:** sau đoạn 03:53, nên hỏi một lần tìm lại, những bước đã thực hiện, công sức và kết quả. Câu 05:08 hỏi cải tiến chuyển cuộc trò chuyện sang giải pháp khi pain chưa được đo. Đề nghị gom note/mở nhanh chỉ là đầu mối; cần Dig về việc user đã cố làm và workaround thực tế.

Không lấy câu trả lời về nội dung “khó hiểu” làm evidence rằng người học ghi chú kém; cũng không suy rằng chuyển sang Notion chứng minh họ muốn AI tạo ghi chú.

### 4.3 Guide được sửa ở đâu và vì sao?

V2 bổ sung recruitment check bảy ngày; đổi opener về khó hiểu chung thành lần lưu nội dung gần nhất; tách trình tự tạo và mở lại; hỏi barrier, workaround và consequence bằng câu mở; bổ sung một câu chuyện sử dụng thuận lợi để kiểm tra cách hiện tại đã đủ. Khi user tự nêu VLearn hoặc đổi công cụ, probe sẽ hỏi sự kiện cụ thể và lý do chuyển. Các câu “đúng không?” và yêu cầu cải tiến được thay bằng hỏi hành vi quá khứ. Big 3 được điều chỉnh để phân biệt pain truy cập note VLearn với khả năng tìm thuận lợi trong Notion, tránh khái quát thành mọi ghi chú đều khó tìm.

Đây là các sửa đổi đã thực hiện trong tài liệu cá nhân dựa trên transcript An, được trình bày ở revision log 3.7; chưa xác nhận là quyết định nhóm trong giờ lab. Bước tiếp theo của An là nghe lại các đoạn chưa rõ, xác nhận nhận xét và thảo luận v2 với hai thành viên còn lại.

## 5. AI Support Log

| Công việc AI hỗ trợ                  | Đầu vào                                                | Kết quả và giới hạn                                                                                                                |
| ------------------------------------ | ------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------- |
| Đọc và đối chiếu lab                 | Sáu trang thực hành VLearn, Case B và bốn gate         | Xác định yêu cầu README, notes, recording và giới hạn AI                                                                           |
| Rà soát bài hiện tại                 | README trên GitHub của An và thư mục local             | README chỉ có tiêu đề; notes trống; file recording tồn tại                                                                         |
| Tham khảo nội dung nhóm              | Google Docs chung và repo của Dũng, theo yêu cầu An    | Giữ nhánh A/B; chỉnh cách diễn đạt và Evidence Map; không chuyển interview evidence của Dũng sang An                               |
| Hoàn thiện giả thuyết và guide       | Directive, bài nhóm, rubric                            | Tách output/outcome; bổ sung khả năng bác bỏ; Big 3 và probe trung tính                                                            |
| Tổ chức notes/reflection và guide v2 | Transcript thật do An lọc và cung cấp; ngày 04/10/2026 | Trích evidence có timestamp; tách self-report, diễn giải và feature request; reflection gắn với lời thoại An; chưa đối chiếu audio |

**Các điểm hời hợt trong bản nhóm được AI đề xuất sửa:**

1. “Directive nguyên văn” trong bài nhóm thực chất là diễn đạt lại và thiếu dấu vết cá nhân/bước xác nhận. Bản này khôi phục mô tả từ đề lab.
2. Chuỗi outcome nhảy tới ghi nhớ hoặc completion: bổ sung mắt xích kiểm tra, lưu và dùng lại; outcome vẫn là giả định.
3. Evidence Map dùng điểm thấp/bỏ khóa và pattern ở đa số learners: thay bằng sự kiện, hành vi và consequence có thể hỏi; không khẳng định quan hệ nhân quả hoặc prevalence.
4. Cách giải thích người không gặp pain là “quản lý thời gian kém”: loại bỏ quy kết; giữ alternative explanation và khả năng cách hiện tại đủ tốt.
5. Lợi ích instructor có thể hàm ý truy cập notes: không tự mở rộng directive thành tính năng chia sẻ ghi chú cá nhân.

**Lần cập nhật từ transcript An:** AI đã giữ evidence trái giả thuyết ở 02:09, phân biệt với pain VLearn ở 03:53; không suy tên đầy đủ công cụ, ngày ví dụ, mức khó khăn hay số bước tại các đoạn có dấu hỏi. Lời đồng ý sau câu dẫn dắt ở 04:53 không được đếm thành evidence độc lập; feature request ở 05:13 không được nâng thành yêu cầu AI đã xác nhận. Không dùng interview data của Dũng cho P01.

**Những việc AI chưa xác nhận:** độ khớp transcript/audio, consent, người ngoài nhóm, recruitment bảy ngày, thời lượng/toàn bộ lượt, việc An tự nghe lại và việc nhóm chốt v2. Mốc cuối transcript là 05:58, không tự kết luận file gốc chỉ dài gần sáu phút. Không khẳng định 15 phút đầu nhóm chưa dùng AI.

Nguyễn Văn An cần tự đọc, đối chiếu audio và xác nhận nội dung trước khi nộp; chưa ghi việc tự sửa hoặc duyệt của người học là đã diễn ra.

### Nguồn tham khảo

- [Đề lab VLearn — Track 1 Day 17](https://vlearn.dev/course/k04-l34-p2-t1/reader?day=D02&part=codelab-016c0a0e8114438a871d96b5c3cee983-s01-doc).
- [Tài liệu nhóm được liên kết trong bài của Dũng](https://docs.google.com/document/d/1ev_OXpRAOvKnDNNxycYnTFmN8uaQBxgVhxsKWAcU1vg/edit): baseline Problem Hypothesis và Solution Parking Lot.
- [Bài của Lưu Xuân Dũng](https://github.com/luuxuandung04/Track1_Day17_2A202602746_LuuXuanDung): tham khảo cấu trúc, Evidence Map và cách thiết kế guide; không dùng interview facts/quote của Dũng làm dữ liệu của An.

### Trạng thái trước nộp

- [x] Đúng tên repo và thông tin nhóm/case.
- [x] Problem Hypothesis đủ chuỗi, có A/B và điều kiện bác bỏ.
- [x] Solution Parking Lot ít nhất năm hướng, có hướng không AI.
- [x] Guide đề xuất có Big 3, tuyển người, opener, probe và câu hỏi làm giả thuyết yếu đi.
- [x] AI Support Log phân biệt nguồn và giới hạn hỗ trợ.
- [x] `interview/notes.md` có evidence từ transcript An, timestamp và giới hạn suy luận.
- [ ] Đối chiếu notes và các từ chưa rõ với audio gốc.
- [ ] Xác nhận người ngoài nhóm, recruitment và consent.
- [ ] Xác minh file có đủ lượt phỏng vấn theo yêu cầu 15 phút.
- [x] Có ba câu trả lời reflection gắn transcript và revision log cụ thể.
- [ ] An tự nghe lại, xác nhận reflection và trao đổi guide v2 với nhóm.
- [ ] Bản ghi truy cập được với giảng viên/TA, không công khai.
- [ ] Kiểm tra các file đã được lưu vào repo bài làm và nộp đúng quy trình.
