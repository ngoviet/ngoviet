### Xin chào, mình là Ngô Đức Việt 👋

[English](README.md) · **Tiếng Việt**

Lập trình viên mã nguồn mở ở **Việt Nam** 🇻🇳 — mình làm **integration cho Home Assistant** và **thiết bị ESP32 / ESPHome**
cho điện mặt trời, mạng gia đình và nhà thông minh. Tất cả cài được qua HACS, giấy phép MIT, có tài liệu tiếng Anh và
tiếng Việt, và đều chạy thật trên hệ thống nhà mình.

---

#### Integration cho Home Assistant

| Dự án | Dành cho | Điểm nổi bật | Phiên bản |
|---|---|---|---|
| 🔆 [Lumentree HA](https://github.com/ngoviet/lumentreeHA/blob/main/README.vi.md) | Inverter hybrid Lumentree | MQTT thời gian thực, thống kê điện năng ngày/tháng/năm, theo dõi pin và PV | ![](https://img.shields.io/github/v/release/ngoviet/lumentreeHA?label=) |
| 🔌 [SmartSolar HA](https://github.com/ngoviet/smartsolar_ha/blob/main/README.vi.md) | Sạc MPPT WiFi Mạnh Quân 40A/45A/60A | Theo dõi bộ sạc, PV và pin | ![](https://img.shields.io/github/v/release/ngoviet/smartsolar_ha?label=) |
| ☀️ [LuxCloud HA](https://github.com/ngoviet/luxcloud_ha/blob/main/README.vi.md) | Inverter LuxPower (API LuxCloud) | Tình trạng dongle, lịch sử lỗi, chi tiết BMS, đường công suất trong ngày, tổng theo năm | ![](https://img.shields.io/github/v/release/ngoviet/luxcloud_ha?label=) |
| 📡 [RouterOS HA](https://github.com/ngoviet/routeros_ha/blob/main/README.vi.md) | MikroTik RouterOS 7 (REST API) | Công tắc chặn Internet từng thiết bị, sức khoẻ router, trạng thái cập nhật | ![](https://img.shields.io/github/v/release/ngoviet/routeros_ha?label=) |
| 📶 [Aruba Instant HA](https://github.com/ngoviet/aruba_instant_ha/blob/main/README.vi.md) | Cụm Wi-Fi Aruba Instant (IAP) | Mọi client Wi-Fi kèm tín hiệu, băng tần, SSID, AP; mức chiếm kênh của từng AP | ![](https://img.shields.io/github/v/release/ngoviet/aruba_instant_ha?label=) |
| 💧 [Karofi HA](https://github.com/ngoviet/karofi_ha/blob/main/README.vi.md) | Máy lọc nước Karofi (Karofi 365) | TDS, chất lượng nước, tuổi lõi lọc, rò rỉ và báo lỗi | ![](https://img.shields.io/github/v/release/ngoviet/karofi_ha?label=) |
| 🚿 [Ariston HA](https://github.com/ngoviet/ariston_ha/blob/main/README.vi.md) | Bình nóng lạnh Ariston Velis Med / Slim3 (Ariston NET) | Nhiệt độ, chế độ MANUAL/PROGRAM, ECO, diệt khuẩn, lịch tuần | ![](https://img.shields.io/github/v/release/ngoviet/ariston_ha?label=) |

#### Thẻ Lovelace và theme

- [**LAN Topology Card**](https://github.com/ngoviet/lan-topo-card/blob/main/README.vi.md) — sơ đồ mạng LAN trực tiếp (Internet → router → switch → cổng), đường nối chuyển động theo lưu lượng; hỗ trợ MikroTik, Netgear Plus hoặc khai báo tay.
- [**Palette AXI Neon**](https://github.com/ngoviet/palette-axi-neon/blob/main/README.vi.md) — theme tối neon: nền xanh đêm, màu nhấn cùng một dải sáng OKLCH, ô nhập chữ dễ đọc.

#### Thiết bị ESP32 / ESPHome

- [**BLDC Smart Fan**](https://github.com/ngoviet/esp32-esphome-bldc-smart-fan/blob/main/README.vi.md) — quạt BLDC chỉnh tốc độ bằng tần số CLK và núm xoay EC11.
- [**JK-BMS Monitor**](https://github.com/ngoviet/esp32-jk-bms-monitor/blob/main/README.vi.md) — giám sát pin JK-BMS 24V 280Ah qua ESP32.
- [**48V BMS Monitor + Fan Control**](https://github.com/ngoviet/esp32-jk-bms-48v-fan-control/blob/main/README.vi.md) — giám sát JK-BMS và tự bật quạt làm mát theo nhiệt độ.
- [**12V Auto Power Switch**](https://github.com/ngoviet/esp32-auto-power-switch-12v/blob/main/README.vi.md) — tự chuyển nguồn theo SOC pin lấy từ Home Assistant.
- [**Smart LED Control**](https://github.com/ngoviet/esp32-smart-led-control/blob/main/README.vi.md) — bộ điều khiển LED ESPHome dạng module, có BME280 và cảm biến chuyển động.
- [**ESP32-C6 Matter Fan**](https://github.com/ngoviet/esp32-c6-matter-fan/blob/main/README.vi.md) — quạt thông minh Matter trên ESP32-C6 (*thử nghiệm*).

#### Công cụ

- [**mikrotik-axi**](https://github.com/ngoviet/mikrotik-axi/blob/main/README.vi.md) — xem và vận hành an toàn MikroTik RouterOS v7 qua REST; CLI viết cho AI agent.
- [**Local LLM on CPU**](https://github.com/ngoviet/local-model-cpu/blob/main/README.vi.md) — chạy Gemma MoE + thị giác bằng llama.cpp, ngữ cảnh 256K, khoảng 11,5 token/giây trên mini PC i5.
- [**Phụ đề YouTube song ngữ**](https://github.com/ngoviet/yt-sub/blob/main/README.vi.md) — extension Chrome: phụ đề song ngữ thời gian thực, bảng transcript, xuất SRT/VTT.

---

#### Công nghệ mình dùng

`Home Assistant` `HACS` `Python` `ESPHome` `ESP32` `MQTT` `Modbus` `MikroTik RouterOS` `Solar / BMS` `Matter`

---

#### Ủng hộ mình

<a href="https://buymeacoffee.com/ngoviet"><img src="https://raw.githubusercontent.com/ngoviet/.github/main/assets/support/btn-coffee.svg" height="48" alt="Buy me a coffee"></a>
&nbsp;
<a href="https://github.com/sponsors/ngoviet"><img src="https://raw.githubusercontent.com/ngoviet/.github/main/assets/support/btn-sponsors.svg" height="48" alt="GitHub Sponsors"></a>

Chuyển khoản trong nước: mã VietQR (MB Bank · NGO DUC VIET · 911051212) có ở mục *Ủng hộ dự án* trong README tiếng Việt
của mỗi repo. Cảm ơn bạn!

📧 vokupt@gmail.com
