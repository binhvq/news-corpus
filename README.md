# Binhvq News Corpus Version 0.1
## Thông tin cơ bản:
* Trích xuất từ khoảng 14.896.998 bài báo trên internet bao gồm các báo:
```
2Sao
ANTG
ANTT
ANTĐ
ATGT
BVPL
BizLIVE
Biên Phòng
Bnews
Báo Văn hóa
Bộ Công thương
Bộ GTVT
Bộ KHĐT
Bộ Ngoại Giao
Bộ Nội Vụ
Bộ Tài Chính
Bộ VHTTDL
CAND
CAĐN
CL&XH
CSTC
Cartimes
Chính Phủ
Công Luận
Công Lý
Công Thương
DNVN
Doanh Nghiệp
Dân Sinh
Dân Việt
Em Đẹp
GD&TĐ
GTVT
Gia Đình Mới
Gia Đình VN
Giao Thông
Giáo Dục VN
GĐ&XH
Hà Nội Mới
Hà Tĩnh
Hải Quan
ICTNews
Infonet
KTNT
KTĐT
Khỏe 365
Khỏe Plus
Khỏe Plus 24h
Kiến Thức
Kiểm Sát
Kiểm sát
Kỷ Nguyên Số
Lao Động
LĐTĐ
MT&CS
Mặt Trận
Một Thế Giới
NCĐT
NLĐ
Nghe Nhìn VN
Nghệ An
Ngày Nay
Người Làm Báo
Người Tiêu Dùng
Người Đô Thị
Người Đưa Tin
Nhân Dân
Nông Nghiệp
NĐ&ĐS
PC World
PL&XH
PLO
PNNews
PNSK
PetroTimes
Pháp Luật Net
Pháp Luật Plus
Pháp Luật VN
Phụ Nữ VN
Quốc Hội
Quốc Hội TV
QĐND
SGGP
SGĐT
SaoStar
Seatimes
Sài Gòn Tiếp Thị
TBDN
TBKTSG
TG&VN
TGTT
TH&PL
TNMT
TTOL
TTXVN
Thanh Hóa
Thanh Niên
Thanh Tra
TheLEADER
Thương Gia
Thế Giới Trẻ
Thế Giới Xe
Tin Nhanh
Tin Thể Thao
Tin Tức TTXVN
Tiền Phong
TuanVietNam
Tuyên Giáo
Tuổi Trẻ TĐ
Tài Chính
Tạp chí Công thương
Tạp chí Xây dựng Đảng
Tạp chí cộng sản
Tổ Quốc
VEF
VNCA
VNEWS
VOV
VTC
VietQ
VietTimes
Vietnam Finance
VietnamNet
VietnamPlus
VnEconomy
VnMedia
Văn Hiến
Văn Hoá
XHTT
Xe Giao Thông
Xây Dựng Đảng
Zing
Ôtô - xe máy
Ôtô Xe Máy
ĐCSVN
ĐS&PL
ĐTCK
Đại Đoàn Kết
Đảng Cộng Sản VN
Đất Việt
Đấu Thầu
Đầu Tư
Đời Sống Plus
```
* Sample: https://github.com/binhvq/news-corpus/blob/master/sample/demo-full.txt
## News Title Corpus
* Kích thước : 219 MB Compress. Uncompress 669 MB

* Số lượng title: 10.787.976

* Donwload: https://drive.google.com/open?id=1ypvEoGRNWrNLmW246RtBm9iMyKXm_2BP

* Sample: https://github.com/binhvq/news-corpus/blob/master/sample/demo-title.txt

## Full Corpus Định dạng TXT
* Kích thước : 3.7 GB Compress. Uncompress ~18.6 GB
 
* Số lượng câu: khoảng 111.274.300 câu
 
* Đã qua xử lý cơ bản như:
    + Tách câu sử dụng PunktSentenceTokenizer abbrev ```{'g.m.t', 'e.g', 'dr', 'dr', 'vs', "000", 'mr', 'mrs', 'prof', 'inc', 'tp', 'ts', 'ths', 'th', 'vs', 'tp', 'k.l', 'a.w.a.k.e', 'a.i', '</i', 'g.w',
                            'ass',
                            'u.n.c.l.e', 't.e.s.t', 'ths', 'd.c', 've…', 'ts', 'f.t', 'b.b', 'z.e', 's.g', 'm.p', 'g.u.y',
                            'l.c', 'g.i', 'j.f', 'r.r', 'v.i', 'm.h', 'a.s', 'bs', 'c.k', 'aug', 't.d.q', 'b…', 'ph', 'j.k', 'e.l', 'o.t', 's.a'}```
 
    + Chỉnh sửa lại những kí tự lỗi khi chuyển từ html sang dạng text
 
    + Loại bỏ những câu giống nhau
 
    + Chuẩn hóa NFC
    
* Donwload: https://drive.google.com/file/d/1ovLbpvzSGrS4NDxZu8Ftdgc73uHzNQJf/view

## Định dạng Mongodb Dump
* Size: 8.9G copmpress. ~76GB Uncompress.

* Download: Vui lòng liên hệ tác giả.

```
{
	"source" : "Thanh Niên",
	"title" : "Đà Nẵng nghiên cứu tiện ích nhắn tin khi vi phạm đến chủ phương tiện",
	"sapo" : "Theo thống kê của Phòng CSGT (PC67, Công an TP.Đà Nẵng), từ ngày 1.1.2016 đến hết tháng 1.2018, PC67 gửi 13.479 lượt thông báo đến chủ phương tiện vi phạm luật Giao thông đường bộ.",
	"body" : "<p class=\"body-image\"><img src=\"https://photo-1-baomoi.zadn.vn/w700_r1/18/02/05/4/24858235/1_54839.jpg\"/></p><p class=\"body-text\"><em>Xử l&yacute; phạt nguội qua camera gi&aacute;m s&aacute;t tại Ph&ograve;ng CSGT C&ocirc;ng an TP.Đ&agrave; Nẵng - Nguyễn T&uacute;</em></p><p class=\"body-text\">Đến nay c&ograve;n 5.199 trường hợp chưa đến giải quyết, chiếm 38,5%. Đối với 8.280 trường hợp đến l&agrave;m việc, qua ph&acirc;n t&iacute;ch lỗi, cơ quan chức năng đ&atilde; lập bi&ecirc;n bản 7.184 trường hợp, chuyển kho bạc hơn 9 tỉ đồng, tước giấy ph&eacute;p l&aacute;i xe (c&oacute; thời hạn) 2.107 trường hợp.</p><p class=\"body-text\">Hiện PC67 Đ&agrave; Nẵng c&oacute; nhiều k&ecirc;nh để th&ocirc;ng b&aacute;o đến chủ xe như gửi th&ocirc;ng b&aacute;o đến địa chỉ đăng k&yacute; qua đường bưu điện, cập nhật danh s&aacute;ch l&ecirc;n trang Facebook &ldquo;Cảnh s&aacute;t giao th&ocirc;ng C&ocirc;ng an TP.Đ&agrave; Nẵng&rdquo;. Từ ng&agrave;y 22.9.2017, trang th&ocirc;ng tin điện tử C&ocirc;ng an TP.Đ&agrave; Nẵng cũng c&oacute; chuy&ecirc;n mục tra cứu vi phạm giao th&ocirc;ng qua hệ thống camera gi&aacute;m s&aacute;t tại địa chỉ www.catp.danang.gov.vn:8001/thongtinvipham...</p><p class=\"body-text\">Tuy nhi&ecirc;n, số trường hợp chưa giải quyết được cũng tương tự TP.HCM l&agrave; do thay đổi địa chỉ, chưa sang t&ecirc;n đổi chủ sau mua b&aacute;n, xe thu&ecirc;, sai th&ocirc;ng tin...</p><p class=\"body-text\">Trung t&aacute; Phan Văn Thương, Ph&oacute; trưởng ph&ograve;ng PC67 C&ocirc;ng an TP.Đ&agrave; Nẵng, cho hay hiện trang Facebook v&agrave; cổng th&ocirc;ng tin c&oacute; nhiệm vụ 1 - 2 ng&agrave;y phải cập nhật danh s&aacute;ch vi phạm mới nhất để người d&acirc;n tra cứu. Nếu chủ phương tiện kh&ocirc;ng đến giải quyết th&igrave; danh s&aacute;ch được chuyển sang Trung t&acirc;m đăng kiểm để từ chối đăng kiểm c&aacute;c phương tiện n&agrave;y.</p><p class=\"body-text\">&ldquo;Thời gian đầu &aacute;p dụng h&igrave;nh thức phạt nguội, c&oacute; chủ phương tiện bị phạt đến 15 lần, khi xe hết hạn, đi đăng kiểm mới nhận được th&ocirc;ng b&aacute;o nộp phạt với số tiền rất lớn. Nay th&igrave; kh&aacute;c, với tổ chức, c&ocirc;ng d&acirc;n vi phạm 2 lần trở l&ecirc;n sẽ bị lực lượng chức năng gọi điện trực tiếp để x&aacute;c minh, nhắc nhở chủ xe kịp thời chấn chỉnh, v&igrave; c&aacute;c xe vi phạm nhiều lần chủ yếu l&agrave; xe l&agrave;m dịch vụ cho thu&ecirc;, giao người kh&aacute;c sử dụng, khai th&aacute;c...&rdquo;, trung t&aacute; Phan Văn Thương cho hay.</p><p class=\"body-text\">C&ocirc;ng an TP.Đ&agrave; Nẵng đang nghi&ecirc;n cứu cho ra đời ứng dụng tr&ecirc;n thiết bị di động, th&ocirc;ng b&aacute;o vi phạm đến số m&aacute;y chủ phương tiện, vừa sử dụng cho c&ocirc;ng t&aacute;c phạt nguội, kết hợp c&aacute;c tiện &iacute;ch phục vụ ph&ograve;ng chống tội phạm kh&aacute;c bằng biện ph&aacute;p tăng mức tương t&aacute;c với chủ phương tiện.</p>",
	"id" : 24858235,
	"publish" : ISODate("2018-02-04T22:15:07Z"),
	"tags" : [ ],
	"keywords" : [
		"Công an TP.Đà Nẵng",
		"Phan Văn Thương",
		"Nguyễn Tú",
		"Luật giao thông đường bộ",
		"Đăng kiểm",
		"Sang tên",
		"Tra cứu",
		"Server",
		"Phòng cảnh sát giao thông",
		"Giấy phép lái xe",
		"Cổng thông tin",
		"Chấn chỉnh",
		"Cho thuê",
		"Nhắc nhở",
		"Di động",
		"Phòng chống",
		"Vi phạm",
		"Mua bán",
		"Đà Nẵng",
		"Ra đời",
		"Giám sát"
	],
	"cates" : [
		"Pháp luật"
	]
}
```
## Tác giả
* Họ tên: Vương Quốc Bình
* Email: binh@haui.vn
* Đơn vị công tác: Trường Đại học công nghiệp Hà Nội
* Github: https://github.com/binhvq
* Skype: binhvq
* FB: https://fb.com/binhvq1411